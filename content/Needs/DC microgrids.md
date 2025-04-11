---
tags:
  - needs
  - work/proto_ventures
  - work/industries/grid
---
up:: [[Microgrids]]
## Description of need
The need for DC microgrids arises from the increasing integration of renewable energy sources, such as solar panels and wind turbines, which inherently produce direct current (DC) power, and the fact that many electrical loads (e.g. computers, [[Electric vehicles]], batteries) consume DC power.

DC microgrids offer greater efficiency in transmitting and storing this DC power, reducing the need for conversion to alternating current (AC) and minimizing energy losses. Additionally, DC microgrids enable the integration of energy storage systems and electric vehicles seamlessly.

To truly unlock DC microgrids, several key challenges must be overcome:
- Cost
- Standardization, interoperability, and regulatory frameworks
	- The nominal voltage is not standardized at the moment
- Stability and controllability in the face of voltage oscillations, faults, and arcing
	- Voltage regulation is challenging
	- Controlling power flow is challenging
	- Voltage oscillations can be caused "by DC converters with negative damping performance, the interaction between the DC microgrid and the DC converters, and the DC voltage control loop with positive feedback"
	- Fault management: No zero-point crossing means that arcs don't extinguish on their own

## Problem severity (1-10)
8

## Who has this need
Data centers, EV charging networks, industrial sites, etc. See [[More efficient and economical power distribution in microgrids and data centers]]

## Total addressable market (TAM)
XL

## Solutions today, and their shortcomings
Many actors are working on DC microgrids, but many challenges related to the stability and control of DC microgrids remain.
### Startups working in this space
- [[Direct Energy Partners]] (https://www.directenergypartners.com/)
- [[Block Energy]] (https://blockenergy.com/)

## Potentially relevant capabilities
### MIT ecosystem technologies
- [[Superconducting cables for DC power distribution]]
- Variable Inverter/Rectifier/Transformer ([link]( https://tlo.mit.edu/industry-entrepreneurs/available-technologies/variable-inverterrectifiertransformer))
- Possibly other MIT IP generated in the Turitsyn Group and/or Perreault Group

### MIT ecosystem folks who know a lot about this topic:
- [[Joseph V Minervini]], [[John Brisson]], and [[Leslie Bromberg]]
- [[Robert Stoner]] (supervised some thesis projects on this topic)
- Konstantin Turitsyn, formerly MIT, now works for DE Shaw
- Andy Campanella (formerly MIT, now at RightHand Robotics)
- Wardah Inam
- [[David Perreault]]
- The founder of [[Waya Energy]], who researched this topic at [[MIT Energy Initiative|MITei]]

### Control schemes
- [Decentralized Power Flow Control Strategy Using Transition Operations of DC-Bus Voltage for Detection of Uncertain DC Microgrid Operations](https://www.mdpi.com/2071-1050/15/15/11635)

## References
- Pires, V.F., Pires, A., and Cordeiro, A. (2023). DC Microgrids: Benefits, Architectures, Perspectives and Challenges. Energies _16_, 1217. [10.3390/en16031217](https://doi.org/10.3390/en16031217).
- [[2024-01-12 Joe Minervini on DC microgrids]]

## Other learnings
DC microgrids:
- Reduce losses in the distribution system, helps reduce the need for transformers and inverters
- Equipment is still expensive and not widely available today
- Lacks common standards
- Not well known to installers yet
- DC microgrids could be the future for many sites, but cost, standardization, and power stability are major challenges
- Inverters are a weakest link in AC microgrids, which is an advantage for DC microgrids
- 💡 SMES and other superconducting technologies to truly unlock DC microgrids