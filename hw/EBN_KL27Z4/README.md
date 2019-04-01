# EBN: KL27Z4 Core Shield

#### General Info

* **MCU:** Freescale MKL27Z256VFM4 in QFN32 package
* **ARM Core:** Cortex-M0+, 50MHz (max)
* **Memory's:** 256kB Flash and 32kB RAM
* **Serial Interfaces:** 1xUSB-Device, 3xUART, 2xSPI, 2xI2C, 1xI2S, ...
* **Other:** 16-bit ADC, 12-bit DAC, RTC, FlexIO (4xIO-Pins)


### Blocking Diagram

<p align="center">
  <img src="images/EBN_CORE_KL27Z4_V04_BD.png" alt="EBN-KL27Z Block Diagram"/>
</p>


### PinOut

<p align="center">
  <img src="images/EBN_CORE_KL27Z4_V05_PinOut.png" alt="EBN-KL27Z PinOut" width="900"/>
</p>


#### Internal Connections

| Name           | Pin    | Description                |
| -------------- | ------ | -------------------------- |
| LED1 (Green)   | VCC    | Power Status LED           |
| LED2 (Red)     | PTA3   | User or Error Status LED   |
| SW1 (Button)   | PTA4   | Enter into Bootloader      |


### Design files

 * [Schematic & PCB (Eagle 7.x)](eagle)


### OSH Park

<a href="https://oshpark.com/shared_projects/JpSgUC9z"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>