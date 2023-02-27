# Muscle BioAmp Shield

![Project Category](https://img.shields.io/badge/Category-Bioelectronics-gold) ![Muscle BioAmp Shield Revision ](https://img.shields.io/badge/Version-v0.3-success)
[![Muscle BioAmp Shield store link](https://img.shields.io/badge/Buy-Store_(India)-white)](https://store.upsidedownlabs.tech/product/muscle-bioamp-shield-v0-3/)
[![Muscle BioAmp Shield Tindie link](https://img.shields.io/badge/Buy-Tindie-cyan)](https://www.tindie.com/products/upsidedownlabs/muscle-bioamp-shield-v03-arduino-shield-for-emg/)
[![Muscle BioAmp Shield intro video ](https://img.shields.io/badge/Intro-YouTube-red)]()
[![Upside Down Labs GitHub Sponsors page ](https://img.shields.io/badge/Support-GitHub_Sponsor-00B5AC)](https://github.com/sponsors/upsidedownlabs)
[![Upside Down Labs GitHub PayPal page](https://img.shields.io/badge/Support-PayPal-00B5AC)](https://paypal.me/upsidedownlabs)


Muscle BioAmp Shield is an all-in-one Arduino Uno ElectroMyography (EMG) shield for learning neuroscience with ease. It is a DIY Electrophysiology/NeuroScience shield inspired from Back Yard Brains (BYB) Muscle Spiker shield and provides similar features like hobby servo output, user buttons, LED Bar, Audio output, and battery input. It is perfect for beginners as they can easily stack it on top of Arduino Uno to record, visualize and listen to their muscle signals to make amazing projects in the domain of Human-Computer Interface (HCI).

## Features & Specifications

Muscle BioAmp Shield comes with various plug-and-play options so you can connect hundreds of extension boards like OLED screens, character displays, accelerometers, and servo controllers to name just a few using the STEMMA I2C interface. You also get STEMMA digital and STEMMA analog ports. On STEMMA analog port you can connect additional [BioAmp EXG Pill](https://github.com/upsidedownlabs/BioAmp-EXG-Pill) or any other sensor with analog output. On STEMMA digital port you can connect any digital sensor or actuator of your choice.

![Muscle BioAmp Shield Specifications](graphics/board/Muscle-BioAmp-Shield_Specifications.jpg)

## Assembly
You can get your own Muscle BioAmp Shield bag of parts from [our store](https://store.upsidedownlabs.tech/product/muscle-bioamp-shield-v0-3/) or [Tindie](www.tindie.com/products/upsidedownlabs/muscle-bioamp-shield-v03-arduino-shield-for-emg/) and for assembling your shield you can take a look at [this interactive BOM](https://upsidedownlabs.github.io/DIY-Muscle-BioAmp-Shield/) or the step by step guide below. 

| Step 1 - Bare board | Step 2 - 1M Resistors | Step 3 - 330R Resistors| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/01_Bare_Board.jpg)|![](graphics/Assembly/jpgs/02_1M_Resistors.jpg)|![](graphics/Assembly/jpgs/03_330R_Resistors.jpg)|

| Step 4 - 10K Resistors | Step 5 - 22K Resistors | Step 6 - 1K Resistors| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/04_10K_Resistors.jpg)|![](graphics/Assembly/jpgs/05_22K_Resistors.jpg)|![](graphics/Assembly/jpgs/06_1K_Resistors.jpg)|

| Step 7 - 220K Resistors | Step 8 - 1nF Capacitors | Step 9 - 100nF Capacitors| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/07_220K_Resistors.jpg)|![](graphics/Assembly/jpgs/08_1nF_Capacitors.jpg)|![](graphics/Assembly/jpgs/09_100nF_Capacitors.jpg)|

| Step 10 - 100pF Capacitors | Step 11 - Servo Header Pin | Step 12 - Buttons| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/10_100pF_Capacitors.jpg)|![](graphics/Assembly/jpgs/11_Angled_Header_Pins.jpg)|![](graphics/Assembly/jpgs/12_5x5mm_Buttons.jpg)|

| Step 13 - Optoisolator | Step 14 - Angled JST Connectors | Step 15 - Straight JST Connectors| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/13_OptoIsolator.jpg)|![](graphics/Assembly/jpgs/14_JST_PH_Angled_Connectors.jpg)|![](graphics/Assembly/jpgs/15_JST_PH_Straight_Connectors.jpg)|

| Step 16 - IC Socket | Step 17 - IC | Step 18 - LEDs| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/16_IC_Socket.jpg)|![](graphics/Assembly/jpgs/17_IC.jpg)|![](graphics/Assembly/jpgs/18_LEDs.jpg)|

| Step 19 - 3.5mm Headphone Jack | Step 20 - 2.2uF Capacitor | Step 21 - 1uF Capacitor| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/19_3.5mm_Headphone_Jack.jpg)|![](graphics/Assembly/jpgs/20_2.2uF_Capacitor.jpg)|![](graphics/Assembly/jpgs/21_1uF_Capacitor.jpg)|

| Step 22 - 470uF Capacitors | Step 23 - Shield Header Pins | Step 24 - Shield Ready| 
| :----: | :----: | :----: |
| ![](graphics/Assembly/jpgs/22_470uF_Capacitor.jpg)|![](graphics/Assembly/jpgs/23_Header_Pins.jpg)|![](graphics/Assembly/jpgs/24_Assembled.jpg)|

## What's in the kit

Muscle BioAmp Shield comes in two variants: Pre-Assembled and DIY (Do-It-Yourself). You can order any of the two variants as per your requirement.

![DIY Kit](graphics/board/DIY_Kit.jpg)
![DIY Kit](graphics/board/Preassembled_Kit.jpg)

## Hardware

Muscle BioAmp Shield has been created using KiCad and all the design files can be found under [hardware](hardware/) folder, including [Interactive BOM](hardware/bom) file. Images below shows a quick overview of the hardware design.

| PCB front | PCB back |
| :-------: | :--------: |
| ![Muscle BioAmp Shield](graphics/board/Muscle-BioAmp-Shield-Front.png) | ![Muscle BioAmp Shield](graphics/board/Muscle-BioAmp-Shield-Back.png) |

![Muscle BioAmp Shield](graphics/board/dimensions.png)

![Muscle BioAmp Shield](graphics/board/Schematic.png)


## License

#### Hardware
CERN Open Hardware License Version 2 - Strongly Reciprocal ([CERN-OHL-S-2.0](https://spdx.org/licenses/CERN-OHL-S-2.0.html)).

#### Software
MIT open source [license](http://opensource.org/licenses/MIT).

#### Documentation:
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.