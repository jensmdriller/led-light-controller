# led-light-controller
This repo focuses around the development of an arduino based controller to program and control LED strip lights. 

- - - -

**Note**, I've created this repo to serve as a centralized storage for all of the LED project files. I'll update the README file as the project progresses. The README as well as the files contained within this folder should be a good reference for any future development. 

- - - -
### Overview
The components used herein are widely used in the hacker/maker community. Thus, much of the work has already been done for us. 
- For example, the **Atmel SAMD21** microcontroller is found in the Arduino Zero as well as many other developer boards.
- The lights are essentially a SMD 5050 LED with an integrated WS2811 microcontroller.
  - This integration of LED + MCU is referred to as **WS2812B**, but companies such as Adafruit use WS2812B LEDs and rebrand it as Neopixels. Other companies are starting to do the same. 
- The main hurdle of using WS2812B chips is their 5v operating voltage as well as their higher current draw. This prevents long runs without power injection along the way

- - - -

### Phase 1: Hardware Design
- Determining which microcontroller (MCU) and WiFi module to use
- Finalize schematic (including audio in or microphone)
- Configuring the power supplies
- Laying out the circuit board
- Ordering the circuit board and components
- Soldering/Assembling the first prototypes

### Phase 2: Coding - App & Embedded Software Design:
- Learn how the microcontroller (MCU) communicates with the LEDs
- Develop initial programs/sequences to control lights
- Work on WiFi integration
- App development (Android & IOS)
- Configure sync between app and LED controller via WiFI
- Refine app and implement additional functionality 

### Phase 3: Case/Enclosure Design
- Well let’s cross this bridge when we come to it

- - - -
- - - -

### Coming to Terms With Reality
- No one is going to buy this. This work is purely out of interest and enjoyment
- Good WiFi chipsets are protected by NDA. Thus we have to use more expensive and more discrete chipsets
- There already exists a lot of products on the market that have done exactly this - well almost...
- I'm pretty busy these days, so progress might be slow
