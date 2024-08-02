---
tags: Note-type/DB
Note: "_Journals_"
TODO: 
---
# Not Linked

```dataview
TABLE Note, TODO
FROM -outgoing([[-Journals]]) and "05–Writing-Research/03–Toolkit/Resources-for-Writers/Journals"
SORT file.name ASC
```

***
# All Pages

```dataview
TABLE Note, TODO
FROM "05–Writing-Research/03–Toolkit/Resources-for-Writers/Journals"
SORT file.name ASC
```
