Traceur GPS (GPS Logger) 
----------

![Wiring GPS](https://github.com/pigetArduino/gpsLogger/raw/master/doc/gpslogger.jpg)

Enregistre les coordonées GPS dans un fichier csv sur une carte micro sd toutes les 15 seconds   
(JOURHEUREMINUTESSECONDES.CSV)
[Fichier d'exemple](https://github.com/pigetArduino/gpsLogger/blob/master/doc/example.csv)

# Télécharger
http://gps.madnerd.org

# Vidéos / Instructables
* Fabrication : https://www.youtube.com/watch?v=jfu29oI2C5M
* Utilisation : https://www.youtube.com/watch?v=2oaBtQ-7Zj4
* Instructables : http://www.instructables.com/id/Simple-GPS-Logger/

# Comment convertir le parcours
## Gpsies.com
* Aller sur http://gpsies.com
* Cliquer sur Créer un parcours
* Importer votre fichier csv
* Ou Cliquer sur convertir pour avoir un fichier gpx

## Viking
* Télécharger Viking ici : https://sourceforge.net/projects/viking/
* Aller sur fichier
* Récupérer
* Import file with GPS Babel
* Choosisez (à la fin de la liste) : Import with gps babel
* Ajouter une map dans couches
* Utilisez Open Street Map (Mapnick) ou Bing Aerial

# Sound du Buzzer
* Son fort: Erreur de câblage ou carte SD absente
* Son calme, court et répétitif : Le GPS est en calibration (cela peut prendre jusqu'à 5 minutes)
* Mélodie : Le GPS est fonctionnel
* Son calme, court , toutes les 15 secondes:  Coordonées sauvegardées  

# Composants
Utilisez ses mots-clés pour chercher les composants:
* Gps module ublox Aircraft model mwc: 8€
* Micro sd card 2go (avec adapteur micro sd): 4€
* Batteries holder 4AAA on/off : 1€ 
* Arduino mini pro 3.3V : 1,50€
* Passive buzzer 3v:  1€  
* Total : 15.50€   

Nous utilisons un adapteur de carte micro sd comme lecteur de carte, vous pouvez évidemment utiliser un module pour lire les cartes microsd à la place.

# Outils
* FTDI basic breakout usb ttl 3.3 : 6.23€
* Cable 30awg  8-color: 5.37€
 

# Logiciels:
  * Arduino (Programmation): http://arduino.madnerd.org
  * Cura (3D printing): https://ultimaker.com/en/products/cura-software

# Modèles 3D
[Voir les modèles 3D](https://github.com/pigetArduino/gpsLogger/blob/master/3D/)
```
Testé sur une ultimaker 2 GO avec du PLA
Pour améliorer la solidité imprimer la partie A en solide.
A Infill: Solid
B Infill: Dense
```
* Auteur : Olivier Sarrailh   
 
# Câblage:
![Wiring GPS](https://github.com/pigetArduino/gpsLogger/blob/master/doc/gpsLogger_wiring.png)
##  Adapteur Carte Micro SD 
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

## Placement des piles
bwh13 sur instructables : Penser à placer le pack de piles au dessous du module GPS, afin de ne pas obstruer l'antenne
```
Nice project.
Moving forward, consider placing your battery pack beneath your GPS module. The antenna works best with an unobstructed view of the sky
```

## Bibliothèques
TinyGPS++ library : https://github.com/mikalhart/TinyGPSPlus
