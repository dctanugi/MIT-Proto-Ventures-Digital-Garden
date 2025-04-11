## Key pain points
- Access to (reliable) power
- Cooling
- Water
- Energy costs
- Cleaner backup generation

## Opportunities in the data center industry
- For [[Kai Chen]] at Microsoft (formerly AWS), the two main headaches for data centers are **access to reliable power** and **cooling demand**.  **Water** access and water quality is another major headache.  **Land** cost is a major constraint, often making onsite renewable energy infeasible.
- "**Power capping** reduces clock speeds during peak demand periods and so can improve resilience and lower electricity costs." Can be useful for DR but also for microgrid control.

According to [[Andy Lubershane]]:
> I think your thesis on data center energy needs & pursuit of behind-the-meter solutions to accelerate time to power (ideally time to clean power) is correct.  (We actually did deep dives on both data centers and microgrids last year.)  Unfortunately, these are pretty tricky pain points to address.  In particular, there’s only one obvious replacement for diesel gensets which offers similarly rapid time to power alongside days-to-weeks of backup supply: natural gas gensets (or ‘linear generators’ a la [[Mainspring Energy]], or fuel cells – neither of which makes sense relative to a modern, clean, efficient conventional gas  genset, IMO).  Our portfolio company [[Enchanted Rock]] is starting to benefit from this trend.  Frankly, all of the other challenges are small compared to this big challenge: data centers want clean power, but they need any sort of power, and right now the power they can get in a timely fashion is natural gas generation.  But they are thinking longer-term.  It’s no surprise that Microsoft hired a head of nuclear last year…

## Hypotheses to test
- Hypothesis: The [[Data centers]] market wants to move towards substantial onsite generation, not just backup generators
- Hypothesis: Data centers really want the ability to island themselves from the main grid (and do not have it today)
- Hypothesis: If you have onsite generation and batteries, then you need a microgrid
- Hypothesis: Managing the power network of a data center with substantial onsite generation is a headache even when not islanded
 - Hypothesis: For data centers that just want backup generators, current solutions are not good enough
 - Hypothesis: O&M is a major pain point for data center operators (what kinds of data centers?)

## Misc
- Researchers have suggested using series-connected interline superconducting magnetic energy storage for transient energy management and load protection. (Chen et al. 2023)
- Thermal storage to provide load flexibility??

## Other learnings & ideas
- Data centers:
	- The cooling system (and its electrical requirements) is a major challenge
	- Need a lot of water for cooling
	- Land is often also a constraint
	- Getting power connection take up to 3 years
	- Getting even more power-hungry due to AI, etc.
	- People are looking at nuclear SMRs for onsite generation
	- The idea of data centers colocating with utility-scale renewable energy projects seems plausible
	- Gas turbines for tri-generation seem promising
	- Power losses are not a major concern (even though we'd be highly motivated to solve this piece)
	- Virginia is instituting a moratorium on new data centers because of their excessive draw on the power grid
	- Unclear whether the data center is moving towards microgrids or not
	- Unclear whether data centers are willing to adopt new solutions
	- 💡 Thermal storage for data centers
	- 💡 District heating using data center waste heat

## Power in data centers
Cooling is responsible for roughly 50% of the energy consumption in data centers. The IT load uses another 37%, power distribution uses 10%, and the remaining 3% is lighting.

Larger data centers typically go for three-phase power at 208V or 415V. Smaller data centers use single-phase power at 120V or 240V. The former is more energy-efficient but is more complex and potentially costlier to implement.

