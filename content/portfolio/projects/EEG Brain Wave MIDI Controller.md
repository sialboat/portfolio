---
title: EEG Brain Wave MIDI Controller
description: EEG Brain Wave MIDI Controller for MPATE-GE 2047 Adv. Computer Music taught by Mason Mann.
aliases:
draft:
tags: project, portfolio
published:
created: 12-22-25
permalink:
---
#project #portfolio 
Final Project for MPATE-GE 2047 Advanced Computer Music.

 This project utilizes a custom ESP32 development board and a MindFlex EEG sensor. The MindFlex sensor transmits the magnitudes of various frequency bins as a digital signal, to which the ESP32 will translate into MIDI-CC via USB and Adafruit's TinyUSB abstraction.

The incredible folks at NYU's ITP program provided a comprehensive [tutorial](https://frontiernerds.com/brain-hack) on how to get this up and running. In addition, they have provided an [Arduino Library](https://github.com/kitschpatrol/Brain) to interface with this MindFlex controller.

## MEAP: Mason's ESP32 Audio Prototyping System
[Mason Mann](https://masonmann.online)'s Advanced Computer Music class utilizes a custom-built ESP32 development board and a custom fork of the Mozzi library to create the optimal audio prototyping environment. You can find more about it [here](https://masonmann.online/electronics/meap). The Mozzi-based audio library can also be found [here](https://masonmann.online/electronics/meap/software)

## Current iteration
For the final project, the MEAP is being used as a MIDI Controller without any other stochastic processes actively modifying the signal. A plugin host like [VCV Rack](https://vcvrack.com) was used alongside select VST plugins ranging from Unfiltered Audio to Freakshow Industries to create an ever evolving soundscape. 

Components within the codebase (development and integration of stochastic processes) will continue to get updated (as they barely work).

You can find more about the project on the [GitHub repository](https://github.com/sialboat/ESP32-Brain-Wave-MIDI-Controller)