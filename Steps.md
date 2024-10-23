ADS1115        Function          Pin No            Function/GPIO
GND            Ground              6                  -GND
VDD          Power Supply          1                  -
SDA            Data bits           3                GPIO 2/ SDA
SCL          Serial clock          5                GPIO 3 / SCL

Enable I2C Interface: sudo  raspi-config
Update: sudo  apt-get update
Upgrade: sudo  apt-get upgrade
Python Module: sudo  apt-get install build-essential python3-dev  python3-smbs git
AdaFruit:  git clone https://github.com/adafruit/Adafruit_Python_ADS1x15.git
CD to AdaFruit: cd Adafruit_Python_ADS1x15
Setup File: sudo  python3  setup.py   install
Matplotlib: sudo apt-get install python3-matplotlib
Run Code: python  oscilloscopeDemo.py
