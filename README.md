# CampusConnect

## Présentation et objectifs
**CampusConnect** est une plateforme collaborative destinée aux étudiants et aux associations d'un campus universitaire. Elle permet de centraliser la vie étudiante en offrant aux organisateurs un espace pour publier leurs événements et aux étudiants un moyen simple de les découvrir et de s'y inscrire.

## État réel du projet
**Phase actuelle : Conception et spécification fonctionnelle / UML.**  
L'application n'est pas encore développée ni déployée en production. Les travaux actuels portent sur l'organisation du Product Backlog, la planification du Sprint 1, la rédaction des spécifications et la modélisation UML.

## Fonctionnalités envisagées
* **Consulter et rechercher :** Afficher les événements à venir et filtrer par mot-clé (`KAN-16`, `KAN-17`).
* **S'inscrire :** Réserver une place en ligne dans la limite de la jauge disponible et recevoir une confirmation (`KAN-18`, `KAN-19`).
* **Gérer les événements :** Publier un événement, modifier ses détails, consulter la liste des inscrits et annuler un événement (`KAN-20`, `KAN-21`, `KAN-22`, `KAN-23`).

## Outils utilisés
* **Jira Software :** Suivi du Product Backlog et pilotage du Sprint 1 ([Tableau Jira](https://campusconnect-efrei.atlassian.net/jira/software/projects/KAN/boards/1)).
* **Confluence :** Documentation fonctionnelle, technique et suivi Agile ([Espace Confluence](https://campusconnect-efrei.atlassian.net/wiki/spaces/C/overview)).
* **GitHub & PlantUML :** Suivi documentaire (`SPRINT_NOTES.md`) et sources des diagrammes UML.

## Liens vers les diagrammes UML et la documentation
* [Espace Confluence — CampusConnect](https://campusconnect-efrei.atlassian.net/wiki/spaces/C/overview)
* Sources UML dans le dossier `/uml` :
  * [Diagramme de cas d'utilisation](uml/usecase_campusconnect.puml)
  * [Diagramme de classes](uml/classes_campusconnect.puml)
  * [Diagramme de séquence (Inscription)](uml/sequence_inscription.puml)

## Consignes de contribution
1. Rattacher chaque contribution à une clé de ticket Jira existante (ex. `KAN-18`).
2. Travailler sur une branche dédiée incluant la clé du ticket (ex. `docs/KAN-18-spec`).
3. Ouvrir une Pull Request descriptive pour relecture par un coéquipier avant fusion sur `main`.
