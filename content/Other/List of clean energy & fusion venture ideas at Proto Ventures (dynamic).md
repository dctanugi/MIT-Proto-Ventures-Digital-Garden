---
tags:
  - work/proto_ventures
  - work
  - private
type: list
publish:
---
> [!NOTE] Note
> This page makes use of DataView, which means it will not render properly in Obsidian Publish.

# By Stage:
Below is a list of venture ideas from the Proto Ventures process, categorized by stage of the process:
## 'Discover' Stage:
Early-stage gathering of as many venture ideas as possible. Sometimes a solution is identified and the application area is speculative; sometimes the application area is clear but the solution set is still speculative.
```dataview
LIST
FROM #venture_ideas AND "Evergreen"
WHERE stage = "Discovery" OR !stage
SORT stage, file.name

```

## 'Explore' Stage:

> [!NOTE] Note
> At this stage, Proto Ventures team members each explore 1-2 opportunity areas.
>
> Key activities include targeted exploration of technologies & market and team formation (potential cofounders, advisors).
```dataview
LIST
FROM #venture_ideas AND "Evergreen"
WHERE stage = "Explore"
SORT stage, file.name

```
## 'Build' Stage:
```dataview
LIST
FROM #venture_ideas AND "Evergreen"
WHERE stage = "Build"
SORT stage, file.name

```
## 'Launch' Stage:
```dataview
LIST
FROM #venture_ideas AND "Evergreen"
	WHERE stage = "Launch"
SORT stage, file.name

```
## Supporting:
```dataview
LIST
FROM #venture_ideas AND "Evergreen"
WHERE stage = "Support"
SORT stage, file.name

```
## Other Categorizations
One can also categorize these venture ideas by potential market size and likely venture type:
- Tadpoles: Promising and could become huge but need more R&D:
- Tunas: Improves an existing process. Good licensing opportunity:
- Orcas: Medium TAM (~$100M); Probably best fit for strategic VCs or a mega-fund.
- Moby Dicks: Large TAM ($1B+). Likely to capture a meaningful part of the value chain. Well poised to raise VC funding.