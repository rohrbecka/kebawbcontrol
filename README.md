# kebawbcontrol
A Swift library to control a KEBA (www.keba.com) Wallbox through it's 'Smart Home' UDP interface.

## Motivation
The motivation to develop this library was to control the charging of a battery electric vehicle (BEV) in a more detailed fashion as it would be possible using the cars features. The final goal is to control the charging processes to load the vehicle with as much power from a photovoltaic grid as possible, taking into account the needs of having the car charged and taking into account the power consumption of the home grid.

## Capabilities of this library
The KebaWallboxControl (kebawbcontrol) library is a Swift wrapper around the UDP interface, which the Keba Wallboxes are providing. (See [the programming guide|https://www.keba.com/web/downloads/e-mobility/KeContact_P20_P30_UDP_ProgrGuide_en.pdf for details]).
