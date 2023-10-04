
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
 * When ACARS message is sent from aircraft to an ACARS core (downlink= to the dual core ADFP (connector) - ADLT (ACARS processor) ground station its 618 (type A message). In the ADLT it converts to 620 (type B message). The message going back is called uplink. 


### The Service Provider (SITA)
The ground-based ACARS networks are globally operated by two main **Datalink Service Providers** (DSP).
The DSP is responsible for the movement of messages via radio link, usually to/from its own ground routing system. ACARS messages are transmitted using one of three possible data link methods:

* **VHF** or **VDL** (VHF Data Link) which is line-of-sight limited
* **SATCOM** in areas where here is no link to a ground station, ACARS uses **satellite communication** (not available in polar regions)
* **HF** or **HFDL** (HF Data Link) which has been added especially for polar region communications. 

The two main DSPs globally are Rockwell Collins (SITA's competitor) and **SITA**.
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
Aircraft goes to 35K feet and VHF 230-240 nautical miles

### VGS 
VGS stands for **VHF Ground Station**. These are the stations that SITA has 

### VDL 
VDL stands for **VHF Digital Link**.  
The VHF Digital Link mode 2 (VDL2) system, has a thirteen times higher transmission rate air-ground link than VHF ACARS, but is very similar to VHF ACARS. Sita's stations are referred to as VHF stations or VDL stations. 

### Internet Working
When an aircraft flies over a region where SITA VHF stations do not operate, ARINC stations will recieve the downlink messages and send them to SITA ADFP and then to the ADLT in either of the main core sites and vice versa. 

### ANSP 
#### Air Navigation Service Providers
An organisation that provides the service of managing the aircraft in flight or on the manoeuvering area of an airport and which is the legitimate holder of that responsibility. 
