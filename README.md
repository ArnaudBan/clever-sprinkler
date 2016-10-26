# Clever sprinkler
A clever sprinkler i'm having fun building

## Concepte

* Toutes les minutes un capteur d'humidité planté dans la terre du pot envoie le taux d'humidité à ThingSpeak
* Tous les jours a 12h on se renseigne sur l'heure du couché du soleil
* A l'heure du couché du soleil, on prend le taux d'humidité et si il est trop faible, on déclenche l'arroseur (on envoie aussi l'info a ThingSpeak )
* Un capteur dans la cuve envoie tout les demi heure le taux de remplissage de la cuve a ThingSpeak
* On envoie une alerte par mail quand la cuve est presque vide
* Une interface web permet d'afficher toutes les données de ThingSpeak

## Envoie de mail

Pour l'envoie de mail [Pushingbox](https://www.pushingbox.com/) semble une bonne alternative.

Resource :
* http://dbrenk.blogspot.fr/2015/03/connecting-thingspeakcom-to.html

## Prototype

### 26 octobre 2016
J'allume un aspirateur en USB en focntion du taux d'humidité. Pour le branchement du l'aspirateur, j'ai eu l'aide d'Alain et de cette page : https://learn.adafruit.com/adafruit-arduino-lesson-13-dc-motors/transistors

## photos

![First proto photo](/img/IMG_1120.JPG?raw=true "First proto photo")
