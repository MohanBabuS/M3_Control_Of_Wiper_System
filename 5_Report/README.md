# ABSTRACT
 A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation,by changing the frequency  As its results the operation of bringing up the wiper speed is varied . The project's goals are to improve ageing cars' systems by giving automated transmission.wiping system, to improve the system by incorporating a sensor and actuator, and to create a simple software that would completely operate with the system.the framework This proposed wiper system's principle is comparable to those of other existing conventional wipers. Despite the fact that. This system will be upgraded to an automatic control system using a Peripheral Interface to remove water from the windscreen.

# INTRODUCTION
  The operational speed of a wiper is controlled by a wiper speed control system in accordance with frequencies. The pulse signal is digitally processed to provide a control signal. A wiper driver circuit receives the control signal and adjusts the operational speed or timing in line with it.
# SOFTWARE REQUIREMENTS
 STM32 CUBE IDE
# COMPONENTS
  STM32F4O7VG MICROCONTROLLER BOARD
## DESCRIPTION
# STM32F407VG
 The STM32F407  Kit takes advantage of the high-performance STM32F407 microcontrollers' capabilities to make it simple for users to create audio-based applications. It comes with an ST-LINK embedded debug tool, an ST-MEMS digital accelerometer, a digital microphone, an audio DAC with integrated class D speaker driver, LEDs, pushbuttons, and a USB OTG micro-AB connector.Ethernet connectivity, an LCD display, and other features have been added to the STM32F4 DISCOVERY kit. The STM32F405xx and STM32F407xx families are built around the high-performance Arm® Cortex®-M4 32-bit RISC core, which runs at up to 168 MHz.
 # FEATURES OF STM32F407VG MICROCONTROLLER
  * In a LQFP100 package, the STM32F407VGT6 microcontroller has a 32-bit ARM Cortex-M4 with FPU core, 1-Mbyte Flash memory, and 192-Kbyte RAM.
  * On-board ST-LINK/V2 or ST-LINK/V2-A on STM32F4 DISCOVERY (old reference) or STM32F407G-DISC1 (new order code)
  * USB ST-LINK with three separate interfaces and re-enumeration capability.
  * Virtual Com port Debug port (with new order code only)
  * Large-scale storage (with new order code only)
  * Board power is supplied through USB or an external 5 V supply source.
  * 3 V and 5 V external application power supply
 # USES
  * This Microcontroller is utilised in printing and scanning machines ,heat ventilation, air conditioning, and security systems. 
  * This module can be found in a variety of household products.
 # WORKING PRINCIPLE
  Assume that the automobile is the microcontroller. If the button is hit, the first led (red) will turn on, Clicking again  the wiper will start, and the second led (blue) will turn on for a desired rate. If the button is pressed again, the third led (green) will turn on, and the wiper's speed will be increased in comparison to the previous one. The fourth press will turn on the fourth led (orange), and the wiper speed will be increased in accordance with the previous one. The microcontroller (vehicle) is turned off after the fifth click.
 ## 4 W'S
 # WHAT IS WIPER SYSTEM
  Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
 # WHY WIPER SYSTEM
   To keep the windscreen clean enough to give adequate view at all times.
 # WHEN SHOULD USE WIPER SYSTEM 
  The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
 # WHO DISCOVERED WIPER SYSTEM
  Mark Anderson invented on 1902
 ## DETAIL REQUIREMENTS :

# HIGHLEVEL REQUIREMENTS 

|High Level Requirements|Description|
|:------|:---------|
|1|Programming language(C language)|
|2|Arm based microcontroller(STM32F40VGT6)|
|3|operating system(Windows)|
|4|RAM(Min 4GB)|
|5|Hard Disk(Min 250GB)|

# LOWLEVEL REQUIREMENTS

|Low Level Reqiurements|Description|Status|
|:-----|:--------|:---|
|1|ON-Ignition key|Implemented|
|2|Press Multi-functional button|Implemented|
|3|4 Different Color Leds|Implemented|
|4|Timer|Implemented|
|5|OFF-Wiper button|Implemented| 
  
  ## SWOT ANALYSIS
 # STRENGTH
  * Low Budget
  * REputation is Good
 # WEAKNESS
  * structural interia
  * high transcation cost
 # OPPRONUNTIES
  * Emerging new market
  * Demand for save Equipments
 # THREAT
  * Low bargaining power buyers
  * Econimical crisis 
#  ENGINE ON STATE
![engine start](https://user-images.githubusercontent.com/74193913/168195223-4ffe543a-e10e-4558-8f71-7fb72f42b8bf.png)

# WIPER SPEED IS LOW
![LOW](https://user-images.githubusercontent.com/74193913/168207426-c329cffd-af87-42a0-bc8b-d875a0c1e922.png)


# WIPER SPEED IS MODERATE
![wiper start](https://user-images.githubusercontent.com/74193913/168195256-babaf133-6f22-4961-be93-fd78d63f2ae4.png)

# WIPER SPEED IS HIGH
![HIGH](https://user-images.githubusercontent.com/74193913/168426068-a835f8a7-460b-4e64-b2c1-6bf446e055a7.png)




# OFF STATE
![off state](https://user-images.githubusercontent.com/74193913/168195291-cc56a05a-6c2d-46f8-842a-e36059586f07.png)
