---
title: "ESP32-S3 WROOM-1U Humidity sensor With LED RGB Matrix"
github: "https://github.com/MinoMark/ESP32-S3-WROOM-1U-Humidity-sensor-With-LED-RGB-Matrix"
description: "The project I am building is an ESP32-S3 WROOM-1U humidity sensor with an LED RGB matrix. This project is a really cool one. The ESP will control and read the data from the sensor and output certain colours, patterns, or make the lights move based on the temperature, humidity, and air quality. An app will run statistics whilst magnets on the base of it can allow you to connect it to fridges and other surfaces."
created_at: "2026-11-12"
total_time: "8h"
---

# November 12, 2026: Designing the schematic!

The first journal for this project! Today I've made the schematic. I used 2 new modules I've never used before as well as way too many RGB LEDs...

I used a temperature and humidity sensor as well as an air quality sensor. I made this because it's able to be put into the fridge and tell you how humid it is, or put it around the house or in your room. You'll be able to see stats as well as graphs of temp, or other changes around the room. I learnt so much. I've learnt how to daisy chain multiple components together, using capacitors to boost and keep the voltage and current clean throughout.

Although this is my second PCB using an ESP32-S3 chip, I've still learnt alot despite it taking me a while.

![](https://fabricate.hackclub-assets.com/9fbc1f4f27170bbfa8ef51eb34107c09cc50b74e21afec76639fea99ff482a13/image-png/Screenshot%202026-11-12%20163026.png)
![](https://fabricate.hackclub-assets.com/495308dd10a4e1d927fdca860643507e7f6e275a13e6bd051d4ba5626a28abd3/image-png/Screenshot%202026-11-12%20163031.png)
![](https://fabricate.hackclub-assets.com/1881d681c57da917c845395325a657d340f3ad0daee2d464785ddb53ab47e7eb/image-png/Screenshot%202026-11-12%20163050.png)

**Total time spent: 3h 42m**

# November 12, 2026: Routed the PCB

Day 2! Today I've done so much, and there is so much more to come!

I finally routed the PCB, this was one of my most challenging ones by far, because of the shape I've chosen for the PCB, it's a very unique one to route. Since I had to get traces around the edge, DCR kept giving me HUNDREDS of errors saying the trace was over the edge cut. I fixed this by manually having to move every trace.

Along with that, because since I made the edge cut in Adobe Illustrator, I had to import it into KiCad as a DXF, then import it as graphics into KiCad and set its layer to edge cut. I've overcome so many challenges whilst making this, including measurements and specifications.

Let me explain. Because I can't accurately determine the real size of the PCB, I had to make an educated guess with making a circle in 120mm circumference and work from there.

![](https://fabricate.hackclub-assets.com/bb9109516c2ef0726fa687d91d0b39cb5c834ab8ee9df5f97c9128d90e59e46e/image-png/Screenshot%202026-11-12%20225140.png)
![](https://fabricate.hackclub-assets.com/84ee385400da92050f90a61174f3a5d4ff6b47ca74fe9904f802fe8fa0c7afb3/image-png/Screenshot%202026-11-12%20225210.png)
![](https://fabricate.hackclub-assets.com/53ca793125bc92dda5b916f96dafbd2219745c45262c48c059cfe49f2505ff04/image-png/Screenshot%202026-11-12%20225217.png)

**Total time spent: 4h 18m**
