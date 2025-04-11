---
tags: work/proto_ventures, capabilities, work/industries/fusion, work/industries/nuclear_fission
---

## Description of capability
[[MIT Plasma Science & Fusion Center]] is proposing to develop a proton source using a cyclotron. This would be a precursor to the [[Fusion Prototypic Neutron Source]] that the fusion industry is talking about. It will cost approximately $25M and would leverage an [IBA Ikon](https://www.iba-radiopharmasolutions.com/cyclotrons/cyclone-ikon/) cyclotron.

It consists of a 10-30 MeV proton beam that uniformly irradiates materials at 0.1-1 mm depth, at a relatively high current (1.6 mA). Preliminary results indicate that proton irradiation in the 0-5 dpa range results in the same changes to yield strength and ultimate tensile strength as neutron irradiation at the same doses. The claim is that in this regime, proton damage is similar to neutron damage, _except_ for the fact that protons don't transmute in the same way as neutrons.

## Key people
- [[Dennis Whyte]]
- [[Mike Short]]
- [[Zach Hartwig]]
- [[Sara Ferry]]

## Technology Readiness Level (1-9)
7

## Needs that this could potentially address
- [[Understanding materials degradation in a deuterium-tritium fusion environment]]
- [[Understanding materials degradation in a nuclear fission reactor]]
- [[Electronics that can sustain Single Event Effects in space]]
- Predicting tritium retention inside the core

## Tech specs
Unknown

## Estimated time & cost to commercialize
The nuclear testing requires high current at ~30 MeV. Space testing requires ~250 MeV protons, which is well aligned with what the existing medical proton therapy devices already do.

What remains to be developed according to [[Lou Wainwright]]:
- Get target in front of the beam. 
- Manage temperature of the targets.
- Homogeneous beam distribution across targets.
- Do metrology on the samples.

[[Zach Hartwig]]'s vision is:
- PSFC raises funds to purchase the cyclotron. Starts testing and demonstrating. Maybe invents and patents some novel materials in the process. NewCo employees hang around and participate for learning purposes.
- NewCo is founded in parallel, mostly a shell company at first, does the business model and the initial pitching and the customer research.
- Once the technique is sufficiently demonstrated, NewCo raises a bunch of money, builds its own facility. Licenses IP from MIT. 

## Outstanding risks
- There may not be a demand for proton irradiation testing, given that neutrons are primarily what's relevant.
	- Neutrons transmute differently than protons. If you shoot steel or concrete with neutron, you'll get transmutation. One of the main phenomena that people are worried about is helium creation, which creates pockets in the material. So alpha particle emission is a key topic. You can induce alpha formation with protons, but differently.
	- Neutrons and protons have different penetration depth. And different damage profiles.
	- Having said all that, MIT's thesis is that the most important thing that damages in materials are ballistic interactions that leaves voids, create defects, etc. So to first order, if you take a thin foil and blast it with neutrons or protons, and they'll create the same displacements.
	- There is an ongoing [[ARPA-e]] proposal at [[MIT Plasma Science & Fusion Center|PSFC]] with Stony Brook to make a high-flux neutron source. That would become operational in 10-15 years. In 10-15 years, we'll have neutron testing. But nothing until then! We could in 24 months have a machine with high fluxes of protons. It's much better than nothing.
- The commercial fusion industry may not be actively paying attention to materials testing needs for another ~decade, at which point perhaps [[Cyclotron proton source|FPNS]] and/or other facilities will already be online.

## References
- https://web.ornl.gov/sci/vlt/pdfs/FPNSSummaryReport01102019.pdf
- Conversation with [[2023-05-12 Lou Wainwright]]
- Compare with the [International Fusion Materials Irradiation Facility](https://en.wikipedia.org/wiki/International_Fusion_Materials_Irradiation_Facility)
- Jepeal, S. J., A. Danagoulian, L. A. Kesler, D. A. Korsun, H. Y. Lee, N. Schwartz, B. N. Sorbom, E. Velez Lopez, and Z. S. Hartwig. “An Accelerator Facility for Intermediate Energy Proton Irradiation and Testing of Nuclear Materials.” Nuclear Instruments and Methods in Physics Research Section B: Beam Interactions with Materials and Atoms 489 (February 2021): 41–49. https://doi.org/10.1016/j.nimb.2020.12.020.
- Jepeal, Steven, Lance Snead, and Zachary Hartwig. “Intermediate Energy Proton Irradiation: Rapid, High-Fidelity Materials Testing for Fusion and Fission Energy Systems.” arXiv, November 25, 2020. https://doi.org/10.48550/arXiv.2009.00048.
