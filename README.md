# Amiga Serial Midi Adapter V1.0
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

## PCB
![image](https://github.com/retronicdesign/AmigaMidi/assets/18539931/2ec80046-7182-4bb6-9913-ab3947b2b78b)
![image](https://github.com/retronicdesign/AmigaMidi/assets/18539931/f4a09e4b-8cd1-4723-bd9b-969d20bef4b7)

You can have it done by [PCBWay here](https://www.pcbway.com/project/shareproject/Amiga_Serial_Midi_Adapter_v1_0_d6b9ad10.html)

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
