---
banner: "https://wallpaperboat.com/wp-content/uploads/2019/06/minimalist-desktop-36.jpg"
tags: dashboard
banner_y: 0.5
---

# Learning Center

## To Learn

### Watch List
```dataview
TABLE
tags as Type,
for as Project,
priority as Priority,
link as Link
FROM "200 Watch List"
SORT priority descending
```
### To reread
```dataview
TABLE
tags as Type,
for as Project,
author as Author,
link as Link
FROM "300 References"
WHERE contains(reread, "yes")
```
### To finish
```dataview
TABLE
tags as Type,
for as Project,
author as Author,
link as Link
FROM "300 References"
WHERE contains(finished, "no")
```
### Music
```dataview
TABLE
row["tags"] as Type,
row["start-learning"] as "Start Learning",
row["Topics"] as Topics
FROM "500 Personal/510 Music Journal"
WHERE contains(can-play, "no")
```

## Learned

### Favourites
```dataview
TABLE
tags as Type,
for as Project,
author as Author,
link as Link
FROM "300 References"
SORT for ascending
WHERE contains(loved, "yes")
```

### All References
```dataview
TABLE
tags as Type,
for as Project,
finished as Finished,
rating as Rating,
link as Link
FROM "300 References"
SORT finished descending
```
### Music
```dataview
TABLE
row["tags"] as Type,
row["start-learning"] as "Start Learning",
row["Topics"] as Topics
FROM "500 Personal/510 Music Journal"
WHERE contains(can-play, "yes")
```
