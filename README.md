🌍 Emoji World – Une aventure interactive IA & Joueurs

Emoji World est un mini-jeu expérimental conçu pour explorer un concept unique : un monde en emojis où l’IA génère dynamiquement des quêtes, des indices, et des interactions entre les joueurs et les PNJ (personnages non-joueurs).

Ce jeu a été développé pour le fun, mais aussi pour tester comment l’intelligence artificielle peut enrichir les mécaniques narratives et la rejouabilité dans un jeu vidéo.

⸻

🎮 Objectif du jeu

Vous incarnez un personnage dans un monde composé de 9 zones colorées (forêt, ville, montagne, océan, désert, etc.). Votre mission : parler aux PNJ, résoudre des énigmes contextuelles et trouver le bon personnage pour accomplir votre mission.

Chaque quête est générée aléatoirement :
	•	L’IA choisit une zone.
	•	Un PNJ y est sélectionné comme cible.
	•	Des indices sont générés par zone et par lieu emblématique pour guider le joueur.
	•	À vous de les interpréter et de partir à l’aventure pour trouver la bonne personne !

⸻

🕹️ Commandes
	•	Flèches directionnelles : déplacer votre personnage dans le monde.
	•	Espace : interagir avec un personnage ou un élément.
	•	M : ouvrir ou fermer la carte du monde.

⸻

📱 Fonctionnalités
	•	Monde composé de 9 zones, chacune avec son propre thème, couleur et ambiance (océan, volcan, université, etc.).
	•	Landmarks et PNJ dynamiques : chaque zone contient des emojis fixes et des PNJ positionnés aléatoirement.
	•	Système de quêtes :
	•	À chaque mission, un PNJ devient la cible à trouver.
	•	Des indices sont générés automatiquement pour orienter le joueur.
	•	Une interaction avec la bonne personne déclenche une récompense 🎉.
	•	Interface légère en React + Canvas pour une expérience fluide, même dans un navigateur.

⸻

🧠 Concept IA & Génération procédurale

Ce projet est avant tout un laboratoire ludique pour expérimenter :
	•	Comment générer dynamiquement des quêtes et des indices selon un contexte aléatoire.
	•	Comment immerger un joueur sans narration linéaire, uniquement via des emojis et des descriptions interprétables.
	•	Comment intégrer des mécanismes de feedback (récompense, interaction, exploration) sans avoir besoin de scénario rigide.

⸻

🛠️ Stack technique
	•	React 18 (via CDN) pour la gestion d’état et de composants.
	•	Canvas HTML5 pour le rendu du monde et des emojis.
	•	JavaScript (Babel standalone) pour maintenir une structure simple, sans transpilation ou bundler.
	•	Génération procédurale : NPCs et missions sont régénérés à chaque partie, les indices sont choisis aléatoirement depuis une base d’énigmes.

⸻

🚀 Lancer le jeu
	1.	Ouvrez le fichier Emoji World Game.html dans un navigateur moderne (Chrome, Firefox, etc.).
	2.	Profitez directement sans installation.
	3.	Optionnel : hébergez-le sur GitHub Pages, Vercel, Netlify ou votre propre serveur.

⸻

💡 Pour aller plus loin

Quelques idées d’évolutions possibles :
	•	Connexion à une IA externe (API GPT) pour générer dynamiquement les quêtes en texte libre.
	•	Ajout d’un inventaire et d’objets à collecter.
	•	Intégration d’un mode multi-joueurs ou de scores partagés.
	•	Sauvegarde de progression dans le LocalStorage.

⸻

🙌 Auteur

Jeu conçu par OdyssAI, dans un esprit d’exploration créative autour des interactions IA / joueur.