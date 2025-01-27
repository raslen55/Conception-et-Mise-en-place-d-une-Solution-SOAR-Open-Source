# 1. Introduction
Présentation du projet et des outils inclus dans l'architecture SOC : The Hive, Cortex, MISP, et Wazuh.

![Image](https://github.com/user-attachments/assets/a7786a9b-d630-46aa-8f09-10e71ed1779a)

# 2. Contexte de projet
Le contexte de ce projet s’inscrit dans un environnement où la cybersécurité est deve- nue une priorité majeure pour les organisations, en raison de la multiplication des menaces informatiques et de la complexité croissante des cyberattaques. Face à ces défis, les entre- prises doivent adopter des solutions de surveillance et de réponse aux incidents capables de détecter rapidement les menaces, de les analyser en profondeur, et de réagir efficacement pour limiter leur impact.
Dans ce cadre, ce projet vise à mettre en place une solution intégrée et automatisée de gestion des incidents de sécurité, en s’appuyant sur des outils open-source reconnus pour leur efficacité. Wazuh est déployé comme solution SIEM (Security Information and Event Management) pour la détection en temps réel des anomalies sur le réseau et les terminaux. À cela s’ajoute MISP et Cortex, qui permettent de centraliser et enrichir les renseignements sur les menaces détectées (indicateurs de compromission). The Hive est utilisé pour la gestion structurée des incidents, facilitant l’analyse et la coordination des réponses.
Parallèlement, OPNsense et son plugin Zenarmor assurent une surveillance et un fil- trage rigoureux du trafic réseau, garantissant une protection optimale contre les menaces extérieures. Ce contexte de projet répond à la nécessité de disposer d’une architecture de sécurité complète, capable de fournir une visibilité totale sur les activités réseau et de coordonner une réponse rapide et efficace en cas de cyberattaque.

# 2.1. Système d'exploitation

Ubuntu 22.04 

![Image](https://github.com/user-attachments/assets/e571ac6e-6980-469e-b2c2-a78c1417c6f8)

# 2.2. Outils nécessaires

Docker et Docker Compose installés pour les services SOC.

Accès administrateur à la machine Ubuntu pour l'installation de Wazuh.

![groups](https://github.com/user-attachments/assets/54f816f0-1fcc-46dc-991c-135ac44c93f4)

# 3. Installation des dépendances

# 3.1. Installation de Docker
![Image](https://github.com/user-attachments/assets/667db6cd-ec75-431d-8839-158a9125cf3c)

# 3.2. Installation de Wazuh sur Ubuntu

# Préparation du système

sudo apt update && sudo apt upgrade 

# Installer Wazuh .

curl -sO https://packages.wazuh.com/4.7/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
![Image](https://github.com/user-attachments/assets/0813fb6d-869c-4b40-9427-d829157783c1)

# Verification de fonctionnemennt

![Image](https://github.com/user-attachments/assets/5b4c177e-a505-4bd7-9120-3e3dddab8806) 








