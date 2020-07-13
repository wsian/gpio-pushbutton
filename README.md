# gpio-pushbutton
How to use GPIO for push buttons on orange pi plus 2e

1. install wiringOP
https://github.com/orangepi-xunlong/wiringOP

2. compiling:
gcc -lwiringPi -lwiringPiDev -o pushbuttons pushbuttons.c

3. use external pull up resistor (4.7k-10k)

4. Source : https://forum.armbian.com/topic/7067-orange-pi-pc-how-to-use-gpio-for-push-buttons-tutorial/ 
