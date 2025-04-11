---
tags:
  - capabilities
  - work/proto_ventures
---

## Description of capability
Transmitting power via radio-frequency waves. Requires a dish antenna (or an array of antennas) on one and and a collector on the other end.

[[Gregory Wallace]] writes:
>To summarize our previous conversation: power beaming over long (many miles) distances doesn’t work because of the diffraction limit combined with the “sparse-array curse” or “thinned-array curse”.  
>The diffraction limit says that you need a really really big antenna (several miles in diameter) to get a sufficiently focused beam from a single antenna to transmit over a gap of a few hundred miles.  (Think about building a dish antenna that big.  Not really practical.)
>RADAR systems combine the radiation from multiple antennas to significantly narrow the beam width without breaking the diffraction limit.  (Think about a 10x10 grid of antennas covering a square mile.  Not that big a deal.)  The problem is that when you combine multiple coherent antennas into a narrow beam you run into the sparse-array curse.  What it boils down to is that the power density in your primary radiation beam stays constant as you make the spot smaller by adding in more antennas, which means you are transmitting more power into the side lobes which go off in undesired directions.  You can get a super narrow radiation pattern (necessary to keep focused on a target many miles away) but almost no power actually makes it to the intended destination. 
>The problem gets easier at shorter range and lower total power.  Wirelessly powering a small robot that’s a few hundred meters away is feasible because the power is low (can get enough power from a single antenna) and the range is short (beam focus is narrow enough from a reasonable size dish antenna - a 1 m antenna at 300 GHz could work for up to 1 km).  So maybe there’s something to be done in that space.  Wouldn’t surprise me if DARPA is working on that.  I’ve also read about powering very low power devices (low power cameras, for example) over WiFi frequencies. 
>The diffraction limit is proportional to wavelength.  At smaller wavelength you can get by with a proportionally smaller antenna.  But you need to consider atmospheric attenuation (generally worse at smaller wavelength in the microwave bands) and ionizing radiation (probably a non-starter to do anything shorter than optical wavelengths).

## Key people
[[Gregory Wallace]]

## Technology Readiness Level (1-9)
4

## Needs that this could potentially address
- Powering microgrids
- Powering drones
- Bypassing difficult spots in the buildout of transmission lines 

## Tech specs
- Currently feasible: ~480 W over 300 m (record by [[Powerlight Technologies]])

## Estimated time & cost to commercialize
$100M, 8 years

## Outstanding risks
Health hazards from high power RF exposure

## References