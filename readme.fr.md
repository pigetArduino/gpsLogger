Traceur GPS (GPS Logger) 
----------

Enregistrer la vitesse/l'altitude/les coordonées GPS dans un fichier universal .csv sur une carte SD toutes les 15 seconds   
(JOURHEUREMINUTESSECONDES.CSV)
[Fichier d'example](https://github.com/pigetArduino/gpsLogger/blob/master/doc/example.csv)

# Compatibilité
* Libre office calc / Excel
* http://www.gpsies.com (Vous pouvez convertir le fichier en gpx) 
* Viking : https://sourceforge.net/projects/viking/

# Sound du Buzzer
* Son fort: Erreur de câblage ou carte SD absente
* Son calme, court et répétitif : Le GPS est en calibration (cela peut prendre jusqu'à 5 minutes)
* Mélodie : Le GPS est fonctionnel
* Son calme, court , toutes les 15 secondes:  Coordonées sauvegardées  

# Composants:
  * Module GPS Ublox (ou compatible avec tinygps++)
  * Adapteur Micro SD vers carte SD
  * Carte MicroSD de 2Go (ou moins) 
  * Un buzzer
  * Un Arduino Pro Mini 3V
  * Un boitier de piles AAA / Piles AAA   

Coût estimée: 15.50€   

Plus de détails ici: [bill_of_materials.md](https://github.com/pigetArduino/gpsLogger/blob/master/doc/bill_of_materials.md)

#  Outils:
 * Programmeur ftdi 3V/5V

# Câblage:
![Wiring GPS](https://github.com/pigetArduino/gpsLogger/blob/master/doc/gpsLogger_wiring.png)
#  Carte SD 
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

# Bibliothèques
```
TinyGPS++ library
```

# Modèles 3D
[Voir les modèles 3D](https://github.com/pigetArduino/gpsLogger/blob/master/3D/)
```
Testé sur une ultimaker 2 GO avec du PLA
Pour améliorer la solidité imprimer la partie A en solide.
A Infill: Solid
B Infill: Dense
```
* Auteur : Olivier Sarrailh   
 
