# STM32_Nucleo_BTS_MotorDriver
Code for STM32F446RET6 to Control BTS MotorDriver

This project demonstrates how to control a high-power DC motor using the BTS7960 (IBT-2) motor driver with the STM32F446RET6 microcontroller.

The BTS7960 driver allows:

1. High current motor control (up to ~43A)
2. Direction control
3. Speed control using PWM signals

This project uses STM32 timers to generate PWM signals for precise motor control.

Features
1. Bidirectional motor control (Forward / Reverse)
2. PWM-based speed control
3. Efficient hardware timer usage
4. Supports high-current motors
5. Easily extendable for robotics applications 
