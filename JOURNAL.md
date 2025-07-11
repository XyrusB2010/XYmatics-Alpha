---
title: "XYmatics Alpha"
author: "Xyrus Babao"
description: "3-in-1 Tool Changer CNC Machine"
created_at: "2025-06-16"
---

# 16/06/2025 - The beginning
I started off by making a quick 10-minute brainstorm of how XYmatics-Alpha will work. Linear rails for Y-Axis, Linear rods for X-Axis, Prusa-XL-like toolchanging system. After spending 45 minutes in Fusion 360, I have designed the base frame. It consists of 4020 aluminium extrusions for the top and bottom, and 2020 for the vertical extrusions. There are also a few corner brackets, but I will add more next time.

<img src="https://github.com/user-attachments/assets/f471dd1e-6da2-4cfe-bfb2-e57255d5f948" alt="XYmatics Alpha frame" width="500">

Total time - 55 minutes

# 17/06/2025 - Complete frame and start motion system
Finishing up the work from yesterday, I finished designing the brackets for the frame. These add extra reinforcement in the corners for stability. I began work on the motion system, and implemented the AB stepper motors and their mounts. The stepper motors I have used are two NEMA 17 42x34mms. I will aim to add more of the pulleys and idlers tomorrow.

<img src="https://github.com/user-attachments/assets/82a96d6b-bcf7-41ed-a0e9-53ae02d7fd7f" alt="AB stepper motor" width="500">

Total time - 1 hour 45 minutes

# 26/06/2025 - Motion System Part Two
Excuse for the long wait. I did not have as much time to work on this project compared to last week. I have begun modelling the Linear Rails for the Y-Axis, as well as the carriage for mounting the X-Axis Linear Rods. For the Linear Rails, I have used two 430mm MGN12H rails, one on each side. The X-Axis uses two 8mm Linear Rods, which are secured with 4 M4 screws each. I just need to complete the rest of the pulley system for the XY axis to be finished.

<img src="https://github.com/user-attachments/assets/73a9b624-32b2-4d86-8c79-f5206dabbdc6" alt="XY carriage bracket" width="500">

Total time - 2 hours

# 7/07/2025 - Begin electronics and PCB
Today I decided to temporarily put the 3D design aside temporarily and start working on the electronics. For the PCB design, I am using KiCad with a few components imported from <a href="https://snapeda.com/">SnapEDA.</a> I have named XYmatics-Alpha's mainboard E64 (Engine64). It utilises a CM4/CM5 compute module running Klipper firmware to control the main MCU - an STM32F407. Like most Klipper systems, the compute module does not directly control the motors, sensors, etc, and instead outputs commands via USB to the STM32. I have completed desigining the Compute module side, and just need to complete the STM32 and other components. Below is an image of the CM4 schematic.

<img src="https://github.com/user-attachments/assets/16006f6d-e0e2-467e-8219-a059112f625b" alt="XYmatics-E64 CM4 schematic" width="500">

(Excuse the resolution, you can view a PDF of the schematic <a href="https://github.com/XyrusB2010/XYmatics-Alpha/blob/main/PCB/xymatics-e64.pdf">here.</a>)

Total time - 45 minutes
