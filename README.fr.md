# Projet Vortex-01

## Objectif
Créez un satellite à faible coût, appelé Vortex-01, qui fournit un réseau Wi-Fi gratuit via une connexion satellite. Le satellite sera équipé de capteurs, de systèmes d'alimentation et d'un système de sécurité à distance.

## Spécifications des satellites

- **Nom :** Vortex-01
- **Fonction :** Fournir une connexion Internet gratuite via satellite

### Composants principaux

- **Raspberry Pi 4B :** Ordinateur central pour le traitement et le contrôle des données.

### Capteurs

- **Capteur de pression atmosphérique :** **BMP180** - Capteur accessible pour mesurer la pression et l'altitude.
- **Capteur d'accélération (IMU) :** **MPU-6050** - Combine un accéléromètre et un gyroscope, idéal pour surveiller le mouvement et l'orientation.
- **Capteur de rayonnement :** **RADFET** - En option, pour surveiller l'exposition aux rayonnements de manière économique.

### Antennes

- **Antenne dipôle large bande :** Antenne dipôle faite maison pour une communication RF à faible coût.
- **Antenne Yagi :** Antenne Yagi DIY pour améliorer la direction et le gain de la communication, construite avec des matériaux abordables.

### Systèmes énergétiques

- **Panneaux solaires :** **Panneaux polycristallins** - Économiques et suffisants pour générer de l'énergie dans de petits projets spatiaux.
- **Contrôleur de charge solaire :** **Contrôleur PWM** - Solution abordable pour la gestion de base de la charge des panneaux solaires.
- **Batterie :** Batteries de voiture ou **batteries 18650 reconditionnées** - Alternative bon marché pour le stockage d'énergie, utilisant des batteries réutilisées provenant d'anciens ordinateurs portables.

### Contrôle thermique

- **Couvertures thermiques :** **Couvertures Mylar** - Solution bon marché pour l'isolation thermique, utilisant des matériaux légers et réfléchissants.

### Système de propulsion

- **Propulseurs à gaz froid :** Propulseurs DIY utilisant des bouteilles de CO2 de paintball, des valves de dégagement, pour des manœuvres sûres et économiques.

### Systèmes de navigation et de contrôle

- **GPS :** **Module GPS NEO-6M** - Module GPS abordable adapté à la navigation de base et au suivi de position.

## Système de sécurité

- **Fonction :** Désactivez le système de carburant et activez un parachute géant en cas de panne ou de danger.
- **Mécanisme :** Activé à distance pour assurer la sécurité en cas de panne critique.

##Logiciel

- **Développement :** Utilisation d'Ubuntu, Python, C, Assembly et Java
- **Communication :** Via des signaux RF

### Caractéristiques

- Code pour la gestion des capteurs
- Code de communication et de transmission de données
- Code pour le système de sécurité

## Conception de satellites

- **Structure:**
 - **Format :** Compact et léger, utilisant de l'acier et de l'aluminium
 - **Panneaux solaires :** Pour la production d'énergie
 - **Batterie :** Batterie de voiture ou batteries 18650 pour le stockage d'énergie

## Lancement

- **Préparation :** Assemblage sur le site de lancement
- **Carburant :** De l'essence sera ajoutée sur le site de lancement
- **Procédures de sécurité :** Distance de sécurité et activation à distance du système de sécurité

### Planification du lancement

- **Phase d'assemblage :** Assemblez le satellite et ajoutez du carburant sur le site de lancement
- **Activation à distance :** Système de sécurité activé à distance pour couper le carburant et ouvrir le parachute en cas d'urgence

## Dépôts

- **Modèle 3D :** [GitHub - Modèle Vortex-01](https://github.com/Vortex-01/Model)
- **Code source :** [GitHub - Code source du Vortex-01](https://github.com/Vortex-01/Source-Code)

## Objectif de reconnaissance

- **Objectif :** Utiliser le projet Vortex-01 comme vitrine pour démontrer des compétences techniques et innovantes, dans le but d'attirer l'attention d'institutions telles que le MIT.
