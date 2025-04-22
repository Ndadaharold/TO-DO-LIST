Voici une documentation complète pour créer une To-Do List inspirée d’iOS (design élégant et minimaliste),en HTML, CSS et JavaScript, avec les étapes pour :
	1.	Développer la To-Do List
	2.	La publier sur GitHub avec GitHub Pages

⸻

1. Projet : To-Do List iOS Style – Objectif

But de l’application

Créer une liste de tâches où l’utilisateur peut :
	•	Ajouter une tâche
	•	Supprimer une tâche
	•	Marquer une tâche comme terminée
	•	Sauvegarder les tâches localement (localStorage)
	•	Avoir une interface inspirée d’iOS (design simple, propre, responsive)

⸻

2. Structure du projet

Fichiers à créer
	•	index.html → structure HTML
	•	style.css → design visuel (iOS style)
	•	script.js → logique de l’application

⸻

3. Fonctionnalités principales

HTML
	•	Champ de saisie (input) pour entrer une tâche
	•	Bouton pour ajouter une tâche
	•	Liste des tâches (ul ou div)
	•	Option pour supprimer ou cocher une tâche

⸻

CSS (style iOS)
	•	Design propre, sobre (blanc, gris clair, bleu iOS)
	•	Boutons arrondis, effets d’ombre doux
	•	Texte lisible avec belle typographie
	•	Responsive : s’adapte aux écrans mobiles

⸻

JavaScript (logique)
	•	Ajouter une tâche dans la liste
	•	Cocher une tâche (et l’afficher comme terminée)
	•	Supprimer une tâche
	•	Sauvegarder la liste dans le navigateur (localStorage)
	•	Charger automatiquement la liste sauvegardée au démarrage

⸻

4. Fonctionnalités supplémentaires (optionnelles)
	•	Mode sombre
	•	Animation lors de l’ajout/suppression
	•	Tri automatique (tâches faites en bas)
	•	Édition d’une tâche existante
	•	Drag and drop pour réorganiser les tâches

⸻

5. Publier la To-Do List sur GitHub

Étape 1 : Créer un dépôt sur GitHub
	•	Va sur https://github.com
	•	Clique sur “New repository”
	•	Nom : todo-ios
	•	Coche “Add README” (facultatif)
	•	Crée le dépôt

⸻

Étape 2 : Préparer les fichiers localement
	•	Place index.html, style.css et script.js dans un même dossier
	•	Teste le projet dans ton navigateur

⸻

Étape 3 : Pousser le projet sur GitHub

Avec GitHub Desktop
	•	Ouvre GitHub Desktop
	•	“Add local repository” > sélectionne ton dossier
	•	Clique sur “Publish repository”

Avec Git en ligne de commande

cd ton-dossier
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/ton-nom/todo-ios.git
git push -u origin main



⸻

Étape 4 : Activer GitHub Pages
	•	Va dans ton dépôt GitHub > Settings > Pages
	•	Source : choisis main branch, dossier / (root)
	•	Clique sur Save

GitHub va te donner un lien du style :

https://ton-nom.github.io/todo-ios/



⸻

6. Astuce design iOS
	•	Utilise la police -apple-system pour un rendu natif
	•	Utilise des couleurs comme : #f9f9f9, #007AFF (bleu iOS), #1c1c1e
	•	Ajoute des transitions douces avec transition: all 0.3s ease;
	•	Ajoute une ombre subtile aux cartes/tâches

⸻

Souhaites-tu maintenant que je t’écrive le code complet pour cette To-Do List iOS ?
