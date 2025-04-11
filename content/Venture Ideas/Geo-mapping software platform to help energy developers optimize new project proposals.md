---
tags:
  - work/proto_ventures
  - venture_ideas
  - work/industries/grid
stage: Discovery
---
## Why this startup?
Developers submit hundreds of gigawatts worth of energy projects for grid interconnection approval every year, spending millions of dollars in land rights acquisition, engineering studies, and permitting. Yet the large majority of these proposed projects will never be built, a colossal waste for developers and the utilities performing interconnection studies alike.

Why is this happening? One major reason for both transmission- and distribution-level projects is that many projects turn out to require very expensive upgrades to the existing power grid ("network upgrades") before they can be connected. Often, choices in a project's configuration and siting could drastically reduce the interconnection cost of a project. But today, developers have extremely limited visibility into the network upgrade costs that will be required for a potential project, and virtually no way to optimize the configuration and design of a project (for example whether to include onsite battery storage, and if so, how much) to minimize the cost & time to get interconnected.

## Providing geo-mapping software to optimize energy projects
This company will deliver grid software to help energy project developers make financially savvier decisions with their new project proposals, offering:
- More visibility into potential network upgrade costs and time to commercial operation
- Fewer failed (i.e. overly expensive) interconnection applications due to siting choice

Unlike third-party siting tools and utility-provided hosting capacity maps — which only tell developers where there might be extra network capacity — this software will provide developers with estimates of the potential network upgrade costs and time to an interconnection agreement for any given project, ultimately providing them with the information they need to make informed project investments. The platform will also help developers optimize project configuration in a way that maximizes expected profitability and minimizes potential network upgrade costs.

This software will also benefit the myriad consulting firms that commonly work with energy developers on project siting and design.

## A unique approach to project estimation
This highly differentiated prediction & optimization software is made possible by a unique technical capability: the ability to automatically answer the question: *what network upgrades would be required to accommodate this potential project, and how much would they cost?*. Whereas conventional power flow software requires highly trained network engineers to manually experiment with potential upgrades until all the network violations triggered by the proposed project have been resolved, this software leverages leverages machine learning trained on massive data sets to rapidly generate an approximate network solution and estimate its costs.

The platform then uses this information to help developers identify optimal sites and optimal configurations for a new project based on factors such as:  
- Estimated time and cost of grid interconnection  
- Ease of environmental permitting  
- Likelihood of community resistance  
- Other factors (wind resource for renewable projects, car traffic)

## A large market
The renewable energy market exceeds $200B per year, with developers spending tens of thousands of dollars per project for siting and preliminary design work, and significantly more capital invested in projects that are ultimately abandoned due to prohibitively expensive network upgrade requirements.

## Current status and next steps
**Technology readiness level**: 1 - Concept formulated

**IP**: Relevant patents identified at [[Comillas Universidad Pontificia]], a partner institution to [[MIT]]

**Further de-risking:**
- Show that the technical capability described above works and provides sufficiently accurate estimates
- Confirm that we can access network data, interconnection study results, and other data that gives us an edge over potential competitors. Of note, FERC is considering requiring utilities to make grid models, previous cluster studies, and cluster study models available to prospective applicants (subject to a standardized confidentiality agreement).
- Quantify the dollar value proposition for project developers in having cost and time estimates and project optimization capability
- Further segment the market, in particular to determine whether project developers or engineering consulting firms are the best customers
- Refine competitive positioning with respect to Pearl Street Technologies, [Paces](https://www.paces.com/), [Nira Energy](https://www.niraenergy.com/), Rhizome, Orennia, and GridTwin.
## Maybe developers are just the beginning...
Project developers represent a strong first market with a strong financial incentive to submit cost-effective and successful projects. But electric utilities may also benefit from this company's offerings. 

 Utilities are slower to adopt new solutions, but they are centrally managed, keen to support more electrification, and eager to build new capital assets. Today, utilities employ a forecasting team that can easily generate thousands of scenarios for demand and supply. But the work of planning the network for any given scenario is very labor intensive, so the typical utility has no ability to model uncertainty. This company's core capabilities will help utilities with:
- Accounting for uncertainty (i.e. the wide range of load growth forecasts, or the location of future 'spot loads') in long-term grid planning.  
- Producing network plans that leverage the full suite of modern options (reconductoring, non-wires alternatives) for optimal reliability and maximum electricity sales.  
- Managing the queue of interconnection requests in a consistent way, including group studies  
- Keeping developers apprised of network capacity

## Competition
- Pearl Street Technologies  
- [Paces](https://www.paces.com/)  
- [Nira Energy](https://www.niraenergy.com/)  
- Rhizome  
- Orennia
- GridTwin

## See Also
- [[2024-02-16 Christina Karapataki]]
- [[2024-05-13 Chris Holcomb (siting software)]]
- [[2024-06-11 Ben Grace (National Grid)]]: Ben likes this idea. They do a lot of restudies when the project developer has changed their inverter, grounding design, GSU, etc.  They see a lot of changes in equipment that cause restudies (not necessarily a software problem). Probably a supply chain. Developers wouldd need a whole lot more data. That might solve the restudy problem but it might create a new problem: the developers and their consultants will challenge everything we say!
- [[2024-06-11 Steve Caldwell]]: maybe this is the same startup as [[Better long-term utility planning that can incorporate uncertainty]] (first sells to developers, then eventually starts selling to utilities)