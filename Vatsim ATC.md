## ATIS

# “This is Schiphol information Delta, main landing runway 18R, main take-off runway 24, transition level 40, 220 degrees 10 knots, CAVOK, temperature 19, dew point 12, QNH 1030, no significant change. End of information Delta.”

You will see that the clearence also contains the ATIS letter, in this case Delta (see flight preparation). This is mandatory, so that the relevant ATC knows that the pilot is aware of the situation at the airport.

An answer from traffic control (EHAM_DEL):

# EHAM_DEL: TRA7137, Delta is correct, cleared to Maastricht, LOPIK 1S departure, runway 24, initial climb FL060, Squawk 4522.

As you can see, an ATC clearance is not difficult to understand, provided you are prepared. Two new elements in the clearance are the “Squawk” and “initial climb”. The “Squawk” is a four-digit code that the pilot must enter in his/her transponder. This way, traffic control sees you appear on the radar. The “Initial climb” is the height to which we are allowed to climb after take-off.

The pilot must always confirm the clearance from the ATC by repeating the clearance, for example:

 **TRA7137: Cleared to Maastricht, LOPIK 1S departure, runway 24, initial climb FL060, Squawk 4522, TRA7137.**

The ATC will then say:

# EHAM_DEL: TRA7137, Readback correct, report fully ready.

In principle, the pilot no longer needs to confirm this, but he can:

## RA7137: Wilco, TRA7137

WILCO means: WILl COmply, so that means that you follow the traffic controller's instruction. So this instruction is that you report when you are ready for the start of the engines and the pushback. Wilco is usually only used when ATC gives an order to report a specific moment.

If you are in doubt, just readback what the ATC tells you. Then in this case you could say:

## TRA7137: Will report fully ready, TRA7137

We have entered the transponder code, namely 4522 and we have already entered the SID, so we are basically ready for the start and the pushback.

We indicate this with:

## TRA7137: TRA7137 fully ready at C11.

The ATC's response will then be:

# EHAM_DEL: TRA7137, Information Delta, QNH 1030, contact Ground 121.800, bye!

## TRA7137: Information Delta, QNH1030, contacting Ground 121.800, bye bye

Our clearance has been received, but to get the pushback and startup clearance we have to go to Ground Control on frequency 121.800.

## TRA7137: Schiphol Ground, TRA7137 at C11 request pushback.

# EHAM_N_GND: TRA7137, Startup and Pushback approved.

## TRA7137: Startup and Pushback approved, TRA7137.

The Schiphol Map shows which side we should pushback from gate C11. This shows that you should stand with your nose to the east. You can deduce this from the “L” that is on the ground map behind C11. “L” means left. Seen from the pushback truck, the flight is pushed to the left, from C11, so with the nose towards the (south-)east.

Once our engines have started and we have been pushed back, we will contact the ATC again to be allowed to taxi:

## TRA7137: TRA7137, ready for taxi

# EHAM_N_GND: TRA7137, taxi to holding point S7 runway 24.

## TRA7137: Taxiing to S7 24, TRA7137

So we have to taxi to point S7 at runway 24. On the map we see that this is the holding company of 24. Furthermore, the ground map of Schiphol shows which taxiways are one-way and how to get to S7.

Once we arrive at the runway, we will be transferred by Ground Control to Schiphol Tower on frequency 119.225:

# EHAM_N_GND: TRA7137, Contact Tower 119.225, have a nice flight, bye bye

## TRA7137: Contacting Tower 119.225, bye bye

And we report to the tower:

## TRA7137: Schiphol Tower, good afternoon, TRA7137 fully ready for departure at S7 runway 24.

# EHAM_M_TWR: TRA7137, good afternoon, wind 220 at 10 knots, runway 24, cleared for takeoff.

## TRA7137: Cleared for takeoff runway 24, TRA7137.

As you can see, we are ready for takeoff. From this moment on things will go very fast. It is useful that you first read the next part of this document in general before you unsuspectingly take to the airspace.
The maps of Schiphol indicate that when we pass 2000ft, we must automatically switch to Schiphol Departure on frequency 119.050. However, at VATSIM it is not so busy that we work with a separate Departure. After we have passed 2000ft we automatically switch to Schiphol Approach on frequency 121.20.

We are initially cleared to climb to FL060. This can be found on the maps in the E-AIP. If we approach FL060, but we have not cleared any higher, you should stay at FL060 and not continue climbing. The Transition Altitude (TA) at Schiphol is 3000ft. This means that at 3000ft we have to set the air pressure to STD (Standard 1013 millibars).

Furthermore, it also states that the speed after take-off must remain at V2+20 up to 3000 feet due to the noise standards and the ATC also takes this into account with regard to separation (keeping aircraft apart). Below FL100 everyone is obliged not to fly faster than 250kts, unless this is allowed by the relevant ATC. The ATC also takes this into account with the separation!

After take-off we will switch to Schiphol Departure at 121.200 to report:

## TRA7137: Departure, TRA7137, passing 2000ft, LOPIK 1S departure.

# EHAM_W_APP: TRA7137, identified, climb to FL070.

## TRA7137: Climbing to FL070, TRA7137.

You must always report the SID when you register at departure, that is why I say that I pass 2000ft, but also that I fly the LOPIK 1S SID. When you climb to FL070 you will at some point hear:

# EHAM_W_APP: TRA7137, contact Amsterdam Radar on frequency 125.750, bye bye.

## TRA7137: Contacting Amsterdam on 125.750, see you soon.

We are transferred to Amsterdam Radar, because we are leaving the Schiphol Approach area.

When we arrive at Amsterdam Radar, we register again. We no longer need to report the SID in this case. Only the cleared height is important:

## TRA7137: Amsterdam, TRA7137 climbing to FL070.

# EHAA_W_CTR: TRA7137, radar contact, proceed directly to OSGOS.

The ATC starts by saying that we have 'radar contact'. This means that we can be seen on the radar and that we have our Squawk code (4522) correctly in our transponder and that the transponder also transmits this code. We can also go directly to the OSGOS point. That's the last point on our flight plan. We can now fly directly from our current position to OSGOS, without having to follow the P57 Airway to OSGOS, for example. This ensures a shorter flight time and you will encounter it much more often on other longer flights.

Dutch airspace has been delegated to several authorities, including Dutch Mil. That is the military branch of traffic control. We fly to Maastricht. To get there we also fly through military areas, so after a while we are told that we have to contact Dutch Mil on frequency 128.350. I think it is now clear how you are transferred to another frequency.

Registration is done as follows:

## TRA7137: Dutch Mil, TRA7137, FL70 inbound OSGOS.

# EHMC_CTR: TRA7137, identified, continuous inbound OSGOS, when ready descend FL50 level by OSGOS.

## TRA7137: When ready descending FL50 level by OSGOS, TRA7137.


This means that we can descend whenever we want, as long as we reach the point OSGOS at FL050. Also not unimportant is the fact that after OSGOS we have to fly less than 20 NM before we reach the runway, so it is important that we do not descend too late, so that we can reduce the speed in time. Try to prepare the approach while descending. Especially if you are just starting to fly online, the approach can be a high workload, because you have to set everything, navigate and also listen to air traffic control. So make sure you are prepared in time!

The airspace around Maastricht is called the Maastricht TMA. Dutch Mil transfers us to EHBK_APP (Maastricht Radar) on frequency 123.975 well before OSGOS, so that we hear the arrival instructions on time. After OSGOS our flight plan stops. If we call up Maastricht radar, we also have to call up the ATIS again. You can do this via the standby com radio, or via the primary when it is quiet. Possibly you can read it via text.

Beek's ATIS will not differ greatly from that of Schiphol. The only difference is that Beek only has 1 runway, which is used for both take-off and landing traffic. In our case we assume that runway 21 is in use. The Transition Level is FL045. This means that above FL045 we must set a standard air pressure (QNH1013), but below FL045 we must set the local air pressure of the airport (QFE). Keep in mind that Transition Level is not the same as Transition Altitude. The Transition Altitude is fixed and is only important for departing traffic. The Transition Level can vary and is highly dependent on the weather.

An example of what communication with traffic control can be:

## TRA7137: Maastricht, TRA7137, passing FL60 descending FL050 inbound OSGOS, we have information BRAVO.

# EHBK_APP: TRA7137, Information BRAVO is correct, leave OSGOS heading 160, runway 21 in use for landing

## TRA7137: Leaving OSGOS heading 160, expecting 21, TRA7137

We are expected to fly a heading of 160 after OSGOS and we can indeed expect runway 21 to land. To prevent the workload from becoming too high, it is useful to prepare the approach now. We take the STAR card from Maastricht to look up the ILS (Instrument Landing System) frequency and course. We see that the ILS frequency is 111,550 (entered in NAV1 and NAV2) and the course associated with it is 213.

Once we reach OSGOS and reach FL050 we will soon have to descend further from the ATC:

# EHBK_APP: TRA7137, Descend 2500ft QNH1006 reduce your speed to 180 knots.

## TRA7137: Descending 2500ft QNH1006 will reduce to 180knots, TRA7137.

This means that we can descend to 2500ft with air pressure set to 1006. We also have to reduce our speed to 180 knots.

About 3 miles from the ILS the ATC will clear us for the approach:

# EHBK_APP: TRA7137, Turn right heading 195, cleared ILS approach runway 21.

## TRA7137: Right 195, cleared ILS approach 21, TRA7137.

This means that we have to make a right turn to heading 195. At that heading we are ready to catch the ILS. Suppose we have to go to heading 195, we have not yet cleared the approach and we are crossing the ILS, then we are not allowed to take the signal and follow the ILS path. We then have to continue flying on heading 195, but that is not the case now.

Once we have the ILS and the glideslope, we can inform the ATC that we are established on the ILS:

## TRA7137: TRA7137, established runway 21.

# EHBK_APP: TRA7137, 7 miles to go, you are number 1, contact Tower on 119.475, bye bye

## TRA7137: Contacting Tower 119.475, TRA7137, bye bye

We now transfer to the tower to get our landing clearance:

## TRA7137: Tower, TRA7137 with you established runway 21.

# EHBK_TWR: TRA7137, Winds 240 at 7 knots, runway 21, cleared to land.

## TRA7137: Cleared to land, TRA7137.


We can land!

After landing at Maastricht airport, the aircraft usually has to “Backtrack”.

After landing, we make a 180 degree turn on the runway and then take the first taxiway to the left, so that we arrive at one of the stands.

# EHBK_TWR: TRA7137, make a 180 turn when possible, take the first exit to the left, report when vacated.

## TRA7137: Making a 180 turn when possible, will take the first exit to the left and report vacated, TRA7137

This has to be done quite quickly, because there may be a crate approaching the track, but you will be told that. When we leave the track we must report this:

## TRA7137: TRA7137, vacating runway 21.

# EHBK_TWR: TRA7137, Taxi to stand A3 for parking with the marshaller.

## TRA7137: Taxiing to stand A3, TRA7137.

We are expected to go to stand A3. If you are standing still at the stand, you can still log out:

## TRA7137: TRA7137 at the stand, switching off and thank you, goodbye.

# EHBK_TWR: TRA7137, have a nice evening and welcome to VATSIM!

Congratulations on completing your first real VATSIM flight!
You are now free to log out or prepare a new flight.

6. Debriefing
This Tutorial uses many air traffic control positions, summarized in the correct order:

Schiphol Delivery [EHAM_DEL]
Schiphol Ground [EHAM_N_GND]
Schiphol Tower [EHAM_M_TWR]
Schiphol Approach / Departure [EHAM_W_APP]
Amsterdam Radar [EHAA_W_CTR]
Dutch Mill [EHMC_CTR]
Beek Approach [EHBK_APP]
Brook Tower [EHBK_TWR]

Not all positions have been used that you get when you have a full complement of air traffic controllers, but the most important positions and the positions that are often online are included. What often happens is that at Schiphol EHAM_M_TWR is online, but EHAM_N_GND and EHAM_DEL are not. Then you have to go to EHAM_M_TWR to get the clearance for the flight. If EHAM_M_TWR is not online then go to EHAM_W_APP. If it is not online then go to EHAA_W_CTR. You should not go further than EHAA_W_CTR. If you have any doubts, you can always send a private message to a controller.

If no one is online, you are expected to take off yourself, preferably via the standard routes. If you are unsure, you can contact other controllers in Dutch airspace via text to ask if ATC is provided on yours. Moreover, if you have questions about something that is unclear, you can always contact people online. It's better to ask a hundred questions than to be faced with surprises after takeoff. It's okay if something goes wrong, but try to prevent that as much as possible by asking questions!

As you can see, there is a lot involved in a typical flight on VATSIM. However, you will notice that every flight gets better and you regard more and more elements of a flight like this as standard and hardly have to think about what to do.

The amount of information may be overwhelming, but remember that each of us started out as an unsuspecting pilot! When things are quiet, ATC is always willing to help you and provide advice. Once you are 'settled' on the VATSIM network, you will never want to go anywhere else! We wish you the best of luck with the upcoming flights, and hope to see you online often!




