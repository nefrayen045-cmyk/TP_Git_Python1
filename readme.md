Nom du TP : TP1 – Gestion des versions avec Git et GitHub.
Objectif du programme : créer un assistant de révision simple en Python qui permet à l'utilisateur de définir son objectif de révision.
Rôle du fichier main.py : ce fichier contient le programme principal. Il affiche un message de bienvenue, demande le prénom de l'utilisateur, la matière à réviser et la durée de révision en minutes.
2. Évolution du programme
Le fichier main.py a évolué en quatre versions :
V1 : création locale du fichier main.py avec un premier message de bienvenue.
V2 : ajout de la saisie du prénom de l'utilisateur, puis premier envoi vers GitHub avec git push.
V3 : ajout de la matière à réviser sur GitHub, puis récupération de cette version sur le PC avec git pull.
V4 : ajout de la durée de révision sur le PC, puis envoi de cette nouvelle version sur GitHub avec git push.
3. Utilisation du programme dans VS Code
Outils nécessaires
Visual Studio Code (VS Code).
Python installé sur le PC.
Git installé sur le PC.
Un compte GitHub.
Étapes pour lancer le programme
Ouvrir Visual Studio Code.
Ouvrir le dossier du projet TP_Git_Python1.
Ouvrir le fichier main.py.
Cliquer sur le bouton Run Python File.
Le programme s'exécute dans le terminal intégré de VS Code.
Informations demandées à l'utilisateur
Le programme demande successivement :
Le prénom de l'utilisateur.
La matière qu'il souhaite réviser.
La durée de révision en minutes.
À la fin, il affiche un message de bienvenue et un résumé de l'objectif de révision.
4. Commandes Git utilisées pendant le TP1
git init : initialise un dépôt Git local dans le dossier du projet.
git add : prépare les modifications pour les enregistrer.
git commit : enregistre les modifications dans l'historique du projet.
git push : envoie les versions enregistrées du PC vers GitHub.
git pull : récupère les modifications de GitHub vers le PC.