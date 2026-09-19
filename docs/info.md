<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

The Campus Sentinel 2.0 monitors smoke, motion, door, and panic inputs, then uses an FSM to determine the system status and activate the appropriate warning, evacuation, buzzer, and exit-routing outputs.

## How to test

Apply different combinations of Smoke, Motion, Door, Panic, Reset, and Ack inputs in Wokwi and verify that the Safe, Warning, Critical, Evacuate, Buzzer, and Route outputs respond according to the defined conditions.

## External hardware

No external hardware is required because the system can be simulated entirely in Wokwi using virtual switches, LEDs, a buzzer, and a clock generator.
