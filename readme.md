GPS Logger
----------

Log speed/altitude/gps coordinate in a .csv file (DAYHOURMINUTESSECOND.csv)   
You can reuse theses values in any spreedsheet software (LibreOffice/Excel...)   
or you can convert .csv to a gpx with http://www.gpsies.com/convert.do   

## Buzzer sound
* Heavy sound : GPS/SD card fatal error
* Soft repetitive sound : GPS is calibrating
* Melody : GPS is online
* Soft and short sound : GPS coordinates saved to sd  

## Components:
  * Ublox GPS module (or compatible with tinygps++)
  * Micro SD to SD card Adapter
  * A buzzer
  * An Arduino Pro Mini 3V
  * Batteries

##  Tools:
 * ftdi 3V/5V programmer

## Wiring:
![Wiring GPS](https://github.com/pigetArduino/gpsLogger/blob/master/doc/gpsLogger_wiring.png)
*  SD card 
*  1 --> X
*  2 --> 12
*  3 --> GND
*  4 --> 13
*  5 --> VCC
*  6 --> GND
*  7 --> 11
*  8 --> 10 (Chip select)

*  GPS
*  RX --> 2
*  TX --> 3
*  VCC --> VCC
*  GND --> GND

## Libraries
  * TinyGPS++ library
  * LowPower library

## 3D models
Design in progress, components will not fit without modification
* Author : Olivier Sarrailh   
https://github.com/pigetArduino/gpsLogger/blob/master/3D/5x7iTOP.stl   
https://github.com/pigetArduino/gpsLogger/blob/master/3D/5x7iBASE.stl   



