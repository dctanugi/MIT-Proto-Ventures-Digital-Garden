---
tags:
  - work/proto_ventures
  - venture_ideas
  - work/proto_ventures/team_projects/grid_interconnection
  - work/industries/grid
stage: Discovery
---
## Description of venture idea
- Provide a comprehensive planning software solution for distribution utilities like [[National Grid]] or [[Commonwealth Edison]].
- These entities are good customers for several reasons: they are centrally managed, keen to support more electrification, and are eager to build new capital assets. They have less incentivize to optimize the use of existing assets, but they probably do want to understand how to manage their existing assets to meet the increasing peak demand.

## Market needs this venture would address
- Accounting for uncertainty (i.e. the wide range of load growth forecasts, or the location of future [[Distribution network planning for large spot loads with confidence|spot loads]]) in network planning
- Faster and more automated ways to plan new asset development
- Leveraging the full suite of modern options (including reconductoring and non-wires alternatives) for optimal reliability and maximum electricity sales as part of the solution development
- Optimizing capacity of the existing system through **non-wires alternatives**, for example with demand management at high resolution
- Understand the current system through a centralized, accurate, real-time digital system of record for all existing network assets

## Solution
We envision a planning software that:  
1. Generates network plans that are based on the probability distribution of future conditions, not on a single forecast scenario.  
2. Includes non-wires alternatives and other modern options as part of the optimization process  
3. Fully accounts for the implications (and promise) of DERs and storage, both utility-owned and customer-owned.

## Differentiation
Reference Network Model from IIT Comillas lets us automatically compute the network implications of thousands of forecasting scenarios (rather than the single-scenario manual study typically run by network engineers today).

Other:
- https://arpa-e.energy.gov/technologies/projects/smartdata-grid-models
- https://eesg.mit.edu/publication/paper-2022-interactive-planning-and-operations/paper-2022-interactive-planning-and-operations.pdf
- Some of the network analysis tools that are being commercialized by [[Waya Energy]] https://energy.mit.edu/news/power-to-the-people/

## Critical hypotheses
- 🚧 Distribution grid expansion would go faster with better modeling  
- ❌ Existing distribution grid could handle more load (in status quo) with better modeling and recommendations for NWAs  
- Planning teams at distribution utilities will gladly adopt a new but better network planning platform (on a reasonable timeline)

## Business model


## Team


## Outstanding risks
- Competition (see Blunomy [Vision](https://vision-grid.com/))
- One key risk is that the planning teams at utilities might not actually care about doing a better job at planning (e.g. modeling uncertainty). Executives like [[Steve Caldwell]] may want this, but the actual planning team might be need to be pushed by the regulator before they adopt something better. They had to go through all this trouble to get the regulator to approve their current methodology in the first place.  (see [[2024-04-16 Scott Burger]])

[[Quinn Nakayama]] cautions:
>It's hard for third parties to break into this space because in order to be truly effective this space, you have to be a planning engineer using our tools, our regulatory framework, and our procedures. Even Quanta, Black & Veech, they have a hard time breaking into this space because they don't have PG&E's really practical know-how.

## References
Suggested by [[2024-01-05 Frank O'Sullivan]]

[[Olivier Pinçon]] recommended interviewing:
	- **Utility planning departments**, e.g.:
		- What is your process?
		- For transmission planning, distribution planning, interconnection requests
		- How do you interface with other teams?
	- **People who sell software for utilities**
	- In certain geographies, the utilities come together, e.g. the "**Joint Utilities of New York**" to look into these future things. Speak with those folks too.

[[Ryan Hledik]]'s understanding is that there are already solutions for utilities to automate their distribution systems. He isn't sure whether these solutions are sufficient enough. If they aren't satisfactory, then Ryan agrees there is a good opportunity here. Distribution utilities would probably be pretty happy to better manage their distribution system (relative to managed load). Ryan is less bullish on the 'managed load' part of the idea. There are already many DERMS providers that claim help utilities manage their DERS. It's never clear how they distinguish themselves from each other. Utilities seem to think that none of them solve their problem. But either way, DER management feels like a crowded space already.

[[2024-04-05 Roger Kranenburg (Eversource)|Roger Kranenburg at Evesource]] writes: Capacity planning is related to interconnection, since proactive planning avoids some of the need for complex network upgrades on a one-off basis. The real need in capacity planning is for systems that let you plan *probabilistically*. The industry is undergoing a cultural change: engineers are traditionally trained to think deterministically. We are moving towards a world where you have to think probabilistically. But of course, the regulatory environment is not suited for probabilistic thinking. This is related to [[Steve Caldwell]]'s comments about modeling uncertainty, but it's also a fact that we typically ask customers: "Tell me your peak power need". We should move towards asking: "Tell me your profile over the year, and how critical it is that you have all 100 MW. I may be able to guarantee you for all hours of the year except these five." (Note: there is a concept in the industry called 'interruptible load', but it didn't really work because customers would complain and eventually get their power restored)

[[2024-03-20 Steve Caldwell (National Grid)|Steve Caldwell at National Grid]] talked about this as well (see [[Better long-term utility planning that can incorporate uncertainty]])

Top opportunities for this software according to [[Lisa Salmore]] at [[National Grid]]]:
- Help utilities plan for spot loads
- Replacing Eaton CYME with a better tool for the system planning team
- Helping the planning team optimize energy storage (both utility-owned and BTM)
- Integrated planning (electric and gas) and “non-pipes alternatives”. Getting those last few customers on the street to switch to all-electric so you can retire the gas pipe entirely.
- Recommending NWAs automatically as part of the planning or interconnection process (currently just an afterthought)