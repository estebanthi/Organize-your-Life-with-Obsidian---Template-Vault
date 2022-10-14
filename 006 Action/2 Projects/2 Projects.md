---
banner: "https://i.redd.it/qmm6mqqdw3k41.jpg"
cssClasses: cards
banner_x: 0.5
banner_y: 0.66466
tags: dashboard
---
⠀
# Projects Dashboard
```dataview
TABLE
	string("Target: " + target) AS "Target",
	string("Goal: ") + goal AS "Goal",
	string("Deadline: ") + deadline as "Deadline",
	string("Complete: ") + complete as "Complete"
FROM "006 Action/2 Projects"
WHERE file.name != "2 Projects"
```