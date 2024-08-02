---
tags: Note-type/DB
Note: "_Books_"
TODO: 
---
# Not Linked

```dataview
TABLE Note, TODO
FROM -outgoing([[-Books]]) and "05–Writing-Research/03–Toolkit/Resources-for-Writers/Books"
SORT file.name ASC
```

***
# All Pages

```dataview
TABLE Note, TODO
FROM "05–Writing-Research/03–Toolkit/Resources-for-Writers/Books"
SORT file.name ASC
```
