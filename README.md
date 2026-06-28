# My Keyboard

- A custom low-profile wireless mechanical keyboard designed from scratch to match the coolness of the Apple Magic Keyboard while teaching me PCB design, firmware development, and CAD. I know it looks pretty simple, but it took me a long time to make it and I'm pretty proud of it

<img width="1410" height="1013" alt="image" src="https://github.com/user-attachments/assets/1a772c35-aa3a-4c91-83cf-5fce31a8f941" />



## Overview

This keyboard is a mechanical and wireless built with the Nice!Nano V2 microcontroller and will use ZMK firmware. My idea was to create a minimal keyboard that matches my dad's MacBook Pro which I occasionally use.

Instead of buying an existing keyboard, I decided to design it myself, so I could learn software like Kicad and Fusion360 more.

The keyboard features:

* Bluetooth connectivity using ZMK firmware
* Nice!Nano V2 controller
* Hot-swappable switches
* Custom Pikachu-themed 3D-printed enclosure
* Rechargeable battery 10000 mah
* Low-profile design

# Why I Built This

I've been using a basic keyboard for a long time and wanted something that felt more premium and minimalist. I wanted something that wasn't that bulky, but still stood out, so I designed the pikachu minamalist keyboard. This keyboard helped me learn major software for the laptop I'm building in the future.

# The Process

## PCB Design

The PCB was designed in KiCad.

Since I was still kinda new to KiCad, I spent a lot of time learning footprint selection, routing techniques, and manufacturing requirements. The PCB includes a way for me to charge a battery using the Nice!Nano. The PCB also uses a matrix to make all the switches fit. 

### Final PCB image

<img width="688" height="429" alt="image" src="https://github.com/user-attachments/assets/e38c4b04-f37b-4879-b5d9-4b9e33c55280" /> 

## Schematic Design

The schematic wasn't that bad for me to do as I learned a decent amount from my macropad, so I didn't spend most of my time here. Most of my time was spent on finding the right symbols. I later learned that the symbol doesn't matter at all if you have the right footprint.

### Final Schematic images

<img width="1079" height="555" alt="image" src="https://github.com/user-attachments/assets/0accbcf5-0325-4324-b000-15d5c2f1d6b9" />

<img width="1101" height="944" alt="image" src="https://github.com/user-attachments/assets/5a898746-f43b-410e-88af-6f6d-6bb0fdf2" />


## Case Design

The enclosure was designed in Fusion 360. My initial design was very basic, practically just a box with screws.

### Version 2

After reviewing the first version, I increased the case thickness and improved the mounting system. I added thicker walls as the thin walls would lead to snapping.

### Version 3 
Made the case a whole pikachu theme, I will print this in yellow to make it something unique to me. I also added a honey comb pattern at the bottom. To me, this was by far the best version and the one I'm the most proud of.

<img width="1480" height="998" alt="image" src="https://github.com/user-attachments/assets/c0ed00c6-715c-4bad-bd95-37b3b0a5f2ae" />

<img width="1309" height="982" alt="image" src="https://github.com/user-attachments/assets/dfae3457-c19e-4dea-8341-412ebd767087" />

<img width="1402" height="1002" alt="image" src="https://github.com/user-attachments/assets/58914f88-4483-46db-9238-4138184396a1" />



# Manufacturing Plan

The keyboard will be assembled using the following process. You will first need to order the PCB and all of the otherb parts in the BOM. Once you recieve all the parts and the PCB, you can start soldering them all and then you can flash ZMK software onto the Nice!Nano. Once thats working you can assemble the case, which means you need to put the heat inserts and screw it together.


# Problems

This project made me learn plenty of things that I didn't know very well before.

### Learning KiCad

Although I had some previous experience creating a macropad, this wass my first PCB project without a tutorial

### Routing the PCB

I had to route the PCB about 5 times as it was very confusing to do.


# What I Learned

Through this project I learned how to use PCB design softwares better, how to use ZMK, and how to use fusion 360 efficiently.


# Resources

The following resources were especially helpful during development:

### PCB Design

https://www.youtube.com/watch?v=7UXsD7nSfDY

### Keyboard Design

ScottO'KeeBs YouTube Channel

### Software
 I used Kicad, Fusion360, and ZMK

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

Estimated Total: $136 (before tax + Shipping)

---

# Future Improvements

Potential future upgrades include:

* CNC (I think) enclosure
* Magnetic charging system (maybe for me to use in a custom laptop I'm designing?)
* Lower-profile enclosure revisions
* Improved battery mounting
* Custom keycaps

  
# Gallery/Images

### PCB Render

<img width="688" height="429" alt="image" src="https://github.com/user-attachments/assets/122d34c6-e81c-4522-bbc5-3073a7d218f8" />

Although it is quite tight the hot-swap pocket does fit under the Nice nano, which I anticipated as per my resources.
<img width="1893" height="1262" alt="image" src="https://github.com/user-attachments/assets/e2d5e8f2-ce83-425a-9a09-84af7f3a0ccc" />


### Schematic

<img width="1101" height="944" alt="image" src="https://github.com/user-attachments/assets/3bda4cb3-1629-4dea-b8ad-dd5bc3fe6908" />

<img width="1318" height="963" alt="image" src="https://github.com/user-attachments/assets/3775489b-a591-4bd1-bfaf-5a0984a79033" />

### Updated Case


<img width="1480" height="998" alt="image" src="https://github.com/user-attachments/assets/c0ed00c6-715c-4bad-bd95-37b3b0a5f2ae" />

<img width="1309" height="982" alt="image" src="https://github.com/user-attachments/assets/dfae3457-c19e-4dea-8341-412ebd767087" />

<img width="1402" height="1002" alt="image" src="https://github.com/user-attachments/assets/58914f88-4483-46db-9238-4138184396a1" />

### Zine Page

Ok look, my Zine was saved in canva (under my school account), so it was hard for me to add the new case on the back side, so I hope y'all will let it slide.

<img width="832" height="1260" alt="Zine_keyboard_new" src="https://github.com/user-attachments/assets/2d13a3f4-c998-4651-a3bf-6572cbfe1ac3" />

