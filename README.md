# Cahier des charges Gants 

## Objectif General
- Contrôle de robot
    - Mouvement
        - Mecanique
        - " peau artificiel "
    - Contraction Muscle
    - Orientation de la main
    - Contact des doigts
    - Haptic feedback (potentiometre)
## Pour qui ?
Doit pouvoir être utilisé par une personne sans handicape 

## Présentation du projet
Objectif général : Contrôler un robot avec un gant 
Objectifs spécifiques :
- Feedback
- Réception des signaux musculaires 
- Retour sur l’orientation - position du robot
- Piloter la main avec le gant ou avoir des actions spécifiques pour chaque mouvement fait avec le gant. 
    
## Description des besoin
Besoins fonctionnels :  
- feedback réception des signaux musculaires 
- retour sur l’orientation 
- position du robot 
- piloter la main avec le gant ou avoir des actions spécifiques pour chaque mouvement fait avec le gant. 
                        
Besoins non fonctionnels : ergonomie, sécurité 

## Contraintes
Contraintes techniques : ROS, Python, C, Arduino IDE, Velostat

Contraintes budgétaires : 

Contraintes temporelles : Janvier 2024.

## Spécifications détaillées
Architecture : décrivez la structure générale du projet.

Interfaces : Cube IDE, VS Code, ROS

Bases de données : décrivez les besoins en matière de stockage et de gestion des données.

## Critères d'acceptation
- Énumérez les conditions qui doivent être remplies pour que le projet soit considéré comme réussi :
- Avoir un gant fonctionnel et ergonomique
- Acquérir des signaux en fonctions de différentes actions de la main ( mouvement des doigts, contraction des muscles, orientation de la main…)
- Avoir une communication stable 

## Liste des capteurs
- Electromyogram :
    - https://www.gotronic.fr/art-capteur-emg-sen0240-27861.htm
    - https://eu.robotshop.com/fr/products/electromyography-emg-sensor
- Gyroscope, accélerometre, magnétomètre, capteur d'orientation : BNO055, to capture hand rotation
- Velostat(artificial skin): to capture pressure, twist
- Pressure sensor: to capture the contact between two fingers
  https://www.gotronic.fr/art-capteur-de-force-fsr01-11552.htm
- Potentiometer: to capture finger bending
- https://www.youtube.com/watch?v=xNSRmXKSI_4
- https://fr.farnell.com/adafruit-industries/1361/accessory-type-conductive-sheet/dp/2419170?gclid=CjwKCAjwsKqoBhBPEiwALrrqiDeGaSW_4uc-rm59poSZfxalWY5j2dFrcLATg-_UMGxAqV16yRr28hoCB38QAvD_BwE&mckv=_dc|pcrid||plid||kword||match||slid||product|2419170|pgrid||ptaid||&CMP=KNC-GFR-GEN-SHOPPING-Catch-All-Geo-Split-Control-12-July-23&gross_price=true

Pourquoi celui la ? 

Pour mettre une image : 
<img src="docs/name.png " alt="name" width="200"/>
