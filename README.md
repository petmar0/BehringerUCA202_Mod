#Behringer UCA202 Condenser Microphone Mod#
##Introduction##
The Behringer UCA202 is not initially set up to handle biased microphones, such as electret or condenser mics. Luckily, it can easily be modified to use these with the addition of a bias voltage source, bias resistors, and DC blocking capacitors. The device has two input channels capable of being sampled at a dynamic range of 16 bits at up to 48 kHz. In order to keep the noise floor low and the inputs from microphones as predictable as possible, standard values of capacitors and resistors are used.
##Parts Needed##
* Behringer UCA202 audio interface
* 2x 2.2 kΩ resistors (1% tolerance if possible)
* 2x 100 pF capacitors (ceramic works best)
* 2x LM2937-3.3 3.3 VDC linear regulators
* Solid-core 26 gauge wire (~0.5 m)
* Kapton tape
* Solder (standard 63-37 mix works fine, silver can be used for RoHS compliance)
* Electret microphone
* RCA cable with pigtail ends
* Computer with Raven or Audacity

##Tools Needed##
* Soldering iron
* Needle nose pliers
* Wire cutter
* Wire stripper
* Scissors
* Phillips #1 screwdriver
* Tweezers
* Solder sucker

##Procedure
1. Remove screws from the underside of the UCA202 case
2. Heat up soldering iron
3. Remove board from case
4. Desolder the RCA connectors from the board
5. Cut the plastic pins on the underside of the board that hold the RCA connectors in place
6. Using the needle nose pliers, gently remove the RCA connectors from the board
7. Put the RCA connectors aside
8. Put kapton tape over the smaller vias closer to the edge of the board, from the output RCA connectors
9. Bend down (away from the body) the center pins of the linear regulators at a 90° angle about 5 mm out from the body of each component
10. Place one regulator on the top of the board, and the other on the bottom with the tabs facing the edge of the board, aligned over the outermost large via, with their bent legs going through the next large via
11. Hold the two regulators in place with tweezers while soldering through the holes in their tabs
12. Solder both center conductors in place in their via
13. Trim the excess conductors with wire cutters
14. Wire pin 1 on each of the two regulators (counting from left to right with the tab up) to the terminal with the red wire going into it from the USB cable
15. Pull the center conductors out of one of the pairs of RCA connectors
16. Cut the bottom spike off of the two RCA connector center conductors
17. Re-insert the RCA center conductors
18. Solder one lead of the capacitor to the center conductor, allowing the other lead to come out below the connector
19. Repeat this process with the other RCA connector
20. Solder one of the 2.2 kΩ resistors to the top of the capacitor (the side connected to the RCA)
21. Connect the other lead of the resistor to the output lead (pin 3) of the regulator
22. Repeat this process with the other RCA connector and the other regulator
23. Trim all excess leads
24. Solder the two leads of the electret mic to the RCA cable; the + pin should be attached to the center conductor
25. Plug in the RCA cable with the mic
26. Plug the USB cable into a computer and listen to the input through Raven or Audacity