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
