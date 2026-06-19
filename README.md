# RF2Digital-internship-2025

> Weekly reports and progress documents from an 8-week embedded graphics internship.

---

### Overview

|                      |                                    |
|:---------------------|:-----------------------------------|
| Role                 | Embedded Graphics Developer Intern |
| Employment type      | Internship                         |
| Organisation         | RF2Digital                         |
| Duration             | 8 weeks (2025 Oct - 2025 Dec)      |
| Participants         | 2 interns                          |
| Provided environment | Raspberry Pi Pico (RP2040)         |
| Location             | Seongnam, Gyeonggi, South Korea    |
| Location type        | Hybrid                             |

---

### Projects

1. Graphical Engine for Dot Matrix LCD - Core rendering engine for driving dot-matrix displays on the RP2040
2. Bitmap to Binary Dot Matrix Converter - Pipeline for converting bitmap images into HEX arrays ready for LCD firmware
3. Dot Matrix Painter - Windows GUI tool (Win32 / C++) for drawing, transforming, and exporting dot-matrix patterns

---

### Tools & Languages

Embedded C  |  Embedded C++  |  Github  |  VS Code  |  Visual Studio

---

### Repository Contents

| File                                       | Description                                                                                                         |
|:-------------------------------------------|:--------------------------------------------------------------------------------------------------------------------|
| [Week 1 report](week_1_report.pdf)         | Development kit received, environment setup (VS Code, Pico SDK), initial build issues                               |
| Week 2 report                              | (missing) - covered in final report: LCD example reviewed, comments added to lcd.c & lcd.h, CMakeLists.txt adjusted |
| [Week 3 report](week_3_report.pdf)         | Bitmap converter pipeline — grayscale conversion implemented; binarisation and dot-matrix export in progress        |
| [Week 4 report](week_4_report.pdf)         | BMP-to-HEX converter implemented as module; LCD output orientation and inversion fixed; integration pending         |
| [Week 5 report](week_5_report.pdf)         | LCD output fixed (rotation/transpose); Win32 GUI grid and mouse interface scaffolded                                |
| [Week 6 report](week_6_report.pdf)         | Win32 GUI painter scaffolded — 8×8 grid, buttons, integer input boxes, and HEX output area                          |
| [Week 7 report](week_7_report.pdf)         | Painter tool completed — black/white toggle brush, editable grid size, BMP export, HEX-to-text output in progress   |
| [Final report](final_report.pdf)           | Full summary of 8 weeks of work                                                                                     |
| [Prototype drawing](prototype_drawing.png) | Win32 GUI layout diagram — mouse event flow, screen sections, button mapping, and HEX output spec                   |

---

### Summary

Developed dot-matrix graphics tools and workflows for embedded LCD systems using Raspberry Pi Pico, C/C++, and Windows utilities.  
- Designed a bitmap-to-binary converter with grayscale processing, binarisation, and HEX array generation for LCD rendering.  
- Built a Windows GUI painter in C++/Win32 API, supporting N×M dot-matrix drawing, rotation, BMP import, and mapped-array output.  
- Implemented a pixel-precise workflow for previewing and testing GUI-generated patterns and converted bitmap images on LCDs.