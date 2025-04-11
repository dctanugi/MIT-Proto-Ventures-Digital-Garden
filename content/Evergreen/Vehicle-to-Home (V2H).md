#work/proto_ventures #work/industries/electric_vehicles 

up:: [[Vehicle-to-Everything (V2X)]]

According to the CTO of [[Fermata Energy]], there will come a day when residential V2H is a mainstream thing. But utilities are not at all used to processing interconnection requests for bidirectional EV chargers, and certified bidirectional EV chargers for residential use basically don't exist today.

For example, the CEO of [[Green Mountain Power]], Mari McClure, owns a Ford F150 Lightning, and it powers her home during outages, but she is using a makeshift system with 9 extension cords (!). She says we absolutely need better tech to connect these EVs to the home. ([[2024-10-11 NextGrid Alliance Summit|source]])

[[Aleksandr Rakitin]] writes:
>And yes, I think it comes down to something like an ATS in terms of required equipment (aka "backup power gateway"?). I don't know exactly what it is yet, but it must be very similar if not the same as you would get as part of a BESS installation (with or without solar).

Alex adds:
>Another angle is related to AMI 2.0: what happens if you have a smart meter with edge capabilities on site? This is a screenshot from an ideation session with a large US utility company. Notice the notion of an "islanding relay inside the meter":

| Capability          | Description                                                          | Why                                                                                                                                                          | Example Experiences                                                                                                                                       |
| ------------------- | -------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Backup power        | Islanding relay inside the meter controllable by the DER and utility | - Reduce cost of home backup<br> - Ability for utility to start an islanding event with DER if needed                                                        | - Customer avoids $2,500 of panel work to install backup power gateway<br>- V2G home backup requires only an AC V2G charger ($700) and no other equipment |
| Backfeed management | Coordination of DER output ensuring panel is not overloaded          | - Reduce cost of DER interconnection<br> - Electric panels are limited to 20-40A of DER backfeed where 100-200A could be available with a coordinated scheme | - Customer avoids a $4,000 panel upgrade for home solar, battery, or EV                                                                                   |

## Open questions and research directions
Suggestions from [[Olivier Pinçon]]:
- What % of households are concerned about outages? What's the willingness to pay for resiliency today? Consider asking Bryan Bollinger about the willingness to pay for backup (see [[2024-05-16 CEEPR Spring Conference]]).
- Are EV owners trying to use their cars as home backup today?
- If so, which part(s) of the process are proving most difficult
- Look at reddit.
- Buy a Ford F-150 Lightning, and try to get the bidirectional functionality. How hard is it? Document your learning. Or see if anybody else has done this.

## Relevant meetings
- [[2024-05-17 V2H deep dive with Alex Rakitin]]

## Relevant readings:
- [https://chargedevs.com/features/the-technical-challenges-of-bidirectional-chargers/](https://chargedevs.com/features/the-technical-challenges-of-bidirectional-chargers/)