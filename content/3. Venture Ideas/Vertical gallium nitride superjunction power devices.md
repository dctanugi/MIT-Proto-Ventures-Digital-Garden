---
tags:
  - capabilities
  - work/proto_ventures
  - venture_ideas
aliases: []
---
## Description of capability
From the ARPA-E website:
>The Massachusetts Institute of Technology (MIT) and collaborators will develop a new generation of power electronics based on vertical [[gallium nitride]] superjunction diodes and transistors that can break the theoretical limit of today’s GaN unipolar power devices. MIT’s new superjunction structure will provide transistors and diodes with an on-resistance at least 5X better than today’s best GaN or silicon carbide (SiC) power devices, and at least 50-100X better than today’s commercial Si power devices with similar voltage ratings. The advantages of the new GaN power devices significantly improve their potential for commercialization in medium- and high-voltage and high-current applications.

## Key people
[[Tomas Palacios]]
[[Cynthia Liao]]
Joshua Perozek

## Technology Readiness Level (1-9)
3

## Needs that this could potentially address
[[Evergreen/Vertical Horizons]], specifically:
- Rectifier and inverter inside a double-conversion UPS (and also DC-DC converter for the battery) . According to ChatGPT, 'Nexperia has developed low voltage e-mode GaN FETs specifically designed for power supply applications, including UPS systems. These devices are valued for their ability to operate at higher frequencies and voltages with better efficiency compared to traditional silicon-based technology​ ([Nexperia](https://www.nexperia.com/applications/industrial-and-power/uninterruptible-power-supply--ups))​."
- 480 V AC to 208 V AC in the PDU transformer
- 208 V AC to 48 V DC in the server rack (rectify and step down voltage)
- 48 V DC to 12 V DC in the server board itself 
- 12 V DC to ~1 V DC to the actual components (note: there is also talk of direct conversion)

> [!NOTE] Note
> The Open Rack architecture proposed by the Open Compute Project (OCP) addresses loss of power by using 48 V bus lines rather than conventional 12 V bus lines [link](https://www.allaboutcircuits.com/industry-articles/half-bridge-dc-dc-converter-scheme-shrinks-power-in-data-centers/)

> [!NOTE] Note
>  DC-DC converters can also be used for hardware accelerators (FPGAs, ASICs, etc.) ([source](https://www.ti.com/lit/an/slvaeg2a/slvaeg2a.pdf?ts=1715780245562&ref_url=https%253A%252F%252Fwww.google.com%252F))



![[Pasted image 20240515095321.png]]
Source: https://www.raritan.com/landing/data-center-power-distribution-wp/thanks
## Tech specs


## Estimated time & cost to commercialize


## Outstanding risks


## References
- https://arpa-e.energy.gov/technologies/projects/8-gan-si-super-junction-devices-next-generation-power-electronics