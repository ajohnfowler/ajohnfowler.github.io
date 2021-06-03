---
title: "Led Matrix"
date: 2021-04-20T22:48:12-03:00
draft: true
toc: false
images:
tags:
  - Projects
  - Arduino
---

The Build:

Electronics:
- ESP32 Dev Board
- 3 x 5M WSB12B LED strips
- Power Cable
- 150W 5V Power Supply

Frame:
- Diffusion material (Thin curtain)
- Wood
- Backing board (Foam core board)

Tools:
- Solding Iron
- Solder
- Wire

Used 2 1"x3"x6' pine boards
Used 2 foam core boards from the dollar store
User a curtain from the dollar store 

Start by testing all the compoents are working.

After all the componets are confirmed to be working I cut the leds down to 1m lengths and re-wired the ends to allow them to be mounted on the backing board.

The board I used was 20"x40" in size. Each strip was mounted starting with the center then spacing evnly every 3.3cm to give a nice grid to the leds.

The Code:

For this I used [platformIO](https://platformio.org/) with Visual Studio Code.

All the is freely availiable under the MIT licencice on [GitHub](https://github.com/ajohnfowler/Led-Panel).

Final Result: