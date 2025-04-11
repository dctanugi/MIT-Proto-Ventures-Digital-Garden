---
tags:
  - capabilities
  - work/proto_ventures
---
## Description of capability
### Thermal Storage System for Space Heating or Water Heating

**Overview**

A wirelessly connected physical system that stores energy by heating a molten salt and discharging that energy to provide space or water heating on demand at a later time.

**What is the invention and how does it work?**

The invention consists of:

-       A thermally insulating box containing a volume of molten salt (e.g. nitrate salt), which will store energy in the form of heat for later use.

-       The insulating box also contains a ferromagnetic metallic plate (e.g. cast iron) at the bottom of the box, to inductively heat the molten salt

-       An induction heating plate, placed below the insulating box, that can electrically heat the molten salt.

-       The insulating box has an adjustable mechanism that can controllably expose thermally conducting heat fins (e.g. made of aluminum) that can conduct heat from the molten salt to the outside of the box. The mechanism can expose the heat fins when heating is desired, and cover the heat fins the rest of the time to prevent heat leakage.

-       A fan that blows air across the heat fins when space heating is desired (for forced-air heating systems). In another embodiment, this is a pump that circulates water across the heat fins when heating is desired (either for water-based or steam-based space heating systems, or for water heating applications).

-       A set of temperature and flow sensors in all relevant parts of the system.

-       A wireless communications device that allows the system to send data to the cloud and to receive operating instructions and other information from the cloud.

-       An edge computing and data storage device that powers the control system (when to charge and at what current, when to expose the heat fins and by how much, when to activate the fan/pump and by how much) and also powers a machine learning model that predicts upcoming heating needs and upcoming electricity prices to inform the control system.

**What problem does this invention solve?**

This invention allows a building (e.g. a residential home) to save money on water or space heating by consuming electricity when it is most affordable (off peak), even if their actual heating usage coincides with peak electricity prices.

It also allows buildings to transition from natural gas or oil heating to electric heating without a costly upgrade to their utility service or electrical panel, since the thermal storage system can trickle-charge at a low electrical current over the course of many hours rather than taxing the electrical system all at once like a heat pump would.

In addition, the system helps electric utilities manage the peak demand for electricity by communicating (directly or via an aggregation partner) with an ensemble of these systems, for example to offer favorable pricing many hours before an expected peak electricity demand event later in the day, or to signal to these systems to stop drawing electricity during a severe peak demand event.

**What are the features and benefits of our invention?**

The molten salt (e.g. nitrate salt) can store a large amount of energy in the form of heat, significantly more than water, because of its high heat capacity and very high boiling point. It can also absorb and transfer heat very quickly due to its high thermal conductivity.

The thermal charging system (induction plate below the insulated box + ferromagnetic plate inside the insulated box) allows the system to charge using electrically without any physical contact between the inside and the outside of the box. This drastically reduces both the leakage of heat out of the box, and the risk of leakage of molten salt.

The mechanism that selectively covers or uncovers the heat fins allows the box to stay thermally insulated and retain its heat for a very long time (days) when heating is not needed; it also allows the system to rapidly transfer heat to an air or water medium on demand.

The control system, edge storage and computing, and wireless communications interface allow the system to operate intelligently, allow the end user to interact with the system remotely, and allow third parties (e.g. electric utilities or demand response providers) to interact with the system remotely.

**How is this invention different from other solutions?**

The state of the art in electric space heating includes resistive heating and heat pump heating. None of these systems incorporate any thermal storage, which means that they have no way to decouple the timing of heating demand from the time of electricity usage.

Thermal storage systems have been developed for providing cooling (typically using ice), but not for storing heat.

Heat storage systems have been developed for other applications (e.g. industrial heat, electricity production), but not for space heating.

**Challenges encountered during the process**

We initially considered water, bricks, and crushed rock as storage media. However, these media cannot store enough energy per unit volume. We had to look at the nuclear energy field, an entirely different field of study, to see the potential of molten salts for this application.

We struggled to devise a ‘charging’ system that could put heat into the system while preventing heat leakage out of the system and while preventing leaks.  We considered coupling the system to a heat pump with a heat exchanger, and we also considered running an electrically resistive coil through the inside the box, but both approaches were unworkable because of the potential for leakage. The inductive approach addresses this problem.

We also struggled to devise a ‘discharging’ approach that could provide high enough heat fluxes to meet the expected heating demand without exposing the molten salt. There was no obvious way to do this from the prior art in building space heating or water heating.

## Key people
[[Weiyue Zhou]], [[Mike Short]], [[Tsolmon Bazarragchaa]]

## Technology Readiness Level (1-9)
1

## Needs that this could potentially address
[[Managed heating demand]] and [[Residential decarbonization in hard-to-electrify urban areas]]

## Tech specs
TBD

## Estimated time & cost to commercialize
3-4 years, $15M

## Outstanding risks


## References