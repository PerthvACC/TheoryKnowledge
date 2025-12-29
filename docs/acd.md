# Airways Clearance Delivery

## Components of a clearance

The following items are mandatory components of any airways clearance:

- Callsign;
- Clearance Limit;
- Route of Flight;
- Altitude; 
- Departure Procedure;
- Transponder Code; and 
- Frequency

**Callsign**

It is important to ensure you are giving the right clearance to the right aircraft.

**Clearance Limit**

This is the point to which the aircraft is cleared to. The aircraft cannot proceed beyond this point without obtaining a new clearance. The clearance limit is always the aircraft's destination aerodrome. 

**Route of Flight**

This is the route the aircraft will fly. If the clearance being issued matches the pilots filed route, this can be referenced by the first waypoint followed by the phrase FLIGHT PLANNED ROUTE. If the pilot has filed from one aerodrome to another with only a single intermediate waypoint in between, the phrase FLIGHT PLANNED ROUTE can be omitted. 

Where an amended route is required, this should be communicated as below. The controller must communicate each new waypoint to the pilot, finishing either with the destination aerodrome or the point at which the amended route joins the filed route. 

- via AMENDED [New Waypoint] [New Waypoint] ... [Destination]
- via AMENDED [New Waypoint] [New Waypoint] [Existing Waypoint on Flight Plan] FLIGHT PLANNED ROUTE

If an aircraft has planned direct to an aerodrome with no intermediate waypoints, simply clear them 'direct'.

- Cleared to Rockford, direct

**Runway**

The departure runway assigned to the pilot should be communicated as part of an airways clearance unless a single runway is nominated on the ATIS for departures or the aircraft is intending to conduct circuits. 

**Departure Procedure**

Aircraft may depart via a visual departure or a SID (Standard Instrument Departure). The majority of IFR aircraft departing a major aerodrome will do so via a SID. VFR aircraft cannot fly SIDs so will be issued with a visual departure.

- [SID Chart Title] departure

**Altitude**

This is the initial altitude the pilot has been cleared to after departure. You can find the Standard Assignable level for each aerodrome in the SOPs. 

**"Climb Via SID"**

This phraseology is used to ensure the pilot complies with all speed and level restrictions shown on the SID. 

- CLIMB VIA SID to [Altitude] 

Aircraft not assigned a SID shall be given the standard climb instruction. 

- CLIMB to [Altitude]

**Transponder Code**

The 4 digit code used to uniquely identify the aircraft. Squawk codes only vary between numbers 0-7 (You cannot squawk 8 or higher)

**Departure Frequency**

This is the frequency the aircraft will contact once airborne after recieving the instruction to 'CONTACT DEPARTURES'. 

- If a TCU controller is online, it will be the most appropriate TCU frequency as per aerodrome SOPs
- If an enroute sector is online and no TCU controller is online, they are most likely providing top-down coverage and so the departure frequency should be the enroute sector that covers the aerodrome
- If none of these apply, departures are on advisory 122.800.

## Phraseology

An airways clearance should always be delivered in the standard format to avoid ambiguity.

!!! phraseology
      **QFA251:** "Perth Delivery, QFA251 to Rockford, request clearance." <br>
      **PH ACD:** "QFA251 Perth Delivery, Cleared to Rockford via CAMEL, flight planned route, CAMEL TWO departure, climb via SID to 2000ft, squawk 2461, departure frequency 135.25." <br>
      **QFA251:** "Cleared to Rockford via CAMEL, flight planned route, CAMEL TWO departure, climb via SID to 6000ft, squawk 2461, departure frequency 135.25, Bay 12, QFA251." <br>
      **PH ACD:** "QFA251."
      
!!! phraseology
      **QLK113D:** "Perth Delivery, QLK113D to Tokyo, request clearance." <br>
      **PH ACD:** "QLK113D Perth Delivery, Cleared to Tokyo direct, Runway 33, PERTH TWO departure, climb via SID to 2000ft, squawk 6347, departure frequency 122.8. "<br>
      **QLK113D:** "Cleared to Tokyo direct, Runway 33, PERTH TWO departure, climb via SID to 2000ft, squawk 6347, departures 122.8, Bay 24, QLK113D." <br>
      **PH ACD:** "QLK113D."

## Readbacks

Listen to the read back to ensure the pilot has received the information correctly, the delivery controller should correct any errors as soon as possible, there is no need to relay the entire clearance when responding with a correction, once all components have been correctly read back, they should respond with the aircraft's callsign only. 

The controller should not respond with the phrase "Readback Correct", as that phraseology is not used in Australia.

## VFR Aircraft

There is often confusion surrounding the handling of VFR aircraft in controlled airspace however the reality is that most phraseology transfers over from handling IFR aircraft with some tweaks. A VFR clearance will contain everything listed above however they cannot be assigned a SID. This is relevant when it comes time to issuing the departure procedure and initial altitude. 

!!! phraseology
      **PH ACD:** "GMO, cleared to Lukla via Stadium, climb to 2000ft, squawk 1271, departure frequency 135.25." <br>
      **GMO:** "Cleared to Lukla via Stadium, climb to 2000ft, squawk 1271, departure frequency 135.25, Bay 45, GMO." <br>
      **PH ACD:** "GMO. "

## Activate the FDR

Once the airways clearance has been read back correctly, the controller should click the checkbox under the 'C' column within the departure list. This is to signify the aircraft has recieved and correctly understood every component of their clearance. 

## Heads-Up Coordination

Note that some clearances require a heads-up call to the relevant TCU/ENR controller where they will approve the clearance based on current traffic volumes and controller workload. It also gives the TCU controller a chance to change the assigned level or tracking for the aircraft to be delivered in the airways clearance. Refer to aerodrome SOPs on which clearances require coordination. 

!!! phraseology 
      **PH ACD:** "YLP requests clearance to Lukla" <br>
      **PH TCU:** "YLP clearance approved"
