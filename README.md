# ACESTMPOSE
PCB design and firmware development of a simple MCU board with sensors and peripherals.

## Hardware

The main blocks of the board are:

- Peripherals: USB-C connettors, and 6-pin header for attaching external I2C sensors, SWD header for JTAG programming
- Power Supply: TVS Diode for ESD protection and Buck Converter to step down voltage from 5 to 3.3 volts
- MCU: STM32f042g6 28-pin QFN package
- Sensors: Bosch 6-axis Acc+gyro IMU

![Capture](https://github.com/user-attachments/assets/aa5bfe7a-0dee-4e95-a0d0-b3eea23b26a5)


