# M457 Pre-Mixer Module · Routing

Ward-Beck Systems M457, 1975|8. Wiki page: [M457 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M457.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 83 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 45 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 16 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 138 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 19 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 24 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 95 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [17 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1975 - M457 - Pre-Mixer Module.pdf](MANUALS/1975%20-%20M457%20-%20Pre-Mixer%20Module.pdf) page 5 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Input sensitivities** |  |
| &nbsp;&nbsp;Line | Mic: -15 to +15 dBm (ref 600 ohms 60 to -30 dBm ref 150 ohms source): source (Sensitivity continuous Ty adjustab 1e over 30 dB range.) |
| **Gain** |  |
| &nbsp;&nbsp;Line | Mic: 15 dB maximum (matched gain) 60 dB maximum (transducer gain) |
| **Frequency response** | f1.0 dB from 30 Hz to 20 kHz (tailored ro]1-0 ff) |
| **Noise** | -122 dBm EIn at maximum SENSITIVity (20 Hz to 20 kHz) |
| **Harmonic distortion** | Less than 0, 5% THD from 50 Hz to 15 kHz at +18 dBm output. |
| **Input levels** |  |
| &nbsp;&nbsp;Line | at maximum sensitivity: at minimum sensitivity -15 dBm nomina] +15 dBm nomina 1 +10 dBm maximum_ +30 dBm maximum |
| &nbsp;&nbsp;Mic | at maximum sensitivity: at minimum sensitivity: 60 dBm nomina 1 -35 dBm maximum. -30 dBm nomina ] -8 dBm maximum |
| **Input impedances** |  |
| &nbsp;&nbsp;Line | Mic: 30 000 ohms 750 ohms |
| **Source impedances** |  |
| &nbsp;&nbsp;Line mic | 150/600 ohms ba Tanced/unba ]anced_ 150 ohms ba anced/unba Lanced |
| &nbsp;&nbsp;Output level | 10 dBm nomina ] +22 dBm max imum_ I -1 |

## Circuit description

From [1975 - M457 - Pre-Mixer Module.pdf](MANUALS/1975%20-%20M457%20-%20Pre-Mixer%20Module.pdf) pages 7-12 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**42 PRE-MIXER**

The M457 PRE-MIXER is intended to accept four separate microphone or Tine inputs and combine them 1n the desired proportion to produce an output 5 igna 1 Two separate output buses are provided ('A and B '). Each preampli fier can feed either one or both output buses as maybe required Preamplifiers Four identical Preamplifiers are contained in the M457 to ilustrate preamp] i fier number consists of Q1 Q2, 21 and associated components _ R2 is continuous Ty variable SENSItIVIty contro] permitting 30 dB input Teve] variation in order to accommodate constant MIXER LEVEL contro] settings _ Thus the SENSITiVity contro 1 permits operation with microphone Teve] s from -60 to -30 dBm or ine Teve] s from -15 to +15 dBm. RI is the MIXER LEVEL contro] norma ] ly positioned with 10 dB &quot;in hand&quot; When the Tine input is to be used 150 ohm resistor is externa ]Iy connected across pins and A of the edge connector The amplifier wil] then present bridging input 30k ohm) to the source External Summing Inputs 27/28 and 25/26 allow for externa ] summing or combining inputs to be injected into theA and B mixing buses respectively _ These inputs are designed to accept the outputs of other M457 pre-mixers In this way, it is possible to form 8 X2, 12X2 or Target pre-mixer groups 5 -101A BOOSTER Amplifier The 5 -101A DUAL BOOSTER AMPLIFIER mixes the four Preamp] i fier outputs as well a $ the outputs of 25/26 and 27/28 Assignment switches SwI through Sw8 determine the routing of the preampli fier outputs to either A and/or B mixing buses The 'A and B outputs of the 5 -101A appear at pins 17/U and 16 /T respectively The output level at these points is -10 dBm nomina Tly.

**4X2 PRE-MIXER**

Summing outputs for buses 'A and Bare brought out at pins 14/R and 15/S Thes terminals maybe para ] Te 1ed with the 5 umming outputs of other pre-mixers to form pre-mixer groups a $ explained earlier and may subsequently be fed to termina ] s 12/N and 11/M of another pre-mixer the output of which Will then produce the combined mix of aj1 inputs_ Alternatively the para ]elTed suMMing outputs maybe used to feed an M457A MASTER MIXER or any other suitable summing input within the console system Power Supply Decoupling C1 through C4 together with RI1 and R12 form passive on-board power supply decoup] ing circuit CRI and CR2 prevent modu ]e damage in the event of accident] po Parity reverse]

**WM 12IN**

15/5

**12 X2 PRE-MXER**

12 1

**M 1**

11/m 12IN

OUTPUt (-10 dBm)

**1 16L1**

B&quot; OUTPUT (-10 dBm) 8X2 PRE_MXER with MASTER output 11/M 12/n 15/5

**6 F**

OUtPut (+8 dBm)

**11/M 12/N**

15/5 2/8 40

B&quot; OUTPUt (+8 dBm)

**PART**

DESCRIPTIOn

**MFG PART NUMBER**

Capacitor 22 uF/25 V Siemens

**B41313-45226-2**

0 E6 C9 C10 C11 C12 C]3 C14 C15 100 uF/25 V Philips

**426ETF]00**

680 pF 2222-630-03681 47 pF uF/35 470 pF uF/ 35 V 68 pF 2222-638-70479 T390B105M0354S 2222-630-03471 T390B105M035AS 2222-638-70689 Kemet Philips Kemet Philips 6.8 pF 10 uF/25 V 150 uF/ 6 V 2222-638-09688 T390C106M025AS T390E157m006as Kemet Delete Capacitor 680 pF Philips 2222-630-03681

**C]6 C17 C18 C19 C20**

47 pF uF/35 V 470 pF 1 uF/35 V 68 pF 2222-638-70479 T390B105M035AS 2222-630-03471 T390B105M035AS 2222-638-70689 Kemet Philips Kemet Philips

**C21 C22 C23 C24 C25**

6 8 pF 10 uF/25 150 uF / 6 V

**2222-638-09688 T390C706M025AS T390E157M006A$**

Kemet Delete Capacitor 680 pF Philips 2222-630-03681 C26 C27 C28 C2g C30 47 pF uF/ 35 V 470 pF 1 uF/35 V 6 8 p F 2222-638-70479 T390B105M035AS 2222-630-03471 T390B105M03545 2222-638-70689 Kemet Philips Kemet Philips

**C31 C32 C33 C34 C35**

6.8 pF 10 uF/25 V 150 uF / 6 V 2222-638-09688 7390c106m025as T390E157M006AS Kemet De Tete Capacitor 6 80 pF Philips 2222-630-03 681

PARTS LiSt

**C36 C37 C38 C39 C40**

Capacitor 47 pF uF/35 V 470 pF 1 uF/35 6 8 pF Philips Kemet Philips Kemet Philips 2222-638-70479 T390B105M035aS 2222-630-03471 T390B105M035As 2222-638-70689

**C41 C42 C43 C44 C45**

6.8 pF 10 uF/25 V 150 uF / 6 2222-638-09688 T390c106m025aS T390E157M0064S Kemet Delete Capacitor 150 uF / 6 V

**C46 C47 C48 C49 C50**

150 uF / 6 V 0 pF 0 pF 1 0 uF/25 150 uF / 6 Philips 2222-638-10109 Kemet

**C51 C52 C53 C54**

150 uF / 6 0 pF 10 pF 10 uF/25 V Philips 2222-638-10109 Kemet T390C106m025A$

**CRI CR2**

Diode Motoro ]a 1n4003 Transistor Nationa]

**2N 4401**

8 6 86 8 R1/2 R3/4 R5 / 6 R7 / 8 R9 Potentiometer Bourns

**WBS 10-013**

De Tete

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOTI3TG96dzZjT1U/view?resourcekey=0-yz-OxzNpBT76aZQhG6hShA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOTI3TG96dzZjT1U&resourcekey=0-yz-OxzNpBT76aZQhG6hShA" width="240" alt="1975 - M457 - 001 (2).png"></a><br><sub>1975|8 · 001 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdkU5dTJRR1RuQjQ/view?resourcekey=0-oQnAXSpMXz4RtFlzYKyOYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdkU5dTJRR1RuQjQ&resourcekey=0-oQnAXSpMXz4RtFlzYKyOYA" width="240" alt="1975 - M457 - 002 (2).png"></a><br><sub>1975|8 · 002 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUnJTazNvN2JIOFU/view?resourcekey=0-pUXGb8HHHXKzurgOYT2ZJw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUnJTazNvN2JIOFU&resourcekey=0-pUXGb8HHHXKzurgOYT2ZJw" width="240" alt="1975 - M457 - 003 (2).png"></a><br><sub>1975|8 · 003 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQlBJN0djdlBQVWM/view?resourcekey=0-uzRRV8ibbB8ZBznVoNrj5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQlBJN0djdlBQVWM&resourcekey=0-uzRRV8ibbB8ZBznVoNrj5Q" width="240" alt="1975 - M457 - 004 (2).png"></a><br><sub>1975|8 · 004 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKay1hQ2N6S3BTQmc/view?resourcekey=0-5x5jTYSlK0T0vylzpKbxzg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKay1hQ2N6S3BTQmc&resourcekey=0-5x5jTYSlK0T0vylzpKbxzg" width="240" alt="1975 - M457 - 005 (2).png"></a><br><sub>1975|8 · 005 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZDhxNnZPX2lISzg/view?resourcekey=0-S4W5XUWw-JeafJX124c6lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZDhxNnZPX2lISzg&resourcekey=0-S4W5XUWw-JeafJX124c6lw" width="240" alt="1975 - M457 - 006 (2).png"></a><br><sub>1975|8 · 006 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNGhIMVg3cllTQTg/view?resourcekey=0-sSjJ4owKi6KDhUbhWZ55Kw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNGhIMVg3cllTQTg&resourcekey=0-sSjJ4owKi6KDhUbhWZ55Kw" width="240" alt="1975 - M457 - 007 (2).png"></a><br><sub>1975|8 · 007 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmlVcE1CVjROUzQ/view?resourcekey=0-JOZgiFx4kOKQAUJsQyU2Eg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmlVcE1CVjROUzQ&resourcekey=0-JOZgiFx4kOKQAUJsQyU2Eg" width="240" alt="1975 - M457 - 008 (2).png"></a><br><sub>1975|8 · 008 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcWRzRUpsUUJKdkU/view?resourcekey=0-u9KxWaxhBDrAuUNAbJV8Rg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcWRzRUpsUUJKdkU&resourcekey=0-u9KxWaxhBDrAuUNAbJV8Rg" width="240" alt="1975 - M457 - 009 (2).png"></a><br><sub>1975|8 · 009 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT2I3eDNUVXBEamc/view?resourcekey=0-_0uWL1m-ZtBIA7qBcR-Wmg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT2I3eDNUVXBEamc&resourcekey=0-_0uWL1m-ZtBIA7qBcR-Wmg" width="240" alt="1975 - M457 - 010 (2).png"></a><br><sub>1975|8 · 010 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV3hXTlY0cUR6VUk/view?resourcekey=0-fU-pqcgdMfJpr5NNO1DHDA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV3hXTlY0cUR6VUk&resourcekey=0-fU-pqcgdMfJpr5NNO1DHDA" width="240" alt="1975 - M457 - 011 (2).png"></a><br><sub>1975|8 · 011 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbGxGc21rRndXcTg/view?resourcekey=0-6RcjYK1wPGj83UleJSq8VQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbGxGc21rRndXcTg&resourcekey=0-6RcjYK1wPGj83UleJSq8VQ" width="240" alt="1975 - M457 - 012 (2).png"></a><br><sub>1975|8 · 012 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1lQa3c3VTlWc2c/view?resourcekey=0-WPxqBYIWDXYrrlBtgAP0OQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1lQa3c3VTlWc2c&resourcekey=0-WPxqBYIWDXYrrlBtgAP0OQ" width="240" alt="1975 - M457 - 013 (2).png"></a><br><sub>1975|8 · 013 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNkxzRElLcTBBOHM/view?resourcekey=0-Ogq6esegqgT4INjuqw3FYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNkxzRElLcTBBOHM&resourcekey=0-Ogq6esegqgT4INjuqw3FYw" width="240" alt="1975 - M457 - 014 (2).png"></a><br><sub>1975|8 · 014 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKOWVJQ2MxdnFPTmc/view?resourcekey=0--1WpPli31XnOVbIFAjGRoA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKOWVJQ2MxdnFPTmc&resourcekey=0--1WpPli31XnOVbIFAjGRoA" width="240" alt="1975 - M457 - 2x2 Pre-Mixer Module.jpg"></a><br><sub>1975|8 · 2x2 Pre-Mixer Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKay1HQnFmRWtJUE0/view?resourcekey=0-dyFjT4VRQaePEP5NAUemxQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKay1HQnFmRWtJUE0&resourcekey=0-dyFjT4VRQaePEP5NAUemxQ" width="240" alt="1975 - M457 - IMG_3190.jpg"></a><br><sub>1975|8 · IMG_3190</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1975|8 · wbsps - module - m457 2x2 pre-mixer module_small](https://drive.google.com/file/d/0B0yR0b5T78SKVlUwcUFEcE10T1E/view?resourcekey=0-irbcPvi6Pgo6ekjJJmXvjQ)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYVktbmRhTlVfOG8/view?resourcekey=0-bPfV0qj33Njv-hU7_sCPjA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYVktbmRhTlVfOG8&resourcekey=0-bPfV0qj33Njv-hU7_sCPjA" width="240" alt="1975 - M457 - 457-04-005 - CHANNE CHE DES IRED PROPORTION FORM TNE UUTPU.jpg"></a><br><sub>1975|8 · 457-04-005 - CHANNE CHE DES IRED PROPORTION FORM TNE UUTPU · <a href="MECHANICAL/1975%20-%20M457%20-%20457-04-005%20-%20CHANNE%20CHE%20DES%20IRED%20PROPORTION%20FORM%20TNE%20UUTPU%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeHAwcnlSTTlYX28/view?resourcekey=0-3KqhcGvtdNHroMP3uL4M8w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeHAwcnlSTTlYX28&resourcekey=0-3KqhcGvtdNHroMP3uL4M8w" width="240" alt="1975 - M457 - 457-04-005 - FORM THE OUTPUT IGNA.jpg"></a><br><sub>1975|8 · 457-04-005 - FORM THE OUTPUT IGNA · <a href="MECHANICAL/1975%20-%20M457%20-%20457-04-005%20-%20FORM%20THE%20OUTPUT%20IGNA%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUFlOXY2UHl1Qjg/view?resourcekey=0-3pMvxUXkXR_JPaLsKeZ1jQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUFlOXY2UHl1Qjg&resourcekey=0-3pMvxUXkXR_JPaLsKeZ1jQ" width="240" alt="1975 - M457 - 457-04-005 - THE DES IRED PROPORT ION.jpg"></a><br><sub>1975|8 · 457-04-005 - THE DES IRED PROPORT ION · <a href="MECHANICAL/1975%20-%20M457%20-%20457-04-005%20-%20THE%20DES%20IRED%20PROPORT%20ION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcVpidUhrWDNsYjA/view?resourcekey=0-YqSh71U3E7rtEDxVmM_EXg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcVpidUhrWDNsYjA&resourcekey=0-YqSh71U3E7rtEDxVmM_EXg" width="240" alt="1975 - M457 - 457-04-005 - THE DES RED PROPORTION.jpg"></a><br><sub>1975|8 · 457-04-005 - THE DES RED PROPORTION · <a href="MECHANICAL/1975%20-%20M457%20-%20457-04-005%20-%20THE%20DES%20RED%20PROPORTION%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKakotVjlCVmRTSXM/view?resourcekey=0-guMaDjE23uabv8Y6lftytg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKakotVjlCVmRTSXM&resourcekey=0-guMaDjE23uabv8Y6lftytg" width="240" alt="1975 - M457 - 461-03-015 - ILSLL MILUE ADDED.jpg"></a><br><sub>1975|8 · 461-03-015 - ILSLL MILUE ADDED · <a href="MECHANICAL/1975%20-%20M457%20-%20461-03-015%20-%20ILSLL%20MILUE%20ADDED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNll1dG9qU0oxb2M/view?resourcekey=0-Kk1o3CDu1d2HJzgXlu7g0Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNll1dG9qU0oxb2M&resourcekey=0-Kk1o3CDu1d2HJzgXlu7g0Q" width="240" alt="1975 - M457 - 461-03-015 - ZOIAN ALL TRANSISTORS ARE.jpg"></a><br><sub>1975|8 · 461-03-015 - ZOIAN ALL TRANSISTORS ARE · <a href="MECHANICAL/1975%20-%20M457%20-%20461-03-015%20-%20ZOIAN%20ALL%20TRANSISTORS%20ARE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRWdWcF91dHc0TTg/view?resourcekey=0-4HvFDobpAMAgZGD5ShdLtw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRWdWcF91dHc0TTg&resourcekey=0-4HvFDobpAMAgZGD5ShdLtw" width="240" alt="1975 - M457 - 481-03-015 - DUAL BOOSTER AMPLIFIER.jpg"></a><br><sub>1975|8 · 481-03-015 - DUAL BOOSTER AMPLIFIER · <a href="MECHANICAL/1975%20-%20M457%20-%20481-03-015%20-%20DUAL%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZnJWSVF1cF9kNnc/view?resourcekey=0-aoaQvTaaUeDlnW_nZY5vMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZnJWSVF1cF9kNnc&resourcekey=0-aoaQvTaaUeDlnW_nZY5vMA" width="240" alt="1975 - M457 - 481-03-015 - GEB USED.jpg"></a><br><sub>1975|8 · 481-03-015 - GEB USED · <a href="MECHANICAL/1975%20-%20M457%20-%20481-03-015%20-%20GEB%20USED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1975|8 · 457-04-005 - CHANNE JIN THE DESIRED PROPORTION IFORM THE OUTPUT](https://drive.google.com/file/d/0B0yR0b5T78SKUDdXTXNnbk9ESlk/view?resourcekey=0-0H0GwGy8ynqPSvic3eOxIg)

Not on Google Drive yet: `1977 - 457-03-007 - TRANSFORMER MOUNTING BRACKET - DRN GEB - ISS 2.jpg`

## 3-D model

[`MECHANICAL/M457.stl`](MECHANICAL/M457.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M457)

- **Size:** 40.93 × 154.09 mm panel, 165 mm deep, 3.2 mm plate (the drawing sheet, taken as drawn 1:1)
- **From the drawing:** 12 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M457 - front panel.svg`)
- the drawn panel is 0.22 wide to high, the size 0.27: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M457.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/13iL9RRKuUrQ6vBddx0FV_Ja1tivM_3et/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=13iL9RRKuUrQ6vBddx0FV_Ja1tivM_3et" width="240" alt="1975 - 457-02-001 - 4X2 PRE-MIXER SCHEMATIC - DRN DM - ISS 5.jpg"></a><br><sub>1975|8 · 457-02-001 - 4X2 PRE-MIXER SCHEMATIC - DRN DM - ISS 5 · <a href="SCHEMATICS/1975%20-%20457-02-001%20-%204X2%20PRE-MIXER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%205%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1aYF3NXHCG1zZbs6lHDWQZMNYx6D7axtN/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1aYF3NXHCG1zZbs6lHDWQZMNYx6D7axtN" width="240" alt="1975 - 457-02-003 - M457A SCHEMATIC MODIFIED FOR I C INPUT (FOR PROJ. No 74030 - STUDIO 4 - DRN DM.jpg"></a><br><sub>1975|8 · 457-02-003 - M457A SCHEMATIC MODIFIED FOR I C INPUT (FOR PROJ. No 74030 - STUDIO 4 - DRN DM · <a href="SCHEMATICS/1975%20-%20457-02-003%20-%20M457A%20SCHEMATIC%20MODIFIED%20FOR%20I%20C%20INPUT%20(FOR%20PROJ.%20No%2074030%20-%20STUDIO%204%20-%20DRN%20DM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT3VJaVpJMWswLTA/view?resourcekey=0-qxoArYgIROIpaVPICBgadQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT3VJaVpJMWswLTA&resourcekey=0-qxoArYgIROIpaVPICBgadQ" width="240" alt="1975 - M457 - 457-01-001 - PRE SUMMING OUTPUT LINE INPUT.jpg"></a><br><sub>1975|8 · 457-01-001 - PRE SUMMING OUTPUT LINE INPUT · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-01-001%20-%20PRE%20SUMMING%20OUTPUT%20LINE%20INPUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZlp5WjkxVnd3bVU/view?resourcekey=0-l3iQAQIDGrHggEmjqIp9OQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZlp5WjkxVnd3bVU&resourcekey=0-l3iQAQIDGrHggEmjqIp9OQ" width="240" alt="1975 - M457 - 457-01-001 - PRE-MIXER MODULE FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1975|8 · 457-01-001 - PRE-MIXER MODULE FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-01-001%20-%20PRE-MIXER%20MODULE%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZjVYalFELVJabEk/view?resourcekey=0-ajmMnZA2CO8SRRIMyMbSZg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZjVYalFELVJabEk&resourcekey=0-ajmMnZA2CO8SRRIMyMbSZg" width="240" alt="1975 - M457 - 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS (2).jpg"></a><br><sub>1975|8 · 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS (2) · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-02-001%20-%20JIO%20EXTERNAL%20SUMMNG%20INOU%20RIS%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeDVqdC01UVNoZ0k/view?resourcekey=0-lki8EAviLXdr1TjJJ569kA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeDVqdC01UVNoZ0k&resourcekey=0-lki8EAviLXdr1TjJJ569kA" width="240" alt="1975 - M457 - 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS (3).jpg"></a><br><sub>1975|8 · 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS (3) · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-02-001%20-%20JIO%20EXTERNAL%20SUMMNG%20INOU%20RIS%20(3)%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZm9pcjFGYU0xbTA/view?resourcekey=0-MS9uGD-BMXAaaEtKmlogVw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZm9pcjFGYU0xbTA&resourcekey=0-MS9uGD-BMXAaaEtKmlogVw" width="240" alt="1975 - M457 - 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS.jpg"></a><br><sub>1975|8 · 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-02-001%20-%20JIO%20EXTERNAL%20SUMMNG%20INOU%20RIS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKREJrVXh6M19XT0E/view?resourcekey=0-W-UT28fefYMrW_IsXsUsIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKREJrVXh6M19XT0E&resourcekey=0-W-UT28fefYMrW_IsXsUsIQ" width="240" alt="1975 - M457 - 457-02-001 - MOD ICKD USED (2).jpg"></a><br><sub>1975|8 · 457-02-001 - MOD ICKD USED (2) · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-02-001%20-%20MOD%20ICKD%20USED%20(2)%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNUhoOERLWmhwVUE/view?resourcekey=0-lXygVj3ElFzkBppl7TYbbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNUhoOERLWmhwVUE&resourcekey=0-lXygVj3ElFzkBppl7TYbbw" width="240" alt="1975 - M457 - 457-02-001 - MOD ICKD USED.jpg"></a><br><sub>1975|8 · 457-02-001 - MOD ICKD USED · <a href="SCHEMATICS/1975%20-%20M457%20-%20457-02-001%20-%20MOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNzJzVnZ5a0hIeWc/view?resourcekey=0-6mO30UxxBJSqQX8fUWSp5A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNzJzVnZ5a0hIeWc&resourcekey=0-6mO30UxxBJSqQX8fUWSp5A" width="240" alt="1975 - M457 - 5-101-02-002 - ERWISE SPECIFIED LAST COMPONENT DLSIGNATIONS CIO CRA ELL.jpg"></a><br><sub>1975|8 · 5-101-02-002 - ERWISE SPECIFIED LAST COMPONENT DLSIGNATIONS CIO CRA ELL · <a href="SCHEMATICS/1975%20-%20M457%20-%205-101-02-002%20-%20ERWISE%20SPECIFIED%20LAST%20COMPONENT%20DLSIGNATIONS%20CIO%20CRA%20ELL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKY01rUnFYMUt4VE0/view?resourcekey=0-kj6lrbdJ-P7MEFD9MgUi9Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKY01rUnFYMUt4VE0&resourcekey=0-kj6lrbdJ-P7MEFD9MgUi9Q" width="240" alt="1975 - M457 - 5-101-02-002 - MOD ICKD USED.jpg"></a><br><sub>1975|8 · 5-101-02-002 - MOD ICKD USED · <a href="SCHEMATICS/1975%20-%20M457%20-%205-101-02-002%20-%20MOD%20ICKD%20USED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNXB2Mk41XzZWVnM/view?resourcekey=0-1rcUhYPqP5E-zc1c73SMMw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNXB2Mk41XzZWVnM&resourcekey=0-1rcUhYPqP5E-zc1c73SMMw" width="240" alt="1975 - M457 - 5-101-02-002 - SPECIFIED LAST COMPONENT DESICNATIONS.jpg"></a><br><sub>1975|8 · 5-101-02-002 - SPECIFIED LAST COMPONENT DESICNATIONS · <a href="SCHEMATICS/1975%20-%20M457%20-%205-101-02-002%20-%20SPECIFIED%20LAST%20COMPONENT%20DESICNATIONS%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeklodlFvRHk1bjA/view?resourcekey=0-C1KKAazbYqKzirH4NNqgOA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeklodlFvRHk1bjA&resourcekey=0-C1KKAazbYqKzirH4NNqgOA" width="240" alt="1975 - M457 - 5-101-02-002 - SPECIFISD LAST COMPONENT DESICNATIONS.jpg"></a><br><sub>1975|8 · 5-101-02-002 - SPECIFISD LAST COMPONENT DESICNATIONS · <a href="SCHEMATICS/1975%20-%20M457%20-%205-101-02-002%20-%20SPECIFISD%20LAST%20COMPONENT%20DESICNATIONS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZzhvLTVkZDEyUzQ/view?resourcekey=0-mYEm0s9QoJnFPpkRQwBMMA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZzhvLTVkZDEyUzQ&resourcekey=0-mYEm0s9QoJnFPpkRQwBMMA" width="240" alt="1975 - M457 - 5-106-06-001.jpg"></a><br><sub>1975|8 · 5-106-06-001 · <a href="SCHEMATICS/1975%20-%20M457%20-%205-106-06-001%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1975 - 457-02-002 - PRE-MIXER MASTER MODULE SCHEMATIC - DRN DM - ISS 3.jpg`, `1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2 (2).jpg`, `1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2 (3).jpg`, `1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2.jpg`, `1977 - 457-01-002 - PRE-MIXER MASTER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjQ1MFlFblhVSlE/view?resourcekey=0-FPDN697IHu0lb8cHmZMoBg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjQ1MFlFblhVSlE&resourcekey=0-FPDN697IHu0lb8cHmZMoBg" width="240" alt="1975 - M457 - Connector layout.jpg"></a><br><sub>1975|8 · Connector layout · <a href="PINOUTS/1975%20-%20M457%20-%20Connector%20layout%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWVONmYxRGtxUDA/view?resourcekey=0-qC3uCu6na5fmchXxpf5zZA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWVONmYxRGtxUDA&resourcekey=0-qC3uCu6na5fmchXxpf5zZA" width="240" alt="1977 - M457 - 457-04-003 - PRE-MIXER CONNECTOR REAR VIEW.jpg"></a><br><sub>1977|10 · 457-04-003 - PRE-MIXER CONNECTOR REAR VIEW · <a href="PINOUTS/1977%20-%20M457%20-%20457-04-003%20-%20PRE-MIXER%20CONNECTOR%20REAR%20VIEW%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M457 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 2 pinout pictures (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 16 of 16 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | MIC 4 IN | in | MIC 4 IN | high |
| 2 | LINE 4 IN | in | LINE 4 IN | high |
| 3 | MIC 3 IN | in | MIC 3 IN | high |
| 4 | LINE 3 IN | in | LINE 3 IN | high |
| 5 | SHIELD | shield | shield | high |
| 6 | MIC 2 IN | in | MIC 2 IN | high |
| 7 | LINE 2 IN | in | LINE 2 IN | high |
| 8 | MIC 1 IN | in | MIC 1 IN | high |
| 9 | LINE 1 IN | in | LINE 1 IN | high |
| 10 | SHIELD | shield | shield | high |
| 11 | B EXTERNAL INPUT | in | B EXTERNAL INPUT | high |
| 12 | A EXTERNAL INPUT | in | A EXTERNAL INPUT | high |
| 13 | N/C | nc |  | high |
| 14 | TO A MIXER BUSS | bus | TO A MIXER BUSS | high |
| 15 | TO B MIXER BUSS | bus | TO B MIXER BUSS | high |
| 16 | B MIX OUT | out | B MIX OUT | high |
| 17 | A MIX OUT | out | A MIX OUT | high |
| 18 | N/C | nc |  | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COMMON | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | MIC 4 IN | in | MIC 4 IN | high |
| B | LINE 4 IN | in | LINE 4 IN | high |
| C | MIC 3 IN | in | MIC 3 IN | high |
| D | LINE 3 IN | in | LINE 3 IN | high |
| E | SHIELD | shield | shield | high |
| F | MIC 2 IN | in | MIC 2 IN | high |
| H | LINE 2 IN | in | LINE 2 IN | high |
| J | MIC 1 IN | in | MIC 1 IN | high |
| K | LINE 1 IN | in | LINE 1 IN | high |
| L | SHIELD | shield | shield | high |
| M | B EXTERNAL INPUT | in | B EXTERNAL INPUT | high |
| N | A EXTERNAL INPUT | in | A EXTERNAL INPUT | high |
| P | N/C | nc |  | high |
| R | TO A MIXER BUSS | bus | TO A MIXER BUSS | high |
| S | TO B MIXER BUSS | bus | TO B MIXER BUSS | high |
| T | B MIX OUT | out | B MIX OUT | high |
| U | A MIX OUT | out | A MIX OUT | high |
| V | N/C | nc |  | high |
| W | N/C | nc |  | high |
| X | N/C | nc |  | high |
| Y | N/C | nc |  | high |
| Z | N/C | nc |  | high |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRlZYM3V6QUppTlU/view?resourcekey=0-U0oC2fc0XH4D7pvrh2E3Og" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRlZYM3V6QUppTlU&resourcekey=0-U0oC2fc0XH4D7pvrh2E3Og" width="240" alt="1975 - M457 - 000 (2).png"></a><br><sub>1975|8 · 000 (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbzU1ZVFycWxNLWs/view?resourcekey=0-HnEFiHJqUwtgjoSe5Fi-4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbzU1ZVFycWxNLWs&resourcekey=0-HnEFiHJqUwtgjoSe5Fi-4w" width="240" alt="1975 - M457 - 000.png"></a><br><sub>1975|8 · 000</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXBXY1A4WW5VcjA/view?resourcekey=0--MWRkoKoP4UNS1VHaHxAJw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXBXY1A4WW5VcjA&resourcekey=0--MWRkoKoP4UNS1VHaHxAJw" width="240" alt="1975 - M457 - 001.png"></a><br><sub>1975|8 · 001</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjU3VTlCd21fOXc/view?resourcekey=0-V96_-LKTS5QFNZHqvA66cQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjU3VTlCd21fOXc&resourcekey=0-V96_-LKTS5QFNZHqvA66cQ" width="240" alt="1975 - M457 - 002.png"></a><br><sub>1975|8 · 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUk1zNFRJQnMxUTQ/view?resourcekey=0-C6LJ-KO3hwCPqdZnc_vrbw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUk1zNFRJQnMxUTQ&resourcekey=0-C6LJ-KO3hwCPqdZnc_vrbw" width="240" alt="1975 - M457 - 003.png"></a><br><sub>1975|8 · 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdGlNbU5zamlsNkk/view?resourcekey=0-mWT44pbLDvPpBqWtjLpsHA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdGlNbU5zamlsNkk&resourcekey=0-mWT44pbLDvPpBqWtjLpsHA" width="240" alt="1975 - M457 - 004.png"></a><br><sub>1975|8 · 004</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdnRkMy1PTzhyMzA/view?resourcekey=0-rl4E4QKZREP7dduCLd_jEQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdnRkMy1PTzhyMzA&resourcekey=0-rl4E4QKZREP7dduCLd_jEQ" width="240" alt="1975 - M457 - 005.png"></a><br><sub>1975|8 · 005</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKXzdDekFOT05EQU0/view?resourcekey=0-FEztwFRIA9ZzH-g-h0MbKQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKXzdDekFOT05EQU0&resourcekey=0-FEztwFRIA9ZzH-g-h0MbKQ" width="240" alt="1975 - M457 - 006.png"></a><br><sub>1975|8 · 006</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFRra3lLblJreXM/view?resourcekey=0-2t-zuRLFDYEtZjx2vO926A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFRra3lLblJreXM&resourcekey=0-2t-zuRLFDYEtZjx2vO926A" width="240" alt="1975 - M457 - 007.png"></a><br><sub>1975|8 · 007</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUjRncm1uUmZ3bEU/view?resourcekey=0-ta77_4kfEq9tMBlba4VAYw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUjRncm1uUmZ3bEU&resourcekey=0-ta77_4kfEq9tMBlba4VAYw" width="240" alt="1975 - M457 - 008.png"></a><br><sub>1975|8 · 008</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLUZkdzdRN0djYzg/view?resourcekey=0-mUVyYk36-9ylyd_WvIs_cw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLUZkdzdRN0djYzg&resourcekey=0-mUVyYk36-9ylyd_WvIs_cw" width="240" alt="1975 - M457 - 009.png"></a><br><sub>1975|8 · 009</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeEw5cWF0LVVXems/view?resourcekey=0-vi1EhmxJ6zAzDCOMOj7EsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeEw5cWF0LVVXems&resourcekey=0-vi1EhmxJ6zAzDCOMOj7EsQ" width="240" alt="1975 - M457 - 010.png"></a><br><sub>1975|8 · 010</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQU1mQ1Q1OEVVaDg/view?resourcekey=0-oPrycyq9esUD7jUGC7bYsQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQU1mQ1Q1OEVVaDg&resourcekey=0-oPrycyq9esUD7jUGC7bYsQ" width="240" alt="1975 - M457 - 011.png"></a><br><sub>1975|8 · 011</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdjRSVVkzeEwxelU/view?resourcekey=0-Jgd0R-tOS_DLrXiq27wrUQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdjRSVVkzeEwxelU&resourcekey=0-Jgd0R-tOS_DLrXiq27wrUQ" width="240" alt="1975 - M457 - 012.png"></a><br><sub>1975|8 · 012</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1dIeS1sMkhUY2M/view?resourcekey=0-yenZ16WwOXfcXvYvXiL4MQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1dIeS1sMkhUY2M&resourcekey=0-yenZ16WwOXfcXvYvXiL4MQ" width="240" alt="1975 - M457 - 013.png"></a><br><sub>1975|8 · 013</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUk9LR0xNVUZ6N3c/view?resourcekey=0-TR6i1AV3dKLuavgSlVZ-eA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUk9LR0xNVUZ6N3c&resourcekey=0-TR6i1AV3dKLuavgSlVZ-eA" width="240" alt="1975 - M457 - 014.png"></a><br><sub>1975|8 · 014</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaUx5cmRuZW1DVGM/view?resourcekey=0-9Y7dAzHRBCiJLxW6pE1EVQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaUx5cmRuZW1DVGM&resourcekey=0-9Y7dAzHRBCiJLxW6pE1EVQ" width="240" alt="1975 - M457 - 015 (3).jpg"></a><br><sub>1975|8 · 015 (3)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGtjZmxCTGl3ZTg/view?resourcekey=0-eRqdMc18kzANeYrHHiM-PA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGtjZmxCTGl3ZTg&resourcekey=0-eRqdMc18kzANeYrHHiM-PA" width="240" alt="1975 - M457 - 015.jpg"></a><br><sub>1975|8 · 015</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUGUtdENUN2RycUU/view?resourcekey=0-NAj4VQiBa5CW2Xwj6p26Og" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUGUtdENUN2RycUU&resourcekey=0-NAj4VQiBa5CW2Xwj6p26Og" width="240" alt="1975 - M457 - 017.jpg"></a><br><sub>1975|8 · 017</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcXFZdjJtTGd1LW8/view?resourcekey=0-HQAv836ACN71LqfIbEnnIQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcXFZdjJtTGd1LW8&resourcekey=0-HQAv836ACN71LqfIbEnnIQ" width="240" alt="1975 - M457 - 019.jpg"></a><br><sub>1975|8 · 019</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMTVLSjVkWExTY28/view?resourcekey=0--ym6gwQ3Lf8SZmiASwh-Lw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMTVLSjVkWExTY28&resourcekey=0--ym6gwQ3Lf8SZmiASwh-Lw" width="240" alt="1975 - M457 - 020 (2).jpg"></a><br><sub>1975|8 · 020 (2)</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUFV3c3JTN2paXzQ/view?resourcekey=0-LitXlaUCnjVkK501smgZUQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUFV3c3JTN2paXzQ&resourcekey=0-LitXlaUCnjVkK501smgZUQ" width="240" alt="1975 - M457 - 022.jpg"></a><br><sub>1975|8 · 022</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQk1seUtLLWRjclk/view?resourcekey=0-j3KV0XVbstQhwztZUQEXtA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQk1seUtLLWRjclk&resourcekey=0-j3KV0XVbstQhwztZUQEXtA" width="240" alt="1975 - M457 - P10.jpg"></a><br><sub>1975|8 · P10</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDVtME5XSWwyRVU/view?resourcekey=0-iAT8NHud0hkgkbqujdbVTg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDVtME5XSWwyRVU&resourcekey=0-iAT8NHud0hkgkbqujdbVTg" width="240" alt="1975 - M457 - P11.jpg"></a><br><sub>1975|8 · P11</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVBfQzl0UUl3Z0E/view?resourcekey=0-r1H-qtjF7vn1-3e1rddxbA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVBfQzl0UUl3Z0E&resourcekey=0-r1H-qtjF7vn1-3e1rddxbA" width="240" alt="1975 - M457 - P12.jpg"></a><br><sub>1975|8 · P12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNEZ3bWNEQUlkTkE/view?resourcekey=0-gVtPIEluEosBuPDNks7v8g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNEZ3bWNEQUlkTkE&resourcekey=0-gVtPIEluEosBuPDNks7v8g" width="240" alt="1975 - M457 - P13.jpg"></a><br><sub>1975|8 · P13</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXNubVRadU13WW8/view?resourcekey=0-bDHVu2wheL9Q9zU7pnfBqg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXNubVRadU13WW8&resourcekey=0-bDHVu2wheL9Q9zU7pnfBqg" width="240" alt="1975 - M457 - P14.jpg"></a><br><sub>1975|8 · P14</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeUpnTEFTNnB2OWs/view?resourcekey=0-wcaaoMkPz4FhGw20R8QixQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeUpnTEFTNnB2OWs&resourcekey=0-wcaaoMkPz4FhGw20R8QixQ" width="240" alt="1975 - M457 - P15.jpg"></a><br><sub>1975|8 · P15</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaWFYS0Q0V2d4dnc/view?resourcekey=0-TX78q3FTmvb-AaFe9Eefsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaWFYS0Q0V2d4dnc&resourcekey=0-TX78q3FTmvb-AaFe9Eefsg" width="240" alt="1975 - M457 - P16.jpg"></a><br><sub>1975|8 · P16</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUXdCZ0EtczhhaHM/view?resourcekey=0-bVUhbWojIKg-ZCY0gEAs-g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUXdCZ0EtczhhaHM&resourcekey=0-bVUhbWojIKg-ZCY0gEAs-g" width="240" alt="1975 - M457 - P17.jpg"></a><br><sub>1975|8 · P17</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbUtOa1pCT0JDTXM/view?resourcekey=0-BcgfqXCZDVqFjWmeMzeeqA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbUtOa1pCT0JDTXM&resourcekey=0-BcgfqXCZDVqFjWmeMzeeqA" width="240" alt="1975 - M457 - P18.jpg"></a><br><sub>1975|8 · P18</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXMzSFZnMmc0bWs/view?resourcekey=0-EF_Kpdlt6lsKsaLbVz9YhA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXMzSFZnMmc0bWs&resourcekey=0-EF_Kpdlt6lsKsaLbVz9YhA" width="240" alt="1975 - M457 - P19.jpg"></a><br><sub>1975|8 · P19</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWpUN0NKckktLVE/view?resourcekey=0-Q5Q_9IZ2kwbyY0ufkJwkxg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWpUN0NKckktLVE&resourcekey=0-Q5Q_9IZ2kwbyY0ufkJwkxg" width="240" alt="1975 - M457 - P2.jpg"></a><br><sub>1975|8 · P2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTnMwNndGSktLUFk/view?resourcekey=0-MntTpW2-TAo1iMytbtw4tQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTnMwNndGSktLUFk&resourcekey=0-MntTpW2-TAo1iMytbtw4tQ" width="240" alt="1975 - M457 - P3.jpg"></a><br><sub>1975|8 · P3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNkExbmNzbUJkck0/view?resourcekey=0-lLolGMBxhYE_Gr-c7eG6xg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNkExbmNzbUJkck0&resourcekey=0-lLolGMBxhYE_Gr-c7eG6xg" width="240" alt="1975 - M457 - P4.jpg"></a><br><sub>1975|8 · P4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbHo5cUxlTGYyeWM/view?resourcekey=0-I1s6cTiQMvZ2eWcMlXLqSw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbHo5cUxlTGYyeWM&resourcekey=0-I1s6cTiQMvZ2eWcMlXLqSw" width="240" alt="1975 - M457 - P5.jpg"></a><br><sub>1975|8 · P5</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTjh4RGhXaTFMbFE/view?resourcekey=0-eZ_pcG2oxJOIvXe21NWoBw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTjh4RGhXaTFMbFE&resourcekey=0-eZ_pcG2oxJOIvXe21NWoBw" width="240" alt="1975 - M457 - P6.jpg"></a><br><sub>1975|8 · P6</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMFg2M25OMmpCdXc/view?resourcekey=0-vyaasTCEiF4AFJ4bHBVCLQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMFg2M25OMmpCdXc&resourcekey=0-vyaasTCEiF4AFJ4bHBVCLQ" width="240" alt="1975 - M457 - P7.jpg"></a><br><sub>1975|8 · P7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZGstR25qSVB1WGs/view?resourcekey=0-uQK4M0w2VMMpw7_vH4MgHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZGstR25qSVB1WGs&resourcekey=0-uQK4M0w2VMMpw7_vH4MgHg" width="240" alt="1975 - M457 - P8.jpg"></a><br><sub>1975|8 · P8</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVXM3VnJFQ2tCQjQ/view?resourcekey=0-SM0i9HLPh8D-cFR7stGtMQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVXM3VnJFQ2tCQjQ&resourcekey=0-SM0i9HLPh8D-cFR7stGtMQ" width="240" alt="1975 - M457 - P9.jpg"></a><br><sub>1975|8 · P9</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/12EMYApxc_gRwZn8IiiiDGh6GjyqDQ7Tc/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=12EMYApxc_gRwZn8IiiiDGh6GjyqDQ7Tc" width="240" alt="1975 - M457 - Pre-Mixer Module.pdf"></a><br><sub>1975|8 · Pre-Mixer Module</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1jRfiXMp14iqoZPdzQAA5P_IJ-L4WaxU4/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1jRfiXMp14iqoZPdzQAA5P_IJ-L4WaxU4" width="240" alt="1977 - M457 - DOC - MOUNTING BRA CKET.jpg"></a><br><sub>1977|10 · DOC - MOUNTING BRA CKET</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0xTajI1aU1KMDg/view?resourcekey=0--Id7Gzx7wbpgkVtCro8XpA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0xTajI1aU1KMDg&resourcekey=0--Id7Gzx7wbpgkVtCro8XpA" width="240" alt="1977 - M457 - P1.jpg"></a><br><sub>1977|10 · P1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZkNNdlpPcmU0LWM/view?resourcekey=0-E_vjEZWmjI4zXD8QpocRHw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZkNNdlpPcmU0LWM&resourcekey=0-E_vjEZWmjI4zXD8QpocRHw" width="240" alt="19xx - M457 - DOC - L2042 - P05.jpg"></a><br><sub>19xx - M457 - DOC - L2042 - P05</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUh0YVhIN2hjclE/view?resourcekey=0-5BbrKsqSG2dcdybh1CqyLg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUh0YVhIN2hjclE&resourcekey=0-5BbrKsqSG2dcdybh1CqyLg" width="240" alt="19xx - M457 - DOC - L3242 - P05.jpg"></a><br><sub>19xx - M457 - DOC - L3242 - P05</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M457 - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M457 - DOC - R1400-R2400 - 007</sub></td></tr>
</table>

Not on Google Drive yet: `19xx - M457 - Application Examples M457 Pre-Mixer.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1975 - 457-02-001 - 4X2 PRE-MIXER SCHEMATIC - DRN DM - ISS 5.kicad_sch](KICAD/1975%20-%20457-02-001%20-%204X2%20PRE-MIXER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%205.kicad_sch)
- [1975 - 457-02-002 - PRE-MIXER MASTER MODULE SCHEMATIC - DRN DM - ISS 3.kicad_sch](KICAD/1975%20-%20457-02-002%20-%20PRE-MIXER%20MASTER%20MODULE%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%203.kicad_sch)
- [1975 - 457-02-003 - M457A SCHEMATIC MODIFIED FOR I C INPUT (FOR PROJ. No 74030 - STUDIO 4 - DRN DM.kicad_sch](KICAD/1975%20-%20457-02-003%20-%20M457A%20SCHEMATIC%20MODIFIED%20FOR%20I%20C%20INPUT%20(FOR%20PROJ.%20No%2074030%20-%20STUDIO%204%20-%20DRN%20DM.kicad_sch)
- [1975 - M457 - 457-01-001 - PRE SUMMING OUTPUT LINE INPUT.kicad_sch](KICAD/1975%20-%20M457%20-%20457-01-001%20-%20PRE%20SUMMING%20OUTPUT%20LINE%20INPUT.kicad_sch)
- [1975 - M457 - 457-01-001 - PRE-MIXER MODULE FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1975%20-%20M457%20-%20457-01-001%20-%20PRE-MIXER%20MODULE%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1975 - M457 - 457-01-001 - PRE-MIXER MODULE.kicad_sch](KICAD/1975%20-%20M457%20-%20457-01-001%20-%20PRE-MIXER%20MODULE.kicad_sch)
- [1975 - M457 - 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS (2).kicad_sch](KICAD/1975%20-%20M457%20-%20457-02-001%20-%20JIO%20EXTERNAL%20SUMMNG%20INOU%20RIS%20(2).kicad_sch)
- [1975 - M457 - 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS (3).kicad_sch](KICAD/1975%20-%20M457%20-%20457-02-001%20-%20JIO%20EXTERNAL%20SUMMNG%20INOU%20RIS%20(3).kicad_sch)
- [1975 - M457 - 457-02-001 - JIO EXTERNAL SUMMNG INOU RIS.kicad_sch](KICAD/1975%20-%20M457%20-%20457-02-001%20-%20JIO%20EXTERNAL%20SUMMNG%20INOU%20RIS.kicad_sch)
- [1975 - M457 - 457-02-001 - MOD ICKD USED (2).kicad_sch](KICAD/1975%20-%20M457%20-%20457-02-001%20-%20MOD%20ICKD%20USED%20(2).kicad_sch)
- [1975 - M457 - 457-02-001 - MOD ICKD USED.kicad_sch](KICAD/1975%20-%20M457%20-%20457-02-001%20-%20MOD%20ICKD%20USED.kicad_sch)
- [1975 - M457 - 5-101-02-002 - ERWISE SPECIFIED LAST COMPONENT DLSIGNATIONS CIO CRA ELL.kicad_sch](KICAD/1975%20-%20M457%20-%205-101-02-002%20-%20ERWISE%20SPECIFIED%20LAST%20COMPONENT%20DLSIGNATIONS%20CIO%20CRA%20ELL.kicad_sch)
- [1975 - M457 - 5-101-02-002 - MOD ICKD USED.kicad_sch](KICAD/1975%20-%20M457%20-%205-101-02-002%20-%20MOD%20ICKD%20USED.kicad_sch)
- [1975 - M457 - 5-101-02-002 - SPECIFIED LAST COMPONENT DESICNATIONS.kicad_sch](KICAD/1975%20-%20M457%20-%205-101-02-002%20-%20SPECIFIED%20LAST%20COMPONENT%20DESICNATIONS.kicad_sch)
- [1975 - M457 - 5-101-02-002 - SPECIFISD LAST COMPONENT DESICNATIONS.kicad_sch](KICAD/1975%20-%20M457%20-%205-101-02-002%20-%20SPECIFISD%20LAST%20COMPONENT%20DESICNATIONS.kicad_sch)
- [1975 - M457 - Pre-Mixer Module p23.kicad_sch](KICAD/1975%20-%20M457%20-%20Pre-Mixer%20Module%20p23.kicad_sch)
- [1975 - M457 - Pre-Mixer Module p28.kicad_sch](KICAD/1975%20-%20M457%20-%20Pre-Mixer%20Module%20p28.kicad_sch)
- [1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2 (2).kicad_sch](KICAD/1977%20-%20457-01-001%20-%204x2%20PRE-MIXER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20DB%20-%20ENG%20RKB%20-%20ISS%202%20(2).kicad_sch)
- [1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2 (3).kicad_sch](KICAD/1977%20-%20457-01-001%20-%204x2%20PRE-MIXER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20DB%20-%20ENG%20RKB%20-%20ISS%202%20(3).kicad_sch)
- [1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2 (4).kicad_sch](KICAD/1977%20-%20457-01-001%20-%204x2%20PRE-MIXER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20DB%20-%20ENG%20RKB%20-%20ISS%202%20(4).kicad_sch)
- [1977 - 457-01-001 - 4x2 PRE-MIXER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2.kicad_sch](KICAD/1977%20-%20457-01-001%20-%204x2%20PRE-MIXER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20DB%20-%20ENG%20RKB%20-%20ISS%202.kicad_sch)
- [1977 - 457-01-002 - PRE-MIXER MASTER MODULE FUNCTIONAL DIAGRAM - DRN DB - ENG RKB - ISS 2.kicad_sch](KICAD/1977%20-%20457-01-002%20-%20PRE-MIXER%20MASTER%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20DB%20-%20ENG%20RKB%20-%20ISS%202.kicad_sch)
- [M457.kicad_sym](KICAD/M457.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
