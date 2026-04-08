# Aziz's Pizza 

📄 README — Aziz’s Pizza (VR Game)
🎯 Résumé en une phrase

Un jeu VR où tu livres des pizzas en moto dans une ville et dois compléter un maximum de livraisons avant la nuit.

🧾 Description du projet

Aziz’s Pizza est un jeu en réalité virtuelle développé avec Unity.

Le joueur incarne un livreur de pizza qui commence sa journée dans une pizzeria.
Il doit prendre des pizzas, monter sur sa moto et les livrer à différents clients dans une île.

Chaque livraison doit être faite dans un temps limité.
Si le joueur dépasse le temps → aucun point n’est gagné.

La journée se termine lorsque la nuit tombe, et le score final est affiché.

🎮 Mécaniques de jeu
🔧 Mécaniques principales
Conduite de moto en VR
Interaction avec les mains (grab pizza)
Système de livraison
Timer par livraison ⏱️
Cycle jour → nuit 🌅🌙
Système de score
⏱️ Timer de livraison
Chaque commande a son propre timer
Si le joueur livre à temps → points gagnés
Si le timer atteint 0 → 0 points
Bonus si livré rapidement
🎓 Tutoriel (écran de départ)

Un écran tutoriel explique au joueur :

Comment prendre une pizza
Comment conduire la moto
Comment livrer
Comment fonctionne le timer
🔁 Boucle de jeu
Start game
Tutoriel (optionnel)
Spawn à la pizzeria
Prendre une pizza
Monter sur la moto
Conduire vers le client
Livrer avant la fin du timer
Gagner (ou non) des points
Recommencer une livraison
Fin quand la nuit arrive
🗺️ Environnement (Île)

Le jeu se déroule sur une île pour éviter les routes inutiles.

Zones :
🍕 Pizzeria (départ)
🏘️ Quartiers résidentiels (clients)
🌴 Zones secondaires (raccourcis)
🌊 Bord de mer
🌉 Ponts et routes principales
🎨 Moodboard
Visuel
Style low poly
Couleurs vives
Ville stylisée/cartoon
Son
Musique arcade
Sons de moto
Sons de livraison
⚙️ Schéma de programmation (logique)

Start
→ Tutoriel
→ Spawn joueur
→ Prendre pizza
→ Monter moto
→ Aller à destination
→ Timer actif

SI livré à temps
→ + points

SINON
→ 0 point

→ Nouvelle livraison

SI nuit
→ Fin du jeu + score final

🧩 Assets à créer
Moto
Pizza (objet interactif)
Pizzeria
Maisons
Routes
Personnages (clients)
UI (score, timer, tutoriel)
📋 Tâches (exemple)
Gameplay
Système de déplacement VR
Système de livraison
Timer
Score
Environnement
Map île
Routes
Bâtiments
UI
Écran tutoriel
Score
Timer
Audio
Sons
Musique
🏁 Objectif du jeu

Faire le plus de livraisons possible avant la nuit et obtenir le meilleur score.
