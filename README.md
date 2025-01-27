# 1. Introduction
Présentation du projet et des outils inclus dans l'architecture SOC : The Hive, Cortex, MISP, et Wazuh.

![Image](https://github.com/user-attachments/assets/a7786a9b-d630-46aa-8f09-10e71ed1779a)

# 2. Contexte de projet
Le contexte de ce projet s’inscrit dans un environnement où la cybersécurité est deve- nue une priorité majeure pour les organisations, en raison de la multiplication des menaces informatiques et de la complexité croissante des cyberattaques. Face à ces défis, les entre- prises doivent adopter des solutions de surveillance et de réponse aux incidents capables de détecter rapidement les menaces, de les analyser en profondeur, et de réagir efficacement pour limiter leur impact.
Dans ce cadre, ce projet vise à mettre en place une solution intégrée et automatisée de gestion des incidents de sécurité, en s’appuyant sur des outils open-source reconnus pour leur efficacité. Wazuh est déployé comme solution SIEM (Security Information and Event Management) pour la détection en temps réel des anomalies sur le réseau et les terminaux. À cela s’ajoute MISP et Cortex, qui permettent de centraliser et enrichir les renseignements sur les menaces détectées (indicateurs de compromission). The Hive est utilisé pour la gestion structurée des incidents, facilitant l’analyse et la coordination des réponses.
Parallèlement, OPNsense et son plugin Zenarmor assurent une surveillance et un fil- trage rigoureux du trafic réseau, garantissant une protection optimale contre les menaces extérieures. Ce contexte de projet répond à la nécessité de disposer d’une architecture de sécurité complète, capable de fournir une visibilité totale sur les activités réseau et de coordonner une réponse rapide et efficace en cas de cyberattaque.

# 2.1. Système d'exploitation

Ubuntu 22.04 

