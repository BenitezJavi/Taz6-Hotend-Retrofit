# Taz6-Hotend-Retrofit
The whole goal of this documentation is to write notes about the process of installing an E3D V6 hotend an existing TAZ6 single toolhead.

Useful Links:

[Rambo Board Schematic](https://download.lulzbot.com/TAZ/6.03/production_parts/electronics/TAZ6_Wiring.pdf)

[E3D V6 3mm HotEnd](https://e3d-online.com/products/v6-3mm-all-metal-hotend?_pos=1&_sid=9686feb59&_ss=r&variant=54890198172028)

[E3D V6 Hotend SpecSheet](https://e3d-online.zendesk.com/hc/en-us/article_attachments/360016249998)

[Molex Male Pins for Extruder Harness](https://www.digikey.com/en/products/detail/molex/0016020107/467790?s=N4IgTCBcDaIAxwIwDY5iXA7CAugXyA)

[Replacement HeatSink Fan for E3D V6 HotEnd](https://www.amazon.com/dp/B0DJQW5S3Z?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1)

[Marlin Firmware Github](https://github.com/MarlinFirmware/Marlin)

[Original TAZ 6 Firmware](https://download.lulzbot.com/TAZ/6.0/software/2016Q2/Marlin/)

- Buying the correct hotend.

  The TAZ 6 requires a toolhead that receives an 24V input, otherwise the voltage needs to be reduced to not damage the hotend. The design chosen for the retrofit is a 24V V6 Bowden Drive Pre-Assembled.

- Custom Parts

  Both fan ducts on the TAZ6 were too short so new ducts were designed. The same is true for the heatsink fan due to the body style of the hotend. The original design called for a hexagon body style that is no longer produced.

- New Parts

  Something to note is that the original fan is a 5V fan while the one provided with the new hotend is a 12V fan. This required that a new fan be purchased that could produce the same amouny of airflow as the one required by the design for the E3D V6 hotend (Testing is still in progress). 

- Firmware Changes

  If you do want to use this new hotend, you will have to create a custom firmware for the printer. All of the needed changes are within the hotend specsheet. 
