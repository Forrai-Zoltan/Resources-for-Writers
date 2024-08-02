---
tags: Note-type/DB
Note: "_Software_"
TODO: 
---
# Not Linked

```dataview
TABLE Note, TODO
FROM -outgoing([[-Software]]) and "05–Writing-Research/03–Toolkit/Resources-for-Writers/Software"
SORT file.name ASC
```

***
# All Pages

```dataview
TABLE Note, TODO
FROM "05–Writing-Research/03–Toolkit/Resources-for-Writers/Software"
SORT file.name ASC
```
