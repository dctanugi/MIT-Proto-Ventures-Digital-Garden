---
tags: needs, work/proto_ventures, work/industries/grid
---
## Description of need
Extreme weather events are escalating weather-related power outages, especially at the distribution level. Undergrounding power lines significantly increase reliability.

However, existing techniques are disruptive, slow, and costly. In particular:
>the **cost** of burying distribution power lines is significant, **up to five to ten times** that of overhead distribution lines, making it the major barrier to making such grid investment decisions. Furthermore, today's undergrounding processes pose **safety** concerns, such as **damage to other buried utilities** during construction, **occupational safety and health hazards** associated with tasks performed in a manhole, and lengthy **surface disruptions and traffic detours** affecting the safety of surrounding communities, making undergrounding a difficult project to undertake.

We need technologies that lower the cost and improve the speed associated with building underground power lines (both distribution and transmission). See [[Residential decarbonization in hard-to-electrify urban areas]].

## Problem severity (1-10)
9

## Who has this need
- Renewable project developers
- EV charging station developers
- Utilities
- Grid operators

## Total addressable market (TAM)
XXL

## Solutions today, and their shortcomings
- TBD
- Emerging competitor: [[Petra (startup)]] ([link](https://www.tdworld.com/intelligent-undergrounding/article/21183533/petra-unveils-the-first-tunneling-technology-for-utilities-to-bore-through-the-hardest-rocks-in-the-world))

## Potentially relevant capabilities
- Boring innovations in the fiber optics sector, e.g. [microtrenching](https://gcpat.com/en/about/news/blog/microtrenching-a-new-and-improved-way-install-fiber-optic-cable)
- Automated and rapid subsurface drilling
- Advanced look-ahead sensors
- Better cable joint designs and installation systems. Cable joints are typically the first to fail during operation. At [[ARPA-e]], there was especially interest in "automated cable splice installation systems as well as novel splice designs to ensure error-free and safe installation of cable joints".
- Surveys for AI predictive [[Digital twins]] of the subsurface
- ARPA-E GOPHURRS awards ([link](https://arpa-e.energy.gov/news-and-media/press-releases/us-department-energy-announces-34-million-improve-reliability))

## References
- https://campos.substack.com/p/before-and-after
- https://arpa-e.energy.gov/technologies/programs/gophurrs
- UNREAD https://arpa-e.energy.gov/events/undergrounding-workshop

## People to talk to
- Phil Kim at ARPA-E: https://www.linkedin.com/in/philseok/

## Feedback
### From [[Naimish Patel]] ([[2021-01-08]]):
>I seem to recall you were specifically thinking of less densely populated areas of the distribution grid, as opposed to urban centers. Why is this?

In developed countries, urban areas typically already have underground distribution. Developing nations is another matter, but the economic equation will be more challenging due to vastly lower labor rates. 

>Are you picturing a world in which undergrounding becomes the default way of building new distribution lines? The recent ARPA-E funding opportunity announcement for distribution undergrounding solutions targets a 50% reduction in cost, which would still put underground lines at ~5x the cost of above-ground lines.

Achieving cost parity with overhead distribution is highly challenging, and I don’t think should be the near-term objective. The best areas to target undergrounding will be those prone to weather related outages. Think suburban costal areas - [[Florida Power and Light]]’s service territory, for example, is particularly vulnerable to hurricane-induced outages and are actively spending capital to underground cables or replace wooden poles with concrete ones. 

>In your mind, is the value of undergrounding primarily in the weatherization and extra reliability?

Yes.

>Or is there a scenario in your mind in which new undergrounding solutions could actually accelerate grid buildout, e.g. by bypassing right-of-first-refusal issues and therefore making it possible to put a line where it wouldn't have been possible above-ground?

In developed nations, grid build-out has largely already been done - it’s only greenfield developments that drive entirely new build out. The real issue is the recurring cost of maintenance in areas prone to outages (tree trimming, etc.) in conjunction with the costs associated with outage recovery. Utilities are incentivized to spend capital (they get paid 8-12% on their approved capital expenditures), so it’s really about making an economic case for increased one-time capital expenses in exchange for lower recurring operating costs. Obtaining rights of way for distribution can be significantly easier once a public utility commission paves the way. Shallow trenching (as opposed to deep boring) could potentially reduce siting / permitting hassles, but I suspect this will not be the dominant driver. 

>Could you point us to some information about the recent innovations in fiber undergrounding that you had in mind?

Microtrenching technologies for optical fiber deployment are potentially applicable to electrical distribution, albeit while addressing the obvious safety concerns associated with 6-12 kV distribution. 

### From [[Paul Woskov]], regarding millimeter-wave drilling:
>It will be a little more challenging to use a millimeter-wave beam horizontally than vertically because gravity will act to flow a melt downward into the beam.  You will need greater beam intensity to quickly vaporize and/or high pressure to overcome gravity to push the melt out of the way to keep the beam propagation path clear.  Higher pressure would be an advantage to increase breakdown threshold to achieve higher beam intensity.  Millimeter-wave breakdown and high-pressure propagation will be your main challenges.

From [[Olivier Pinçon]]:
>There are studies that break down the cost of undergrounding.  Figure out the cost breakdown to estimate what microtrenching would solve.