# Amiga Serial Midi Adapter V1.2
![MIDI-B](https://user-images.githubusercontent.com/18539931/230472239-8f5f75cc-09ab-45d8-9a18-404810288ec5.png)
## Schematic
![image](https://github.com/retronicdesign/AmigaMidi/assets/18539931/8ce9c4f6-58bd-4377-ae44-80cd34c68443)
(C)2023 Retronic Design - Open Hardware

## Features
- This serial midi interface is compatible with most Amiga Midi softwares.
- It simply convert serial RS-232 RX and TX signals to MIDI TTL standard.
- MIDI IN is opto-isolated to prevent ground loops and induction noise.
- Self powered via serial port.
- Convenient thru connector to connect other instruments to MIDI IN in daisy-chain.
- Tested on Bar and Pipes professional and OCTA-MED. (Let us know yours!)

## Versions
- v1.0 Initial release
- v1.1 Corrected LED polarity
- v1.2 Corrected DB-25 PCB footprint

## PCB
![image](https://github.com/retronicdesign/AmigaMidi/assets/18539931/1c25cb96-cc20-4b32-a4ac-9e8b5ca61921)
![image](https://github.com/retronicdesign/AmigaMidi/assets/18539931/a8dbc4b6-b9c0-4f1e-90a0-c7f044fd3959)

You can have it build at [PCBWay](https://pcbway.com/g/J4X1Dw) under my shared projects.

## Part List

| Quantity | Designator | Part |
| --- | --- | --- |
| 7 |	C1,C2,C3,C4,C5,C6,C7|	0.1uF |
| 1 |	D1 | 1N4148 |
| 2 |	D2,D3 | LED |
| 3 |	J1,J2,J3 | DIN 5 FEMALE |
| 1 |	J4 | D-SUB 25 Female |
| 5 |	R1,R2,R3,R4,R5 | 220 Ohms |
| 2 |	R6,R8 | 1K |
| 1 |	R7 | 3.3K |
| 1 |	U1 | 6N136S |
| 1 |	U2 | MAX232 |
| 1 |	U3 | L78L05 |
