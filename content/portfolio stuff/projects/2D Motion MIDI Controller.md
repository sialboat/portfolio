---
title: 2D Motion MIDI Controller
tags:
  - project
  - portfolio
TQ_show_tags:
---
Fall 2024 Digital Electronics final project featuring a Teensy, two dual-axis joysticks, a DAC, and a 2.2" ILI9341 Display. 
Essentially the barebones of a game engine using C++ and Arduino's GFX Library, this project creates a controllable triangle that enables the user to have direct control over its position and orientation.

The triangle simulates 2D Motion. Both direction and orientation are implemented as momentum-based, meaning the character will accelerate and decelerate to the respective direction interpreted by the joystick. The position and orientation of the character can be translated into CV and MIDI CC to be used as a controller for musical devices ranging from Eurorack to VST plugins. 

Future iterations with this project will involve refactoring the statically-typed C++ code to an object-oriented system, porting the development environment to PlatformIO, and fleshing out gameplay mechanics to better resemble a top-down spaceship shooter like the retro game Asteroids.

[Project Overview](https://docs.google.com/document/d/1EwBQhJmSSoC8HgRFptuw8qkn9xVgbsGXSP5RETaCfTY/edit?tab=t.0) [GitHub](https://github.com/sialboat/digitalElectronics-finalProject)