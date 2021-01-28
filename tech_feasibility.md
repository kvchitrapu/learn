# Technology feasibility

We first look at a packet journey from source to destination. Describe terminals, devices, software components in the path.

## Packet journey

<diagram>

### Total end to end into 3 segments 
From https://arxiv.org/pdf/1912.08110.pdf

1.	Space segment: Satellite constellation. Inter satellite communication.  
2.	Ground segments: Set of ground Stations (GS), which are responsible for the Control and management of space segment.  GS are also used for the packet transmission.
3.	User segments: This includes the Mobile devices, Gateways for 5G and other existing technologies.


### End to end latency
 
1.	Packet latency = Processing delay + Queueing delay + transmission delay + propagation delay.
2.	End to end satellites delay = Uplink delay + Inter Satellite delay + Downlink delay
3.	Uplink delay, intersatellite delay and downlink delay, each has Packet latency specified in the step 1.
Calculations for the above formulas can be found in https://onlinelibrary.wiley.com/doi/pdf/10.1002/wcm.97

### With the above formulas we can create a simulator for latency.
Simulator can take following parameters:
1.	Number of satellites
2.	Number of orbits
3.	Height of satellites
4.	Rotation time
5.	Source and Destination angles

### Propagation delay is the main difference between the existing 5G, Fiber compared to LEO.
1.	Visibility period of a satellite = Around 15 mins (this depends on the height of the satellite). Fiber is constant.
2.	Ground Stations can be used to limit the Intersatellite delay during the initial days of deployment.
3.	Light transmission speed in vacuum is 1.47 times faster compare to Fiber.  

## How a simple packet flows

## how it works with ground internet?
### how does DNS work?
### how does routing work?


## what are the latency characateristics?


### does cdn caching compete with leo 



## Other notes:
Satellite Link Budget Calculator (tutorialsweb.com)


Uplink path loss = 10 log⁡  〖(4πdC/f)〗^2 dB
downlink path loss = 10 log⁡  〖(4πdf/C)〗^2 dB

	'd' is the distance between satellite & ground station in Km
	'f' is the frequency in GHz
	C is the velocity of light in Kmps 


SpaceX operating parameters: Altitude and Band
	First: 1,440 in a 550 km (340 mi) altitude shell
	Second: 2,825 Ku-band and Ka-band spectrum satellites at 1,110 km (690 mi),
	Third: 7,500 V-band satellites at 340 km (210 mi).
	
