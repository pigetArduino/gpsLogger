GPS Logger
----------

![Wiring GPS](https://github.com/pigetArduino/gpsLogger/raw/master/doc/gpslogger.jpg)

[Version française / French version](https://github.com/pigetArduino/gpsLogger/blob/master/readme.fr.md)

Record gps coordinate in a csv file on an SD card every 15 seconds (DAYHOURMINUTESSECOND.csv)   
[Example file](https://github.com/pigetArduino/gpsLogger/blob/master/doc/example.csv)

# Download link
http://gps.madnerd.org

# How to convert the track

## Gpsies.com
* Go to http://gpsies.com
* Click on Create a track
* Import the csv file
* Or click on convert to get a gpx track file

## Viking
* Download it here : https://sourceforge.net/projects/viking/
* Go to file
* Retrieve
* Import file with GPS Babel
* Choose (at the end of the list) : universal csv with field structure in first line
* Add a map in layer
* Use Open Street Map (Mapnick) or Bing Aerial

# Buzzer
The buzzer will tell you if there is any issues with the gps/sdcard
* Heavy sound : Wiring issues or no microsd 
* Soft repetitive sound : GPS is calibrating (can take up to 5 minutes)
* Melody : GPS is online
* Soft and short sound : GPS coordinates saved to sd  

# Components
Use theses keyword to find the components
* Gps module ublox Aircraft model mwc: 8€
* Micro sd card 2go : 4€
* Batteries holder 4AAA on/off : 1€ 
* Arduino mini pro 3.3V : 1,50€
* Passive buzzer 3v:  1€  
* Total : 15.50€   

# Tools
* FTDI basic breakout usb ttl 3.3 : 6.23€
* Cable 30awg  8-color: 5.37€
 
# Software needed:
  * Arduino (Programmation): http://arduino.madnerd.org
  * Cura (3D printing): https://ultimaker.com/en/products/cura-software

# 3D models
[See 3D models](https://github.com/pigetArduino/gpsLogger/blob/master/3D/)
```
Tested on Ultimaker 2 GO with PLA
To improve solidity print A in solid
A Infill: Solid
B Infill: Light
```
* Author : Olivier Sarrailh   

# Wiring:
![Wiring GPS](https://github.com/pigetArduino/gpsLogger/blob/master/doc/gpsLogger_wiring.png)
##  SD card 
```
1 --> X
2 --> 12
3 --> GND
4 --> 13
5 --> VCC
6 --> GND
7 --> 11
8 --> 10 (Chip select)
```
##  GPS
```
RX --> 2
TX --> 3

```
## Buzzer
```
+ ---> 9
```

## Libraries
TinyGPS++ library : https://github.com/mikalhart/TinyGPSPlus
