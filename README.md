# GameMaster (1.0)
_Par Elodie DUFLAUT_
<hr/>

GameMaster est un ensemble d'outils crées spécifiquement pour aider les games masters (maîtres du jeu) de l'association Groupe Escape à encadrer les joueurs lors d'une partie. 
Ces applications web ne necessitent pas d'Internet pour fonctionner. Elles ont cependant été développées pour un appareil specifique et peuvent par conséquent ne pas fonctionner sur tous les supports.

GameMaster prévois de regrouper un système de caméras, un minuteur et une banque de ressources intéractives répertoriant les indices et les réponses aux énigmes de la salle, le tout accessible depuis un ordinateur portable. Pour l'instant, seul le système de caméra est opérationel; les autres fonctionalités sont en cours de développement.


## Sytème de caméras

### Description matérielle
Le système de caméras comprend deux modules de caméras ESP32 "AI-Thinker", programmables avec l'IDE Arduino et équipées d'objectifs OV2640 & d'antennes WiFi, et un routeur TP-Link TL-WR841N. Chacune des caméra héberge un site web à partir duquel il est possible de voir leur flux vidéo direct et de gerer leurs paramètres vidéo (résolution, colorimétrie, etc.). Ces sites ne sont accessibles que depuis le réseau WiFi du routeur de Groupe Escape, qui n'est pas connecté à Internet, et au sein duquel chaque caméra a une addresse IP réservée. 

Les caméras sont toutes deux alimentées par un cable micro-usb et montées dans un support imprimé, visible et facilement distinguable par les joueurs. Pour les éteindre, il suffit de les débrancher. 

### Comment l'utiliser ?
Tout d'abord, assurez vous que les caméras et le routeur sont bien branchés et alumés. Vous pouvez ensuite acceder au site web:

#### Depuis l'ordinateur portable de Groupe Escape
1. Choisissez l'utilisateur "Game Master" et entrez le mot de passe confidentiel
2. Vérifiez que vous êtes connecté au réseau WiFi "Groupe Escape"
3. Ouvrez Firefox
4. Dans les marques page affichés juste en dessous de la barre de recherche, cliquez sur "Caméra | Salle 1/2"

   Et voilà, vous pouvez maintenant lancer le stream et jouer avec les paramètres.

#### Depuis un autre appareil
1. Connectez-vous au réseau WiFi "Groupe Escape" et entrez le mot de passe
2. Ouvrez votre navigateur et entrez dans la barre de recherche "192.168.0.101" pour la caméra 1 et "192.168.0.102" pour la caméra 2

   Et normalement, vous voilà connecté !


## Me contacter
Mail : elodie.duflaut@efrei.net | Discord : rakkoun | GitHub : El0o
