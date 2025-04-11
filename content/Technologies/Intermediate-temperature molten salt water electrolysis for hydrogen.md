---
tags:
  - capabilities
  - work/proto_ventures
  - work/industries/hydrogen
stage: Discovery
---
up:: [[Clean hydrogen]]
## Description of capability
A molten salt electrolysis technology for producing green hydrogen.

Key benefits:
- Can operate across a wider range of current densities (0-2 A/cm2), which allows for load-following similar to PEM (unlike liquid alkaline technologies)
- Does not require iridium (unlike PEM)
- Simple system for greater durability (no flowing electrolyte, no membrane)

Yogi and his group have a lab-scale prototype today.

For background, the three ways of doing [[Clean hydrogen]] production from water hydrolysis are:
- alkaline
- acidic PEM
- solid oxide

Alkaline is most mature, but cannot load-follow or operate at high current densities. PEM requires iridium so it's "not scalable". Solid oxide has durability problems and requires high temperatures.  This is a potentially improved way of doing alkaline electrolysis.

In this process, a basic (alkaline) electrolyte solution, typically potassium hydroxide (KOH) or sodium hydroxide (NaOH), is used. The electrolyte conducts ions and facilitates the migration of hydroxide ions (OH-) to the cathode and hydrogen ions (H+) to the anode. At the cathode, hydrogen gas is produced, while oxygen gas is generated at the anode.

## Key people
[[Yogesh (Yogi) Surendranath]]

## Technology Readiness Level (1-9)
3

## Needs that this could potentially address
[[Clean hydrogen]], especially for industrial hydrogen users. For example, one of the largest early buyers for hydrogen is probably in the mining sector - an example could be a iron ore miner looking to to H2 reduction of their ore on-site so they can ship the metal rather than the ore. The lower freight cost is probably the main value proposition for them (this is pitch that [[Boston Metal]] is making as well) with the decarbonization as a plus. Because of the geographic isolation of many mines - they'd have to likely rely on their own dedicated solar and wind placing a higher premium on ramp-up ramp-down.

[[Hydrogen production that can ramp down with variable renewable energy and doesn't depend on critical minerals]]

## Tech specs
With alkaline processes, flowing the solution through the electrodes is the limiting factor: it's a transport problem. Yogi doesn't have the people to do the more translational work on this. MITei has helped with techno-economic modeling. Need to do more applied bench-scale work to de-risk some aspects (e.g. **separator fabrication**) and to refine the technical data for a **techno-economic analysis**. The anodes and cathodes work well. But the bottleneck is that to make a cell well, you need to fabricate a really good separator (and that could also unlock IP).

## Estimated time & cost to commercialize
Unknown

## Outstanding technical risks

| Risk                                                                                                                 | Demonstration to retire this risk                                                                            |
| -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Failure and/or corrosion of the catalyst layer under variable operation                                              | TBD                                                                                                          |
| Electrolyte leakage                                                                                                  | No visual evidence of leakage, and no gas crossover after realistic intermittent operation                   |
| Operation at high current density (1-2 A) degrades the system                                                        | No loss of performance at 1-2 A operation                                                                    |
| Something intrinsic about the materials that makes these materials difficult to produce uniformly on the meter scale | Went from 1 cm -> 5 cm > 10 cm without significant issues                                                    |
| The balance of plant requires this system to be sized much larger in order to be economically favorable.             | A detailed techno-economic analysis indicates that the minimum viable system size is not prohibitively large |

## Key market hypotheses
**"If you believe that green hydrogen will play a large role in the future, then it is inevitable that a lot of this green hydrogen must be produced by a technology that doesn't require iridium and that can follow variable electricity availability." — true or false?**

[[Greg Thiel]] at [[Energy Impact Partners]] says:
>Generally true. Policy incentives aside, I have a hard time seeing how you get anywhere close to 1-2 $/kg H2 without the very cheap electricity that only comes when the sun shines or the wind blows. It’s been a while since I ran the numbers on Ir supply, but seem to remember being able to get sizeable H2 deployments if you could work down the Ir loading without eliminating it completely. Still, zero Ir would of course be better, which is why AEM is a nice next-gen approach – if you can get the membranes to last.

[[Leonardo Banchik]] at [[Voyager VC]] says:
>Yes my sense is electrolyzers will need to be rampable, but the iridium piece depends on whether efficiency or reliability is sacrificed by removing it. It will ultimately come down to the levelized cost of H2 which will factor in maintenance requirements (e.g. do electrodes need to be replaced every 6 months instead of two years?) and efficiency 


**Green hydrogen is still expensive today (e.g. relative to blue hydrogen, not to mention grey hydrogen), so what's motivating the early adopters who are buying PEM systems today?**

[[Greg Thiel]] at [[Energy Impact Partners]] says:
>Big question. A short answer is the IRA. Rules of course still pending, but $3/kg H2 is some juice. And some companies (EH2!) are also making much cheaper electrolysis systems than what’s been available historically. Blue hydrogen of course also needs CO2 (transport &) storage, which isn’t widely developed yet either, though I’ve seen a handful of announcements on some pretty sizeable projects on the Gulf coast.

[[Leonardo Banchik]] at [[Voyager VC]] says:
>Corporate altruism I'm afraid. I think the H2 space is massively over hyped, but still critical for us to green. 

**What's a realistic minimum system unit size in today's green hydrogen market (1 kW? 1 MW?)**

[[Greg Thiel]] at [[Energy Impact Partners]] says:
>Think it really depends on the market you want to sell into. Do you mean from a venture investor / tech proof perspective, or just generally the smallest commercially available electrolyzers?

[[Leonardo Banchik]] at [[Voyager VC]] says:
>Since they're modular systems, you can build em small or large by just adding more cells. Depending on current density, would take a look at existing electrolyzers systems you can find online to get a sense of scale

My own research suggests that 1 MW is a minimum module size for an industrially relevant system.

## Notes
MITei did a full process model ( [[Dharik Mallapragada]] et al.). In almost all cases they beat liquid alkaline in LCOH terms. To be beat PEM, the high end of your variable operation has to be at very high current density (1-2 A).

## References
- [[2023-08-18 Yogi Surendranath]]
- https://www.irena.org/-/media/Files/IRENA/Agency/Publication/2020/Dec/IRENA_Green_hydrogen_cost_2020.pdf
- Startup concept: [[hydrogen]]