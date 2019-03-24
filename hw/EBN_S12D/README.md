# EBN: Sensor Shield

#### General Info

* **Base On:** 128x32 pixels OLED Display
* **Other:** Button and Speaker

#### Block Diagram of Sensor Shield

<p align="center">
  <img src="images/EBN_S12D_V02_BD.png" alt="EBN-S12D Block Diagram"/>
</p>

#### PinOut of Sensor Shield

<p align="center">
  <img src="images/EBN_S12D_V02_PinOut.png" alt="EBN-S12D PinOut" width="500"/>
</p>

#### Connection of Sensor Shield with Core Shield

| EBN-S12D        | EBN-KL27Z4  |
| --------------- | ----------- |
| I2C-SDA         | PTB1        |
| I2C-SCL         | PTB0        |
| IRQ (20 / 17)   | PTC1 / PTE0 |
