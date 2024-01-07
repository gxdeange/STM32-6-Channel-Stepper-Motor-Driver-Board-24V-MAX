# STM32 6-Channel Stepper Motor Driver Board @24V MAX With RC Filter Inputs (6 X GPIO's)

STM32F401RCT6 based Stepper Motor Driver capable of running at 24V MAX.

This board is designed for experimental or low current applications with a max current drive of ~800mA.

Features include:

* Reverse Polarity Protection (with LED indicator)
* Adjustable current setting via VREF potentiometer)
* 14 X GPIO solder pads (can use standard 2.54mm Dupont Header pins)
* 6 of the GPIO solder pads with R/C input filtering (PC3, PC2, PC1, PC0, PA1, PB9)
* USB Mini Connector
* MicroStep at 1/8
* **All GPIO Inputs / Outputs are rated at 3.3V**
* Small Form Factor (Approx 36mm X 64mm)

  <img width="388" alt="STM32 6-CHANNEL STEPPER MOTOR DRIVER BOARD" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/89e7c1cc-c3b4-4a7e-bd3b-56b2b17136bd">

# STM32 6-Channel Stepper Motor Driver Board @24V MAX With RC Filter Inputs (6 X GPIO's) with Adjustable Micro Stepping

  <img width="427" alt="STM32F401RCT6 Stepper Driver RC MS" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/c3c18bcc-e2c7-45e8-bfbe-b9e61ec2fc6f">

* M0 and M1 Slide Switches for Adjustable Micro Stepping
* Small Form Factor (Approx 41mm X 64mm)

# STM32 6-Channel Stepper Motor Driver Board @24V MAX With Buffered, Schmitt Trigger Inputs (10 X GPIO's)

* 10 of the GPIO solder pads have buffered Schmitt trigger inputs (PC2, PC3, PC0, PC1, PA1, PB9, PA4, PA12, PB4, PB6)
* Inputs for above 10 GPIO's are pulled High (3.3V via 10K resistor)
* MicroStep at 1/8
* Small Form Factor (Approx 36mm X 64mm)

  <img width="388" alt="STM32F401RCT6 6-Channel Stepper Motor Buffered Driver Board 24V MAx " src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/4112a82d-11dd-40d9-9eb1-6c6bae7ca69a">

# STM32 6-Channel Stepper Motor Driver Board @24V MAX With Buffered, Schmitt Trigger Inputs (10 X GPIO's) with Adjustable Micro Stepping

* M0 and M1 Slide Switches for Adjustable Micro Stepping
* Small Form Factor (Approx 41mm X 64mm)

  <img width="441" alt="STM32F401RCT6 6 Channel Stepper Buffered MS" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/560ba881-4fd3-4571-a874-2339c31aaa5b">
  
![image](https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/7dcd851c-5134-4cc1-b7cb-51486d36d430)

# Motor Driver / MCU Pin Mappings

![image](https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/d87c9526-b2da-4b74-9b9c-753a8a06ca2d)


  <img width="953" alt="STM32 6-CHANNEL PIN MAPPINGS" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/4922b281-1117-4433-bf1b-916a516e2396">

# PROGRAMMING NOTE

This MCU does not use an external crystal. The Internal RC Clock (HSI) must be initialised at the start of your code.
