---
<%*    const priority = await tp.system.suggester(
        ["🎥 ",
        "🐦 Tweet",
        "💭 Thought",
        "🎧 Podcast",
        "👤 Person",
        "📜 Paper",
        "🌱 Seedling",
        "📚 Book",
        "📰 Article"], 
        ["🎥 Video",
        "🐦 Tweet",
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
    await tp.file.move("/Semester 1/" + title + "/" +title)%>



==<%tp.file.creation_date("YYYY-MM-DD")%>==
