---
toc: true
toc_label: "Starlink Satellite Overview"
---

Authors: [Ravi Chamarti](https://www.linkedin.com/in/ravi-chamarti-804538/), [Naren Byrapuram](https://www.linkedin.com/in/narendra-byrapuram-823535/), [Kishore Chitrapu](https://www.linkedin.com/in/kishorechitrapu/)

## Abstract

Low-Earth Orbit (LEO) communication satellites recently pioneered by SpaceX’s Starlink and other players demonstrated global internet is achievable. A steady flow of breakthroughs in rocket launchers, satellites, small chips, favorable social sentiment, and high investments positioned LEO satellite constellations in the right trajectory. Latency around 30ms uniformly across the globe is an unprecedented feature of this technology. Many published articles cite remote area households, automated driving, data centers, supply chains including freight, agriculture as immediate benefactors of low latency global internet. We provide a walkthrough from LEO satellite constellation formation to satellite deactivation followed by a brief preview of benefits and challenges.

## Introduction
Ever since the first satellite launch on Oct 4, 1957, the satellites steadily commanded a permanent spot in telecommunications infrastructure. By the end of 2021, there will be 3,372 (Union of Concerned Scientists) orbiting around Earth. Private companies in space exploration created a concourse to LEO satellite constellations. Here we present a broad picture with basic characteristics of satellite orbits, advantages LEO, satellite constellation formation, packet routing overview, and finally sunset of a satellite. 

## Orbits and Satellites
The satellite orbital distance impacts communications, observation, and remote sensing applications. The satellite size, satellite speed, radiofrequency, and satellite count vary with the orbit. For communication purposes, there are mainly two near-earth orbits for satellites: GEO and LEO.

![Orbits](../assets/images/satellites-orbits.png)

### Geostationary Orbit (GEO)
About sixteen percent of the current satellite population is parked in GEO. As shown in the above figure, the orbit is aligned with the equator and is 35,786km above sea level with orientation aligned with Earth’s rotation. The satellite orbital speed is aligned with Earth. The orbit serves communication systems and Global Positioning Systems (GPS). The satellites in this orbit have the highest failure rate. A GEO satellite life expectancy is between seven and fifteen years (Northern Sky Research).

#### GEO challenges
The long-distance from sea level ( > 35,000km) incurs unavoidable signal travel times, **high latency (400ms) and low bandwidth (50-100Mbps)**. Satellite signal strength has to be high to survive long-distance travel. GEO delivers a wide terrestrial coverage area, finite orbit times around Earth, fewer ground stations, and concentrated equipment. The frequency spectrum is liberally spaced among competitors. As GEO satellites orbit right above the equator, most countries in the higher altitudes of the northern hemisphere and southern hemisphere suffer interference. Above sixty percent of GEO have aged beyond the expected lifespan. GEO satellite companies are faced with a decision to replace or exhaust out these satellites. Some companies interested in continuance are replacing GEO with LEO satellites.


### Low Earth Orbit (LEO)
Low-Earth Orbit objects revolve 160-2,000km above sea level. Most of the man-made objects revolve in this region. The International space station (ISS) and Hubble telescope are two notable satellites orbiting here. In contrast to the GEO satellite propagation delay of 400 ms, LEO’s proximity to Earth brings the signal packet propagation delay down ten to fifteen times (30-40ms).
Small form factor electronic devices, long-lasting batteries, efficient solar panels, and rocket launchers to deliver satellites are some of the recent advancements in space technology that exploded the growth in satellites launched into this orbit. The LEO satellites have been shrinking in size while simultaneously lower launching costs. In the new millennium, SpaceX, Telesat, and Amazon Kuiper have been in news with plans to launch thousands of satellites to form artificial constellations in space. With abundant funds, these companies aim to tackle the ubiquitous Internet problem along with confidential long-term overarching business goals. The companies plan to launch thousands of “small satellites” into numerous orbital planes to form a satellite constellation. Satellites further smaller in size namely micro and nanosatellites are pursued mostly by smaller players.
In the next sections, we elaborate on small satellite constellations in LEO, which are referred to as LEO satellites.  

## LEO satellite constellations
The LEO satellite launch technology attained an unprecedented level of precision and cost efficiency in the last decade. SpaceX Starlink, Amazon Kuiper tied to Blue Origins are two amply funded companies launching satellites. While both remain in early stages and secretive about the plans, netizens have widely gleaned SpaceX Starlink information. As of March 2021, Starlink has already launched 1,023 in 18 launches and is aiming to deploy a total of 1,440 to complete the initial constellation. According to the FCC filings, Starlink applied for 42,000 satellites to orbit in LEO to provide Internet service. Most of the information we present here is based on SpaceX Starlink satellite information on the Internet. In addition to delivering communication, satellites provide monitoring Earth and enhance space observation.

Stacks of satellites launched into LEO to form a constellation orbiting around Earth. The satellites are sorted into multiple planes orchestrated to best serve internet in planned geographic cells. The satellites are managed at scale bringing economies of scale for the owning enterprise.

### LEO satellites
SpaceX LEO satellites are small satellites called Starlink satellites. A Starlink satellite weighs around 227kg to 260kg. It orbits in LEO with a lifespan of three to four years. While there are tens of components, an LEO satellite typically has these key components: two redundant solar flat panels to power the satellite thrusters for position adjustment in the orbit, high-power phased array antennas for ground communication over Ku and Ka bands Optical inter-satellite links, The phased array antennas shoot narrow beams to 27,000 kmph orbiting Earth. The satellites’ orbits at 400km - 2000km above sea level.


## The lifecycle of LEO satellites

### Launch
The liftoff to the deployment of Starlink satellites on the SpaceX Falcon9 rocket completes in 65 minutes. Satellite launch transformed from a magical event to a routine deployment. SpaceX slashed launch costs at least ten times (projected to be 1000x) employing breakthroughs especially with the reuse of engines and fairings. A launch is estimated to cost $30 million. The 70m tall Falcon9 launches in two stages:

![Falcon9](../assets/images/falcon9.png)

_Source: https://asd.gsfc.nasa.gov/archive/tess/launch.html (edited for clarity)_
#### Stage1
The 60 Starlink satellites are stacked as payload in the rocker. Smallsats are powered down and assorted in the top one-third fairing of the rocket in the above picture. The bottom two-third is the booster engine with a mission to carry the payload to 65 km altitude. On completing a successful stage 1 launch, the booster returns to Earth for reuse. SpaceX’s reusable launch system technology for the first booster stage saves all nine engines. The boosters are reused up to nine times. After taking additional fuel, refurbishment (10%), and payload reduction (under 40%) into consideration, SpaceX brings rocket launch cost down to $30 million. The rocket payload approximately costs $1,350/kg. For comparison, international shipping rates are approximately $15/kg. See Appendix A for launch costs. This stage completes with the main engine cutoff in about two and half minutes. The booster returns to Earth with main engines while Stage 2 heads to orbit.

#### Stage 2
The Stage 2 head is clamshell-like “fairing” to protect smallsats from launch time excessive heat and pressure. The fairing shell peels down to Earth at the beginning of this stage. The lone engine carries the payload to orbit. At this, the Stage 2 engine takes 35 minutes to get to orbit and park Starlink satellites. About 64 minutes after launch, the rocket deploys smallsats into their orbits.

### Joining a constellation
The orbiting smallsats take 2 weeks to distance themselves and take a position. Each smallsat is configured to occupy a position using: Orbit’s height from sea level, the angle from the equator, and angle from a fixed space direction Smallsat’s angle from a fixed space direction The smallsats are launched initially into a lower orbit. As orbital velocity decreases with altitude, the smallsat changes velocity to match with the target orbital plane. On arriving into the position, the smallsat will lock velocity. As the count of satellites locked into position increases, the constellation size increases. The constellation formation model is nicely depicted in {% include video id="rddTXl_7Wr8" provider="youtube" %}

### On a mission
Once in orbit, a satellite becomes a constellation member. Its mission is to route packets from the terrestrial network, among satellites, and back to the terrestrial network. The satellites forward packets amongst themselves to expand the continuity of the network. Packets flow from the edge device to the Spacelink user terminal, which is a pizza-sized dish antenna. Packets are encrypted at the user terminal before beaming to the smallsat. The first smallsat inspects the destination address to route to another smallsat positioned in the packet direction. The last satellite closer to the destination coordinates will beam the packet down to all user terminals in its coverage. Only the user terminal will have a decryption key to read the packet. The entire packet end-to-end latency is close to 30ms - a huge milestone in internet service across the globe.

{% include video id="m05abdGSOxY" provider="youtube" %}

### Disposal
The long-term sustainability of space programs requires the safe post-mission disposal of satellites. FCC in the US requires satellite companies to disclose debris mitigation plans[14] before launching satellites. The risk of collision with other objects and casualty risk on re-entry is the main concerns listed in FCC regulation. Starlink aims to deorbit from 550km altitude to 200 km leading to re-entry into Earth’s atmosphere and burn. A smallsat is life expectancy is about five years. Starting from 2024 hundreds of satellites will be retired to prove the efficacy of the small satellite sunsetting plan.

## Satellite constellation internet - A paradigm shift
Based on current projections, the new LEO satellite constellations will **break barriers of low latency**. The internet packet latency is proportional to the distance between source and destination. The operating transatlantic cables in the ocean provide lowest latency between New Jersey and London which is a little under 60ms. The Starlink service is expected to provide packets with **30ms**. Additionally, a uniform service across the globe breathes life into a wide variety of applications. A few applications are:
1. internet for remote areas (Rural Digital Opportunity Fund).
2. end-to-end secure data services withing public cloud interworks. 
3. GPS and internet communication for autonomous vehicles.
4. backhaul for 5G networks.
5. custom secure communication for military and governments.
6. asset tracking on aircraft, ship, logistics, fleet management.
7. geo-dispersed collaborative organizations.

Many unforeseen applications will be innovated. Internet adoption increases global dissemination of information faster than ever before impacting economies and geo-political conditions which are beyond the scope of this article. The owners of the satellite constellations have the power to steer the direction of applications based on key parameters like price, location, and SLAs. They may limit the application to a small set like inter-datacenter connectivity, remote area internet, and automated driving or take up a global internet.

## Challenges
The road to the global internet has some predictable challenges and potentially unknown hurdles. The operating satellite constellation plans published in the public domain are aimed at sparsely populated areas. Additionally, satellite constellations have to within weather conditions and round-the-clock operational challenges. Scaling to global demand necessitates consensus with many countries and companies spread across the world most notably spectrum allocation in various countries.

## Summary

We are confident LEO satellite constellation can provide ubiquitous internet. The path is curvy ahead. The satellite constellations are breaking the barriers of traditional satellite and terrestrial communication. The technology has the potential to better level the field for seven billion people around the globe. The characteristics of satellite constellation internet aid inter-data center encrypted private channels, supply chain automation, mobility automation, natural vegetation, and numerous other applications. It remains to see the direction owners of satellite constellations take. The progress thus far has been towards the global internet.

## References
1. [A Basic Guide to small satellites](https://www.satelliteevolutiongroup.com/articles/leosat-April17.pdf)
2. [NSR Insight: A Critical Assessment Of HTS Satellite Constellations – SatNews](http://clarkeinstitute.org/wp-content/uploads/2010/04/ClarkeWirelessWorldArticle.pdf)
4. [Large LEO satellite constellations: Will it be different this time?](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9051712)
5.  [Starlink satellites - N2YO](https://www.n2yo.com/satellites/?c=52)
6.  [Launch and deployment of distributed small satellite systems - ScienceDirect](https://www.sciencedirect.com/science/article/pii/S009457651500171X)
7. [From Connectivity to Advanced Internet Services: A Comprehensive Review of Small Satellites Communications and Networks](https://www.hindawi.com/journals/wcmc/2019/6243505/)
8. [Northern Sky Research. “Satellite EOL: No one size fits all.”](https://www.nsr.com/satellite-eol-not-one-size-fits-all/)
9. [“SpaceX releases new details on Starlink satellite design.” SpaceX releases new details on Starlink satellite design](https://spaceflightnow.com/2019/05/15/spacex-releases-new-details-on-starlink-satellite-design/)
10. [Starlink Satellites](https://space.skyrocket.de/doc_sdat/starlink-v1-0.htm)
11. [Union of Concerned Scientists. “UCS Satellite Database.”](https://www.ucsusa.org/resources/satellite-database#.W7WcwpMza9Y.)
12. [Starlink packet routing](https://caseyhandmer.wordpress.com/2020/09/23/starlink-packet-routing/)
13. [SpaceX launches Starlink satellites as it deorbits original ones](https://spacenews.com/spacex-launches-starlink-satellites-as-it-deorbits-original-ones/)
14. [Mitigation of Orbital Debris in the New Space Age](https://docs.fcc.gov/public/attachments/DOC-363486A1.pdf)
15. [Large LEO satellite constellations: Will it be different this time?](https://www.mckinsey.com/industries/aerospace-and-defense/our-insights/large-leo-satellite-constellations-will-it-be-different-this-time)


Om shanti shanti shanti
 

## Appendix

### Orbits and their altitudes

| Orbital Altitude | Space band  |
| ------------- |:-------------:| 
|    >15,000 km  | upper van allen belt |
| 5000 - 15,000 km      | MEO|
| 2000 - 5000 km | lower van allen belt |
| 200 - 2000 km | LEO |
| 10 km | international flights|


### Internet provide launch costs

Comparison of internet service providers 

| Parameter | Fiber  | GEO | 5G | LEO |
| ------------- |:-------------:| :-------------:| :-------------:| :-------------:| 
| Speed  | 5Gbps (leased) | 5-100Mpbps | 1-2Gbps | 1-5 Gbps |
| Latency  |  | 400ms |  | 25ms |
| Cost  |  | proportional to distance | Launching costss | Tower setup, repeater count | Launching costs, operational costs |
| Variations | Terrain | Weather | Line of sight | Weather |


