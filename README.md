# M712B · Communication

Ward-Beck Systems M712B, 1982|15. Wiki page: [M712B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M712B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 6 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 15 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 17 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 0 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 0 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 1 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 24 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1982 - M712B - 003.jpg](MANUALS/1982%20-%20M712B%20-%20003.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | Unity, +3 dB trim range. ±0.25 dB from 100 Hz to kHz |
| **Noise** | Better than 70 dB below +8 dBm (20 Hz to 20 kHz)_ Less than 0.25% ThD from 100 Hz to kHz at +18 dBm output into 600 ohm Toad |
| **Harmonic distortion** |  |
| &nbsp;&nbsp;Input level | +8 dBm nomina] +20 dBm maximum. |
| **Input impedance** | Larger than 30k ohms balanced = center-tapped _ 600 ohms maximum, balanced |
| **Source impedance** | Output Leve]: Output Impedance: +8 dBm nominal, +20 dBm maximum. Less than 50 ohms ba lanced_ center-tapped 600 ohms nomina], 100 ohms minimum (for +18 dBm output) |
| **Phasing** | Input and output termina ]s designated by numbers are in phase |
| **Cross point attenuation** | 100 dB when switched off |
| **Cross point level variation** | +0.5 dB |
| **Power requirements** | +25 volts dc regulated, 40 mA |
| **Ambient temperature** | to 60 degrees Celsius |
| **Dimensions** | 0 7&quot; wide 4.4&quot; high 11&quot; deep (18 mm 112 Mm 280 mm) |

## Circuit description

From [1982 - M712B - 004.jpg](MANUALS/1982%20-%20M712B%20-%20004.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Additionally, by inserting the appropriate resistors PART-MUTE/ FULLY On and FULLY ON/ PART-MUTE crosspoints maybe implemented (refer to drawing B712-02-101) Norma ]y, partial muting of 12 or 18 dB is utilized Qutput_Ampli fier ' '. The integrated circuit 013 serves a $ mixing and output. amplifier. R134 is gain contro] with trim range of +3 dB Norma ]ly, the M712B operates at standard Tine level of dBm and at unity gain. When driving 600 ohm Toad, the maximum output capability is +20 dBm Alternatively the amplifier will deliver up to +18 dBm maximum into ioo ohm Toad permitting the operation of severa] 600 ohm headsets directly from the output of the M712B without the need for separate output amplifier. t Power_Supply Decoupling 2 The unit is designed to work from +25 volt regulated power supply _.. CR25 protects the amplifier from inadvertent polarity reverse] R140 C49 as well a $ Q1 with its associated components serve a$ filtering and decoupiing components. The emitter of Q1 supplies nomina] +11 volts to the crosspoint circuits_ 4.. ` 7 ' ' ' ` n `..s...

&quot;.. ` n. 4`.. 3

</details>

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1f09bZl-SxykSHpLojyacDWl3xE39yvKp/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1f09bZl-SxykSHpLojyacDWl3xE39yvKp" width="240" alt="1994 - M712B - DOC - 940443-04-002 - UJA CAUTION DISCCHHAE POMER UEL RDPLAGNC.jpg"></a><br><sub>1994|27 · DOC - 940443-04-002 - UJA CAUTION DISCCHHAE POMER UEL RDPLAGNC</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1h7QoJ9t8kbPlgKXbLtsFQMsrG5v5nEo9/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1h7QoJ9t8kbPlgKXbLtsFQMsrG5v5nEo9" width="240" alt="1994 - M712B - DOC - 940444-03-004 - CARD TUBS NOTE REVOVE ALL BURRS AND SHARP.jpg"></a><br><sub>1994|27 · DOC - 940444-03-004 - CARD TUBS NOTE REVOVE ALL BURRS AND SHARP</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1LGVN5Vyd4RQs1LU7peadIQ2pnBHpRf3x/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1LGVN5Vyd4RQs1LU7peadIQ2pnBHpRf3x" width="240" alt="1994 - M712B - DOC - 940444-04-004 - HYBRID UTL UTL HYBRID HYBRID CUTPUTS CORD REAR.jpg"></a><br><sub>1994|27 · DOC - 940444-04-004 - HYBRID UTL UTL HYBRID HYBRID CUTPUTS CORD REAR</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1cdNIPuFQbn_EDEDAWgDl1LxMNWR9ag7L/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1cdNIPuFQbn_EDEDAWgDl1LxMNWR9ag7L" width="240" alt="1994 - M712B - DOC - 94063-04-003 - MODUNES V-ADJ V-ADJ CAUTION DISCOVNECI PONKK REFCRI IRSERMNG.jpg"></a><br><sub>1994|27 · DOC - 94063-04-003 - MODUNES V-ADJ V-ADJ CAUTION DISCOVNECI PONKK REFCRI IRSERMNG</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1PXuPYwVuCfj6cI6EF089y0azi5lEoG3x/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1PXuPYwVuCfj6cI6EF089y0azi5lEoG3x" width="240" alt="1996 - M712B - DOC - 960296-04-001 - RACTRG JOKER VOULLS V-ADJ V-ADJ CAUTION DISCCNNECT PORER.jpg"></a><br><sub>1996|29 · DOC - 960296-04-001 - RACTRG JOKER VOULLS V-ADJ V-ADJ CAUTION DISCCNNECT PORER</sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1ci2d5sfRZ6S1leva3C8pLHIAW4ixnlVt/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1ci2d5sfRZ6S1leva3C8pLHIAW4ixnlVt" width="240" alt="1994 - M712B - DOC - 940249-01-001 - CENTENNIAL COLLEGE RADIO INTERCOM FUNCTIONAL.jpg"></a><br><sub>1994|27 · DOC - 940249-01-001 - CENTENNIAL COLLEGE RADIO INTERCOM FUNCTIONAL</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1mgdA89Fk11XlB0KuC3BDKfFTTM27gAaS/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1mgdA89Fk11XlB0KuC3BDKfFTTM27gAaS" width="240" alt="1996 - M712B - DOC - 96017-01-001 - ISSUEI REMSION.jpg"></a><br><sub>1996|29 · DOC - 96017-01-001 - ISSUEI REMSION</sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRmY2SXNYbGZnUDg/view?resourcekey=0-BU7PuSgk_0h7cVP0bZhXxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRmY2SXNYbGZnUDg&resourcekey=0-BU7PuSgk_0h7cVP0bZhXxQ" width="240" alt="1982 - M712B - 000 - cover.jpg"></a><br><sub>1982|15 · 000 - cover</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWnhmSG5Hd1g5aUE/view?resourcekey=0-cSkDIaOA50mli5Lgu6cXRQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWnhmSG5Hd1g5aUE&resourcekey=0-cSkDIaOA50mli5Lgu6cXRQ" width="240" alt="1982 - M712B - 001.jpg"></a><br><sub>1982|15 · 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZUhDZUhUcERaNzQ/view?resourcekey=0-RYQZwRNxCX21JzU5yek5Sg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZUhDZUhUcERaNzQ&resourcekey=0-RYQZwRNxCX21JzU5yek5Sg" width="240" alt="1982 - M712B - 002.jpg"></a><br><sub>1982|15 · 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbnlRWHlUTlJXa28/view?resourcekey=0-LCZjI3INOVbFE7Avzo6Wyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbnlRWHlUTlJXa28&resourcekey=0-LCZjI3INOVbFE7Avzo6Wyw" width="240" alt="1982 - M712B - 003.jpg"></a><br><sub>1982|15 · 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaFFJOW5NMjdJbzA/view?resourcekey=0-fgjsKrMngG9kLZkbqbSr6g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaFFJOW5NMjdJbzA&resourcekey=0-fgjsKrMngG9kLZkbqbSr6g" width="240" alt="1982 - M712B - 004.jpg"></a><br><sub>1982|15 · 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKclhrMzZpOHVLajg/view?resourcekey=0-CRzNZRJS5-oGqLHfNuLjUg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKclhrMzZpOHVLajg&resourcekey=0-CRzNZRJS5-oGqLHfNuLjUg" width="240" alt="1982 - M712B - 005.jpg"></a><br><sub>1982|15 · 005</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX1dOaFNheFBmUnc/view?resourcekey=0-ka5EBkpKlP3NjBCp8-BU0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX1dOaFNheFBmUnc&resourcekey=0-ka5EBkpKlP3NjBCp8-BU0A" width="240" alt="1982 - M712B - 006.jpg"></a><br><sub>1982|15 · 006</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR2tFbTJDbmxTQ1U/view?resourcekey=0-7MGCi_MKd-Rm5Qbsk2MiMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR2tFbTJDbmxTQ1U&resourcekey=0-7MGCi_MKd-Rm5Qbsk2MiMA" width="240" alt="1982 - M712B - 007.jpg"></a><br><sub>1982|15 · 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlFDdG9ZUEJNSDg/view?resourcekey=0-_8twlggTb7wo0F4ohHayNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlFDdG9ZUEJNSDg&resourcekey=0-_8twlggTb7wo0F4ohHayNw" width="240" alt="1982 - M712B - 008.jpg"></a><br><sub>1982|15 · 008</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb0tVVFhFRjR3UE0/view?resourcekey=0-R2Ay-gczwVdlVzEzzuMc8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb0tVVFhFRjR3UE0&resourcekey=0-R2Ay-gczwVdlVzEzzuMc8w" width="240" alt="1982 - M712B - 009.jpg"></a><br><sub>1982|15 · 009</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbU1KQkxMN2VKY1U/view?resourcekey=0-6iy77rp31PEcjj-Owv1_vA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbU1KQkxMN2VKY1U&resourcekey=0-6iy77rp31PEcjj-Owv1_vA" width="240" alt="1982 - M712B - 010.jpg"></a><br><sub>1982|15 · 010</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNk5oVnV0WEpCRWs/view?resourcekey=0-6LCGXOwCLQf-2L0BY_X3OQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNk5oVnV0WEpCRWs&resourcekey=0-6LCGXOwCLQf-2L0BY_X3OQ" width="240" alt="1982 - M712B - 011.jpg"></a><br><sub>1982|15 · 011</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWG0wcFZpaTBrN28/view?resourcekey=0-EwoUJU2S1meI1HxuiPQ7Fw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWG0wcFZpaTBrN28&resourcekey=0-EwoUJU2S1meI1HxuiPQ7Fw" width="240" alt="1982 - M712B - 012.jpg"></a><br><sub>1982|15 · 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKazF2dnlEOEZ6Ulk/view?resourcekey=0-lc2doQKlssfUYGoKDrNXwA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKazF2dnlEOEZ6Ulk&resourcekey=0-lc2doQKlssfUYGoKDrNXwA" width="240" alt="1982 - M712B - 013.jpg"></a><br><sub>1982|15 · 013</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1ablzAyX5hRqSIyJLiOUdoC4xy5y68tn3/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1ablzAyX5hRqSIyJLiOUdoC4xy5y68tn3" width="240" alt="1996 - M712B - DOC - 2021-3-16-23-22-21.jpg"></a><br><sub>1996|29 · DOC - 2021-3-16-23-22-21</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/16KDXNhmVHwZAA9b2iSEZlTD6yfay3kh-/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=16KDXNhmVHwZAA9b2iSEZlTD6yfay3kh-" width="240" alt="19xx - M712B - DOC - 2021-3-16-23-19-37.jpg"></a><br><sub>19xx - M712B - DOC - 2021-3-16-23-19-37</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1gtTOoy8udi8ug_F4luQBvMkWs0sCJ9SV/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1gtTOoy8udi8ug_F4luQBvMkWs0sCJ9SV" width="240" alt="19xx - M712B - DOC - 2021-3-16-23-22-3.jpg"></a><br><sub>19xx - M712B - DOC - 2021-3-16-23-22-3</sub></td></tr>
</table>

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it). Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | +25 V | power |  | medium |
| 2 | BUS OUTPUT | out | OUTPUT | medium |
| 3 | CROSSPOINT 6 CONTROL | control_in | CROSSPOINT 6 CONTROL | medium |
| 4 | CROSSPOINT 5 CONTROL | control_in | CROSSPOINT 5 CONTROL | medium |
| 5 | CROSSPOINT 4 CONTROL | control_in | CROSSPOINT 4 CONTROL | medium |
| 6 | MATRIX INPUT 1 | in | MATRIX INPUT 1 | medium |
| 7 | MATRIX INPUT 2 | in | MATRIX INPUT 2 | medium |
| 8 | MATRIX INPUT 3 | in | MATRIX INPUT 3 | medium |
| 9 | MATRIX INPUT 4 | in | MATRIX INPUT 4 | medium |
| 10 | MATRIX INPUT 5 | in | MATRIX INPUT 5 | medium |
| 11 | MATRIX INPUT 6 | in | MATRIX INPUT 6 | medium |
| 12 | MATRIX INPUT 7 | in | MATRIX INPUT 7 | medium |
| 13 | MATRIX INPUT 8 | in | MATRIX INPUT 8 | medium |
| 14 | MATRIX INPUT 9 | in | MATRIX INPUT 9 | medium |
| 15 | MATRIX INPUT 10 | in | MATRIX INPUT 10 | medium |
| 16 | MATRIX INPUT 11 | in | MATRIX INPUT 11 | medium |
| 17 | MATRIX INPUT 12 | in | MATRIX INPUT 12 | medium |
| 18 | CROSSPOINT 12 CONTROL | control_in | CROSSPOINT 12 CONTROL | medium |
| 19 | CROSSPOINT 11 CONTROL | control_in | CROSSPOINT 11 CONTROL | medium |
| 20 | CROSSPOINT 10 CONTROL | control_in | CROSSPOINT 10 CONTROL | medium |
| 21 | BUS CASCADE INPUT | bus | BUS CASCADE | medium |
| 22 | GROUND | ground |  | medium |
| B | BUS OUTPUT | out | OUTPUT | medium |
| C | CROSSPOINT 3 CONTROL | control_in | CROSSPOINT 3 CONTROL | medium |
| D | CROSSPOINT 2 CONTROL | control_in | CROSSPOINT 2 CONTROL | medium |
| E | CROSSPOINT 1 CONTROL | control_in | CROSSPOINT 1 CONTROL | medium |
| F | MATRIX INPUT 1 | in | MATRIX INPUT 1 | medium |
| H | MATRIX INPUT 2 | in | MATRIX INPUT 2 | medium |
| J | MATRIX INPUT 3 | in | MATRIX INPUT 3 | medium |
| K | MATRIX INPUT 4 | in | MATRIX INPUT 4 | medium |
| L | MATRIX INPUT 5 | in | MATRIX INPUT 5 | medium |
| M | MATRIX INPUT 6 | in | MATRIX INPUT 6 | medium |
| N | MATRIX INPUT 7 | in | MATRIX INPUT 7 | medium |
| P | MATRIX INPUT 8 | in | MATRIX INPUT 8 | medium |
| R | MATRIX INPUT 9 | in | MATRIX INPUT 9 | medium |
| S | MATRIX INPUT 10 | in | MATRIX INPUT 10 | medium |
| T | MATRIX INPUT 11 | in | MATRIX INPUT 11 | medium |
| U | MATRIX INPUT 12 | in | MATRIX INPUT 12 | medium |
| V | CROSSPOINT 9 CONTROL | control_in | CROSSPOINT 9 CONTROL | medium |
| W | CROSSPOINT 8 CONTROL | control_in | CROSSPOINT 8 CONTROL | medium |
| X | CROSSPOINT 7 CONTROL | control_in | CROSSPOINT 7 CONTROL | medium |
| Y | BUS CASCADE INPUT | bus | BUS CASCADE | medium |

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [M712B.kicad_sym](KICAD/M712B.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
