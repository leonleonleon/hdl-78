# hdl-78

## Description
A project to build a simple drum machine/module inspired by the old ones like cr-78, korg mini pops etc.

## The circuit / sound PCB
The main circuit was designed by ehisforadam (https://lookmumnocomputer.discourse.group/t/verified-stripboard-layouts/81/487) based on the 2700 Twin-T drums by lmnc (https://www.lookmumnocomputer.com/projects#/rhythm-generator) who looked at a copy of Practical Electronics January 1978 ( https://worldradiohistory.com/UK/Practical-Electronics/70s/Practical-Electronics-1978-01.pdf ). I didn't change anything.

## The PSU
Not wanting to work with more than 12V-20V i chose to use some old power adapter that outputs 15V. This is connected to:

- one TPS5430 board delivering +12V and -12V https://www.amazon.de/dp/B096FNSJ6Q/ref=pe_27091401_487027711_TE_SCE_3p_dp_2
- one conververt board delivering +5V https://www.amazon.de/dp/B0B4JG32L5/ref=pe_27091401_487027711_TE_SCE_3p_dp_1

## BOM

#### sound PCB

|     Piece           | Quantity |
|---------------------|----------|
| Diode 1N4148        |       13 |
| 10k                 |        4 |
| 12k                 |        4 |
| 27k                 |        5 |
| 18k                 |        2 |
| 47k                 |        4 |
| 68k                 |        8 |
| 150k                |        4 |
| 100k                |       17 |
| 2k2	              |        1 |
| 1M	              |        2 |
| 4k7                 |        1 |
| 47nF                |	       5 |
| 470nF	              |        5 |
| 15nF	              |        2 |
| 33nF	              |        2 |
| 10nF	              |        2 |
| 150nF	              |        2 |
| 100nF	              |        1 |
| 1n5	              |        2 |
| 4n7	              |        3 |	
| Trim Poti 1M LIN    |	       4 |
| Poti 500k LIN       |	       5 |
| Poti 1M LIN         |        1 |
| 100k attenuator pot |	       6 |
| 100mH	              |        1 |
| CD4011AE	      |        1 |
| TL074	              |        2 |
| 2N3904 Transistor   |        3 |
| DPDT	              |        1 |

#### Arduino MIDI Recieve

|     Piece     | Quantity |
|---------------|----------|
| MIDI female Jack |     1 |
| 220Ohm        |        1 |
| 1N4148        |        1 |
| 10kOhm	      |        1 |
| 470 Ohm       |	       1 |
| 6N138 optocoupler | 	 1 |

	
