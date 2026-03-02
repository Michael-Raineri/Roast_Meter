# Roast Meter
As I went down the coffee and coffee roasting rabbit hole I wanted to have a way of measuring a consistent roast profiles which could be repeated. 

The aim of this was to be able to measure roasts between batches and identify how close each roast. 

This project is based off the Arduino core based roast meter https://github.com/juztins-lab/roast-meter. However, this project will use ESP32 instead of Arduino so having this resource has been helpful https://sites.google.com/view/coffee4randy/projects/roast-meter.
## Usage
For usage and a user guide, review: https://github.com/juztins-lab/roast-meter/wiki/Roast-Meter-User's-Guide#calibration-methods 
## Assembly and development of the roast meter
See Wiki
## Alternative Colorimeter - MyTonino 
The Tonino uses a different sensor to measure the colour of the beans. It uses a TCS3200 sensor which measures RGB instead of the roast meter which using the MAX30101. The Roast meter uses IR sensor to measure the colour of the beans.
Tonino: https://github.com/myTonino
Tonino example: https://www.byleew.nl/coffee/resurrecting-the-tonino-coffee-roast-color-meter/
https://www.byleew.nl/experiment/communicating-roast-color-values/

## Helpful links: 
- DIY Colour Meter [https://www.home-barista.com/roasting/diy-color-meter-t8650](https://www.home-barista.com/roasting/diy-color-meter-t86508.html
- https://artisan-roasterscope.blogspot.com/2023/03/understanding-roast-color.html
- https://www.home-barista.com/roasting/tonino-revisited-t37769.html
## Authors and acknowledgment
This project was based on the work of Juztins-lab: https://github.com/juztins-lab/roast-meter. I also used reviewed work from Randytsuch: https://gitlab.com/randytsuch/roast_meter as  randytsuch uses ESP32 which this project is based on. 

This project was not forked from https://github.com/juztins-lab/roast-meter as this uses a Different hardware was used: 
1. Different microcontroller (esp32) compared to the Arduino based one that was used by juztins-lab.
2. An alternative OLED display was used
3. Additional hardware was added in the form of adding a rotary encoder

## Challenges and concerns
No access to other coffee colorimeters and the difficulty of measuring colour. There are challenges with finding and accurately measuring Agtron scores.  https://www.home-barista.com/roasting/tonino-revisited-t37769.html#p430477
- I am not as concerned about the accuracy of making sure that the Agtron score is as expected (within reason). I want to be able to make sure the numbers are consistent  between roasts. This will allow for better repeatability when roasting coffee between batches.  

No access to 3D printer
- I aim to work around this buy buying off the shelf components and modifying them to match the needs of the roast meter.
## License
Uses GPL 3.0
