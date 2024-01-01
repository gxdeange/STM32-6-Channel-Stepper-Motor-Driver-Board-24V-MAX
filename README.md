# STM32 4-Channel Stepper Motor Driver Board @24V MAX

STM32F401RCT6 based Stepper Motor Driver capable of running at 24V MAX.

This board is designed for experimental or low current robotics with a max current drive of ~800mA.

Features include:

* Reverse Polarity Protection (with LED indicator)
* Adjustable current setting via VREF potentiometer)
* 12 X GPIO solder pads (can use standard 2.54mm Dupont Header pins)
* 4 of the GPIO solder pads with R/C input filtering (PC1, PC0, PA1, PB9)
* USB Mini Connector
* Small Form Factor (Approx 36mm X 64mm)

  <img width="388" alt="STM32 6-CHANNEL STEPPER MOTOR DRIVER BOARD" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/89e7c1cc-c3b4-4a7e-bd3b-56b2b17136bd">

# Motor Driver / MCU Pin Mappings

Motor 1: 
* STEP1 - PA11
* DIR1 - PA10
* EN1 - PA9
  
Motor2:
* STEP2 - PA8
* DIR2 - PC9
* EN2 - PC8
  
Motor 3:
* STEP3 - PC7
* DIR3 - PC6
* EN3 - PB15
  
Motor 4:
* STEP4 - PB14
* DIR4 - PB13
* EN4 - PB12

Motor 5:
* STEP5 - PB10
* DIR5 - PB2
* EN5 - PB1

Motor 6:
* STEP6 - PB0
* DIR6 - PC5
* EN6 -  PC4

<img width="953" alt="STM32 6-CHANNEL PIN MAPPINGS" src="https://github.com/gxdeange/STM32-6-Channel-Stepper-Motor-Driver-Board-24V-MAX/assets/57690555/4922b281-1117-4433-bf1b-916a516e2396">
