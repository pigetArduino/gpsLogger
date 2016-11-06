# Présentation

- Aujourd'hui on va voir un traceur GPS  
- Ce traceur GPS peut être fabriqué pour moins de 20 euros   
- Et il fonctionne vraiment simplement.   
- Il y a un bouton on/off, lorsque l'on appuie sur ON    
- Le gps va s'activer et une fois qu'il aura trouver les satellites
- Il va écrire toutes les 15 secondes sur une carte micro sd, votre position.
- Si vous voulez voir un peu comment ce GPS a été fabriqué.
- J'ai fait une vidéo très rapide où on voit toutes les étapes de fabrication 
de ce gps
- Allons voir un peu les composants à l'intérieur de ce boitier.   

# Composants
- A l'intérieur de notre boitier, 
- on a un arduino mini pro 3V
- Un adaptateur de microsd
- un gps ainsi que son antenne
- Et un buzzer qui va nous permettre de savoir si le gps fonctionne correctement
- Evidemment nous avons aussi un boitier de piles en bas qui va nous permettre d'alimenter notre arduino

Maintenant nous allons voir comment utiliser les données de notre GPS sur le site gpsies.com et directement avec le logiciel viking

# Récupérer le parcours GPS
* Comme exemple, nous allons prendre le fichier qui est fourni avec la documentation

## Editeur de texte
* example.csv, nous allons l'ouvrir avec un éditeur de texte standard
* Comme vous pouvez voir c'est un fichier qui est complètement lisible même avec le programme le plus basique possible
* Qu'est que'on va faire de ce fichier ?

## Gpsies.com
* Le plus simple si vous voulez le convertir où l'afficher c'est d'utiliser le site gpsies.com
* Sur ce site , on peut créer un parcours sur lequel on va importer notre fichier example.csv
* Et voilà! Nous avons notre tracé GPS sur une magnifique carte
* Alors, Si vous voulez juste convertir le fichier de façon à ce qu'il soit lisible par un GPS
* Il faut aller sur convertir, parcourir, ouvrir le fichier de la carte SD de votre GPS
* Convertir , et il vous donnera directement un fichier GPX

### Viking
* Si vous ne voulez pas passer par un site, vous pouvez utiliser le logiciel libre viking
* Pour cela, il faut aller dans fichier, récupérer, import file with gps babel
* Vous ouvrez votre fichier csv de la carte SD du GPSLogger
* Et après vous aller toute en bas à universal csv with field structure in first line
* Et vous faites valider
* Ca fait afficher toutes les points que le gps a récupéré
* Par défaut Viking n'utilise aucune carte
* Nous allons utiliser openstreetmap pour notre carte
* Vous pouvez utiliser d'autres cartes, voir même utiliser des images
* Vue que le logiciel est vraiment malléable là-dessus.
* Une fois que vous aurez télécharger la carte , vous n'aurez plus besoin d'internet normalement
* pour exploiter vos données.
* Reste plus qu'à valider
* Et voilà! Nous avons une jolie carte.

# Fin
* Comme d'habitude les liens sont dans la description
* N'hésitez pas à poster un commentaire si vous avez des questions
* Abonnez vous pour ne pas louper les prochaines vidéos
* La prochaine fois nous verrons comment faire un synthé avec un Raspberry Pi
* Non seulement on va faire un synthé mais aussi une boite à rythme
* Tout ça sans utiliser la moindre soudure
* Et sans passer par le terminal
* Juste en copier des trucs sur une carte SD 
* Et sur une clé USB.
* Allez à la prochaine

# Démonstration



