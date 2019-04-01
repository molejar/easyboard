# EBN: OLED Shield

#### General Info

* **Base On:** 128x32 pixels OLED Display
* **Other:** Button and Speaker


### Blocking Diagram

<p align="center">
  <img src="images/EBN_OLED_V01_BD.png" alt="EBN-OLED Block Diagram"/>
</p>


### PinOut

<p align="center">
  <img src="images/EBN_OLED_V01_I2C_PinOut.png" alt="EBN-OLED I2C PinOut" width="500"/>
  <img src="images/EBN_OLED_V01_SPI_PinOut.png" alt="EBN-OLED SPI PinOut" width="500"/>
</p>


#### Connection with Core Shield

| EBN-OLED-I2C    | EBN-KL27Z4  |
| --------------- | ----------- |
| BUTTON          | PTA4        |
| SPKR            | PTC1        |
| I2C-SDA         | PTB1        |
| I2C-SCL         | PTB0        |
| OLED-RST        | PTE0        |

| EBN-OLED-SPI    | EBN-KL27Z4  |
| --------------- | ----------- |
| BUTTON          | PTA4        |
| SPKR            | PTC1        |
| SPI-MISO        | PTC7        |
| SPI-MOSI        | PTC6        |
| SPI-SCKL        | PTC5        |
| OLED-DC         | PTC2        |
| OLED-RST        | PTE0        |

### Design files

 * [Schematic & PCB (Eagle 7.x)](eagle)