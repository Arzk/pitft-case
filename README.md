# pitft-case
Raspberry Pi case with 3,5" PiTFT and CD drive

Hardware inside:
- Raspberry Pi 3 Model B
- WittyPi: http://www.uugear.com/witty-pi-realtime-clock-power-management-for-raspberry-pi/
- PiFi DAC+ v2.0: https://www.itead.cc/hifi-dac-for-raspberry-pi.html
- PiTFT+ 3,5": https://www.adafruit.com/product/2441
- Any laptop CD drive, slot-loader looks cooler
- Button adapter (PiFi IR receiver takes one of the pins, so soldered only 5 buttons: http://frederickvandenbosch.be/?p=2462)


Misc stuff (ebay examples of similar items):
- 40-pin male-female flat cable for connecting the display ( https://www.modmypi.com/raspberry-pi/gpio-and-breadboarding/40-pin-ribbon-cables/40-pin-gpio-male-to-female-ribbon-cable-150mm-(gertboard) )
- 2,1mm x 5,5mm power jack ( https://www.ebay.co.uk/itm/132546759735 )
- USB panel mount female connector (solder male USB plugs to this https://www.ebay.co.uk/itm/112528529024 )
- RJ45 panel mount extender ( https://www.ebay.co.uk/itm/232946761250 )
- USB to SATA adapter (solder a new connector, draw additional 5V power from wall jack: https://www.ebay.co.uk/itm/292763327008 )
- 12mm power button ( https://www.ebay.co.uk/itm/202386970703 )
- A quality 5V power supply with 2,1x5,5mm connector
- Some small connector cables: ( https://www.ebay.co.uk/itm/232485892646 )

Soldering required:
- A new 40-pin header for the PiFi DAC+ - The original one can't be extended anymore and we need a GPIO display
- IR receiver off from the PiFi and attached to an extension cable - I mounted a PC fan header on board for easy removal
- Fixes for the PiFi to make its power delivery work at all, see: http://www.runeaudio.com/forum/p1fi-dac-i2s-random-audio-clicks-solved-read-t3534.html
- Button adapter to the GPIO extender cable
- Power switch off the WittyPi, attach a cable to the 12mm power switch
- USB extender and SATA adapter male connectors, as mentioned earlier
