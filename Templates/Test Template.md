<%*
    const title_prefix = await tp.system.suggester(
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
        "Type of Note"

    )
    let title = await tp.system.prompt("What is the name of your new note?")
    await tp.file.rename(title)
    await tp.file.move("/Test/" + title)

%>

---
Priority: <% title_prefix %>

---
==<%tp.file.creation_date("YYYY-MM-DD")%>==
