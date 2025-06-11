# Amiga Serial Midi Adapter V1.3
![image](https://github.com/user-attachments/assets/68131b47-9ebf-49ff-b9f5-74145a12df0a)

## Schematic
![image](https://github.com/user-attachments/assets/d484175c-1128-4702-aada-584567cf04ca)
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
- v1.3 Corrected Schematic and PCB (Larger traces / LED alignement / Smaller but capable 5v regulator)

## PCB
![image](https://github.com/user-attachments/assets/426d9b6f-cc8f-4fd5-8617-712a850fca36)
![image](https://github.com/user-attachments/assets/c30a81bf-acde-4c28-bf46-66e8fb0746f4)

You can have it build at [PCBWay](https://pcbway.com/g/J4X1Dw) under my shared projects.

## Part List

| Quantity | Designator | Part |
| --- | --- | --- |
| 1 |	C1|	100pF |
| 6 |	C2,C3,C4,C5,C6,C7|	0.1uF |
| 1 |	D1 | 1N4148 |
| 2 |	D2,D3 | LED |
| 3 |	J1,J2,J3 | DIN 5 FEMALE |
| 1 |	J4 | D-SUB 25 Female |
| 5 |	R1,R2,R3,R4,R5 | 220 Ohms |
| 2 |	R6,R8 | 1K |
| 1 |	R7 | 3.3K |
| 1 |	U1 | 6N136 |
| 1 |	U2 | MAX232 |
| 1 |	U3 | L4931-5.0 |
