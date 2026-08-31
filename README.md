[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Unlicense License][license-shield]][license-url]

<br />
<div align="center">
  <a><img src="assets/Fullbringer.png" alt="logo" width="120" height="100">
  </a>
  <h3 align="center">FullBringer</h3>

  <p align="center">
    A Cooler PCB Card
    <br />
    <br />
    <a href="https://github.com/TrulyVagabond/FullBringer/blob/main/JOURNAL.md">Journal</a>
    &middot;
    <a href="https://github.com/TrulyVagabond/FullBringer/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/TrulyVagabond/FullBringer/issues">Request Feature</a>
  </p>
</div>

## What is FullBringer?

<p align="center"><img src="PCB/FullBringer-Front.png" /></p>

<p align="center"><img src="PCB/FullBringer-Back.png" /></p>

FullBringer is A PCB Business/Portfolio/ID Card with NFC and Design Inspired by Bleach. There are 2 LED's on the Front and the Entire Circuit on the Bottom Layer. This is Purely Designed to Look Cooler and Impress Recruiters or Friends. The integrated planar antenna harvests power from the phone's magnetic field to illuminate two red LEDs embedded in the skull's eye sockets, while simultaneously broadcasting an NDEF payload (custom URL, or GitHub portfolio) directly to the device.

### Built With

* [![EasyEDA][EasyEDA]][EasyEDA-url]
* [![Inkscape][Inkscape]][Inkscape-url]

## Getting Started

To get Your own FullBringer, you need two things.

- PCB
- Money

### Ordering the PCB

1. Navigate to the Gerber Files in the **"Gerber"** Folder. 

2. Download the ".zip" File

3. Upload this '.zip' file to a custom PCB manufacturer (Like PCBWay, OSH Park or JLCPCB)

4. Standard Manufacturing Settings (1.6mm thickness, HASL finish) work Perfectly for this Board.

## Bills Of Materials (BOM)

| Item | Designator | Qty | Value / Param | Package | Description | Manufacturer | MPN | JLCPCB / LCSC Part # |
| :---: | :--- | :---: | :--- | :--- | :--- | :--- | :--- | :---: |
| 1 | **U1** | 1 | 13.56 MHz | XQFN-8 (1.6×1.6mm) | NTAG I²C Plus NFC Transponder IC with Energy Harvesting Rail (`VOUT`) | NXP Semiconductors | `NT3H1101W0FHKH` | [C73156](https://www.lcsc.com/product-detail/C73156.html) |
| 2 | **C1** | 1 | 1 µF, 50V, X5R | 0603 | Energy Harvesting Buffer & Decoupling Capacitor (VOUT to GND) | Samsung Electro-Mechanics | `CL10A105KB8NNNC` | [C15849](https://www.lcsc.com/product-detail/C15849.html) |
| 3 | **C2** | 1 | 33 pF, 50V, C0G/NP0 | 0603 | RF Tank Tuning Capacitor (Parallel across LA/LB terminals) | Samsung Electro-Mechanics | `CL10C330JB8NNNC` | [C1663](https://www.lcsc.com/product-detail/C1663.html) |
| 4 | **R1, R2** | 2 | 470 Ω, 1% | 0603 | Current-Limiting Resistors for Eye LEDs (~1.2 mA per branch) | UNI-ROYAL (厚声) | `0603WAF4700T5E` | [C23179](https://www.lcsc.com/product-detail/C23179.html) |
| 5 | **LED1, LED2** | 2 | 620–625 nm (Red) | 0603 (1608 Metric) | High-Efficiency Red SMD Diffused LEDs (Skull Eye Sockets) | KENTO (广东风华) | `KT-0603R` | [C2286](https://www.lcsc.com/product-detail/C2286.html) |
| 6 | **ANT** | 1 | ~1.65 µH | PCB Trace | 5-Turn Hexagonal Planar Spiral Inductor (0.4 mm width / 0.4 mm spacing) | Custom Embedded | Embedded Copper | *Integrated* | 

### **Total: $6-7** (DON'T SAY IT)

## Using FullBringer

You Just need to Solder the Chip/Capacitors etc (unless you bought from PCBWay). Then Just use the Free NFC tools App for Android/IOS to Setup the NFC. Thats it, your Fullbringer is Ready!

## Special Thanks:

- **EasyEDA** for the Amazing PCB Designing Free Software.

- **Hack Club** for making me Motivated enough to make this.

## License

This Project is Distributed Under MIT License. Check License.txt for More Information.

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/TrulyVagabond/FullBringer.svg?style=for-the-badge
[contributors-url]: https://github.com/TrulyVagabond/FullBringer/graphs/contributors

[forks-shield]: https://img.shields.io/github/forks/TrulyVagabond/FullBringer.svg?style=for-the-badge
[forks-url]: https://github.com/TrulyVagabond/FullBringer/network/members

[stars-shield]: https://img.shields.io/github/stars/TrulyVagabond/FullBringer.svg?style=for-the-badge
[stars-url]: https://github.com/TrulyVagabond/FullBringer/stargazers

[issues-shield]: https://img.shields.io/github/issues/TrulyVagabond/FullBringer.svg?style=for-the-badge
[issues-url]: https://github.com/TrulyVagabond/FullBringer/issues

[license-shield]: https://img.shields.io/github/license/TrulyVagabond/FullBringer.svg?style=for-the-badge
[license-url]: https://github.com/TrulyVagabond/FullBringer/blob/main/LICENSE

[EasyEDA]: https://img.shields.io/badge/EasyEDA-0177D7?style=for-the-badge
[EasyEDA-url]: https://easyeda.com/

[FreeCAD]: https://img.shields.io/badge/FreeCAD-2D9CDB?style=for-the-badge&logo=freecad&logoColor=white
[FreeCAD-url]: https://www.freecad.org/

[Inkscape]: https://img.shields.io/badge/Inkscape-000000?style=for-the-badge&logo=inkscape&logoColor=white
[Inkscape-url]: https://inkscape.org/

<br>

###### Note: A.I was only used for Research Purposes.


  
