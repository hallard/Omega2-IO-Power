Power FTDI SPI and I2C Shield for Onion Omega2
==============================================

<img src="https://raw.githubusercontent.com/OnionIoT/Onion-Docs/master/Omega2/Documentation/Hardware-Overview/img/Omega-2-Pinout-Diagram.png" alt="Omega2" width="50%" height="50%"> 

This shield is used to power and to expose [Onion Omega2](https://onion.io/) Serial/SPI/I2C bus, it has just few minimal features such as wiring and 3V3 regulator. 
- I2C Pullups placement
- I2C 4 pins connector
- SPI 6 pins connector
- Placement for FTDI connectors SMD or PTH (Serial0) 
- USB Mini connector to power the whole thing and Omega2

You can find more information on WeMos on their [site](https://onion.io/), it's really well [documented](https://docs.onion.io/omega2-docs/index.html) here and pinout is [here](https://docs.onion.io/omega2-docs/omega2.html#the-pins)

**Waiting for V1.0 Boards from [PCBs.io](https://PCBs.io/share/4976j). I did not fully tested them yet, I will update ASAP. Use at your own risks**

Detailed Description
====================

Very simple, you plug your Omega2 on the shield, then you're ready to go. But pay attention, this board run at 3.3V.

You have 2 options to power board :

- Mini USB connector 5V goes to 3V3 regulator and you're ready to go
- Close JP1 and use **Only 3V3** FTDI connector that already have regulator on board. FTDI connector will then power the shield and Omega2 without any Mini USB plugged.

Take care if you are powered with mini USB and you want to use FTDI cable to connect to console, use a 3V3 FTDI cable and do not close JP1 connector

Here are example of FTDI 3V3 connector that should work 

- SparkFun Beefy 3 [FTDI Basic Breakout](https://www.sparkfun.com/products/13746) up to 600mA out at 3V3
- RocketScream [USB/Serial with CH340](http://www.rocketscream.com/blog/product/ch340g-usb-serial-adapter/) up to 100mA out at 3V3
- EZSBC [Usb To Serial UART 5V or 3V3](https://www.tindie.com/products/ddebeer/usb-to-serial--uart-5v-or-33v-695-/) up to 250mA out at 3V3

### Schematic
![schematic](https://raw.githubusercontent.com/hallard/Omega2-IO-Power/master/pictures/Omega2-IO-Power-sch.png)  

### Boards 

**Top**
![Top](https://raw.githubusercontent.com/hallard/Omega2-IO-Power/master/pictures/Omega2-IO-Power-top.jpg)  

**Bottom**
![Bottom](https://raw.githubusercontent.com/hallard/Omega2-IO-Power/master/pictures/Omega2-IO-Power-bot.jpg)  

You can order the PCB of this board at [PCBs.io](https://PCBs.io/share/4976j). PCBs.io give me reward when you order my designed boards from their site. This is pretty good, because I can use these rewards to create and design new boards and order boards for a discounted price and share new boards. So if you don't care about PCB manufacturer please use PCBs.io.

### Assembled boards (V1.0)

TBD

##License

<img alt="Creative Commons Attribution-NonCommercial 4.0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png">   
This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)    
If you want to do commercial stuff with this project, please contact [CH2i company](http://ch2i.eu) so we can organize an simple agreement.

##Misc
See news and other projects on my [blog](https://hallard.me)
 