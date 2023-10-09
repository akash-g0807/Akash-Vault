# Assignments Page
---

```dataview
table without id from #assignment
```
```dataview
table without id
file.link AS "Assignments",
date AS "Deadline",
	Days_Left AS "📆",
	choice(completion,"✅","❌") AS "📝"
from  #assignment
```
