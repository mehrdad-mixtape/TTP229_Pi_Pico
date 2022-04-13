# TTP229_Pi_Pico
Simple code to read keys from TTP229 Touch Keypad! It work so good on raspberry pi pico!
If you want enable 16keyMode, set jumper on pins like this:
![alt text](https://github.com/mehrdad-mixtape/TTP229_Pi_Pico/blob/master/TTP229_16keyMode.jpg)
# This Keypad don't work with I2C!
# scl: Pin = Pin(19, mode=Pin.OUT) -> GP19
# sdo: Pin = Pin(18, mode=Pin.IN, pull=Pin.PULL_UP) -> GP18
![alt text](https://github.com/mehrdad-mixtape/TTP229_Pi_Pico/blob/master/main.png)
