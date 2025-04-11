---
tags:
  - capabilities
  - work/proto_ventures
  - work/industries/grid
---
## Description of capability
[[Daniel R Cohn]] has proposed using cheap engines (fueled by natural gas in the near term, or hydrogen or ammonia in the longer term) to provide load balancing for the power grid.

In the long run, this could enable a firm, dispatchable, load-following, fast-ramp up, and emission-free power source for the 21st century. In contrast, fusion and fission are not fast ramp up, and fission is not load following.

In the short term, this could enable a lower NOx alternative to diesel generators. It could also compete with natural gas peaking power plants (faster cold start, lower NOx). It could also provide power in dense neighborhoods and possibly even provide heat (co-generation).

Cohn envisions ~20 engines acting as generators in a large container, producing 3 MW per container.

This could become the de factor way of converting ammonia to power: in a hydrogen world, ammonia is the primary carrier. You cannot burn ammonia in a gas turbine (although IHI and others are trying), so this could become the de factor way of converting ammonia to power. 

If the $150/kW capital cost is true, some back of the envelope calculations suggest that the levelized cost of electricity (LCOE) for this system would be $0.05-0.08/kWh if it runs on natural gas. That is roughly on par with utility-scale solar PV. If the system runs on hydrogen produced on-site from solar, we are talking $0.15/kWh. This is very sensitive to capacity factor: need 25% or more to make economical sense.

If we wanted to power a 3 MW container with hydrogen produced via electrolysis and produced from solar PV, we'd need a 5 MW solar farm. That farm would cost $15M and would consist of 15,000 solar panels covering 20 acres. The container itself, allegedly, would only cost $0.5M.

For comparison, [[Moxion Power]]'s [MP-75](https://www.moxionpower.com/technology/) battery trailers provide roughly 35 kW at 208 V (three-phase), with 530 kWh of usable energy. They can provide energy for 12-48 hours depending on the loading.

An MAE module consists of:
- A set of spark ignition engines
- A set of EV motors physically coupled to them (the coupling should be relatively straightforward)
- A set of automotive power rectifiers, which convert from the motor's AC output to DC current at ~600 V
- A cooling system, hopefully just some fans and radiators*
- A power inverter (e.g. from utility-scale solar) that takes all the DC inputs and converts into a single 60 Hz 3-phase AC power*
- A fuel tank*
- A control system*

Items with asterisks * are not accounted for in the $150/kW cost estimate.

## Key people
[[Daniel R Cohn]]
[[Leslie Bromberg]]
[[Robert Stoner]]
[[Howard Gruenspecht]]

## Technology Readiness Level (1-9)
3

## Needs that this could potentially address
- Backup power for critical infrastructure (compare with commercial and industrial backup generators)
- Intra-day supplementary electricity (compare with OCGT and batteries) (see [[Duck curve]])
- Multi-day long-duration energy storage (compare with CAES, and large reciprocating engines from Wärtsilä and Jenbacher. Also [[Form Energy]].).
- Power generation for off-grid locations (e.g. [[How do you power a mine using clean energy?]])
- Baseload power for the bulk grid
- Marine applications: ammonia to move ships? Maybe there is a new market for marine engines? Containers that burn ammonia, Ahmed Ghoneim knows about this stuff. 
- An ammonia storage tank to produce 1 GWh of electricity would be about 500 cubic meters large.

## Tech specs
- Overnight capital cost: $150/kW
- Fixed O&M ($/kW/Year): Unknown
- Variable O&M ($/MWh/Year)
- Heat rate: 8500 Btu/kWh
- LCOE: $0.05-0.08/kWh
- [[Guiyan Zang]] estimates that if the fuel is ammonia, the fuel costs $0.15 (if it comes from blue hydrogen) to $0.35 (if it comes green hydrogen) per kWhe.

## Estimated time & cost to commercialize
- 2-5 years
- $10-50M

## Outstanding risks
- How is this different from reciprocating engines already being used for grid reliability ([source](https://www.energy.gov/sites/prod/files/2016/09/f33/CHP-Recip%20Engines.pdf) and [source](https://www.eia.gov/todayinenergy/detail.php?id=37972))
## Other notes
- Balance-of-system equipment includes:
	- Step-up transformers
	- External low-voltage power lines
	- Fuses
	- External tanks, e.g. for fuel
- Prior art:
	- https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20160273211 (Container)
	- https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20170237264 (Parallel set of electric generators)
	- https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/8427005 PowerSecure, acquired by Southern Company in 2016 ([link](https://news.google.com/articles/CBMieGh0dHBzOi8vd3d3LmdyZWVudGVjaG1lZGlhLmNvbS9hcnRpY2xlcy9yZWFkL3NvdXRoZXJuLWNvbXBhbnktZ29lcy1iaWctaW50by1taWNyb2dyaWRzLXdpdGgtNDEzbS1hY3F1aXNpdGlvbi1vZi1wb3dlcnNlY9IBdmh0dHBzOi8vd3d3LmdyZWVudGVjaG1lZGlhLmNvbS9hbXAvYXJ0aWNsZS9zb3V0aGVybi1jb21wYW55LWdvZXMtYmlnLWludG8tbWljcm9ncmlkcy13aXRoLTQxM20tYWNxdWlzaXRpb24tb2YtcG93ZXJzZWM?hl=en-US&gl=US&ceid=US%3Aen))
	- https://image-ppubs.uspto.gov/dirsearch-public/print/downloadPdf/20140210213 
- According to [[2023-09-14 MITei Annual Research Conference]],  it _is_ actually feasible to modify modern, large frame gas turbines to take up to 100% hydrogen as fuel.

## Competitors
- [[Mainspring Energy]] (https://www.mainspringenergy.com/)
-  [[Radiant Nuclear]] has a similar value proposition as [[Multiplexed auto-derived engine power modules]]
- [[Aza Power]] (https://www.azapowersys.com/)

## References
- [[2023-07-21 Multiplexed auto-derived engines (slides)]]
- [[2023-07-14 Dan Cohn]]
- [[2023-07-21 Multiplexed auto engines (Rob Stoner, Leslie Bromberg, Dan Cohn)]]
