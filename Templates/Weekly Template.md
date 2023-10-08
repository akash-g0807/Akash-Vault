# <% tp.file.title %>
---

## <%moment(tp.file.title).startOf("isoWeek").format("MMM DD") %> - <%moment(tp.file.title).endOf("isoWeek").format("MMM DD") %>

[[Journal/Weekly/<%moment(tp.file.title).subtract(1,'week').format("gggg-[W]ww")%>|↶ Previous Week]] | [[Journal/Weekly/<%moment(tp.file.title).add(1,'week').format("gggg-[W]ww")%>|↷ Next Week]]

## Days

- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(0,'day').format("YYYY-MM-DD")%>|Monday]]
- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(1,'day').format("YYYY-MM-DD")%>|Tuesday]]
- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(2,'day').format("YYYY-MM-DD")%>|Wednesday]]
- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(3,'day').format("YYYY-MM-DD")%>|Thursday]]
- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(4,'day').format("YYYY-MM-DD")%>|Friday]]
- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(5,'day').format("YYYY-MM-DD")%>|Saturday]]
- [[Journal/Daily/<%moment(tp.file.title).startOf("isoWeek").add(6,'day').format("YYYY-MM-DD")%>|Sunday]]

## Overview

```dataview
table without id
	file.link AS "Day",
	dinner AS "🍚",
	choice(sleep,"✅","❌") AS "😴",
	choice(study, "✅","❌") AS "📖",
	choice(wellbeing, "✅","❌") AS "🧑‍⚕️"
from "Journal/Daily"
where week = "<% moment(tp.file.title).format("gggg-[W]ww")%>"
sort file.name ASC
```
