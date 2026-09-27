<div align="center">

<img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad20/MonkiiPad20_PCB/MonkiiPad20_PCB.jpg" width="520"/>

# Hoang

### Hardware · Embedded Systems · PCB Design · Keyboards · FPGA

**Prospective Electrical Engineering Major** · The Dewey School, Class of 2027

<a href="https://drive.google.com/drive/folders/1BFVVmQ3QBUyOTTLp1HZsr7EzWfzYBr1I?usp=sharing">Portfolio & CV</a> · <a href="https://monkiiboard.com">Website</a> · <a href="https://www.youtube.com/@gomonkiiboard">YouTube</a> · <a href="https://www.instagram.com/go_monkiiboard/">Instagram</a> · <a href="https://github.com/Simbashrek276?tab=repositories">Projects</a>

<a href="https://drive.google.com/drive/folders/1BFVVmQ3QBUyOTTLp1HZsr7EzWfzYBr1I?usp=sharing"><img src="https://img.shields.io/badge/Portfolio%20%26%20CV-8ECAE6?style=for-the-badge&logo=googledrive&logoColor=111111"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=8ECAE6&height=3" width="100%"/>

## About

Hi! I'm Huy Hoang Le, currently a senior who likes to disassemble and then reassemble things. This habit has refined me more and more into a builder. 
Right now, aside from other past projects, I'm currently building **MonkiiBoard** and working across hardware, embedded systems, custom keyboards, PCB design, and FPGA development.

**Languages**

![Languages](https://skillicons.dev/icons?i=c,py,java,js,html,css,arduino,raspberrypi)

![Verilog](https://img.shields.io/badge/Verilog-8ECAE6?style=for-the-badge&logoColor=111111)

**Hardware & Tools**

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![PCB Design](https://img.shields.io/badge/PCB%20Design-8ECAE6?style=for-the-badge&logoColor=111111)

![ATmega32U4](https://img.shields.io/badge/ATmega32U4-111111?style=for-the-badge)
![Tang Nano 4K](https://img.shields.io/badge/Tang%20Nano%204K-111111?style=for-the-badge)
![Pro Micro](https://img.shields.io/badge/Pro%20Micro-111111?style=for-the-badge)
![RP2040-Zero](https://img.shields.io/badge/RP2040--Zero-111111?style=for-the-badge)
![ESP32-S3](https://img.shields.io/badge/ESP32--S3-111111?style=for-the-badge)

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=8ECAE6&height=3" width="100%"/>

## MonkiiBoard

**Custom hardware · Embedded systems · Open source builds**

An open little family of keyboards you can build, flash and print yourself. Every board comes with its own firmware, a 3D printable case and a readme that walks you through the build.

`5 keyboards` · `4 PCBs` · `Firmware generator website` · `10+ build guides` · `1,700+ followers` · `2.4M+ views`

<a href="https://github.com/Simbashrek276/MonkiiBoard_Keyboards"><img src="https://img.shields.io/badge/Hardware%20Projects-8ECAE6?style=for-the-badge&logo=github&logoColor=111111"/></a>
<a href="https://monkiiboard.com"><img src="https://img.shields.io/badge/Website-8ECAE6?style=for-the-badge&logo=googlechrome&logoColor=111111"/></a>
<a href="https://www.youtube.com/@gomonkiiboard"><img src="https://img.shields.io/badge/YouTube-8ECAE6?style=for-the-badge&logo=youtube&logoColor=111111"/></a>
<a href="https://www.instagram.com/go_monkiiboard/"><img src="https://img.shields.io/badge/Instagram-8ECAE6?style=for-the-badge&logo=instagram&logoColor=111111"/></a>

<div align="center">

| **Board**         | **Keys** | **Controller**         | **What it does**                                            |
| :---------------- | :------: | :--------------------- | :---------------------------------------------------------- |
| **MonkiiBoard58** |    58    | ESP32-S3-WROOM-1       | Wireless over Bluetooth · LiPo battery · Rotary encoder · OLED |
| **MonkiiBoard39** |    39    | Pro Micro / ATmega32U4 | Sticky modifiers · Double tap Windows key                   |
| **MonkiiPad20**   |    20    | RP2040-Zero            | OLED · Robot eye screensaver · Diode matrix                 |
| **MonkiiPad16**   |    16    | RP2040-Zero            | OLED · Spin the knob to switch layers                       |
| **MonkiiPad3x3**  |     9    | Pro Micro / ATmega32U4 | Numpad · Macro layer · Our very first board                 |

</div>

### MonkiiBoard58

58 key wireless keyboard built around an **ESP32-S3-WROOM-1**. The most ambitious board so far.

`5 × 12 matrix` · `Bluetooth` · `LiPo charger` · `Voltage regulator` · `MOSFET power gate` · `Rotary encoder` · `OLED`

The schematic and layout are finished and the gerbers are ready.

<div align="center">

|                                                                                           **PCB Top**                                                                                          |                                                                    **PCB Bottom**                                                                    |                                                                        **Schematic**                                                                        |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiBoard58/MonkiiBoard58_PCB/MonkiiBoard58_PCB_render_top_full_view_v2_mounting_holes.png" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiBoard58/MonkiiBoard58_PCB/MonkiiBoard58_PCB_render_bottom.png" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiBoard58/MonkiiBoard58_PCB/MonkiiBoard58_schematics_full_view.png" width="230"/> |
|                                                                                       KiCad · 235 × 123 mm                                                                                     |                                                                 ESP32-S3 · Diodes · Charger                                                                 |                                                                 Matrix · MCU · Power                                                                 |

</div>

### MonkiiBoard39

39 key custom keyboard built around a **Pro Micro / ATmega32U4**.

`4 × 10 matrix` · `Sticky modifiers` · `Double tap Windows key` · `C`

<div align="center">

|                                                                   **Angled**                                                                  |                                                                  **Top**                                                                 |                                                                           **PCB**                                                                           |
| :-------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiBoard39/MonkiiBoard39_angledview.jpg" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiBoard39/MonkiiBoard39_topview.jpg" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiBoard39/MonkiiBoard39_PCB/MonkiiBoard39_PCB_CAD_front.png" width="230"/> |

</div>

### MonkiiPad20

20 key macropad built around an **RP2040 Zero**.

`4 × 6 diode matrix` · `SSD1306 OLED` · `I²C` · `2 layers` · `C`

Shortcuter and Typist layers with a robot eye screensaver. This is also my first proper custom PCB designed in **KiCad**.

`2 layer` · `120 × 86 mm` · `Switch diodes` · `RP2040 Zero`

<div align="center">

|                                                                          **KiCad Layout**                                                                         |                                                                     **Fabricated PCB**                                                                     |                                                                             **Assembled**                                                                             |                                                              **Robot Eyes**                                                              |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad20/MonkiiPad20_PCB/MonkiiPad20_PCB_design1.png" width="170"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad20/MonkiiPad20_PCB/MonkiiPad20_PCB.jpg" width="170"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad20/MonkiiPad20_PCB/MonkiiPad20_PCB_assembled_bottom_view.jpg" width="170"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad20/MonkiiPad20_diagonal_view.jpg" width="170"/> |

</div>

### MonkiiPad16

16 key macropad with a rotary encoder, built around an **RP2040 Zero**.

`4 × 4 matrix` · `Rotary encoder` · `SSD1306 OLED` · `Layer menu` · `C`

Spin the knob to pick a layer, a numpad by default and a page of editing shortcuts one turn away. The OLED shows the current layer and the last key pressed.

<div align="center">

|                                                                   **Angled**                                                                  |                                                                **Knob**                                                               |                                                                  **Top**                                                                 |
| :-------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad16/MonkiiPad16_angled_view.jpg" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad16/MonkiiPad16_knob.jpg" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad16/MonkiiPad16_top_view.jpg" width="230"/> |

</div>

### MonkiiPad3x3

Compact 3 × 3 macropad with a switchable input layer. The first keyboard I ever made.

`3 × 3 matrix` · `Numpad` · `Macro layer` · `C`

<div align="center">

|                                                                  **Top**                                                                  |                                                                  **Inside**                                                                 |                                                                           **PCB**                                                                           |
| :---------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad3x3/MonkiiPad3x3_top_view.jpg" height="172"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad3x3/MonkiiPad3x3_inside.jpg" height="172"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/MonkiiBoard_Keyboards/main/Medias/MonkiiPad3x3/MonkiiPad3x3_PCB/MonkiiPad3x3_PCB_CAD_front.png" height="172"/> |

</div>

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=8ECAE6&height=3" width="100%"/>

## Hackathon Projects

### Heritage Guessr · 1st Prize

AI web game where you identify Vietnamese cultural heritage sites through 3D virtual environments.

`AI` · `Web` · `3D` · `EdTech`

Presented as Team Neural Ninjas at the **Vietnam National Youth AI Hackathon**, organized by STEAM for Vietnam, HUST, UNICEF and the US Embassy. We took **1st Prize out of 50+ teams**. The game now documents 124+ heritage sites and has reached 390+ students across 2 partner schools.

<a href="https://heritageguessr.com/">Play Heritage Guessr →</a>

### Receptra · Top 7

AI chatbot for patient pre-screening and inquiries, built with **Python** and **Llama 3**.

`Python` · `Llama 3` · `LLM` · `Healthcare`

Led a team of 3 at the **FCT AI Hackathon** by FPT Software Computer Talents Club.

<a herf="https://github.com/PhucPhamHong-dev/Receptra"> Repository →</a>

### Zombie Survival · 3rd Prize

Hardware survival game running directly on a **Tang Nano 4K FPGA**, drawn straight out to HDMI at 640 × 480.

`Verilog` · `FPGA` · `HDMI` · `Physical input`

Built in 4 days at the **TSIC × Synopsys Summer Camp** hackathon in Taiwan, where I led our 5 member Team 7A from never writing a line of Verilog to a live demo in front of the judges. We won **3rd Prize in the Creative Ideation Award** out of 14 teams.

<div align="center">

|                                                           **Live Demo**                                                           |                                                            **Presenting**                                                            |                                                            **3rd Prize**                                                           |
| :-------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/Zombie-survival-game-fpga/main/images/gamedemo.jpg" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/Zombie-survival-game-fpga/main/images/presenting1.jpg" width="230"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/Zombie-survival-game-fpga/main/images/3rd-prize.jpg" width="230"/> |

</div>

<a href="https://github.com/Simbashrek276/Zombie-survival-game-fpga">Repository →</a>

---

<img src="https://capsule-render.vercel.app/api?type=rect&color=8ECAE6&height=3" width="100%"/>

## Research & Lab Work

### NMEA Smartwatch

NMEA parser developed at **EDABK Lab, Hanoi University of Science and Technology**.

`C` · `Embedded Systems` · `GPS` · `GNSS` · `NMEA`

Parses GPS and GNSS coordinate data for a **screenless smartwatch**. Decodes 6 NMEA data types across all four satellite networks, GPS, GLONASS, Galileo and BeiDou, and was tested on 1,300 sentences from a field log of the wristband's **Quectel LC76G** module.

Also studied PCB design and circuit fundamentals at the lab under **Prof. Duc Minh Nguyen**.

<div align="center">

|                                                                                  **Wristband PCB**                                                                                 |                                                                                         **System Schematic**                                                                                        |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/NMEA-Data-Parsing-for-Screenless-Smart-Wristband-EDABK-Lab/main/media/EDABK%20wristband%20PCB.jpg" height="200"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/NMEA-Data-Parsing-for-Screenless-Smart-Wristband-EDABK-Lab/main/media/A%20section%20of%20the%20whole%20wristband%20schematics.png" height="200"/> |

</div>

<a href="https://github.com/Simbashrek276/NMEA-Data-Parsing-for-Screenless-Smart-Wristband-EDABK-Lab">Repository →</a>

### LHC Particle Collision Simulator

Monte Carlo simulation of proton–proton collisions at the **Large Hadron Collider**, built at **Phenikaa University Research Lab**.

`Python` · `Monte Carlo` · `Computational Physics` · `3D Kinematics`

Collides two protons at 13.6 TeV, the LHC's current operating energy, over and over. Models 2 to 2, 3 and 4 relativistic decays using sequential two body decays and Lorentz boosts, checks that energy and momentum are conserved on every single event, then filters the results through a simplified detector and plots them.

Built in a team of 3 as lead developer, advised by **Prof. Duc Ninh Le**.

<div align="center">

|                                                                          **Particle Energies**                                                                          |                                                                        **Diphoton Mass**                                                                        |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/LHC-Simplified-Particle-Collision-Simulator/main/plots/energy_steps_4particles.png" width="340"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/LHC-Simplified-Particle-Collision-Simulator/main/plots/mass_diphoton_steps.png" width="340"/> |

</div>

<a href="https://github.com/Simbashrek276/LHC-Simplified-Particle-Collision-Simulator">Repository →</a>

### Context Grounded AI Chatbot

Question answering chatbot that only answers from the notes it is given, and refuses when it isn't sure.

`Python` · `DistilBERT` · `Hugging Face` · `NLP`

Started as a self directed project in 9th grade, then written up as a research report with feedback from **Dr. Duc Tri Phan, Nanyang Technological University**. Gets **18 / 20** on its test set and refuses every out of scope question.

<div align="center">

|                                                                 **Confidence per Question**                                                                 |                                                                    **Evaluation**                                                                    |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://raw.githubusercontent.com/Simbashrek276/Context-Grounded-AI-Chatbot/main/confidence_chart.png" height="200"/> | <img src="https://raw.githubusercontent.com/Simbashrek276/Context-Grounded-AI-Chatbot/main/images/evaluation_output.png" height="200"/> |

</div>

<a href="https://github.com/Simbashrek276/Context-Grounded-AI-Chatbot">Repository →</a>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=8ECAE6&height=3" width="100%"/>

### Hardware · Embedded · Open Source

</div>
