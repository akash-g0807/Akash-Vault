---
<%*    const priority = await tp.system.suggester(
        ["🎥 ",
        "🔺 Highest priority.",
        "💭 Thought",
        "🎧 Podcast",
        "👤 Person",
        "📜 Paper",
        "🌱 Seedling",
        "📚 Book",
        "📰 Article"], 
        ["🎥 Video",
        "🔺 Highest Priority.",
        "💭 Thought",
        "🎧 Podcast",
        "👤 Person",
        "📜 Paper",
        "🌱 Seedling",
        "📚 Book",
        "📰 Article"], 
        false,
        "Priority"

    ) %>
priority: <%priority%>
---

<%*  

    let title = await tp.system.prompt("What is the name of your new note?")
    
    await tp.file.rename(title)
    await tp.file.move("/Semester 1/" + title + "/" +title)
    
	await tp.file.create_new("--- \r\n kanban-plugin: basic \r\n --- \r\n", "Kanban", true).basename
    %>


