# M712B Intercom Matrix Amplifier · Communication

Ward-Beck Systems M712B, 1982|15. Wiki page: [M712B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M712B.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 9 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 24 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 2 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 18 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
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
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1f09bZl-SxykSHpLojyacDWl3xE39yvKp/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1f09bZl-SxykSHpLojyacDWl3xE39yvKp" width="240" alt="1994 - M712B - DOC - 940443-04-002 - UJA CAUTION DISCCHHAE POMER UEL RDPLAGNC.jpg"></a><br><sub>1994|27 · DOC - 940443-04-002 - UJA CAUTION DISCCHHAE POMER UEL RDPLAGNC · <a href="MECHANICAL/1994%20-%20M712B%20-%20DOC%20-%20940443-04-002%20-%20UJA%20CAUTION%20DISCCHHAE%20POMER%20UEL%20RDPLAGNC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1h7QoJ9t8kbPlgKXbLtsFQMsrG5v5nEo9/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1h7QoJ9t8kbPlgKXbLtsFQMsrG5v5nEo9" width="240" alt="1994 - M712B - DOC - 940444-03-004 - CARD TUBS NOTE REVOVE ALL BURRS AND SHARP.jpg"></a><br><sub>1994|27 · DOC - 940444-03-004 - CARD TUBS NOTE REVOVE ALL BURRS AND SHARP · <a href="MECHANICAL/1994%20-%20M712B%20-%20DOC%20-%20940444-03-004%20-%20CARD%20TUBS%20NOTE%20REVOVE%20ALL%20BURRS%20AND%20SHARP%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1LGVN5Vyd4RQs1LU7peadIQ2pnBHpRf3x/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1LGVN5Vyd4RQs1LU7peadIQ2pnBHpRf3x" width="240" alt="1994 - M712B - DOC - 940444-04-004 - HYBRID UTL UTL HYBRID HYBRID CUTPUTS CORD REAR.jpg"></a><br><sub>1994|27 · DOC - 940444-04-004 - HYBRID UTL UTL HYBRID HYBRID CUTPUTS CORD REAR · <a href="MECHANICAL/1994%20-%20M712B%20-%20DOC%20-%20940444-04-004%20-%20HYBRID%20UTL%20UTL%20HYBRID%20HYBRID%20CUTPUTS%20CORD%20REAR%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1cdNIPuFQbn_EDEDAWgDl1LxMNWR9ag7L/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1cdNIPuFQbn_EDEDAWgDl1LxMNWR9ag7L" width="240" alt="1994 - M712B - DOC - 94063-04-003 - MODUNES V-ADJ V-ADJ CAUTION DISCOVNECI PONKK REFCRI IRSERMNG.jpg"></a><br><sub>1994|27 · DOC - 94063-04-003 - MODUNES V-ADJ V-ADJ CAUTION DISCOVNECI PONKK REFCRI IRSERMNG · <a href="MECHANICAL/1994%20-%20M712B%20-%20DOC%20-%2094063-04-003%20-%20MODUNES%20V-ADJ%20V-ADJ%20CAUTION%20DISCOVNECI%20PONKK%20REFCRI%20IRSERMNG%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1PXuPYwVuCfj6cI6EF089y0azi5lEoG3x/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1PXuPYwVuCfj6cI6EF089y0azi5lEoG3x" width="240" alt="1996 - M712B - DOC - 960296-04-001 - RACTRG JOKER VOULLS V-ADJ V-ADJ CAUTION DISCCNNECT PORER.jpg"></a><br><sub>1996|29 · DOC - 960296-04-001 - RACTRG JOKER VOULLS V-ADJ V-ADJ CAUTION DISCCNNECT PORER · <a href="MECHANICAL/1996%20-%20M712B%20-%20DOC%20-%20960296-04-001%20-%20RACTRG%20JOKER%20VOULLS%20V-ADJ%20V-ADJ%20CAUTION%20DISCCNNECT%20PORER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1ci2d5sfRZ6S1leva3C8pLHIAW4ixnlVt/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1ci2d5sfRZ6S1leva3C8pLHIAW4ixnlVt" width="240" alt="1994 - M712B - DOC - 940249-01-001 - CENTENNIAL COLLEGE RADIO INTERCOM FUNCTIONAL.jpg"></a><br><sub>1994|27 · DOC - 940249-01-001 - CENTENNIAL COLLEGE RADIO INTERCOM FUNCTIONAL · <a href="SCHEMATICS/1994%20-%20M712B%20-%20DOC%20-%20940249-01-001%20-%20CENTENNIAL%20COLLEGE%20RADIO%20INTERCOM%20FUNCTIONAL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1mgdA89Fk11XlB0KuC3BDKfFTTM27gAaS/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1mgdA89Fk11XlB0KuC3BDKfFTTM27gAaS" width="240" alt="1996 - M712B - DOC - 96017-01-001 - ISSUEI REMSION.jpg"></a><br><sub>1996|29 · DOC - 96017-01-001 - ISSUEI REMSION · <a href="SCHEMATICS/1996%20-%20M712B%20-%20DOC%20-%2096017-01-001%20-%20ISSUEI%20REMSION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
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

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1994 - M712B - DOC - 940249-01-001 - CENTENNIAL COLLEGE RADIO INTERCOM FUNCTIONAL.kicad_sch](KICAD/1994%20-%20M712B%20-%20DOC%20-%20940249-01-001%20-%20CENTENNIAL%20COLLEGE%20RADIO%20INTERCOM%20FUNCTIONAL.kicad_sch)
- [1996 - M712B - DOC - 96017-01-001 - ISSUEI REMSION.kicad_sch](KICAD/1996%20-%20M712B%20-%20DOC%20-%2096017-01-001%20-%20ISSUEI%20REMSION.kicad_sch)
- [M712B.kicad_sym](KICAD/M712B.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
