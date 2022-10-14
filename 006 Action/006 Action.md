---
banner: "https://i.redd.it/ghbmrbnbhba81.png"
tag: dashboard
cssClasses: row-alt, table-small, table-max
banner_x: 0.5
banner_y: 0.5
---
⠀
#  ▲ Alignment
####  ◩ VALUES
```dataview
TABLE
why AS "Why"
FROM "006 Action/4 Values"
WHERE file.name != "4 Values"
```

#### ◎ GOALS
```dataview
TABLE
	why AS "Why",
	value as "Value",
	deadline as "Deadline",
	complete as "Complete"
FROM "006 Action/3 Goals"
WHERE file.name != "3 Goals"
```

#### ◺ PROJECTS
```dataview
TABLE
	target AS "Target",
	goal AS "Goal",
	deadline as "Deadline",
	complete as "Complete"
FROM "006 Action/2 Projects"
WHERE file.name != "2 Projects"
SORT complete DESCENDING
```
#### ⌁ ◶Trackers
```dataview
TABLE WITHOUT ID
	link(file.name) as "Day",
	row["cold shower"] AS "🚿",
	row["piano"] AS "🎹",
	row["guitar"] AS "🎸",
	row["workout"] AS "🏃‍♂️",
	anki AS "🎴",
	row["no-fap"] AS "🔞",
	reading AS "📖",
	row["improved-today"] as "Improved"
	FROM "600 Periodic/610 Daily" 
	SORT file.name DESC
	LIMIT 30
	WHERE file.name != "610 Daily"
```

