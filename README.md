pour run du projet il faut ce mettre dans le dossier du projet et puis executer:
nuts ntexup show .
noté bien qu'il faut installé  nuts et ntexup
# Smart Cart Project - Presentation

Cette présentation couvre le projet de prototype **Smart Cart**, une solution simulée de chariots autonomes intelligents pour l'optimisation logistique.

Elle est construite avec **ntexup**, un générateur de présentations déclaratif à base de texte.

## Contenu

- **Introduction** : Contexte et objectifs du projet.
- **Microservices** : Architecture (Quarkus, Kafka, Kong).
- **Infrastructure** : Déploiement Kubernetes (K8s).
- **Monitoring** : Prometheus et Grafana.
- **Conclusion** : Bilan et perspectives.

## Prérequis

Assurez-vous d'avoir installé **nuts** et **ntexup** :

```bash
# Installer nuts
curl -s https://thevpc.net/nuts/install-latest.sh | bash

# Installer ntexup
nuts -y install ntexup
```

## Lancer la Présentation

Pour visualiser la présentation en mode interactif (Swing) :

```bash
nuts ntexup show .
```

## Générer le PDF

Pour générer la version PDF de la présentation :

```bash
nuts ntexup generate .
```

Le fichier PDF sera généré dans le dossier courant ou dans un sous-dossier de sortie (ex: `target` ou `dist`).

## Structure du Projet

- `main.ntx` : Point d'entrée principal.
- `01-styles/` : Définitions des thèmes et composants (miniPage, etc.).
- `02-pages/` : Contenu des slides divisé par modules.

## Auteurs

- Ahlem Kaabi
- Mohanned Ben Abdelhafith
- Rim Elourajini
- Sarrah Chakroun
- Yassmin Elayeb
