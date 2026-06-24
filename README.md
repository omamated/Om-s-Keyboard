# Om's Keyboard

- A custom low-profile wireless mechanical keyboard designed from scratch to match the aesthetic of the Apple Magic Keyboard while teaching me PCB design, firmware development, and CAD. I know it looks pretty simple, but it took me a long time to make it.

<img width="1410" height="1013" alt="image" src="https://github.com/user-attachments/assets/1a772c35-aa3a-4c91-83cf-5fce31a8f941" />



## Overview

This project is a fully custom wireless keyboard built around the Nice!Nano V2 microcontroller and ZMK firmware. My goal was to create a sleek, minimal keyboard that matches my dad's MacBook Pro which I occasionally use.

Instead of buying an existing keyboard, I decided to design every major component myself, including the PCB and enclosure. This project gave me the opportunity to learn KiCad, improve my Fusion 360, and learn ZMK firmware.

The keyboard features:

* Bluetooth connectivity using ZMK firmware
* Nice!Nano V2 controller
* Hot-swappable switches
* Custom-designed PCB
* Custom 3D-printed enclosure
* Rechargeable battery support
* Low-profile design inspired by the Apple Magic Keyboard

---

# Project Goals

When I started this project, I wanted to achieve several objectives:

* Design a fully functional keyboard PCB from scratch
* Learn professional PCB design workflows using KiCad
* Create a sleek, low-profile enclosure
* Build a wireless keyboard using ZMK
* Improve my CAD skills using Fusion 360
* Gain experience preparing hardware for manufacturing

---

# Why I Built This

I've been using a basic keyboard for a long time and wanted something that felt more premium and minimalist.

The Apple Magic Keyboard has always stood out to me because of its clean appearance and slim profile, so I used that as inspiration for this project.

Rather than purchasing a keyboard, I wanted to build one myself so I could better understand:

* PCB design
* Keyboard matrix design
* Hardware prototyping
* Bluetooth firmware
* Product design

This project also serves as a stepping stone toward larger hardware projects I want to build in the future.

---

# Design Process

## PCB Design

The PCB was designed entirely in KiCad.

Since I was still kinda new to KiCad, I spent a significant amount of time learning schematic capture, footprint selection, routing techniques, and manufacturing requirements.

The PCB includes:

* Nice!Nano V2
* Keyboard matrix
* Diodes
* Hot-swap sockets
* Battery support
* Power switch

### Final PCB

<img width="688" height="429" alt="image" src="https://github.com/user-attachments/assets/e38c4b04-f37b-4879-b5d9-4b9e33c55280" />



---

## Schematic Design

The schematic was the foundation for the entire project.

Key components include:

* Nice!Nano V2
* Keyboard matrix
* Switches
* Diodes
* Battery connector
* Power switch

### Final Schematic

<img width="1079" height="555" alt="image" src="https://github.com/user-attachments/assets/0accbcf5-0325-4324-b000-15d5c2f1d6b9" />

<img width="1101" height="944" alt="image" src="https://github.com/user-attachments/assets/5a898746-f43b-410e-88af-6f6d-6bb0fdf2" />

---

## Case Design

The enclosure was designed in Fusion 360.

I wanted a slim design while still maintaining enough structural strength to support daily use.

The enclosure uses:

* Heat-set inserts
* Screws for assembly
* Internal mounting points
* Custom-fit dimensions for the PCB


### Version 2

After reviewing the first version, I increased the case thickness and improved the mounting system.

Changes included:

* Added screw holes
* Improved internal clearances
* Increased wall thickness
* Better support for assembly

### Version 3 
Made the case a whole pikachu theme, I will print this in yellow to make it something unique to me. I also added a honey comb pattern at the  bottom.

<img width="1480" height="998" alt="image" src="https://github.com/user-attachments/assets/c0ed00c6-715c-4bad-bd95-37b3b0a5f2ae" />

<img width="1309" height="982" alt="image" src="https://github.com/user-attachments/assets/dfae3457-c19e-4dea-8341-412ebd767087" />

<img width="1402" height="1002" alt="image" src="https://github.com/user-attachments/assets/58914f88-4483-46db-9238-4138184396a1" />


---

# Manufacturing Plan

The keyboard will be assembled using the following process:

1. Order custom PCB
2. Solder all components
3. Install hot-swap sockets
4. Flash ZMK firmware
5. Install switches
6. Assemble enclosure
7. Test Bluetooth connectivity
8. Daily-use testing

---

# Challenges

This project pushed me outside my comfort zone in several areas.

### Learning KiCad

Although I had some previous experience creating a macropad, this was my first larger PCB project.

### Routing the PCB

Learning proper routing practices and organizing traces took significant trial and error.

### Designing Around Physical Constraints

Making the enclosure thin while still fitting all components required multiple iterations.

### Hardware Integration

Balancing PCB dimensions, switch placement, mounting points, and case geometry was one of the most difficult parts of the project. 

---

# What I Learned

Through this project I learned:

* PCB schematic design
* PCB layout and routing
* Manufacturing considerations
* Keyboard matrix design
* Fusion 360 enclosure design
* Hardware prototyping workflows
* ZMK firmware 

Most importantly, I learned how multiple engineering disciplines work together when designing a product.

---

# Resources

The following resources were especially helpful during development:

### PCB Design

https://www.youtube.com/watch?v=7UXsD7nSfDY

### Keyboard Design

ScottO'KeeBs YouTube Channel

### Software

* KiCad
* Fusion 360
* ZMK Firmware

---

# Bill of Materials
(links are in BOM.csv)

| Item                       | Cost      | Quantity                    |
| -------------------------- | --------- | --------------------------- |
| Low Profile Switches       | $15       | 80                          |
| Nice!Nano V2               | $25       | 1                           |
| Diodes                     | $6        | 80 (only packs of ten)      |
| Custom Keyboard PCB        | $30       | 1 (Minimum order is 5)      |
| Hot-swap Sockets           | $12       | 80                          |
| Power Switch               | $1.50     | 1 (minimum order is 2)      |
| Battery Jack               | $1        | 1 (minimum order is 2)      |
| Battery                    | $7        | 1                           |
| Filament for Case          | $20       | 1                           |
| Heat Inserts & Screws      | $8        | 1 (M2.5 should work)        |

**Estimated Total: $136**

---

# Future Improvements

Potential future upgrades include:

* CNC (I think) enclosure
* Magnetic charging system (maybe for me to use in a custom laptop?)
* Lower-profile enclosure revisions
* Improved battery mounting
* Custom keycaps
* Docking support for future laptop projects

---

# Gallery

### PCB Render

<img width="688" height="429" alt="image" src="https://github.com/user-attachments/assets/122d34c6-e81c-4522-bbc5-3073a7d218f8" />


### Schematic

<img width="1101" height="944" alt="image" src="https://github.com/user-attachments/assets/3bda4cb3-1629-4dea-b8ad-dd5bc3fe6908" />


### Updated Case


<img width="1480" height="998" alt="image" src="https://github.com/user-attachments/assets/c0ed00c6-715c-4bad-bd95-37b3b0a5f2ae" />

<img width="1309" height="982" alt="image" src="https://github.com/user-attachments/assets/dfae3457-c19e-4dea-8341-412ebd767087" />

<img width="1402" height="1002" alt="image" src="https://github.com/user-attachments/assets/58914f88-4483-46db-9238-4138184396a1" />

### Zine Page

Ok look, my Zine was saved in canva (under my school account), so it was hard for me to add the new case on the back side, so I hope y'all will let it slide.

<img width="832" height="1260" alt="Zine_keyboard_new" src="https://github.com/user-attachments/assets/2d13a3f4-c998-4651-a3bf-6572cbfe1ac3" />

