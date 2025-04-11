---
tags:
  - capabilities
  - work/proto_ventures
  - work/industries/nuclear_fission
---
## Description of capability
A mini [[Transient grating spectroscopy (TGS)]] device as small as a laptop that would help reactor researchers or nuclear reactor diagnostics professionals.

A bread-board proof of concept exists in the Short Lab at MIT. It consists of a laser pump, a second laser that acts as a probe, an optics table with mostly off-the-shelf optical components, and a photodetector hooked up to an oscilloscope.

The signal from the oscilloscope tells you about the uniformity of the material (at the microcrystalline level, which tells you about Oswald ripening and radiation damage in the material), the thermal diffusivity, and the elastic modulus. Mike Short believes these properties can all be used as proxies for what inspectors and regulatory bodies _actually_ care about, which is the fracture toughness (specifically, the Sharpie Impact Toughness) of the material.

The technique was invented at MIT in the 1980s, but the real innovation here is in the design of a fully planar setup, which drastically simplifies the design and allows it to be more compact. There may be additional IP in:
- The development of a **materials database** that correlates TGS measurement outputs with properties of interest (e.g. fracture toughness) for a library of materials (e.g. different steel alloys)
- Automatically-realigning control systems for the optics

This is the only _non-destructive_ way of testing these properties.

## Key people
[[Jonas Rajagopal]]
[[Angus Wylie]]

## Technology Readiness Level (1-9)
3

## Needs that this could potentially address
- [[Extending nuclear plant lifetimes]]:
	- Materials to be inspected include the pressure vessel, the primary pipes, the core barrels, etc.
	- The setup needs to be exactly normal to the surface
	- A nuclear inspector would come in, plug the device in, buff some of the inner vessel surface, position the device at exactly the right focal point distance (the method is very sensitive to distance)
	- The intent would be to extend the lifetime of nuclear plants even after there are no "coupons" left.
- Materials and nuclear research labs that would benefit from this technique
- Process control in anything that involves deposition techniques. Is the film adhered? Are there are nanoscale cracks?

## Tech specs
- The technique probes at the micrometer depth. Depth is tunable based on power of laser.

## Estimated time & cost to commercialize
3 years, $15M. 
The oscilloscope could be replaced by FPGAs.

## Outstanding risks
- The nuclear industry may not be willing to believe that elastic modulus and thermal diffusivity are reliable proxies for fracture toughness

## References
[[2023-05-15 A-STAR (Singapore Research Entity)]]