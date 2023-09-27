# EVE_2023-2024_Project

# Lunettes pour personnes atteintes de cécité 

# I Introduction
**Objectif du projet** : Réalisation de lunettes pour aveugle ( Création depuis le début de ces lunettes ) en utilisant des capteurs. 

**Problématique** : Comment aider les personnes devenues malvoyantes à appréhender de nouveau l'environnement?

**Equipe** : 

Thomas PHAM : Responsable Livrable 

Meryem TURHAN : Responsable Software 

Manon COTTAR : Chef de projet

Valentin GU-LU : Responsable Hardware 

**Contexte et Définition du projet**

L'objectif de notre projet est de concevoir des lunettes technologiques innovantes spécialement destinées aux personnes aveugles, avec pour mission de faciliter leur navigation au quotidien. Ces lunettes seront équipées de capteurs avancés pour détecter les obstacles, de systèmes de vision par ordinateur pour reconnaître les éléments environnants, et d'une assistance audio pour fournir des informations en temps réel à l'utilisateur. En combinant la technologie électronique et informatique, notre objectif ultime est d'aider les personnes malvoyantes à réhappréander leur environnement et améliorer leur autonomie, leur sécurité et leur qualité de vie. 

Utiliser de l’IA pour le capteur d’obstacle, traitement d’image pour qu’ils reconnaissent les obstacles de la vie courante.
Création d’une PCB pour l’alimentation de capteurs et de la STM32
Relier la commande vocale détection d’images avec distance

	
# II Capteurs
## Détection d’obstacles
Trottoirs, passages piétons, humains, escaliers, panneaux, arbres, voitures

Introduire de l’IA en énonçant l’objet touché (identification de produits)
## Communication
Voix, Applications, Information GPS.

Reconnaissances de visages

Lecture des panneaux ( dans les transports en commun )

Reconnaissance vocale (activation de la commande vocale)

## Intégration d’un GPS
AirTag, localisation en extérieur
## Luminosité
Capteur de lumière (les aveugles deviennent photo phobiques)

Option données cardiaques

## Capteur de rythme cardiaque


# III Système Acquisition
## Carte STM32
Si possible avec un écran pour afficher les images ou les obstacles ou bien les couleurs pour le recensement de données (pour nous)


# IV Traitement du signal
IA : Voix  et Image ( obstacle )

Voix : Edge Impulse : création d’échantillons de données vocales

Image.. 

Géolocalisation / Antenne 


**Liste des composants:**
GPS / Gyroscope

Micro / Haut-parleur au-dessus des oreilles

Caméras de petite taille sur la longueur / Capteurs ultrasons

Capteurs luminosité (verres polarisants)

**Exigences:**

L’utilisateur doit pouvoir:

- activer la détection vocale (“push to talk”) pour choisir les différentes fonctionnalités

- effectuer un itinéraire de façon autonome 

- hauts parleurs au niveau des oreilles sans obstruer l’ouïe de l’utilisateur

- communication vocale de l’appareil

- pas trop lourdes

- confortables

- reconnaître la voix de l’utilisateur

- mesurer la distance de l’obstacle en face en temps réel

- IA: panneaux/trottoirs/passage piéton/voiture/escalier/humains/voitures

- mesurer la distance de l’obstacle en face en temps réel

**Liens et idées pour les différents capteurs**
 - Capteur cardiaque (capteur)
         - evolution du rythme


 - Ultrasons (capteur)
	- Emetteur / Récepteur
   	- Pour voir le “danger” imminent
	- Sonar https://www.gotronic.fr/art-lv-maxsonar-ez0-11547.htm#complte_desc
	- https://www.gotronic.fr/art-emetteur-a-ultrasons-tr4010t-18335.htm#complte_desc
	- https://www.gotronic.fr/art-recepteur-a-ultrasons-tr4010r-18336.htm



 - Caméras (capteur intégré)
	- Voir plus loin que les ultrasons, mais pas de distance 
	- Event based camera dvs 128
	- Caméra “normale” : Carte Add-On, Module caméra Pcam 5C, Capteur de couleur OV5640, 5 MP, pour cartes de dév. FPGA


 - Lumière

Les données reçues de l’intensité lumineuse de la caméra pourront nous servir pour élargir le projet vers une polarisation de verres adaptable à l’individu car chaque malvoyant a une sensibilité qui lui est propre et plus ou moins accrue

 - GPS (capteur intégré)
	- Lien téléphone casque ? données GPS du téléphone ? Traceur GPS téléphone
	- Connexion WIFi / Bluetooth
	- “Ok Google ouvre Google Maps”. 


 - Micro
	- Micro cravate : Rode SmartLavPlus , Meilleur micro cravate : lequel choisir en 2023 ? (meilleurtest.fr)
	- Rode SmartLav+ – Thomann France
	- Micro casque
	- Air Pods, écouteurs bluetooth
	- Capteur micro : Capteur du Son avec Arduino – Microphone – Cours | Projets Divers (electronique-mixte.fr)

 - Rythme cardiaque


 - sites à check :
   
prophesee
gensight
pixiumvision
inilabs/inivation

# Commande 
## RS

Camera Module Caméra Raspberry Pi, CSI-2, 1 canal, **lien code commande 913-2664**

## Farnell


## Gotronic 

Carte Raspberry Pi 4 B - 8 GB code commande : **36838** https://www.gotronic.fr/art-carte-raspberry-pi-4-b-8-gb-31984.htm








