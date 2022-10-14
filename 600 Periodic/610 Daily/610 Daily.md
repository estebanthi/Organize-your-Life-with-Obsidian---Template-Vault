---
banner: "https://wallpapercave.com/wp/wp9583563.jpg"
---
⠀
# Daily Overview
 
```dataview
TABLE WITHOUT ID
	link(file.name) as "Day",
	row["cold-shower"] AS "🚿",
	row["piano"] AS "🎹",
	row["guitar"] AS "🎸",
	row["workout"] AS "🏃‍♂️",
	reading AS "📖",
	row["improved-today"] as "Improved"
	FROM "600 Periodic/610 Daily" 
	SORT file.name DESC
	LIMIT 30
	WHERE file.name != "610 Daily"
```
 
