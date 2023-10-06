/*jshint esversion: 9 */
module.exports = (tp, attributes = {}) => {
	if (typeof attributes !== "object") {
		throw new Error("attributes must be an object");
	}
	let { position, ...frontmatter } =
		tp.frontmatter && typeof tp.frontmatter === "object" ? tp.frontmatter : {};
	for (let key in attributes) {
		if (Array.isArray(frontmatter[key]) || Array.isArray(attributes[key])) {
			if (Array.isArray(frontmatter[key]) && Array.isArray(attributes[key])) {
				frontmatter[key] = frontmatter[key].concat(attributes[key]);
			} else if (
				!Array.isArray(frontmatter[key]) &&
				Array.isArray(attributes[key])
			) {
				frontmatter[key] = attributes[key].concat([frontmatter[key]]);
			} else if (
				Array.isArray(frontmatter[key]) &&
				!Array.isArray(attributes[key])
			) {
				frontmatter[key] = frontmatter[key].concat([attributes[key]]);
			} else {
				frontmatter[key] = { ...frontmatter[key], ...attributes[key] };
			}
			frontmatter[key] = Array.from(new Set(frontmatter[key].filter(val => val)));
		} else if (
			typeof frontmatter[key] === "object" &&
			typeof attributes[key] === "object"
		) {
			frontmatter[key] = { ...frontmatter[key], ...attributes[key] };
		} else {
			frontmatter[key] = attributes[key];
		}
	}
	// remove duplicates from array values
	frontmatter = Object.fromEntries(
		Object.entries(frontmatter).map(([key, value]) => {
			if (Array.isArray(value)) {
				return [key, Array.from(new Set(value))];
			}
			return [key, value];
		})
	);


	return tp.user.formatted_frontmatter(frontmatter);
};