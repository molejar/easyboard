# EBN: Smart Battery Shield

#### General Info

* **Charger:** TI bq24075 (1A Li-Ion linear charger with power path)
* **BMS:** TI bq27421-G1 (System-Side Impedance Track Fuel Gauge With Integrated Sense Resistor)
* **DC/DC:** TI TPS6300x (High Efficient Single Inductor Buck-Boost Converter 3.3V/1A)


### Blocking Diagram

<p align="center">
  <img src="images/EBN_SBAT_V01_BD.png" alt="EBN-SBAT Block Diagram"/>
</p>


### PinOut

<p align="center">
  <img src="images/EBN_SBAT_V01_PinOut.png" alt="EBN-SBAT PinOut" width="500"/>
</p>


#### Connection with Core Shield

| EBN-SBAT        | EBN-KL27Z4  |
| --------------- | ----------- |
| I2C-SDA         | PTB1        |
| I2C-SCL         | PTB0        |
| MODE            | PTC2        |


### Design files

 * [Schematic & PCB (Eagle 7.x)](eagle)


### OSH Park

<a href="https://oshpark.com/shared_projects/VrX0jsdq"><img src="https://oshpark.com/assets/badge-5b7ec47045b78aef6eb9d83b3bac6b1920de805e9a0c227658eac6e19a045b9c.png" alt="Order from OSH Park"></img></a>