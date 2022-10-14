---
banner: "https://preview.redd.it/arqa352ph7x61.jpg?width=960&crop=smart&auto=webp&s=84f9245d607b029667d5bfc4abf36547fc6213de"
tags: periodic/weekly-note
week: <% tp.date.now("ww") %>
month: <% tp.date.now("YYYY - MM-MMMM") %>
year: <% tp.date.now("YYYY") %>
---

###### [[<% tp.date.now("gggg-[W]ww", -7, tp.file.title, "gggg-[W]ww") %>|↶ PREVIOUS WEEK]] ⁝ [[<% tp.date.now("gggg-[W]ww", 7, tp.file.title, "gggg-[W]ww") %>|FOLLOWING WEEK ↷]]
# ◌ <% tp.file.title %>
```dataview
TABLE
week as "Week"
FROM "600 Periodic/610 Daily"
WHERE week = "<% tp.file.title %>"
```