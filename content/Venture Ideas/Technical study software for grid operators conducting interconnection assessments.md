---
tags:
  - venture_ideas
  - work/industries/grid
  - work/proto_ventures/team_projects/grid_interconnection
stage: Discovery
---
## Description of venture idea
Delivers software that electric utilities adopt to speed up the grid interconnection study process. Focuses on increasing visibility, automating various steps, and reduce procedural barriers in the study process.

## Market needs this venture would address
For ISOs/RTOs, utilities, and/or their interconnection consultants (e.g. [[Black & Veatch]]): [[Shortening the transmission grid interconnection queue for new electricity projects]]

## Solution
Power flow modeling software for cluster feasibility studies that:  
1. Seamlessly integrates data & assumptions from physical T&D power flow, T&D planning, and production cost  
2. Automates parts of the feasibility study process that are currently manual  
3. Runs faster


> [!NOTE] Note
> Stability, protection, EMT, and QSTS are typically modeled using different software. We're assuming we'd replace stability software but we are not sure.

## Technical capabilities this venture might leverage
- Parallelization on GPUs and other modern high performance computing features  
- Gen AI for automation of manual steps

## Business model
Get energy project developers to pay for the software on behalf of the utilities

## Team
None - [[Scott Burger]] has some good thoughts on this topic. This dovetails well with [[Geo-mapping software platform to help energy developers optimize new project proposals]]. For example:
>First sell to developers to help them identify the best sites and estimate the cost of interconnection. Then go to the utility: "Hey utility, all the developers are using this; don't you want to see all the data of where they're exploring sites, what their estimates are looking like, etc?" 

## Critical hypotheses and outstanding risks
- "There is a desire among ISOs for power flow software that integrates the processes & data of siloed teams "
- "Incumbent and emerging solutions (e.g. [[Pearl Street Technologies]]) are insufficient"
- "TAM is big enough"
- "Customers will gladly adopt a new but better solution (on a reasonable timeline)"
- "Speeding up feasibility studies would meaningfully accelerate the overall queue time"
- "There are manual parts in power flow studies that can be automated"
- Market risk: [[Phil Giudice]] is not bullish on this: utilities feel that if there was a better way to do something, they would have already done it. By definition, anything new is riskier than existing solutions in their view.

## References
[[Scott Burger]] writes via email:
>Generally speaking I think there are tools that project developers are paying for and would be willing to pay for enhancements on. Siting is a general challenge that involves many layers of data, including interconnection, and the best-in-class shops are using tools that provide various cuts at those layers.  (see [[Geo-mapping software platform to help energy developers optimize new project proposals]])
I could certainly see a world in which interconnection tools are paid for by developers and provided to the utility for free. The adoption of the tool by the utility would be of immense value to the developers on the platform, so there's a strong incentive to make that frictionless to the utility. Likewise, a utility may be more willing to adopt a tool that many developers are already using. 
I see (at least) three problems with interconnection right now:
>- Procedural: the study process; SW / **startups may increase visibility, automate various steps, and reduce procedural barriers.** 
>- Regulatory: the process by which costs are allocated and thresholds are set (e.g. connect and manage vs. pay to connect). It's not immediately obvious to me what the role of SW / startups is here. 
>- Technical: **the process by which we assess impacts. There are some interesting opportunities here**, some of which are being explored by startups like [[Pearl Street Technologies]]. 

Scott sees an opportunity to develop better software for power project developers (and ultimately for utilities) that helps them identify the best sites for new projects and estimate the system upgrade costs that they will be responsible for.