# TSOC_GROVEY_FOUR


The **TSOC_GROVEY_FOUR** allows you to connect [thingSoC](http://thingsoc.github.io/), [Mikrobus](http://www.mikroe.com/mikrobus/), 
and/or [Grove System](http://www.seeedstudio.com/blog/2016/03/09/tutorial-intro-to-grove-connectors-for-arduinoraspberry-pi-projects/) 
Modules all at the same time, either standalone, or with any Processor or Radio module.
This gives you maximum flexiblity for parts selection and reuse. 

The **TSOC_GROVEY_FOUR** uses a Cypress Semiconductor PsoC4, a CY8C4245PVI-482 model in a 28 pin TSSOP package, for easy hand soldering.

The thingSoC "Grovey Series" was designed as "Everyday Electronics", a no-frills, low cost, approach to modular embedded product design.
thingSoC boards are similar in size to most break-out-boards (BOBs), but feature a standardized stacking pinout, as well as an I2C metadata store (EEPROM)
to indicate what peripherals are installed.

[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/product/TSOC_GROVEY_FOUR.png?raw=true)TSOC_GROVEY_FOUR](https://github.com/thingSoC/TSOC_GROVEY_FOUR)


**thingSoC Reference Designs** are example thingSoC implementations that implement
various reference and testing circuits for demonstrating the use of the thingSoC libraries.
These reference designs can serve as starting templates for user designs.

---------------------------------------

## TSOC_GROVEY_FOUR Grove Application Pictures

Add the thingSoC GROVEY_WIFI for wireless measurement and control. This example uses a knob (potentiometer) for input, a water level sensor, a buzzer,  and a pump.
If the system detects water in the basement, it can sound the buzzer and start the pump (as an example...) 


[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/product/TSOC_GROVEY_FOUR_moist_wifi.png?raw=true)*TSOC_GROVEY_FOUR*](https://github.com/thingSoC/TSOC_GROVEY_FOUR)

Or use a soil moisture sensor to control when your plants get watered. Add an OLED display to get you measusements.

[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/product/TSOC_GROVEY_FOUR_watering.png?raw=true)*TSOC_GROVEY_FOUR*](https://github.com/thingSoC/TSOC_GROVEY_FOUR)

---------------------------------------

## TSOC_GROVEY_FOUR Mikrobus "Click" Application Pictures

The **TSOC_GROVEY_FOUR** is also compatibile with most [Mikrobus](http://www.mikroe.com/mikrobus/) peripherals.

[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/product/TSOC_GROVEY_FOUR_with_Click.png?raw=true)*TSOC_GROVEY_FOUR*](https://github.com/thingSoC/TSOC_GROVEY_FOUR)


---------------------------------------

## TSOC_GROVEY_FOUR Arduino Sketch Examples

Under the "examples" directory are several Arduino IDE examples for using the TSOC_GROVEY_FOUR board with Arduino IDE.
Using the Arduino "Wire" library for I2C communications, it is simple to control the TSOC_GROVEY_FOUR

```c
 
 coming...
 
 
```

---------------------------------------
## TSOC_GROVEY_FOUR Programming

You can reprogram the board using any Grove UART adapter :

In order to reprogram the Cypress PSoC4 device, you will need to download and install the PSoC Creator tool, which includes a serial bootloader host application.

Select Tools -> Bootloader Host 

Then select the hex (cyacd) file that you wish to program, and the COM: port of your device. Proess the "Upload" button to reflash teh device.

[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/product/TSOC_GROVEY_FOUR_bootloader.png?raw=true)PSoC Creator Bootloader Host](https://github.com/thingSoC/TSOC_GROVEY_FOUR)


---------------------------------------
## Other Applications

The TSOC_GROVEY_FOUR can also drive other devices, such as Servos, Motors, Relays and more.


---------------------------------------

## TSOC_GROVEY_FOUR Status <a name="TSOC_GROVEY_FOUR_status"/>

**09/02/2016:** 
Revision 1.0 - Initial Layout 


---------------------------------------
## TSOC_GROVEY_FOUR Model Images


[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/TSOC_GROVEY_FOUR_top.png?raw=true)TSOC_GROVEY_FOUR](https://github.com/thingSoC/TSOC_GROVEY_FOUR)


[![thingSoC TSOC_GROVEY_FOUR](https://raw.githubusercontent.com/thingSoC/TSOC_GROVEY_FOUR/master/TSOC_GROVEY_FOUR/images/TSOC_GROVEY_FOUR_bot.png?raw=true)TSOC_GROVEY_FOUR](https://github.com/thingSoC/TSOC_GROVEY_FOUR)


---------------------------------------

## TSOC_GROVEY_FOUR Documentation Index <a name="TSOC_GROVEY_FOUR_documentation_index"/>

[TSOC_GROVEY_FOUR Project](http://thingsoc.github.io/projects/TSOC_GROVEY_FOUR.html)

[TSOC_GROVEY_FOUR Hardware](https://github.com/thingSoC/TSOC_GROVEY_FOUR/tree/master/TSOC_GROVEY_FOUR/hardware)


---------------------------------------

## thingSoC Documentation Index <a name="thingSoC_documentation_index"/>

[thingSoC Organization Website](http://thingSoC.github.io)

[thingSoC FAQ - Frequently Asked Questions](http://thingsoc.github.io/support/faq.html)

---------------------------------------

[![thingSoC](http://thingsoc.github.io/img/projects/thingSoC/thingSoC_thumb.png?raw=true) 
*thingSoC*](http://thingsoc.github.io)
