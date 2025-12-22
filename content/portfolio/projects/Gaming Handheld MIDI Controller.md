---
title: Gaming Handheld MIDI Controller
tags:
  - project
  - portfolio
TQ_show_tags:
description:
aliases:
draft:
published:
created:
permalink:
---
Fall 2025 Product Design project; a Teensy-based handheld gaming controller akin to a SteamDeck or a Wii-U that aims to simultaneously control music software/hardware and a video game. This project uses two dual-axis joysticks each with a select button, a DAC and a LSM6DSOX gyroscope, a handful of buttons, and a 320x240 ILI9341 TFT Display.

The backend utilizes a [framebuffer](https://github.com/vindar/ILI9341_T4) and [the tgx graphics library](https://vindar.github.io/tgx/html/index.html) to print information onto the screen (GUI is a work in progress). Raw data from parameters (knobs, buttons, and gyroscope input) can be adjusted with macro-level behaviors and micro-level modifiers and (hopefully) modulators that can adjust said behaviors and modifiers. The Teensy utilizes a custom USB Type that combines HID Mouse and Keyboard output with USB Serial and MIDI.

Additional documentation (including a [demo video](https://www.youtube.com/watch?v=1ZILFzvfqQk)) about the project's direction can be found below.

[GitHub](https://github.com/sialboat/product-design-sound-controller)

<iframe src="/prod-design-final-documentation.pdf"
width="100%" 
height="600px"
style="border: none;"
title="Product Design Final Documentation">
</iframe>