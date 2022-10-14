---
tags: monthly-note  
month: <% tp.date.now("MM") %>-<% tp.date.now("MMM") %>  
year: <% tp.date.now("YYYY") %>  
banner:"https://preview.redd.it/arqa352ph7x61.jpg?width=960&crop=smart&auto=webp&s=84f9245d607b029667d5bfc4abf36547fc6213de"
---
⠀  
###### [[<% tp.date.now("gggg-[W]ww", -7, tp.file.title, "gggg-[W]ww") %>|↶ PREVIOUS WEEK]] ⁝ [[<% tp.date.now("gggg-[W]ww", 7, tp.file.title, "gggg-[W]ww") %>|FOLLOWING WEEK ↷]]  
# ◌ <% tp.file.title %>  
  
## Weeks  
```dataview  
TABLE  
month as "Month"  
FROM "600 Periodic/620 Weekly"  
WHERE month = "<% tp.file.title %>"  
```  
  
## Days  
```dataview  
TABLE  
month as "Month"  
FROM "600 Periodic/610 Daily"  
WHERE month = "<% tp.file.title %>"  
```