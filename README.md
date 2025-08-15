A small PCB for the Fender AB763 treble and bass tone stack. Inspired by Tristan Collins's [Bandmaster PCB](https://github.com/tristancollins/Guitar-ToneBandmaster), with the same dimensions and for the PCB and mounting holes, and created in KiCad 9.

# Components and their values

* R1: 100k (tone slope resistor, 0.5W or greater)
* R2: 6.8k (mid resistor, 0.5W or greater)
* C1: 250pF (treble capacitor, 400V or greater)
* C2: 100nF/0.1uF (bass capacitor, 400V or greater), has through holes for axial or 5mm radial caps
* C3: 4.7nF/0.0047uF (mid capacitor, 400V or greater)
* J1, J2: 2 pin screw terminal, 5mm spacing
* RV1, RV2: 3 pin screw terminal, 5mm spacing

You can adjust the values of the components to change the behavior of the tone stack. Select the Fender Treble-Bass tonestack at [Yet Another Tonestack Calculator](https://tonestack.yuriturov.com) to compare the frequency response to the standard values here.

Rob Robinette has a great [page on how the TMB tone stack works](https://robrobinette.com/How_The_TMB_Tone_Stack_Works.htm).

# Fabricating the PCB

The 53mm x 45mm PCB can be manufactured by any of the online PCB fabrication sites, like [PCBWay](https://pcbway.com) or [JLCPCB](https://jlcpcb.com/). I use PCBWay, so the back text `WayWayWay` will be converted to the PCBWay product number when it is manufactured. You may want to modify this if you use another manufacturer.

A Gerber file ZIP is included in the repository, generated using the PCBWay plugin for KiCad 9.
