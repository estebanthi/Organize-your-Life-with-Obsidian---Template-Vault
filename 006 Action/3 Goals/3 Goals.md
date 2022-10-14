---
banner: "https://assets.hongkiat.com/uploads/minimalist-dekstop-wallpapers/4k/original/10.jpg"
cssClasses: cards
tags: dashboard
---
⠀
# Goals Dashboard
```dataview
TABLE
	string("Why: " + why) AS "Why",
	string("Value: ") + value AS "Value",
	string("Deadline: ") + deadline as "Deadline",
	string("Complete: ") + complete as "Complete"
FROM "006 Action/3 Goals"
WHERE file.name != "3 Goals"
```