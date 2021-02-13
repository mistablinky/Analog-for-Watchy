# Analog for Watchy

Analog Watchface for Watchy E-Paper Watch

![Analog for Watchy Light Mode](/images/analog-for-watchy_light.png)
![Analog for Watchy Dark Mode](/images/analog-for-watchy_dark.png)

**Setup**
- Follow the instructions on [https://github.com/sqfmi/Watchy](https://github.com/sqfmi/Watchy) to setup your Arduino IDE for Watchy
- Make sure the RTClib by Adafruit is installed (tested with version 1.12.4)
- Open the ino File with your Arduino IDE and upload to your Watchy
- Enjoy :)

The Watchy time will automatically set to the watchface upload time in case the power has lost. Thats the way I like it. But for sure there is room for improvement, because there seems to be a gap between taking and setting the time (depends on Arduino compilation time, sometimes up to a minute for me).

**Free Culture License**
This work is licensed under a Creative Commons *Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0)*.
Adaptations and commercial use are allowed AS LONG AS OTHERS SHARE ALIKE. [License terms](https://creativecommons.org/licenses/by-sa/4.0/)