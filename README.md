# ACESTMPOSE
PCB design and firmware development of a simple MCU board with sensors and peripherals. This design was completely based on Philip Salmony tutorial you can find [here](https://www.youtube.com/watch?v=gFmm91c_mr8&list=PL3aaAq2OJU5FdyG8e1wjMVJ9t68w8QvJ7&index=8)

## Hardware

The main blocks of the board are:

- Peripherals: USB-C connettors, and 6-pin header for attaching external I2C sensors, SWD header for JTAG programming
- Power Supply: TVS Diode for ESD protection and Buck Converter to step down voltage from 5 to 3.3 volts
- MCU: STM32f042g6 28-pin QFN package
- Sensors: Bosch 6-axis Acc+gyro IMU

![Capture](https://github.com/user-attachments/assets/aa5bfe7a-0dee-4e95-a0d0-b3eea23b26a5)


