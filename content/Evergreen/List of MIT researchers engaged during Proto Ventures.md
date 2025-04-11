---
tags:
  - work/proto_ventures
type: list
---
```dataview
TABLE
FROM #people AND #work/psfc 
WHERE contact_type != "internal" AND met != false AND company = "MIT"
SORT file.name DESC

```
