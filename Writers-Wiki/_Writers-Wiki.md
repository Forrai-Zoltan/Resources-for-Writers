---
tags: Note-type/DB
Note: "_Wiki_"
TODO: 
---
# Not Linked

```dataview
TABLE Note, TODO
FROM -outgoing([[-Writers-Wiki]]) and "05–Writing-Research/03–Toolkit/Resources-for-Writers/Writers-Wiki"
SORT file.name ASC
```

***
# Database

```dataview
TABLE Note, TODO
FROM "05–Writing-Research/03–Toolkit/Resources-for-Writers/Writers-Wiki"
SORT file.name ASC
```
