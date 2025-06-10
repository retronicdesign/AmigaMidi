# Amiga Serial Midi Adapter V1.3
![image](https://github.com/user-attachments/assets/76b89823-1769-4808-a696-94092413ad71)

## Schematic
![image](https://github.com/user-attachments/assets/0bac3334-f0eb-40da-9841-3a9a870de065)
(C)2025 Retronic Design - Open Hardware

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
- v1.3 Corrected Schematic and PCB (Larger traces / LED alignement / Smaller 5v regulator)

## PCB
![image](https://github.com/user-attachments/assets/fb43279b-a8b8-41ff-9f54-d08eeab8dc82)
![image](https://github.com/user-attachments/assets/8fc69eff-0014-424f-9058-c4c60ae00185)

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
| 1 |	U1 | 6N136 |
| 1 |	U2 | MAX232 |
| 1 |	U3 | L78L05 |
