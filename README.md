# OCTAVA
OCTAVA is a miniature electronic musical instrument that transforms eight capacitive touch pads into a simple, interactive piano. Instead of conventional mechanical keys, users touch copper electrodes to generate musical notes across one octave, from C4 to C5.<hr>
##  Project Overview

OCTAVA is being developed around an ESP32 microcontroller and an MPR121 capacitive touch sensor. Each of its eight touch pads corresponds to a different musical note.

When a user touches a pad, the sensor detects the change in capacitance and communicates the input to the ESP32. The microcontroller then generates the corresponding frequency through a passive piezo buzzer.
##  Key Features

-  8 capacitive touch pads
-  One-octave range
-  Real-time touch detection
-  Frequency-based sound generation.
-  ESP32-based control.
-  Compact enclosure.
-  USB-powered operation.
  ##  Working Principle

-  The user touches one of the eight copper electrodes.
-  The MPR121 detects the change in capacitance.
-  Touch information is transmitted to the ESP32 through I2C communication.
-  The ESP32 identifies the corresponding input channel.
-  The appropriate musical frequency is generated.
-  The passive buzzer produces the corresponding note.
  ##  Software and Programming
-  Development environment: Arduino IDE
-  Programming language: C++
-  Microcontroller platform: ESP32
- Planned software functionality:
  
  --  Initialise communication with the MPR121 sensor.
  
  --  Read the eight capacitive touch inputs.
  
  --  Map each input to its corresponding musical frequency.
  
  --  Generate sound using the ESP32.
  
  --  Handle touch release and prevent unwanted repeated triggering.
  ##  Mechanical Design

The enclosure is being developed using Onshape CAD.

Current design specifications:
-  Overall length: 30 cm
-  Overall width: 9 cm
-  Initial enclosure height: 3 cm
-  Eight rectangular touch-pad positions
-  Rounded external corners
-  Hollow interior for electronic components
-  Planned removable bottom cover
  ##  Motivation

OCTAVA was chosen as a way to explore the intersection of music, electronics, and interactive design. The project provides an opportunity to understand capacitive sensing, microcontroller programming, I2C communication, and frequency generation while developing a physical device.The intention is to build something that is not only technically functional but also approachable, creative, and enjoyable to interact with.
