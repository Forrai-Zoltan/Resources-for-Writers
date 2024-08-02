---
tags: Note-type/DB
Note: "_Podcasts_"
TODO: 
---
# Not Linked

```dataview
TABLE Note, TODO
FROM -outgoing([[-Podcasts]]) and "05–Writing-Research/03–Toolkit/Resources-for-Writers/Podcasts"
SORT file.name ASC
```

***
# All Pages

```dataview
TABLE Note, TODO
FROM "05–Writing-Research/03–Toolkit/Resources-for-Writers/Podcasts"
SORT file.name ASC
```
