# FPGABoard
This is a FPGA (Field Programmable Array) board that consists of a iCE40 FPGA, FT2232 Programmer, and IO options. It has 2 PMOD headers (12 pin and 6 pin) along with an programming header and 26 pin header for anything else you want to plug in. On the board it has 3 LEDs and 3 buttons, allowing you to interact with the board without plugging anything in

# Why I Made It
I have a decent amount of experience working with microcontrollers but never any with FPGAs. I also want to learn Verilog which allows you to design circuits using programming, so a FPGA board would be perfect for this use case allowing me to experiment with Verilog and designing circuits while also learning something new.

# Pictures

![alt text](FPGABOARD.png)
![alt text](image.png)
![alt text](image2.png)

# BOM

|Name                  |Purpose                        |Quantity|Total Cost (USD)|Link                                                                                                                       |Distributor|
|----------------------|-------------------------------|--------|----------------|---------------------------------------------------------------------------------------------------------------------------|-----------|
|6 Pin Header          |6 Pin PMOD Connector           |        |0.39            |https://www.lcsc.com/product-detail/C2935996.html                                                                          |LCSC       |
|2x6 Pin Header        |12 Pin PMOD Connector          |        |0.74            |https://www.lcsc.com/product-detail/C47326634.html                                                                         |LCSC       |
|2x4 Pin Header        |Programing Header              |        |0.52            |https://www.lcsc.com/product-detail/C7494793.html                                                                          |LCSC       |
|2x13 Pin Female Header|IO Pin Header                  |        |0.32            |https://www.lcsc.com/product-detail/C19268725.html                                                                         |LCSC       |
|Ferrite Bead 60@100   |Power Filtering                |        |0.23            |https://www.lcsc.com/product-detail/C307775.html                                                                           |LCSC       |
|Solder Paste          |Solder Components              |1       |4.79            |https://www.aliexpress.us/item/3256809026940371.html                                                                       |Aliexpress |
|4.7u Capacitors       |Decoupling Capacitors          |        |0.10            |                                                                                                                           |LCSC       |
|12k Resistor          |Resistor                       |        |0.11            |                                                                                                                           |LCSC       |
|2.2k Resistor         |Resistor                       |        |0.13            |                                                                                                                           |LCSC       |
|IS62LV256AL-45ULI     |SRAM for Chip                  |1       |1.84            |https://www.digikey.com/short/70fz9v3d                                                                                     |Digikey    |
|12Mhz Oscillator      |Clock for FPGA and FT2232      |2       |0.87            |https://www.lcsc.com/product-detail/C37635404.html                                                                         |LCSC       |
|93LC66BT-I/OT         |FT2232 Memory                  |        |0.35            |https://www.digikey.com/short/q0nprmz5                                                                                     |Digikey    |
|AP2127K-1.2           |1.2V Voltage Regulator         |        |0.59            |https://www.lcsc.com/product-detail/C151376.html                                                                           |LCSC       |
|AP2127K-3.3           |3.3V Voltage Regulator         |        |0.53            |https://www.lcsc.com/product-detail/C156285.html                                                                           |LCSC       |
|FT2232HPQ             |USB to SPI Chip for programming|1       |8.88            |https://www.lcsc.com/product-detail/C3228692.html                                                                          |LCSC       |
|iCE40HX1K-VQ100       |Main FPGA Chip                 |1       |12.17           |https://www.lcsc.com/product-detail/C1519043.html?lcsc_vid=EwVcU11XEQBXAlBTE1QPVFVTRFELUl0HFAIPUlVTQQMxVlNRQVldU1dRQVFaVDtW|LCSC       |
|Stencil               |For PCB assembly               |1       |7.11            |                                                                                                                           |JLCPCB     |
|PCB                   |PCB for Build                  |5       |12.00           |                                                                                                                           |JLCPCB     |
