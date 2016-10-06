GPS Logger
----------

[Version française disponible](https://github.com/pigetArduino/gpsLogger/blob/master/readme.fr.md)

Log speed/altitude/gps coordinate in a universal .csv file on an SD card every 15 seconds (DAYHOURMINUTESSECOND.csv)   
[Example file](https://github.com/pigetArduino/gpsLogger/blob/master/doc/example.csv)

# Compatibility
* Libre office calc / Excel
* Gpsies.com (you can convert it in gpx) 
* Viking : https://sourceforge.net/projects/viking/

# Buzzer sound
* Heavy sound : GPS/SD card fatal error
* Soft repetitive sound : GPS is calibrating (can take up to 5 minutes)
* Melody : GPS is online
* Soft and short sound : GPS coordinates saved to sd  

# Components:
  * Ublox GPS module (or compatible with tinygps++)
  * Micro SD to SD card Adapter
  * 2Go (or less) Micro SD card 
  * A buzzer
  * An Arduino Pro Mini 3V
  * Batteries   

Estimate cost : 15.50€   

More details on [bill_of_materials.md](https://github.com/pigetArduino/gpsLogger/blob/master/doc/bill_of_materials.md)

#  Tools:
 * ftdi 3V/5V programmer

# Wiring:
![Wiring GPS](https://github.com/pigetArduino/gpsLogger/blob/master/doc/gpsLogger_wiring.png)
#  SD card 
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
#  GPS
```
RX --> 2
TX --> 3

```
# Buzzer
```
+ ---> 9
```

# Libraries
```
TinyGPS++ library
```

# 3D models
[See 3D models](https://github.com/pigetArduino/gpsLogger/blob/master/3D/)
```
Tested on Ultimaker 2 GO with PLA
To improve solidity print A in solid
A Infill: Solid
B Infill: Dense
```
* Author : Olivier Sarrailh   
 
