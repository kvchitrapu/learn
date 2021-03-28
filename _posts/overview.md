# LEO Satellites

## Abstract

We are in the ascending phase of the space exploration era, yet, global connectivity remains an unsolved problem. In 2020, the COVID-19 pandemic escalated the urgency for internet access everywhere and everyone, especially in rural areas. COVID-19 lockdowns are temporary, but the under-connected population will have a lasting impact. With rapid breakthroughs in rocket launchers, satellites, small chips, societal favorability, and favorable investment markets, the low-earth orbit (LEO) small satellite constellations have the potential to bring global internet access. It can break barriers to provide audio, video, and data to remote users with 30ms or less latency. It can enable supply chains including freight, agriculture, and other prominent industries. This paper discusses the advantages of LEO nanosat technology feasibility, challenges ahead, and issues in the offing.

## Introduction
Ever since the satellite launch kickoff on Oct 4, 1957, space technology never stopped. By 12/31/2021, there will be 3,372 (Union of Concerned Scientists) orbiting around Earth. A burst of talent and funding in the last decade has increased low orbit constellations. Private funded space exploration, the rise of data use, nanotechnology,  robotics, and social media have created a concourse to LEO satellites. We here examine Low-Earth Orbit (LEO) small satellite technology, applications, and challenges in this paper. A sequel of this paper will give an in-depth analysis of technology, business, and ethical challenges.

## Orbits and Satellites
Satellite technology has been extensively used in telecommunications, observation, and remote sensing. The primary factor in satellite technology is orbital distance. Satellite orbit determines
satellite size, satellite speed, radiofrequency, and satellite count. For communication purposes, there are mainly two low orbits for satellites:
### Geostationary orbit (GEO)
About sixteen percent of the current satellite population is parked in GEO. As shown in the above figure, the orbit is aligned with the equator and is 35,786km above sea level with orientation aligned with Earth’s rotation. The satellite orbital speed is aligned with Earth. It serves communication systems and Global Positioning Systems (GPS).  The satellites launched into this orbit have the highest failure rate. GEO satellite life expectancy is from seven to fifteen years (Northern Sky Research). About seventy percent of the satellites in this orbit have come to EOL but still are expected to be prolonged due to advanced operational efficiencies.
#### Problems with satellites in GEO
The long-distance ( > 35,000km) incurs unavoidable travel times, delivering high latency (400ms) and low bandwidth (50-100Mbps). Strong satellite signal strength has to be high to survive during travel. GEO delivers a wide coverage area. Lesser times to orbit around Earth. Fewer ground stations and concentrated equipment. The frequency spectrum is liberally spaced among competitors. As GEO satellites orbit concentric to the equator, most countries in the northern hemisphere and southern hemisphere in higher altitudes suffer interference due to dish angle pointing at the satellite. 
Above sixty percent of GEO have aged beyond expected lifespan. GEO satellite companies are faced with a decision to replace or exhaust out these satellites. Some companies interested in continuance are replacing GEO with LEO satellites.

## Low Earth Orbit
Low-Earth Orbit objects revolve 160-2,000km from sea level. Most of the man-made objects revolve in this region. The International space station (ISS) and Hubble telescope are two notable satellites orbiting in this region. 

Small form factor electronic devices, long lasting batteries, efficient solar panels, and rocket launches to deliver satellites are some of the recent advancements in space technology which exploded the growth in satellites launched into this orbit. The LEO satellites have been shrinking in size while simultaneously lower launching costs. In the new millennium, SpaceX, TeleSat, and Amazon Kuiper have been in news with plans to launch thousands of satellites to form artificial constellations in space. With abundant funds, these companies aim to tackle the ubiquitous Internet problem along with confidential long-term overarching business goals. The companies plan to launch thousands of “small satellites” into numerous orbital planes to form a satellite constellation. Satellites further smaller in size namely micro and nano satellites are pursued mostly by smaller players.

In this paper, we discuss small satellite constellations in LEO.  
## Small satellites constellations 
The small satellite launch technology attained an unprecedented level of precision and cost efficiency in the last decade.  SpaceX Starlink, Amazon Kuiper tied to Blue Origins are two amply funded companies launching satellites. While both remain in early stages and secretive about the plans, netizens have widely gleaned SpaceX Starlink information. As of March 2021, Starlink has already launched 1,023 in 18 launches and is aiming to deploy a total 1,440 to complete the initial constellation. According to the FCC filings, Starlink applied for 42,000 satellites to orbit in LEO to provide Internet service. Most of the information we present here is based on SpaceX Starlink small satellites information on the Internet. In addition to delivering communication, small satellites provide monitoring Earth and enhance space observation.
## Small satellite
Small satellites in short form are smallsats. A Starlink smallsat weighs around 227kg to 260kg. It orbits in LEO with a lifespan of three to four years. While there are tens of components, a small satellite typically has these key components:
Two redundant solar flat panels to power the satellite
Thrusters for position adjustment in the orbit
High-power phased array antennas for ground communication over Ku and Ka bands
Optical inter-satellite links
The phased array antennas shoot narrow beams to 27,000 kmph orbiting Earth. The satellites orbits at 400km - 2000km above sea level.
## Constellation

Constellations are identical small satellites orbiting Earth in multiple planes. The smallsats are managed at scale bringing economies of scale for the owning enterprise. 

## The lifecycle of small satellites

### Launch
The liftoff to deployment of Starlink smallsats on the SpaceX Falcon9 rocket completes in 65 minutes. Satellite launch transformed from a magical event to a routine deployment. SpaceX slashed launch costs at least ten times (projected to be 1000x) employing major breakthroughs especially with reuse of engines and fairings. A launch is estimated to cost $30 million. 
The 70m tall Falcon9 launches in two stages:

Source: https://asd.gsfc.nasa.gov/archive/tess/launch.html
#### Stage1 
The 60 Starlink smallsats are stacked as payload in the rocker. Smallsats are powered down and assorted in the top one-third fairing of the rocket in the above picture. The bottom two-third is the booster engine with a mission to carry payload to 65 km altitude. On completing successful stage 1 launch, the booster returns to Earth for reuse .
SpaceX’s reusable launch system technology for the first booster stage saves all nine engines. The boosters are reused up to nine times (SpaceX #). After taking additional fuel, refurbishment (10%), and payload reduction (under 40%) into consideration, SpaceX brings rocket launch cost down to $30 million. The rocket payload approximately costs $1,350/kg. For comparison, international shipping rates are approximately $15/kg. See Appendix A for launch costs. 
This stage completes with the main engine cutoff in about two and half minutes. The booster returns back to Earth with main engines while Stage 2 heads to orbit.
#### Stage 2
The Stage 2 head is clam shell like “fairing” to protect smallsats from launch time excessive heat and pressure. The fairing shell peels down to Earth at the beginning of this stage. The lone engine carries the payload to orbit. At this, the Stage 2 engine takes 35 minutes to get to orbit and park starlink satellites. About 64 minutes after launch, the rocket deploys smallsats into their orbits. 
Constellation formation
The orbiting smallsats takes 2 weeks to distance themselves and take position. Each smallsat is configured to occupy a position using:
Orbit’s height from sea level, angle from equator and angle from a fixed space direction
Smallsat’s angle from a fixed space direction
The smallsats are launched initially into lower orbit. As orbital velocity decreases with altitude, the smallsat changes velocity to match with the target orbital plane. On arriving into the position, the smallsat will lock velocity. As the count of satellites locked into position increases, the constellation size increases. The constellation formation model is nicely depicted in this video (Eccli)
### Steadystate  (TBD)
Once in orbit, a smallsat is a member of the constellation in routing packets from the terrestrial network. The smallsat forward packets amongst themselves for reliability and continuity of the network. 

Packets flow from the edge device to Spacelink user terminal, which is a pizza sized dish antenna. Packets are encrypted at the user terminal before beaming to the smallsat. The first smallsat will inspect the destination address to route to a smallsat positioned in the same direction as the packet. The last satellite closer to the destination coordinates will beam the packet down to all user terminals in its coverage. Only the user terminal will have a decryption key to read the packet. 
### EOL (TBD)
After 5 years of runtime satellite parts erode due to cosmic rays. Need to be decommissioned. The satellite is maneuvered out of the orbit.
Navigate out of orbit 
Ready to self-burn

Telesat Iridium has 50, StarLink has close 3,000 ...
## Applications
1. End-to-end secure cloud services. Datacenters/Kuiper
2. Autonomous vehicles/Starlink
3. Mobility market includes backhaul for 5G in COW autonomous vehicles
4. Government or military
5. Underserved rural areas (Rural Digital Opportunity Fund)
6. Asset tracking on aircraft, ship, logistics, fleet management
LEO small satellites bring the internet around the globe with homogenous characteristics: with predictable latency (<25ms) steady throughput 100 Mbps 100% coverage area We envision advancements will be in many areas especially in logistics, online learning, online health, and online banking. In-depth look in here.
## What next? (Move this to summary)
When time permits, we will expand on these topics:
1. Packet management - routing algorithms, network management
3 Satellite management - collision avoidance, debris, inter-constellation interfaces
# Summary
We are confident LEO small satellite technology can provide ubiquitous internet. The path is curvy ahead. LEOstat is breaking the barriers of traditional satellite communication. It has the potential to better level the field for 7 billion people around the globe. The LEOsats will play a key role in inter-data center encrypted private channels, supply chain automation, mobility automation, and natural vegetation. Is this the next big thing?
References
1. [A Basic Guide to small satellites](https://www.satelliteevolutiongroup.com/articles/leosat-April17.pdf)
2. [NSR Insight: A Critical Assessment Of HTS Satellite Constellations – SatNews](http://clarkeinstitute.org/wp-content/uploads/2010/04/ClarkeWirelessWorldArticle.pdf)
3. [https://ec.europa.eu/growth/tools-databases/dem/monitor/sites/default/files/DTM_LEO%20-%20Spectrum%20access%20v1_0.pdf]
4. [Large LEO satellite constellations: Will it be different this time?](
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9051712)
5.  "Starlink satellites - N2YO.com." Starlink satellites. Accessed 21 Feb. 2021.
6.  [Launch and deployment of distributed small satellite systems - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S009457651500171X)
 
Om shanti shanti shanti
 





## Appendix

| Orbital Altitude | Space band  |
| ------------- |:-------------:| 
|    >15,000 km  | upper van allen belt |
| 5000 - 15,000 km      | MEO|
| 2000 - 5000 km | lower van allen belt |
| 200 - 2000 km | LEO |
| 10 km | international flights|


Launch Costs

Comparison of internet service providers 

| Parameter | Fiber  | GEO | 5G | LEO |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
| Speed  | 5Gbps (leased) | 5-100Mpbps | 1-2Gbps | 1-5 Gbps |
| Latency  |  | 400ms |  | 25ms |
| Cost  |  | proportional to distance | Launching costss | Tower setup, repeater count | Launching costs, operational costs |
| Variations | Terrain | Weather | Line of sight | Weather |

## Bibliography
1. Burleigh, Scott C. “From Connectivity to Advanced Internet Services: A Comprehensive Review of Small Satellites Communications and Networks.” Wireless Communications and Mobile Computiing, vol. 2019, https://www.hindawi.com/journals/wcmc/2019/6243505/.
Northern Sky Research. “Satellite EOL: No one size fits all.” https://www.nsr.com/satellite-eol-not-one-size-fits-all/.
“SpaceX releases new details on Starlink satellite design.” SpaceX releases new details on Starlink satellite design, https://spaceflightnow.com/2019/05/15/spacex-releases-new-details-on-starlink-satellite-design/.
“Starlink.” Starlink Satellites, https://space.skyrocket.de/doc_sdat/starlink-v1-0.htm#:~:text=The%20Starlink%20satellites%20feature%20a,use%20krypton%2Dfueled%20Hall%20thrusters.
Union of Concerned Scientists. “UCS Satellite Database.” https://www.ucsusa.org/resources/satellite-database#.W7WcwpMza9Y.

To Do
After launch ( launch + 2weeks ) 
Before operational state
Setup: defining Orbits, self-evaluation of coordinates, maneuvering to the designated position
Join as constellation member
Interlink establishment
Ground station to smallsat membership update
Smoke test

While operational state (5 years)
Interlink datapath
End-to-end packet routing with updates, failure recovery
monitoring
Traffic management to avoid collision
Orbital correction due to astral decay

After operational state 
Navigate out of orbit 
Ready to self-burn


Future Projects for this team
Opportunities
Power management (battery)
Data accumulation about users, autos, satellites
Metadata about moving objects

Open Problems
Obtain satellite for a user coordinates
Given satellite parameters (speed, …) find geographical location it serves.
Develop a function to give available satellites to serve a given geographical location.

Solutions

Setup
Satellite database with dynamic coordinates

Input
Time of day
User coordinates

Output
Satellite id, satellite coordinates
Availability duration
Overlay on a map

