# Salvage Scanner

*...for when you are too lazy to look for a datasheet*

This Arduino sketch allows you to measure many electronic components (you have just salvaged from e-waste) with the goal of identifying them, checking basic functionality and determining the pinout without googling the part number (if any; if readable; if PDF available online).

## Compatible components
- PNP, NPN transistors
- N or P Channel MOSFETs
- Diodes, Zener diodes
- Resistors
- Capacitors
- Inductors
- Thyristors, Triacs
- IGBTs

## Other features
- generating PWM signals 100Hz..25kHz (uses timer1)
- measuring frequency up to 4 kHz (uses timer1/comparator)

## What is different from mTester, AVR Transistortester and ArduTester?
- no need for custom board like AVR Transistortester
- only supports Nokia 3310 or 5110 displays (everybody and their dog had one of these phones back in the day)
- code is simpler and easier to contribute to unlike ArduTester
- is DIY unlike mTester

## Origins
Original Source from: http://www.mikrocontroller.net/articles/AVR-Transistortester

Original Software: by Karl-Heinz Kuebbeler (kh_kuebbeler@web.de)

The Ardutester software is based on porting by Markus Reschke (madires@theca-tabellaria.de)

Schematic & Home Page: http://www.pighixxx.com/lavori/ardutester/ (dead link or suspicious)

Arduino version: PighiXXX (info@pighixxx.com); PaoloP (http://www.arduino.cc/forum/index.php?action=profile;u=58300)

Villem Vannas (https://github.com/willux6, https://github.com/willux6/ArduProj)

Tapia Favio (https://github.com/kr4fty, https://github.com/kr4fty/ArduProj)

Influenced by ArduTester V1.13 by plouc68000 (https://create.arduino.cc/projecthub/plouc68000/ardutester-v1-13-the-arduino-uno-transistor-tester-dbafb4)

More related links (not in English): https://www.elforum.info/topic/29508-super-multi-tester/?do=findComment&comment=1683652

And now it's my turn to contribute.