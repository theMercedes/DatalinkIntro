
### Datalink technology
Means of connecting one location to another, to transmit and receive digital data. 

Data link communications are characterized by any information relayed from the aircraft to the ground or from aircraft to aircraft. Specifically, data link systems include information shared over networks like the **Aircraft Communication Addressing and Reporting System (ACARS)** and the **Aeronautical Telecommunications Network (ATN)**. Both networks utilize high-frequency (HF) or very high-frequency (VHF) data link and satellite communications to send messages.  

In most cases, pilot to **Air Traffic Control (ATC)** communications are made via the ACARS data link system because this system is available over transoceanic flights. Due to this, most Future Air Navigation System (FANS) avionics are ACARS-based.
#### Uses of datalink communications: 
1.  **OOOI events** 
    * Out of the gate
    * Off the ground
    * On the ground
    * Into the gate
2. **FMS** (Flight Management Systems)
    * Communication system for flight plans and weather information sent from the ground to the aircraft
3. **Equipment Health and Maintenence Information**
    * Aircraft health is monitored and sent to the ground in real time via data link systems.
4. **Ping Messages**
    * Automated messages referencing the aircraft's connection to ensure the ATC can reach the aircraft correctly. 
5. **Manually sent messages**
    * ACARS interfaces with interactive display units in the cockpit, and can track when of any reports or messages between flight crew and ground are sent or received. 
 
> If there's too much communication traffic at a specific frequency channel the ground station initiates an automated frequency change to another channel (**Remote Tuning**).

### ACARS 
##### (Aircraft Communications, Addressing and Reporting System)

ACARS (pronounced AY-CARS) is a digital data link system for the transmission of short, simple messages between aircraft and ground stations via **radio** or **satellite**. At first it relied exclusively on VHF channels but more recently, alternative means of data transmission have been added, enhancing its geographical coverage.

ARINC’s (Aeronautical Radio, Inc.) developed the ACARS **AEEC** (airlines electronic engineering committee) **618** protocol by the end of the 1970s. This was followed by SITA’s (Systemes Internationale de Telecommunications Aeronautique) launch of its **VHF AIRCOM** service, based on the same communications protocol, positioning ACARS as the industry’s standard for real time data exchange between aircraft and flight crews, and operators’ ground based staff and systems.

> Arinc now operates under the commercial name Rockwell Collins and is SITA's main competitor. SITA has always used the ARINC 618 protocol for its Datalink services. SITA and Collins  are the only two companies in the world that provide datalink services and VHF technology to the aeronautical industry. 

Modern ACARS equipment now includes the facility for automatic as well as manual initiation of messaging. ARINC guidelines have been defined for all the various avionic components of ACARS.

There are three types of ACARS messages: 
* **ATC (Air Traffic Control)**
    *   ATC messages include:
    * aircraft requests for clearances
    * ATC issue of clearances and instructions to aircraft. 
    * used often to deliver Pre-Departure, Datalink ATIS and en route Oceanic Clearances. 

* **AOC (Aeronautical Operational Control)**
* **AAC (Airline Administrative Control)**



Other examples of typical ACARS messages: 
* Mode identifier

* Aircraft identifier

* Message label

* Block identifier

* Message number

* Flight number

* Message content


#### PROTOCOL
 * ACARS uses the protocols defined in the **ARINC 618**-based air-to-ground specification to transfer data between the avionics systems and the ground-based ACARS networks. 
 * Provides character-based data connectivity between an aircraft and ground-based service providers
 * When an ACARS message is sent from the aircraft to an ACARS core, it's called **downlink**. It goes from the aircraft to the dual core ADFP (connector) + ADLT (ACARS processor) ground station as a 618 (**type A** message). In the ADLT it converts to a 620 (**type B** message). The message going back is called **uplink**. 


### The Service Provider (SITA)
The ground-based ACARS networks are globally operated by two main **Datalink Service Providers** (DSP).
The DSP is responsible for the movement of messages via radio link, usually to/from its own ground routing system. ACARS messages are transmitted using one of three possible data link methods:

* **VHF** or **VDL** (VHF Data Link) which is line-of-sight limited
* **SATCOM** in areas where here is no link to a ground station, ACARS uses **satellite communication** (not available in polar regions)
* **HF** or **HFDL** (HF Data Link) which has been added especially for polar region communications. 

As mentioned before, the two main DSPs globally are Rockwell Collins (SITA's competitor) and **SITA**.
>   ARINC (Traffic designated to ARINC is routed to the appropriate Data Service Processor in Chicago via separate telex connections). USA is ARINC-ACARS dominant at 131.550 MHz

### Aircraft Equipment
* MU (Management Unit)
* CMU (Communications Management Unit) mainly used in newer aircrafts.

Both work as routers for all data transmitted or received externally. 

The ACARS MU/CMU can automatically select the most efficient air-ground transmission method if there is an available choice. 

**ANSP** (Air Navigation Service Provider)

#### Ground Processing System
Ground System provision is the responsibility of either a participating ANSP or an Aircraft Operator. Aircraft Operators often contract out the function to either DSP or to a separate service provider. 

Messages from aircraft, especially automatically generated ones, can be pre-configured according to message type so that they're automatically delivered to the appropriate recipient. The same applies to ground-originated messages can be configured to reach the correct aircraft.

### VHF 
VHF stands for **Very High Frequency**. 
The VHF range is between **118 MHz - 137 MHz**.


**Cruising Altitude**: 
VHF can travel up to 230-240 nautical miles (**444.48 km**).
Commercial airliners and many other aircraft cruise at altitudes ranging from approximately 30,000 feet (9,144 meters) to 40,000 feet (**12,192 meters**) or even higher for long-haul flights.

VHF (Very High Frequency) is used in aeronautical communications for several important reasons:

**Propagation Characteristics**: VHF signals have relatively long wavelengths, which allows them to travel relatively long distances in the Earth's atmosphere before they are absorbed or reflected. This makes VHF suitable for both ground-to-air and air-to-air communication.

**Line of Sight**: VHF signals primarily travel in a straight line, known as line-of-sight propagation. This characteristic is well-suited for aviation, where aircraft are often at relatively high altitudes. VHF signals can reach aircraft at cruising altitudes and are effective for communication with air traffic control.

**Frequency Allocation**: VHF frequencies are allocated for aeronautical communication by international agreements and regulatory authorities. This ensures that these frequencies are reserved for aviation use, reducing the likelihood of interference from other services.

**Quality and Clarity**: VHF signals are less prone to interference and noise compared to lower-frequency bands. This results in clear and reliable communication, which is crucial for aviation safety.

As for the range of VHF signals in aeronautical communication, it depends on several factors, including the altitude of the aircraft, the power of the transmitters, and the sensitivity of the receivers. In general, VHF signals can travel over a line of sight, which means they follow the curvature of the Earth. The maximum line-of-sight distance is approximately 200 miles at typical cruising altitudes, but it can be more or less depending on various conditions.

For example, if an aircraft is flying at a higher altitude, it may have an extended line-of-sight range. If the aircraft is close to the ground or flying in mountainous terrain, the range might be limited due to obstructions. Additionally, atmospheric conditions, such as temperature inversions, can affect signal propagation.

To ensure reliable communication over longer distances, aviation uses a network of ground-based VHF radio transmitters and receivers to cover airports and airspace. This network, combined with the use of relay stations or satellites, helps extend the effective range of VHF communication and ensures that aircraft maintain communication with air traffic control even when beyond the line of sight.
### VGS 
VGS stands for **VHF Ground Station**. These are the stations that SITA has 

### VDL 
VDL stands for **VHF Digital Link**.  
The VHF Digital Link mode 2 (VDL2) system, has a thirteen times higher transmission rate air-ground link than VHF ACARS, but is very similar to VHF ACARS. Sita's stations are referred to as VHF stations or VDL stations. 
imary Functions:

### Air Traffic Control (ATC): 

VHF stations are used by air traffic controllers to communicate with aircraft within the airport's airspace. This communication includes providing instructions for takeoff, landing, taxiing, and other aspects of aircraft movement on the ground and in the air.

#### Aircraft Communication: 
Aircraft use VHF radios to communicate with air traffic control and other aircraft. Pilots use VHF radios to receive clearances, weather information, and updates on their flight plan.

#### Navigation Aids: 
VHF stations can also be part of the navigation aids used by aircraft, such as the VOR (VHF Omnidirectional Range) and ILS (Instrument Landing System), which help guide aircraft during takeoff, approach, and landing.

### Internet Working
When an aircraft flies over a region where SITA VHF stations do not operate, ARINC stations will recieve the downlink messages and send them to SITA ADFP and then to the ADLT in either of the main core sites and vice versa. 

### Equipment:
* **VHF Radios**: 
Air traffic controllers in the tower and on the ground use VHF radios to communicate with pilots. These radios operate in the VHF frequency band, typically in the 118-136 MHz range.
* **Ground-Based Transmitters and Receivers**: 
 Airports have ground-based transmitters and receivers that are strategically placed to ensure complete coverage of the airport's airspace. These stations are often located at the airport and around its periphery.
* **Antennas**:
Antennas are used to transmit and receive VHF signals. These antennas are typically mounted on tall structures, such as the airport control tower.

### VHF use cases in an airport

* **Air Traffic Control (ATC) Tower**: Every controlled airport will have an ATC tower, and within it, there are multiple VHF radios. These are used by air traffic controllers to communicate with aircraft within the airport's airspace.

* **Ground Control**: Some larger airports have separate ground control frequencies, typically in the VHF band, to manage aircraft movements on the runways and taxiways. This can help avoid congestion on the main tower frequency.

* **Clearance Delivery**: Some airports have a separate frequency for clearance delivery, where pilots can receive initial instructions and clearances before they depart.

* **Ramp Control**: At airports with a significant volume of airline and ground handling activity, a separate VHF frequency may be used for ramp control. This helps coordinate the movement of ground vehicles and aircraft on the apron.

* **Aircraft Services**: Some airports provide maintenance and service facilities for aircraft. They may have VHF stations for communication between the service providers and aircraft operators.

* **Emergency Services**: Airports typically maintain VHF stations for communication with emergency services like fire and rescue.

* **Navigation Aids**: Airports with VOR (VHF Omnidirectional Range) or ILS (Instrument Landing System) installations will have VHF transmitters and receivers associated with these navigation aids.

* **Airport Operations**: The airport operations staff may have VHF radios for communication related to the overall management and maintenance of the airport.
### ANSP 
#### Air Navigation Service Providers
An organisation that provides the service of managing the aircraft **in flight**, or on the **manoeuvering area** of an airport. The ANSP is the legitimate holder of that responsibility and manages flight traffic on behalf of a company (normally an airline), region or country.

SITA enables ANSPs to transmit clearance information to departing aircrafts via datalink messaging. This includes
operational data such as:

* Call sign
* Departure and destination airport 
* Runway to use
* Exit point 
* Standard instrument departure (SID)
* Squawk code 
* Departure time 
* Ground ATC frequency
* Current ATIS identifier.


### ATC Network 
Air traffic control Networks are provided by SITA to ANSPs and airlines around the world. It comprises the complete air/ground VHF infrastructure for aircraft communications
### ATN Aeronautical Tele communication Network Router
Sounds similar to the previous acronym. This plus a datalink processor usually make up the core of a VHF station

#### Safety and Redundancy:
Airports often have redundant VHF systems to ensure communication and navigation capabilities are maintained even in the event of equipment failures. These systems are vital for aviation safety and **switch over** procedures. 
####  Regulation and Standards:

VHF station operation is subject to strict regulations and standards set by aviation authorities in each country. These regulations ensure that frequencies are allocated properly, equipment is maintained, and safety standards are met.

