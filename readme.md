1. Présentation du TP

Nom du TP : TP1 – Gestion des versions avec Git et GitHub.

Objectif du programme :

Créer un assistant de révision simple en Python qui permet à l'utilisateur de définir son objectif de révision.

Rôle du fichier main.py :

Ce fichier contient le programme principal. Il permet de :

Afficher un message de bienvenue.

Demander le prénom de l'utilisateur.

Demander la matière à réviser.

Demander la durée de révision en minutes.

Afficher un résumé de l'objectif de révision.

2. Évolution du programme

Le fichier main.py a évolué en quatre versions :

V1 : Création locale du fichier main.py avec un premier message de bienvenue.

V2 : Ajout de la saisie du prénom de l'utilisateur, puis premier envoi vers GitHub avec git push.

V3 : Ajout de la matière à réviser sur GitHub, puis récupération de cette version sur le PC avec git pull.

V4 : Ajout de la durée de révision sur le PC, puis envoi de cette nouvelle version sur GitHub avec git push.

3. Utilisation du programme dans VS Code

Outils nécessaires

Visual Studio Code (VS Code).

Python installé sur le PC.

Git installé sur le PC.

Un compte GitHub.

Étapes pour lancer le programme sans saisir de commande

Ouvrir Visual Studio Code.

Ouvrir le dossier du projet TP_Git_Python1.

Ouvrir le fichier main.py.

Cliquer sur le bouton ▶ Run Python File en haut à droite de l'éditeur.

Si nécessaire, choisir l'interpréteur Python.

Le programme s'exécute dans le terminal intégré de VS Code.

Informations demandées à l'utilisateur

Le programme demande successivement :

Le prénom de l'utilisateur.

La matière qu'il souhaite réviser.

La durée de révision en minutes.

À la fin, il affiche un message de bienvenue et un résumé de l'objectif de révision.

4. Commandes Git utilisées pendant le TP1

Commande

Explication

git init

Initialise un dépôt Git local dans le dossier du projet.

git add

Prépare les modifications pour les enregistrer.

git commit

Enregistre les modifications dans l'historique du projet.

git push

Envoie les versions enregistrées du PC vers GitHub.

git pull

Récupère les modifications de GitHub vers le PC.

5. Conclusion

Ce TP m'a permis de découvrir la gestion des versions avec Git et GitHub, de comprendre l'évolution d'un programme Python en plusieurs versions et d'apprendre à synchroniser un projet entre mon ordinateur et GitHub.