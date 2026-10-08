# Modèle de Rapport de Physique (VS Code)

Ce dossier est un **modèle autonome** prêt à l'emploi pour les rapports de laboratoire de Physique dans **VS Code**.

---

## ⚡ Compilation automatique dans VS Code

- **À la modification** : Dès que vous tapez ou enregistrez une modification dans n'importe quel fichier (`03_Experience_1.tex`, `metadata.tex`, etc.), VS Code recompile automatiquement `main.pdf`.
- **Fichier racine fixé** : Peu importe le sous-fichier ouvert dans `content/`, VS Code sait que le document principal à compiler est toujours `main.tex`.
- **Visualiseur PDF intégré** : Ouvrez votre PDF directement dans un onglet VS Code (via LaTeX Workshop : clic sur l'icône de vue PDF en haut à droite) ; il se rafraîchit en temps réel à chaque compilation.

---

## 📁 Comment démarrer un nouveau laboratoire ?

1. **Copiez** ce dossier `Template_Labo` et renommez-le (ex: `LaboE8`).
2. Ouvrez le dossier dans **VS Code**.
3. Remplissez vos métadonnées dans `config/metadata.tex` (Titre, Date, Groupe, Superviseur).
4. Rédigez vos expériences dans `content/03_Experience_1.tex`, `content/03_Experience_2.tex`, etc.
   *(Pour enlever ou ajouter une expérience, décommentez ou commentez son inclusion dans `content/03_mesures_resultats_analyse.tex`)*.
5. Remplacez `assets/images/SUJET.png` par l'image de votre sujet.
