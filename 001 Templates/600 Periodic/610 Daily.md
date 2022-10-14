---
banner: "https://preview.redd.it/arqa352ph7x61.jpg?width=960&crop=smart&auto=webp&s=84f9245d607b029667d5bfc4abf36547fc6213de"
tags: periodic/daily-note
full-date: <%tp.file.title%>
week: <% tp.date.now("YYYY-[W]ww") %>
month: <% tp.date.now("YYYY - MM-MMMM") %>
year: <% tp.date.now("YYYY") %>

cold-shower: ➖
workout: ➖
anki: ➖
reading: ➖
piano: 0
guitar: 0

improved-today: 
do-better:
notable: 
---
⠀
###### [[<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>|↶ YESTERDAY]] ⁝ [[<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>|TOMORROW ↷]]
# ◌ <% tp.date.now("dddd -  MMMM Do YYYY") %>
#### ✓  TASKS

######  ↑ TOP TASK
```tasks
due before <% tp.date.now("YYYY-MM-DD",1, tp.file.title, "YYYY-MM-DD") %>
not done
priority is high
hide task count
```
###### ○ TASKS
```tasks
due before <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>
not done
priority is below high
short mode
hide task count
```
###### ✓ COMPLETED TODAY
```tasks
done date is <% tp.date.now("YYYY-MM-DD", 0, tp.file.title, "YYYY-MM-DD") %>
hide task count
```
####  ↻ DAILIES

###### ◨ EVENING JOURNAL

