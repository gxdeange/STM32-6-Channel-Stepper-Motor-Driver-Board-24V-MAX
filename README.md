# STM32 4-Channel Stepper Motor Driver Board @24V MAX With RC Filter Inputs (6 X GPIO's)

STM32F401RCT6 based Stepper Motor Driver capable of running at 24V MAX.

This board is designed for experimental or low current robotics with a max current drive of ~800mA.

Features include:

* Reverse Polarity Protection (with LED indicator)
* Adjustable current setting via VREF potentiometer)
* 14 X GPIO solder pads (can use standard 2.54mm Dupont Header pins)
* 6 of the GPIO solder pads with R/C input filtering (PC3, PC2, PC1, PC0, PA1, PB9)
* USB Mini Connector
* Small Form Factor (Approx 36mm X 64mm)

  <img width="388" alt="STM32 6-CHANNEL STEPPER MOTOR DRIVER BOARD" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/89e7c1cc-c3b4-4a7e-bd3b-56b2b17136bd">

# Motor Driver / MCU Pin Mappings

![image](https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/d87c9526-b2da-4b74-9b9c-753a8a06ca2d)


<img width="953" alt="STM32 6-CHANNEL PIN MAPPINGS" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/4922b281-1117-4433-bf1b-916a516e2396">

# PROGRAMMING NOTE

This MCU does not use an external crystal. The Internal RC Clock (HSI) must be initialised at the start of you sketch.
