# Chameleon 

![Chameleon](https://github.com/TweetyDaBird/Chameleon/blob/cacc1df8e47305e165246d7c2ac52fd11dd8695b/Store%20images/9nrq1ur6bhpt908ksrl6s7qjo6i8.jpg)

## Features
**Chameleon is a grid type orthogonal keyboard with two optional layouts in one single PCB.** Being able to break off the bottom row allows both a 5x12 layout similar to the popular Preonic and a 4x12 layout similar to the equally popular little brother Planck on the same PCB. 

Using the more common 19.05 mm grid spacing (vs Preonic & Planck's unique 19 mm) this PCB fit's several popular 'aftermarket' keyboard cases intended for JJ40/JJ50 and BM40 PCB's without modification. (Please read below!)

Being fully hot-swap and with PCB mounted stabilizers, Chameleon adds support for up to four encoders and a bottom row allowing either a single stabilized 2u key or two 2u keys in the middle, allowing for a layout that suits most users. If used as a 5 row keyboard, the bottom encoders can alternatively be placed at the edges on the second row, but **not more than one per corner.** 

The Chameleon features 8 bottomfacing RGB LEDs for underglow effects or to be used for layer indication or similar. 

**Please Note! This PCB does NOT fit a Planck/Preonic case! You will need a different case to complete the build!**

### Main Features:
* QMK and VIAL compatible, fully programmable keyboard**
* RP2040 MCU, Dual-core Arm Cortex M0+ processor, flexible clock running up to 133 MHz
* 264KB of SRAM, and 4MB of on-board Flash memory
* USB-C connector, (USB 1.1 device and host support)
* Low-power sleep and dormant modes
* Drag-and-drop programming using mass storage over USB
* Kaihl hot-swap sockets for Cherry MX compatible switches (3 & 5-pin)
* Cherry Style PCB mounted stabilizers
* Two main layouts:
	* 5x12 with 58 to 60 keys
	* 4x12 with 46 to 48 keys (Break off bottom row) 
* Configurable bottom row:
	* Full 1u grid
	* 1x centered, stabilized 2u key
	* 2x centered,  stabilized 2u keys

### Optional add-ons:
* Support for up to 4 rotary encoders **(one encoder per corner)**
* Optional RGB underglow (8x SK6812 mini-e)
* FR4 Front plate (FR4 material, same as PCB), with full layout options (Black / White). This is designed to fit most/all existing cases of a tray (or burger) mounting type, 3D printed or CNC. Se below for listed tested cases.

**These options requires additional components not included in this listing and sold separately.**

## Assembly
**Little or no tools at all needed!** The PCB can be delivered fully soldered and ready to use, either as a full matrix, or with your selection of rotary encoders (encoders need to be added to the order), or as a "DIY Kit" with the hotswap sockets for the 6 encoder positions not soldered.

The 8 optional RGB LED's needs to be soldered in place if used. (These are pre-soldered together with the encoders/hot-swap sockets at no extra cost, if that option is selected and all parts are purchased in the same order).

# Case & Plate
**The design is made to fit any existing cases for JJ40/JJ50 & BM40 both CNC and 3D printed.** This means that existing cases with an *integrated* plate is then limited to the layout options supported by that case/plate even if the PCB supports more layouts. 

#### Cases verified to work:

- [JJ50 Aluminium & Acrylic Case](https://kprepublic.com/collections/jj50-50/products/anodized-aluminium-case-for-jj50-50-custom-keyboard-acrylic-diffuser-rotary-brace-similar-with-preonic)
- [JJ50 Stainless Steel Case](https://kprepublic.com/collections/jj50-50/products/stainless-steel-bent-case-enclosed-case-for-jj50-jj50-50-custom-keyboard-acrylic-panels-acrylic-panel-diffuser-similar-preonic)
- [JJ40 Aluminium Tray Case](https://kprepublic.com/products/anodized-aluminium-jj40-bm40-flat-case-metal-feet-black-sliver-grey-for-40-mini?_pos=1&_sid=b33f69eef&_ss=r)
- [JJ40 Aluminium & Acrylic Case](https://kprepublic.com/products/anodized-aluminium-case-for-jj40-40-custom-keyboard-acrylic-panels-acrylic-diffuser-jj40-rotary-brace-supporter-for-planck?_pos=4&_sid=b33f69eef&_ss=r)
- [Poseidon PSD40 Case Anodized](https://kprepublic.com/products/poseidon-psd40-case-anodized-aluminium-case-for-custom-mechanical-keyboard-black-siver-grey-blue-red-for-jj40-bm40-bm40-rgb?_pos=5&_sid=b33f69eef&_ss=r) 
- [Poseidon PSD40 Case Electonplated](https://kprepublic.com/products/kp-poseidon-psd40-case-electrophoresis-cnc-case-for-custom-mechanical-keyboard-yellow-purple-cyan-white-for-jj40-bm40-bm40-rgb?_pos=6&_sid=b33f69eef&_ss=r)

*Mounting hardware is associated with the case, and not delivered with the Chameleon PCB and Plate.

## Front Plate
**A front plate in FR4 (PCB core material) is available as an add-on, but may not fit all cases.** To be as much a "one size fit's all" plate, this plate has rounded corners, which may leave gaps in the corners on some cases.

## Sandwich type case/plates
A full sandwich type case in FR4 material will be added at a later date for those interested, but is for now WIP.

** Firmware pending

![Built Chameleon](https://github.com/TweetyDaBird/Chameleon/blob/cacc1df8e47305e165246d7c2ac52fd11dd8695b/Store%20images/IMG_1473.JPEG)
![Lit Chameleon](https://github.com/TweetyDaBird/Chameleon/blob/cacc1df8e47305e165246d7c2ac52fd11dd8695b/Store%20images/IMG_1472.JPEG)

# Making Chameleon yourself
**Chameleon is open source / open hardware, and can be manufactured by anyone. The release contains all the neccesary files like parts lists, positions files etc for a full PCB/SMT production.** 

The formatting and files are geared towards [JLCPCB](http://jlcpcb.com), but never tested as such, as I only manufacture the PCB then do the assembly myself (at least until this reaches a volume justifying full SMT production).

The components are small enough that you would have to be highly skilled to attempt to assemble this either as hand soldered, or small scale/DIY SMT. I would highly recommend ordering the PCB as fully assembled unless you know you have the neccesary skill-set.

## Buy a kit!
I sell complete kits, making it easy to build your keyboard, and it also supports prototypes for new wacky ones. 

<a href="https://lectronz.com/stores/tweetys-wild-thinking"><img alt="Buy it on Lectronz" src="https://lectronz.com/static/badges/buy-it-on-lectronz-small.png" /></a>

## Discord for build help and discussions!

<a href="https://discord.gg/G6QzcJQUnm"><img alt="Discuss on Discord" src="https://assets-global.website-files.com/6257adef93867e50d84d30e2/625eb604bb8605784489d361_Discord-Logo%2BWordmark-Color%20(1).png" width="219" height="60"/></a>

# License

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa] - This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

