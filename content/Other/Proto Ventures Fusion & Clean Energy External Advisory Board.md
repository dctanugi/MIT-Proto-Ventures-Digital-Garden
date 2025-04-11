---
tags:
  - work/proto_ventures
aliases:
  - EAB
---
## Advisory Board meetings
```dataview
LIST
FROM #work/proto_ventures 
WHERE contains( lower(file.name), "advisory board meeting")
sort file.name desc
```
