# 4-Input XOR Logic Circuit PCB Project

Digital logic design project completed at Seneca Polytechnic.  
This project implements a **4-input XOR circuit** using push-button inputs and an LED output, with verification on both **breadboard** and **PCB**.

## Highlights
- Designed, breadboard-tested, and soldered a **4-input XOR logic circuit**
- Created **schematic** and **PCB layout** in **Fusion 360 Electronics**
- Verified circuit behavior against the **truth table**
- Improved assembly reliability by addressing **solder bridging**, **polygon short risks**, and **routing / clearance tradeoffs**

## Project Overview
The circuit takes 4 digital inputs: **A, B, C, and D**.  
The LED output turns **ON** when there is an **odd number of HIGH inputs**, and **OFF** when there is an **even number of HIGH inputs**.

The project followed a typical hardware workflow:
1. logic design
2. breadboard validation
3. schematic capture
4. PCB layout
5. soldering and final testing

## Tools and Skills
- **Fusion 360 Electronics**
- **Breadboard prototyping**
- **Digital logic design**
- **Truth table verification**
- **PCB layout**
- **Through-hole soldering**
- **Hardware testing**
- **Assembly troubleshooting**

## Key Engineering Lessons
1. **Breadboard testing reduces PCB risk**  
   Verifying the truth table on a breadboard helped confirm circuit logic before soldering.

2. **Layout choices affect manufacturability**  
   Trace width, clearance, and compact placement all influence how easy the board is to solder and debug.

3. **Ground fill can create hidden risks**  
   Excess solder and nearby copper areas can create unintended shorts if layout spacing is not carefully managed.

## Repository Structure
```text
4-Input-XOR-Logic-Circuit-PCB-Project/
├── README.md
├── docs/
│   ├── breadboard-condition-1.jpg
│   ├── breadboard-condition-2.jpg
│   ├── schematic.png
│   ├── pcb-layout.png
│   ├── pcb-3d-view.png
│   └── final-board.jpg
└── report/
    └── 4-Input-XOR-Logic-Circuit-PCB-Project-Report.docx
```

## Suggested Images to Add
Place these inside the `docs/` folder and then update the image links below:
- breadboard test photos
- schematic screenshot
- PCB layout screenshot
- 3D board view
- final soldered PCB photo

## Example Image Section
<!--
## Breadboard Test
![Breadboard test](docs/breadboard-condition-1.jpg)

## Schematic
![Schematic](docs/schematic.png)

## PCB Layout
![PCB layout](docs/pcb-layout.png)

## Final PCB
![Final board](docs/final-board.jpg)
-->

## Report
Full project report: [`report/4-Input-XOR-Logic-Circuit-PCB-Project-Report.docx`](report/4-Input-XOR-Logic-Circuit-PCB-Project-Report.docx)

## Resume Version
For resume use, this project can be summarized as:

> Designed, breadboard-tested, and soldered a 4-input XOR logic circuit using push-button inputs and LED output indication. Created the schematic and PCB layout in Fusion 360 and verified digital circuit behavior against the truth table during testing. Improved assembly reliability by addressing solder bridging, polygon short risks, and routing/clearance tradeoffs during PCB fabrication and debugging.
