---
title: "thing"
author: "pizzalover125"
description: "A Spotify car thing clone."
created_at: "2025-05-27"
---
**Time Spent: 12 hours**

5/27
I saw Ducc's ESP32 Car Thing clone while on YouTube, so I wanted to make my own! I did some research and for some reason picked the Raspberry Pi Pico, in hopes of using my Orpheus Pico. I started designing but realized my Orpheus Pico doesn't have WiFi/BLE :skull:. So then I researched ESP32-based XIAO boards. I came up with the Seeed Studio Xiao ESP32-C3 due to them advertising it as a low-cost board with WiFi and BLE support. Then I had to pick a display. After tons of additional research, I came up with the Adafruit 2.0" SPI display. AdaFruit is on the premium side, but seems more reliable than AliExpress. Also, the Sprig console used an AdaFruit display, so I'll go with it. Finally, I began the schematic. It was SUPER simple. I was originally planning to have a knob, but realized it is VERY big and would force me to have stand-offs for the display, something I did not want. So, I just ended up using 5 buttons. I then designed the PCB, which was also easy. I then designed the 3D case, which is when I realized the project is SUPER ugly and I need to restart. Take a look for your self:

![image](https://github.com/user-attachments/assets/028a0d33-64fe-456f-8b76-309765d96c50)

So I'll design a better solution tomorrow :).

5/28
Okay so I basically just designed the new, smaller PCB. People also liked it in the Slack. It looks ok I guess. Idk what to say as that's pretty much all I did. I also deisgned the case using a similar style to Hackpad.

5/29
Today, I built the firmware. I don't really know how to make firmware without the hardware at hand... so I just adjusted @Ducc's firmware. Turns out we used a different MCU and different display chip. I modified the code to work with my variant. I also added support for volume up and volume down. When I get the PCB and stuff, I'll actually make custom firmware that shows the album art and everything. 
