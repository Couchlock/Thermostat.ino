# Thermostat.ino
This is a work in progress arduino based thermostat with the intention of becoming a smart thermostat.
The code is based off using a tmp36 temperature sensor. Data sheet can be found online. I decided to use software conversion for Farenheit readings at this point. I've also found that using the 3.3v as Vi gives a more accurate reading than 5.5v.

currently only displays through the serial monitor (I need to get a display!)
long-press left button to turn thermostat on/off
left/right presses then adjust temperature down/up

Work in progress.
Still to come:
  Menu/Settings
  Multiple Sensors(multiple temp,humidity,CO, etc)
