# uv_light
Licence: CERN Open Hardware Licence Version 2 - Strongly Reciprocal

 Custom Sun Lamp / Full Spectrum Lamp
 
 Background writeup [here](https://syllepsis.live/2024/12/31/light-for-health-and-a-custom-sun-lamp/)

A heatsink is important. All 16 leds are too much, unfortunately.

Problem: the comparator circuit for voltage sensing doesn't work properly, and needs a look at.

Minor problem: there's one trace that is bridged by the heatsink here. Using a non conductive thermal pad between the pcb and heatsink solves that problem, or redesign.

Recommendation: add a switch to the UV circuit as well. Also perhaps use larger switches than those specced here if you intend to switch the active lights often.

Designed for:
* QLUV07EYGE
* JE2835 3V N CLASS FAR RED
* Samsung LM302N White, Cool 6500K 
* Samsung LM302N WARM WHT 2700K 1212
* GT PSLR31.13-LUMQ-T1T2-1-150-R18 LED DURIS S5 GREEN 540NM SMD

![plot](./img/light.jpg)
