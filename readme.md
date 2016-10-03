GPS Logger
----------

Log speed/altitude/gps coordinate in a universal .csv file (DAYHOURMINUTESSECOND.csv)   

# Compatibility
* Libre office calc / Excel
* Gpsies.com (you can convert it in gpx) 
* Viking : https://sourceforge.net/projects/viking/

# Buzzer sound
* Heavy sound : GPS/SD card fatal error
* Soft repetitive sound : GPS is calibrating
* Melody : GPS is online
* Soft and short sound : GPS coordinates saved to sd  

# Components:
  * Ublox GPS module (or compatible with tinygps++)
  * Micro SD to SD card Adapter
  * A buzzer
  * An Arduino Pro Mini 3V
  * Batteries

#  Tools:
 * ftdi 3V/5V programmer

# Wiring:
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

* Buzzer
* + ---> 9

# Libraries
  * TinyGPS++ library
  * LowPower library

# 3D models
New design will be upload...
* Author : Olivier Sarrailh   
 
