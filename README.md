An Open Source PCB Business/Portfolio Card with NFC and Design Inspired by Bleach


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Unlicense License][license-shield]][license-url]

<br />
<div align="center">
  <a><img src="assets/Fullbringer.png" alt="logo" width="100" height="100">
  </a>
  <h3 align="center">Vashtastic</h3>

  <p align="center">
    A Cooler Meshtastic Node
    <br />
    <br />
    <a href="https://github.com/TrulyVagabond/Vashtastic/blob/main/JOURNAL.md">Journal</a>
    &middot;
    <a href="https://github.com/TrulyVagabond/Vashtastic/issues">Report Bug</a>
    &middot;
    <a href="https://github.com/TrulyVagabond/Vashtastic/issues">Request Feature</a>
  </p>
</div>

## What is Vashtastic?

<p align="center"><img src="assets/Vashtastic.png" /></p>

<p align="center"><img src="assets/Vashtastic-pcb1.png" /></p>

<p align="center"><img src="assets/Vashtastic-pcb-front.png" /></p>

<p align="center"><img src="assets/Vashtastic-Case.png" /></p>

Vashtastic is an off-grid communication terminal. This Project integrates a Custom Printed Circuit Board (PCB) with a Heavily Customized 3D-printable enclosure. Designed to Operate Completely Independent of cellular networks and Wi-Fi, Vashtastic Leverages Long Range (LoRa) Radio Frequencies to send and receive data across Vast distances. It is basically a way of communication without internet.

### Built With

* [![EasyEDA][EasyEDA]][EasyEDA-url]
* [![FreeCAD][FreeCAD]][FreeCAD-url]
* [![Inkscape][Inkscape]][Inkscape-url]

## Getting Started

To get Your own Vashtastic, you need three things.

- PCB
- 3d-Printed Enclosure
- Money

### Ordering the PCB

1. Navigate to the Gerber Files in the **"Gerber"** Folder. 

2. Download the ".zip" File

3. Upload this '.zip' file to a custom PCB manufacturer (Like PCBWay, OSH Park or JLCPCB)

4. Standard Manufacturing Settings (1.6mm thickness, HASL finish) work Perfectly for this Board.


### 3D Printing the Enclosure

1. Navigate to the **"CAD"** folder.

2. Download any of the File Formats and Upload it into your Desired 3D slicing Software.

3. Use a durable, temperature-resistant filament like **PETG or ABS**. Set your wall thickness to at least 4 perimeters for high structural strength.

4. **Important**: Print the D-pad and Zoom buttons with the flat "cap" face pointing UP, and enable supports for the internal flanges.

## Bills Of Materials (BOM)



## Assembling Vashtastic

- **PCB Assembly:**

   1. You can Either Order the PCB pre-soldered from Manufacturers. or you can Solder on your own. See the PCB layout for Soldering. 

  2. After Soldering and getting the PCB ready, you just have to attach the U.FL to SMA Cable to the PCB and the Antenna and Screw in the E-ink Display.

  3. After Doing all that, Your PCB would finally be ready.

- **Case Assembly:**

  1. 3D Print the Enclosure with the Specified Settings Above.

  2. You Must 3D print the Front and Back Shell Separately. The Front Shell Contains the Holes for the Buttons and E-ink Display. The Back Shell Contains a Space for the Battery Sled to go in and a Hole For Smooth Connection between the Battery and the Connector on the PCB (JST connector)

  3. Put the Antenna Through the Hole in the Enclosure.

  4. Add the buttons in the Desired hole Created in the Enclosure Before Closing it shut.

  5. After Adding the battery in the Back Shell and Covering it with the Battery Cover. Use **M3 Screws** to Screw in everything, The Front Shell and Back Shell, and the Battery Cover. 

  6. Your **Vashtastic** is Ready to Use.


#### <p align="center">Note: This Repo Does Not Contain the Firmware. Add the Firmware On Your Own.</p>

## Using Vashtastic

Vashtastic Comes in 2 types of Usage. You can flash the Required Firmware and then you can use the:

  1. Maps Layout
  2. Normal Meshtastic Layout

### Maps Layout:

The Maps Layout is the Intended way to use Vashtastic. You can Add Your Friends Device in the **"Normal Meshtastic Layout"** and then when you switch to the Maps Layout You can see the Exact Coordinates of Your Friend's Device. and Communicate with him From Vast distances
(20+ Km)

Use the Buttons to Navigate the E-Ink Display. 

- **D-Pad**:
Use the D-Pad to navigate the display by pressing the Buttons for the Intended Direction. Cmon bruh You've a use a D-pad before.

- **Zoom-Button**:
Use the Circular Button above the D-Pad to Zoom into the Map.

### Normal Meshtastic Layout: 

Use this to add Your Friends and Setting up the Device. Check **Meshtastic Repo** for More Information.

## Contributing:

You can Contribute by Writing the Firmware for me HAHA. or Making Awesome Changes to the Case.

## Special Thanks:

- **FreeCAD** for the Amazing 3D Modeling Free Software.

- **EasyEDA** for the Amazing PCB Designing Free Software.

- **Hack Club** for making me Motivated enough to make this haha.

## License

This Project is Distributed Under MIT License. Check License.txt for More Information.

<br>

###### Note: A.I was only used for Research Purposes. 


  
