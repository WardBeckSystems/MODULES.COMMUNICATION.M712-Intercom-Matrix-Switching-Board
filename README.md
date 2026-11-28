# M712 Intercom Matrix Switching Board · Communication

Ward-Beck Systems M712, 1972|5. Wiki page: [M712 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.COMMUNICATION.M712-Intercom-Matrix-Switching-Board/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 48 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 1 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 18 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 14 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 33 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [19xx - M712 - DOC - 7000 series - 006.jpg](MANUALS/19xx%20-%20M712%20-%20DOC%20-%207000%20series%20-%20006.jpg) page 1 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | Unity (#6dB pre-set control incorporated) |
| **Frequency response** | 1 0.5dB 5OHz to 10kHz |
| **Noise** | S/N better than 7 0aB measured from +8dBm |
| **Total harmonic distortion** | Less than 0.58 measured at +18dBm |
| **Input** | +8dBm nominal (+18dBm Max.) balanced from direct line or from M703 preamplifier |
| **Input impedance** | 30k ohm balanced bridging |
| **Output** | OdBm to +8dBm nominal (+18dBm Max.) |
| **CROSSPOINT ISOLATION/CUT OFF** | 100dB |
| **TURN ON/OFF TRANSIENT** | Inaudible |
| **Power requirements** | 24 volts dc regulated 15mA |

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMXZYbGVIU3NDNVU/view?resourcekey=0-hTPExW3VrqYhrhD4tghm4A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMXZYbGVIU3NDNVU&resourcekey=0-hTPExW3VrqYhrhD4tghm4A" width="240" alt="1972 - M712 - 7000 series - M712 Crosspoint Mb.jpg"></a><br><sub>1972|5 · 7000 series - M712 Crosspoint Mb</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKREozdEhsbHlLVW8/view?resourcekey=0-oAd6HLG_K-NKfb6UAd8pGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKREozdEhsbHlLVW8&resourcekey=0-oAd6HLG_K-NKfb6UAd8pGw" width="240" alt="1972 - M712 - Crosspoint Mb.jpg"></a><br><sub>1972|5 · Crosspoint Mb</sub></td></tr>
</table>

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1DuNdPww8TxqdH6WQaEE0p_EF-Cq0ljLM/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1DuNdPww8TxqdH6WQaEE0p_EF-Cq0ljLM" width="240" alt="1972 - M712 - DOC - 712-02-012 - DIRECT SUMMING INPUT.jpg"></a><br><sub>1972|5 · DOC - 712-02-012 - DIRECT SUMMING INPUT · <a href="SCHEMATICS/1972%20-%20M712%20-%20DOC%20-%20712-02-012%20-%20DIRECT%20SUMMING%20INPUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1OMTP-BeBJfFaBrEtKnQDHkSo8WKKAR4u/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1OMTP-BeBJfFaBrEtKnQDHkSo8WKKAR4u" width="240" alt="1974 - M712 - DOC - WIL TURN OFF CROSSPOINT.jpg"></a><br><sub>1974|7 · DOC - WIL TURN OFF CROSSPOINT</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1c56uRuzssed6A4s-R2l00PWysR9oi0r3/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1c56uRuzssed6A4s-R2l00PWysR9oi0r3" width="240" alt="1974 - M712 - DOC - WILL MUTE CROSSPOINT OWN ONTROL AUDIO INPUT SSMOD.jpg"></a><br><sub>1974|7 · DOC - WILL MUTE CROSSPOINT OWN ONTROL AUDIO INPUT SSMOD</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M712 - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNnlHRlZkM3JsTm8/view?resourcekey=0-revQ6vu3rMBcMR5nVFaNdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNnlHRlZkM3JsTm8&resourcekey=0-revQ6vu3rMBcMR5nVFaNdw" width="240" alt="1977 - M712 - PRICE LIST - 7000 series - price list.jpg"></a><br><sub>1977|10 · PRICE LIST - 7000 series - price list</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXo5Qlg1WHhSVFU/view?resourcekey=0-w8rjcBS4MPo85YWFx8ocVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXo5Qlg1WHhSVFU&resourcekey=0-w8rjcBS4MPo85YWFx8ocVg" width="240" alt="1977 - M712 - PRICE LIST - price list.jpg"></a><br><sub>1977|10 · PRICE LIST - price list</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzVBVVQ2bTZqVnM/view?resourcekey=0-repGA0g2M-cYjkNLkdVC3g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzVBVVQ2bTZqVnM&resourcekey=0-repGA0g2M-cYjkNLkdVC3g" width="240" alt="19xx - M712 - DOC - 7000 series - 001 (2).jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 001 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQmpjMlhlWWFVN2s/view?resourcekey=0-w3Y1UUp--G6NBkxFWSM2kg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQmpjMlhlWWFVN2s&resourcekey=0-w3Y1UUp--G6NBkxFWSM2kg" width="240" alt="19xx - M712 - DOC - 7000 series - 001.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNEF0RmxZZ1g0UVE/view?resourcekey=0-EwEiWuVjwL2wyMU0QftAQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNEF0RmxZZ1g0UVE&resourcekey=0-EwEiWuVjwL2wyMU0QftAQg" width="240" alt="19xx - M712 - DOC - 7000 series - 003 (2).jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 003 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTEllR0Q0WUFRX2s/view?resourcekey=0-JhQL-e1AkYcRWZs2UT2MjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTEllR0Q0WUFRX2s&resourcekey=0-JhQL-e1AkYcRWZs2UT2MjA" width="240" alt="19xx - M712 - DOC - 7000 series - 003.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0NEU0YtWURWNlE/view?resourcekey=0-Yf2B9a0EfFRM67BLHoOQuA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0NEU0YtWURWNlE&resourcekey=0-Yf2B9a0EfFRM67BLHoOQuA" width="240" alt="19xx - M712 - DOC - 7000 series - 006.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 006</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY3pZOXlrZ0t0RFE/view?resourcekey=0-8h2LY0DkIjvm921fBUtGJg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY3pZOXlrZ0t0RFE&resourcekey=0-8h2LY0DkIjvm921fBUtGJg" width="240" alt="19xx - M712 - DOC - 7000 series - 011.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 011</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKR1JWcGZlSDNzM0U/view?resourcekey=0-q1CE3Al4-WnXujmnazn8cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKR1JWcGZlSDNzM0U&resourcekey=0-q1CE3Al4-WnXujmnazn8cw" width="240" alt="19xx - M712 - DOC - 7000 series - 012.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - 012</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWJVRFZCOWs4Uk0/view?resourcekey=0-ZJor6LD49vuAcIvMSiy5cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWJVRFZCOWs4Uk0&resourcekey=0-ZJor6LD49vuAcIvMSiy5cg" width="240" alt="19xx - M712 - DOC - 7000 series - promo - 002.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - promo - 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHFONVE3R2lZeEk/view?resourcekey=0--zLmPVtRl3x81ljGMdSuNQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHFONVE3R2lZeEk&resourcekey=0--zLmPVtRl3x81ljGMdSuNQ" width="240" alt="19xx - M712 - DOC - 7000 series - promo - 003.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - promo - 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHItYXZndkV6RzQ/view?resourcekey=0-hPzwxujvl48SsPZZXRCqMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHItYXZndkV6RzQ&resourcekey=0-hPzwxujvl48SsPZZXRCqMQ" width="240" alt="19xx - M712 - DOC - 7000 series - promo - 004.jpg"></a><br><sub>19xx - M712 - DOC - 7000 series - promo - 004</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM09MSGZTbG1najA/view?resourcekey=0-CdUJhT2w3TBOWyw-3_hUIg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM09MSGZTbG1najA&resourcekey=0-CdUJhT2w3TBOWyw-3_hUIg" width="240" alt="19xx - M712 - DOC - promo - 7000 series - 002.jpg"></a><br><sub>19xx - M712 - DOC - promo - 7000 series - 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU18zSWp5RWMyb0k/view?resourcekey=0-b1mkkSaaCbTCVCqJ67urww" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU18zSWp5RWMyb0k&resourcekey=0-b1mkkSaaCbTCVCqJ67urww" width="240" alt="19xx - M712 - DOC - promo - 7000 series - 003.jpg"></a><br><sub>19xx - M712 - DOC - promo - 7000 series - 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVmRYSDJwZ1lmWE0/view?resourcekey=0-NygdkiuhQYLAYXP5dnAvcg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVmRYSDJwZ1lmWE0&resourcekey=0-NygdkiuhQYLAYXP5dnAvcg" width="240" alt="19xx - M712 - DOC - promo - 7000 series - 004.jpg"></a><br><sub>19xx - M712 - DOC - promo - 7000 series - 004</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1972 - 712-02-003 - PART FULL MUTE CROSS POINT SCHEMATIC - DRN TY - ISS 2.kicad_sch](KICAD/1972%20-%20712-02-003%20-%20PART%20FULL%20MUTE%20CROSS%20POINT%20SCHEMATIC%20-%20DRN%20TY%20-%20ISS%202.kicad_sch)
- [1972 - M712 - DOC - 712-02-012 - DIRECT SUMMING INPUT.kicad_sch](KICAD/1972%20-%20M712%20-%20DOC%20-%20712-02-012%20-%20DIRECT%20SUMMING%20INPUT.kicad_sch)
- [1973 - 712-02-004 - CASCADE CONFIGURATION - DRN GEB - ISS 2.kicad_sch](KICAD/1973%20-%20712-02-004%20-%20CASCADE%20CONFIGURATION%20-%20DRN%20GEB%20-%20ISS%202.kicad_sch)
- [1973 - 712-02-006 - M722 CROSSPOINT - DRN GEB - ISS 2.kicad_sch](KICAD/1973%20-%20712-02-006%20-%20M722%20CROSSPOINT%20-%20DRN%20GEB%20-%20ISS%202.kicad_sch)
- [1973 - 712-02-007 - M723 CROSSPOINT - DRN GEB - ISS 3.kicad_sch](KICAD/1973%20-%20712-02-007%20-%20M723%20CROSSPOINT%20-%20DRN%20GEB%20-%20ISS%203.kicad_sch)
- [1973 - 712-02-008 - M724 CROSSPOINT - DRN GEB.kicad_sch](KICAD/1973%20-%20712-02-008%20-%20M724%20CROSSPOINT%20-%20DRN%20GEB.kicad_sch)
- [1973 - 712-02-010 - M726 CROSSPOINT - DRN GEB - ISS 3.kicad_sch](KICAD/1973%20-%20712-02-010%20-%20M726%20CROSSPOINT%20-%20DRN%20GEB%20-%20ISS%203.kicad_sch)
- [1973 - 712-02-012 - M728 CROSSPOINT - DRN GEB - ISS 3.kicad_sch](KICAD/1973%20-%20712-02-012%20-%20M728%20CROSSPOINT%20-%20DRN%20GEB%20-%20ISS%203.kicad_sch)
- [1974 - 712-02-009 - M725 CROSSPOINT - DRN GEB - ISS 3.kicad_sch](KICAD/1974%20-%20712-02-009%20-%20M725%20CROSSPOINT%20-%20DRN%20GEB%20-%20ISS%203.kicad_sch)
- [1974 - 712-02-013 - M729 CROSSPOINT - DRN GEB - ISS 1.kicad_sch](KICAD/1974%20-%20712-02-013%20-%20M729%20CROSSPOINT%20-%20DRN%20GEB%20-%20ISS%201.kicad_sch)
- [1979 - 712-02-102 - M712B INTERCOM MATRIX AMPLIFIER CONNECTION OF MULTIPLE MODULES - DRN MRW - ENG MRW - ISS 1.kicad_sch](KICAD/1979%20-%20712-02-102%20-%20M712B%20INTERCOM%20MATRIX%20AMPLIFIER%20CONNECTION%20OF%20MULTIPLE%20MODULES%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1980 - 712-01-002 - INTERCOM MATRIX AMPLIFIER FUNCTIONAL DIAGRAM - DRN P. Mahoney - ISS 2.kicad_sch](KICAD/1980%20-%20712-01-002%20-%20INTERCOM%20MATRIX%20AMPLIFIER%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20Mahoney%20-%20ISS%202.kicad_sch)
- [19xx - 712-02-104 - M712A T TEST FIXTURE SCHEMATIC - DRN HM - ENG HM - ISS 1.kicad_sch](KICAD/19xx%20-%20712-02-104%20-%20M712A%20T%20TEST%20FIXTURE%20SCHEMATIC%20-%20DRN%20HM%20-%20ENG%20HM%20-%20ISS%201.kicad_sch)
- [M712.kicad_sym](KICAD/M712.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
