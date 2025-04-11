---
tags:
  - capabilities
  - work/proto_ventures
  - work/industries/fusion
aliases:
  - RAM-3D
---
## Description of capability
### Problem statement
- The problem that [[Rapid Automated Materials - Design, Downselect, Deploy (RAM-3D)]] sets out to solve: the traditional approach to nuclear materials is too slow. This is a "cook and look" method with a 5-7 year cycle time.

### Approach overview
- The basis for this approach is to *stop* using neutron radiation as a design tool. Instead, it becomes a verification & qualification tool for candidates.
- This approach relies on both computational methods and experimental framework.
- Currently using plasma vapor deposition (PVD) and arc melting for synthesis, paired with TGS and nano-indentation for characterization.

### Step 1: Computation
- Computational tools:
	- Computational thermodynamics.
	- Activation analysis and neutronics modeling.
	- Radiation resistance prediction tool
	- Ductility and strength models
- Computation:
	- **Activation**: (currently using FISPACT soon to use OpenMC): which materials have a Sieverts per hour or specific activity that is acceptable for maintenance, short-term storage, long-term storage, and recycling? Given a certain neutron dose, what is the radioactive activity, tritium production, and helium production over time of this material? This lets you downselect from 1E20 to 1E12
	- **Computational thermodynamics** (using CALPHAD).  Input composition, with constraints (e.g. no [Laves phases](https://en.wikipedia.org/wiki/Laves_phase)). This tells you which compositions are single phase and their estimated properties (strength, conductivity, even coefficient of thermal expansion). This gets you to 1E3.
	- **[DBTT](https://en.wikipedia.org/wiki/Ductility)** (specific to BCC alloys). Input is composition. Output is whether this alloy has inherent ductility (which is desirable). This gets you to ~50 candidates.
	- **DFT**: Input is composition ranges. We train a potential within this region. We're left with 10-30 candidates.

### Step 2: Wafer synthesis and testing
- Aiming for 20-30 wafers (~ 1.5 µm thick). Initially, the idea was to have grating on each wafer, but Myles is concerned about delamination or composition control.
- One of Myles' UROPs (Eleni) wrote a code that predicts the atomic composition within 0.01% as a function of PVD machine input parameters. You can't quite specify the atomic composition, but you can specify operating parameters of the PVD machine. Trying to get it patented.
- Another UROP (Alex) is working on the characterization of wafers using TGS, which is nontrivial because the depth of TGS is thicker than the wafers (so that the TGS is measuring the substrate as well). Making thicker wafers would make it hard to get uniform radiation damage. 
- Perform radiation damage using ions (currently thinking silicon). If the TGS signal doesn't change that much when we irradiate, then that means the material is probably radiation-resistant (or self-healing).
- We're also looking for high thermal diffusivity, since that's desirable inside a fusion system.
- If we had nano-indentation, we'd also look for high hardness (Vickers hardness test)

### Step 3: Bulk ingots
- We take the best and the worst thin wafers, recreate them in bulk with arc melting (ingots on the inch scale). Then we cut them with wire EDM. This lets us do bulk characterization. This bulk characterization of heat capacity, CTE, yield strength, DBTT, and thermal conductivity lets us compare with both the computational predictions and wafer results (ideally also we also do I3-TGS).

### Opportunities for closed-loop operation
You can correct or reinforce some of the computational models based on your experimental results. This is true for CALPHAD and DBTT. Strength, conductivity, coefficient of thermal expansion, and DBTT in particular.

### Applications
- For refractory metals with BCC structure (relevant for fusion vacuum vessel and plasma facing components), the parameter space is 1E20 (assuming the minimum % for any atomic species is 1 atomic percent). The goal is to down-select to 1-10 candidates from this 1E20.
- Only useful for nuclear materials? You get the best bang for your buck with nuclear materials, but it could also help with high-temperature materials (e.g. for [Materials Development for Hypersonic Flight Vehicles](https://ntrs.nasa.gov/api/citations/20070004792/downloads/20070004792.pdf)).

### Limitations
- This is good for crystalline alloys: not good for composites. You could do it for FCC materials too. 
- Doesn't handle precipitation strengthening. It only deals with single phase.
- Capital-expensive:
	- Arc melting
	- PVD

### Status:
- For bulk measurements, we can do Cp, CTE, soon $\sigma_Y$ at 800 ºC, $\kappa$ , and I3-TGS.
- We can do ARC melting
- We can do I3-TGS on wafers. 
- We can make the wafers. It's slow and the machine in the Short Lab is terrible.
- Lacking a lab space to do this at MIT!
- Myles also hopes to prove that DFT can predict radiation resistance. The approach is to map out of the potential energy landscape for vacancies. The hypothesis is that rougher landscape correlates with radiation resistance, and the approach to testing this would be to do I3-TGS on resulting samples and show that the compositions predicted in DFT to be radiation-resistant yield more stable TGS readings when irradiated.

## Key people
[[Myles Stapelberg]]
[[Mike Short]]

## Technology Readiness Level (1-9)
2-3

[[Mike Short]] is now looking
>for industry funding to quickly find a second application area in which to prove things out, and I'd love to have some ideas of where we could go. [He is] thinking a 2 year maximum effort, where then we'd have two test cases (V-alloys and TBD) to show the more universal power of the framework.

## Needs that this could potentially address
[[High-throughput alloy design for fusion RF antennas]]
[[High-throughput alloy design for fusion vacuum vessels and plasma-facing components]]

[[Myles Stapelberg]] writes:
>One of the big limitations that [[QuesTek Innovations]] had with their original business model in my opinion (doing materials design as a service) was that they lacked the ability to rapidly validate their results. They would go from computational modeling straight to bulk processing and it was still lengthy and expensive. They now have pivoted to being a software as a service company giving companies with their own materials testing the ability to computationally design their materials.

I still see the issue of linking models to experiments in a quick manner. Perhaps this is where value could be generated and also made Fusion Agnostic?

## Tech specs
TBD

## Estimated time & cost to commercialize
TBD

## Outstanding risks
TBD

## References
[[2023-11-13 RAM3D Myles Stapelberg]]