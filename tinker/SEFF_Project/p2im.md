https://www.usenix.org/conference/usenixsecurity20/presentation/feng
* peripherals : SPI, USART, I2C, GPIO, ADC, DC, Timer, PWM![[Screenshot 2024-10-24 at 11.34.02 AM.png]]


* We conducted all experiments on a moderate-spec
computer with a dual-core Intel® Core™ i5-7260U CPU @
2.20GHz, 8 GB of RAM, and Ubuntu 16.04
* We identified the 8 most popular MCU
peripherals—implemented as on-chip peripherals—by
analyzing the entire MCU product line (1686 MCU parts)
offered by Microchip Technology, a top global MCU vendor.
We selected these peripherals (the left column in Table 1)
for our unit tests. We also selected 3 widely used **MCU
OS/system libraries, (NuttX, RIOT, and Arduino) and 3 target
MCU SoCs (STM32 F103RB, NXP MK64FN1M0VLL12,
and Atmel SAM3X8E)**. 
![[Screenshot 2024-10-24 at 3.23.33 PM.png]]

1. Self-balancing robot source code. https://github.com/mbocaneg/Inverted-Pendulum-Robot .
2. PLC : Controllino maxi modbus library. https://github.com/CONTROLLINO-PLC/CONTROLLINO_Library/tree/master/MAXI .
and  Controllino maxi plc. https://controllino.biz/controllino/maxi .

3. Gateway : Firmata library. https://github.com/firmata/arduino. (Gateway)
4. Drone : Quad-copter drone source code. https://github.com/heethesh/eYSIP-2017_Control_and_Algorithms_development_for_Quadcopter .  and  Drona Aviation. Pluto drone. https://www.dronaaviation.com/  2017.
5. CNC : Cnc grbl stm32f4 source code. https://github.com/deadsy/grbl_stm32f4 and Building the krmx01 cnc. http://www.kronosrobotics.com/krmx01/
6. Reflow oven : Reflow oven source code. https://github.com/rocketscream/Reflow-Oven-Controller and Tiny reflow controller v2. https://www.rocketscream.com/blog/product/tiny-reflow-controller-v2
7. Console : Riot os console. https://github.com/RIOT-OS/RIOT/tree/master/examples/default
8. Steering control : Steering control source code. https://github.com/jabelone/car-controller
9. Soldering Iron : Soldering iron source code. https://github.com/Ralim/ts100 and Sainsmart toolpac pro32. https://www.amazon.com/SainSmart-ToolPAC-Soldering-Heating-Intelligent/dp/B01FFPE0EG
10. Heat Press : proprietary (same as PLC 2nd link)