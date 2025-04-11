---
aliases: MHD generators
tags: work/proto_ventures, capabilities
---
## Description of capability
A magnetohydrodynamic (MHD) power generation technique is a nonconventional electric power harvesting modality in which the electricity is generated from an ionised fluid flow under a magnetic field. The ionized fluid moving under a magnetic field works as a moving electrical conductor and the MHD generator generates electrical energy according to the Faraday's electromagnetic principle.

An MHD generator would be inserted between the heat generation and the steam cycle. Part of the point is that the heat may be coming out at 600 ºC or more, and that most steam turbines actually perform *better* at lower temperatures than that. MHD generators could significantly increase the efficiency of thermal power plants, as long as the outlet is 1000 K or higher.

The challenge is that the gas doesn't ionize much if the temperature is only ~1000 K (which is the best you can do with fission and fusion plants). But [[Jeffrey P Freidberg]] and [[Samuel Frank]] found that if argon is the coolant, you can create a plasma in which the electrons are much hotter than the ions in the background! The downside is that the plasma becomes unstable like that. Sam thinks he's found a way to stabilize the plasma using RF. He'll know in a few weeks.

## Background
According to [[Dennis Whyte]], an MHD generator uses high field magnets (and a hot fluid / gas) to convert kinetic energy in the moving fluid into electricity, with no moving parts. In the 1980s, there was a competition between turbines and MHD generators, and turbines won. But now we have much higher-field magnets. 2500 K outlet gas from a coal plant. Topping Cycle. 50% extraction of the enthalpy. Maybe we don't displace turbines anytime soon, but the power density scales as $T^2$ so maybe this is useful for remote applications? 

According to [[Jeffrey P Freidberg]], from the 1960s to the 1990s, the US had an MHD generator research program with hundreds of millions of dollars per year (including at MIT and at the Avco Everett Research Laboratory. In the 1990s, all MHD research in the US was terminated. There is zero effort on MHD energy conversion at the moment, except one modest-sized experimental program in Japan. According to [[Samuel Frank]], most of the research in this topic happened in the 1950-80s, and a lot of the papers haven't been digitized. There was an annual MHD Generator Conference, but there is no trace of the conference proceedings anywhere!

MHD energy conversion has two promising applications:
1. Retrofit existing coal power plants to reduce CO2 emissions by a factor of two. In a coal plant, the furnace heats some steam, which drives a turbine. The cycle efficiency can't get much higher than 30-40%. That's because there is a penalty in converting a high-entropy form of energy like heat to a low-entropy one. Put a MHD generator between the furnace and the steam turbine. Converts the energy directly to electricity without having to go through a thermal cycle. You still keep the steam turbine for the output from the MHD generator.
2. Improve the thermal efficiency of other thermal power plants that don't have a combined cycle, such as [[Nuclear fission]], [[Nuclear fusion]], or [[Concentrated solar power]]
3. [[Jeffrey P Freidberg]] isn't bullish on MHD as a primary cycle (e.g. for remote applications), because the efficiency wouldn't be much higher than 30%.

Note: MHD generators work better with high temperature steam (e.g. 2500 K, which is achievable with coal), less so with lower-temperature steam (e.g. 1000 K like [[Nuclear fission]] or [[Concentrated solar power]] or [[Nuclear fusion]]). The topping cycle uses the MHD generators. 

Why does it make sense to look at MHD generators again now?
- Development of [[High-temperature superconducting magnets]]. At the time, the max was 3 Tesla. We can get up to 15-20 T now. Improvements in power density scales as $T^2$. In fusion, energy density is ~ MW per m2. In MHD generators, it's easy to get to 100 MW per m2.
- [[Additive manufacturing]] could enable more complex and effective gas channels for the ionized helium plasma
- In 1960s-1990s, as we transitioned from coal to gas, nobody was worrying about CO2 emissions.

Peter Hsieh at the [[National Energy Technology Laboratory (NETL)]] is working on MHD generators: https://netl.doe.gov/node/9790

Note: You could also theoretically run an MHD generator in reverse, as a pump (e.g. for water or for a liquid metal).

## Key people
[[Jeffrey P Freidberg]]
[[Dennis Whyte]]
[[Samuel Frank]]
[[Matthew Clingerman]], who just finished his masters on this topic, together with Sam and [[Jeffrey P Freidberg]].

## Technology Readiness Level (1-9)

## Needs that this could potentially address
[[Increasing the efficiency of thermal power plants]]

## Tech specs
[[Jeffrey P Freidberg]] estimates that we can probably increase the efficiency of a nuclear plant from ~30% to ~55%, and cut the CO2 emissions of coal plants by a factor of two.

## Estimated time & cost to commercialize
[[Jeffrey P Freidberg]] and [[Samuel Frank]] are working on the theory of MHD generators with an [[MIT Energy Initiative]] grant that runs out in December 2023. 

If the results are promising, the next steps are:
1. Extend the theory to add more and more realism to the models.
2. Find a MechE or Aero/Astro professor who is interested in getting involved and leading an experimental effort (e.g. with [[ARPA-e]] funding).
3. ARPA-e proposal.
4. Build an pilot in the 1-10 MW range. Probably costs $10-100M. Needs to be big enough that edge viscosity and other effects don't dominate.

- IP opportunities:
	- Stabilizing the plasma with RF
	- Treating the channel as a nozzle, which lets you start supersonic and go down to Mach < 1 while avoiding shockwaves
- Key technical risks:
	- Plasma instability
	- Too much RF power required to stabilize the plasma
	- Loss mechanisms
	- Electrode performance and lifetime
	- Slag (for coal)
	- Plasma seed regeneration cost

## Outstanding risks
- You need 1000 K at minimum, otherwise you get plasma instabilities. You might be able to heat the plasma externally, e.g. with an RF antenna.
- Supersonic flows in the exhaust manifold might result in big pressure drops, which would reduce the efficiency significantly.
- Too much RF power required to stabilize the plasma
- Loss mechanisms
- Electrode performance and lifetime
- Slag (for coal)
- Plasma seed regeneration cost

## References
- [Open-cycle magnetohydrodynamic electrical power generation: a review and future perspectives](https://www.sciencedirect.com/science/article/abs/pii/S0360128503000637?casa_token=ZP-hOC_bYHIAAAAA:kbKO_79cf0knZ2GlSzxmkwnBOzUz0Trb_VOv6fYayDH5Nv-l66hYU_ZdMPHBwzWWVsBOl9j5PP8)
- https://www.sciencedirect.com/science/article/pii/S1110016816300126
- 1968 textbook about MHD generation (Richard Rosa), and a revised edition in 1995 (Hugo Messerlee) 
- [[2023-05-05 Jeffrey Freidberg]]
- [[2023-05-17 Samuel Frank]]
- [[2023-08-01 MHD generators with Jeff and Theo]]
