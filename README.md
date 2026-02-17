# 🧮 Boulier Chinois - Numération & Entraînement

Une application pédagogique interactive conçue pour l'apprentissage de la numération en classe. Cet outil permet de manipuler un boulier virtuel (Soroban) pour travailler la lecture et l'écriture des nombres de manière ludique et adaptative.

![Version](https://img.shields.io/badge/Version-2025-blue)
![Pédagogie](https://img.shields.io/badge/Pédagogie-Classe--Adaptative-green)

## 🌟 Fonctionnalités principales

* **Multi-joueurs adaptable** : Modes Solo, Duel (2 joueurs) ou Équipe (4 joueurs) pour dynamiser la classe.
* **3 Modes de jeu** :
    * **Libre** : Manipulation manuelle du boulier avec calcul automatique du résultat.
    * **Lecture** : L'IA génère un boulier, l'élève doit lire le nombre.
    * **Sprint (Dictée)** : L'IA donne un nombre (chiffres, lettres ou romains), l'élève doit le placer sur le boulier avant la fin du chrono !
* **Correction complète** : Visualisation instantanée au verso de la carte (écriture en chiffres, lettres selon les règles d'orthographe, chiffres romains et décompositions additives).
* **Large plage numérique** : Travaillez des dizaines jusqu'aux milliards.
* **Style Personnalisé (IA)** : Possibilité de changer le thème visuel de l'application via un prompt (nécessite une clé API Gemini).



## 🚀 Installation rapide

1.  Créez un dépôt sur GitHub.
2.  Ajoutez un fichier nommé **`index.html`** et collez-y le code source.
3.  Activez **GitHub Pages** dans les paramètres de votre dépôt (`Settings > Pages`).
4.  Votre application est en ligne !

## 🎮 Comment jouer ?

1.  **Choisir le mode** : Cliquez sur Solo, Duel ou Équipe en haut de la page.
2.  **Sélectionner la difficulté** : Utilisez les boutons de plage (ex: `< 1000` ou `< 1M`).
3.  **Manipuler les perles** : 
    * Cliquez sur les perles du haut (rouges) pour ajouter/enlever **5**.
    * Cliquez sur les perles du bas (bleues) pour ajouter/enlever **1**.
4.  **Vérifier** : Cliquez sur le gros bouton **Vérifier** pour retourner la carte et voir la correction détaillée.

## 🛠️ Technologies utilisées

* **HTML5 / CSS3** : Structure et animations fluides (effets 3D Flip).
* **Tailwind CSS** : Design moderne et interface réactive (compatible tablettes/écrans).
* **JavaScript (ES6+)** : Logique de calcul mathématique, gestion des modes et moteur de conversion en lettres.
* **Google Gemini API** : (Optionnel) Pour la personnalisation esthétique par IA.

## 📝 Licence

Ce projet est destiné à un usage pédagogique. Libre à vous de le modifier pour l'adapter aux besoins de vos élèves !

---
*Développé pour la **Classe Adaptative** • Pédagogie Numérique 2025*
