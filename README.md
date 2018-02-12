# Temp-Sensor
A temperature and humidity sensor with io.adafruit.com integration


## Setting Up

1. Plug in usb to power. After plugging it in it should start blinking orange.

2. On your phone/computer, connect to **TemperatureSetupWifi**. 
  A website should automatically popup.
  If nothing pops up. Open a web browser and in the search bar type http://192.168.4.1/

3. In the popup window tap/click **Configure Wifi**, than select your wifi network and enter the password.
  It will than try to connect to that network.
  Upon a successful connection it will light up green.
  If it continues to flash Orange go to Step 2.
  
## Troubleshooting

Below is a table showing the different LED states, there meaning and solution.

LED Colour | Meaning | Solution
Solid Green | Everything is working | n/a
Flashing Orange | Wifi connection mode | Refer to **Setting Up**
Flashing Red | Broken Connection | Unplug and replug the device from the wall. If this error persists call the email iliffe.harry@gmail.com or contact the phone number on the bottom of the box
Solid Orange | Broken Wifi Connection | The device will reset on its own and begin the setup process. Refer to Setting Up.
