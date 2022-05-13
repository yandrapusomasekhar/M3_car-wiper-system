# M3_car-wiper-system

### OBJECTIVE

The aim of the project is to design a wiper control system which automatically controls the wiper according to the rain fall of water.In large cities and industries where supply and distribution tanks are at a largedistance from water control station, it is very difficult situation to monitor the water.

The main objective of this project is through ARM microcontroller to design a wiper control system. The project mainly insists on controlling the motion of wiper based on frequency and time period (in seconds).


### SOFTWARE REQUIRMENTS:
* STM32CUBEIDE
* CYGWIN
* QEMU
### COMPONENTS USED IN PROJECT:
* STM32F407G-DISC1

STM32F407 series of microcontrollers are high-performance MCUs designed for medical, industrial and consumer applications. It is based on ARM Cortex-M4 and offers up to 168MHz. The STM32F407VGT6 is the onboard chip which comes in a 100-pin LQFP package.

The STM32F407G-DISC1 is a Discovery Kit allows users to easily develop applications with the STM32F407 high performance microcontrollers with ARM cortex-M4 32-bit core. It includes everything required either for beginners or for experienced users to get quickly started. Based on the STM32F407VGT6, it includes an ST-LINK/V2 or ST-LINK/V2-A embedded debug tool, two ST MEMS digital accelerometers, a digital microphone, one audio DAC with integrated class D speaker driver, LEDs and push buttons and an USB OTG micro-AB connector.


![Requirements](https://user-images.githubusercontent.com/101333790/168214465-9e3fb173-b205-4829-af87-b3ac6b815964.png)



# 4'WS and 1H:
### Who
All automobiles have wiper system and The drive moves the two wiper arms at a certain angle across the windshield, providing a clear view for the driver and passenger while travelling.

### What
The main purpose of the wiper system is to clean the windscreen sufficiently to provide suitable visibility at all times. In this project three LEDs are used to control the system.

### When
Wipers are a small part of any automobiles like cars,trains,truck and so on but they have a big impact on driving and overall safety. They remove rain, snow, dirt, pollen, frost and other debris quickly. In this project when ignition system is turn on or off where the three LEDs turn on or off depending upon the frequency.

### Where
Wipers system are used in automobiles.

### How
This system has been done by LED and Timer.

# SWOT ANALYSIS:
### Strengths:
a) Growth in production of vehicles

b) Higher demand for luxury features

c) Automatic wiper control system

d) Less power consumption

e) Operating level is easy

### Weakness:
a) May not be working at inclement weather

b) May not detect objects

c) It may also malfunction if components fail

d) Sometimes not working properly

e) High cost

### Opportunities:
a) The wiper serves to clean the windshield of the any automobile at the front and rear. Wiper works by removing oil, dust, rainwater, and dirt that get stuck to the windshield.

b) Wipers detect moisture on the windshield and activate the wipers to help increase driver visibility.

c) Improve safety by decressing driver distraction.

### Threats:
a) Time interval may vary thereby it cause some problem on wiper system.

b) Due to so much ice or snow on windshield may cause the wipers to get jammed and cause circuit overloading.

c) Accident may occur due to fault in wiper system.


### High Level Requirements
| RID | Description | Status |
| -- | ----------- | ------ |
| HLR1 | EMBEDDED C LANGUAGE | IMPLEMENTED |
| HLR2 | OS WINDOWS | IMPLEMENTED |
| HLR3 | STM32CUBEIDE | IMPLEMENTED |
| HLR4 | CYGWIN | IMPLEMENTED |
| HLR5 | QEMU  | IMPLEMENTED |
| HLR6 | HARDDISK | IMPLEMENTED |
| HLR7 | RAM 4GB | IMPLEMENTED |


### Low Level Requirements
| RID | Description | Status |
| -- | ----------- | ------ |
| LLR1 | RED LED ON | IMPLEMENTED |
| LLR2 | BLUE LED FREQUENCY 1HZ | IMPLEMENTED |
| LLR3 | GREEN LED FREQUENCY 4HZ | IMPLEMENTED |
| LLR4 | ORANGE LED FREQUENCY 8HZ | IMPLEMENTED |
| LLR5 | RED LED OFF  | IMPLEMENTED |
