# TP : Initiation à Git & GitHub
*BTS SIO – Travail en équipe avec branches, commits et Pull Requests*

---

## 🎯 Objectifs du TP

Dans ce TP, vous allez apprendre à utiliser les bases de **Git** et **GitHub**, les deux outils les plus utilisés dans le travail collaboratif en informatique.

À la fin du TP, vous saurez :

- créer et utiliser un dépôt Git  
- comprendre les notions de *working directory*, *commit*, *branche*, *HEAD*  
- créer une branche pour isoler une fonctionnalité  
- modifier des fichiers et enregistrer votre travail  
- envoyer votre travail sur GitHub  
- ouvrir une **Pull Request**  
- faire une **review** sur# TP : Initiation à Git & GitHub
*BTS SIO – Travail en équipe avec branches, commits et Pull Requests*

---

## 🎯 Objectifs du TP

Dans ce TP, vous allez apprendre à utiliser les bases de **Git** et **GitHub**, les deux outils les plus utilisés dans le travail collaboratif en informatique.

À la fin du TP, vous saurez :

- créer et utiliser un dépôt Git  
- comprendre les notions de *working directory*, *commit*, *branche*, *HEAD*  
- créer une branche pour isoler une fonctionnalité  
- modifier des fichiers et enregistrer votre travail  
- envoyer votre travail sur GitHub  
- ouvrir une **Pull Request**  
- faire une **review** sur le travail d’un autre groupe  
- résoudre un **conflit de merge**

---

## 🏗️ Organisation du TP

Vous êtes répartis en **équipes de 3–4 étudiants**.  
Chaque équipe disposera d’un **dépôt GitHub cloné automatiquement** via GitHub Classroom.

Chaque équipe devra :

1. **Créer une branche** (ex. : `feature-ajout-section`, `fix-bug-01`, …)  
2. **Modifier un fichier** dans le dossier `src/`  
3. **Ajouter et committer** ses modifications  
4. **Pousser** la branche sur GitHub  
5. **Ouvrir une Pull Request**  
6. **Faire une review** sur la PR d’une autre équipe  
7. **Résoudre un conflit** si nécessaire  
8. **Fusionner (merge)** la branche dans `main`

---

## 📂 Structure du dépôt

Voici l’arborescence du projet :

 le travail d’un autre groupe  
- résoudre un **conflit de merge**

---

## 🏗️ Organisation du TP

Vous êtes répartis en **équipes de 3–4 étudiants**.  
Chaque équipe disposera d’un **dépôt GitHub cloné automatiquement** via GitHub Classroom.

Chaque équipe devra :

1. **Créer une branche** (ex. : `feature-ajout-section`, `fix-bug-01`, …)  
2. **Modifier un fichier** dans le dossier `src/`  
3. **Ajouter et committer** ses modifications  
4. **Pousser** la branche sur GitHub  
5. **Ouvrir une Pull Request**  
6. **Faire une review** sur la PR d’une autre équipe  
7. **Résoudre un conflit** si nécessaire  
8. **Fusionner (merge)** la branche dans `main`

---

## 📂 Structure du dépôt


```
.
├── README.md               # Ce fichier
├── src/                    # Code source simple utilisé pour le TP
│   ├── index.html
│   ├── style.css
│   └── script.js
└── docs/                   # Dossier vide pour l'exercice
```
Vous devrez modifier les fichiers dans `src/`.

---

## 🧪 Exercice : vos premières commandes Git

Voici les commandes essentielles que vous utiliserez pendant le TP.

### 🔍 Vérifier l'état du dépôt
```bash
git status
```
### Ajouter des fichiers pour le commit
```bash
git add .
```
### Enregistrer les modifications
```bash
git commit -m "Description claire du travail effectué"
```
### Créer et se déplacer dans une branche
```bash
git checkout -b ma-branche
```
### Envoyer votre branche sur GitHub
```bash
git push origin ma-branche
```

## 🔀 Pull Request (PR)
Une Pull Request permet :

1. de proposer vos modifications
2. de discuter et d’ajouter des commentaires
3. de demander une review à un autre groupe
4. de fusionner votre branche dans main

➡️ La PR se fait via l’interface github.com.

## ⚠️ Résolution d’un conflit de merge
Si deux équipes modifient la même ligne d’un fichier, Git ne sait pas choisir :
```bash
<<<<<<< HEAD
version actuelle
=======
version de la branche
>>>>>>> ma-branche
```
Vous devez :

1. Modifier manuellement le fichier
2. Supprimer les marqueurs <<<<<<<, =======, >>>>>>>
3. Garder la version souhaitée
4. Committer la résolution :
```bash
git add fichier
git commit
git push
```

## 🎉 Fin du TP
À la fin de l’activité, vous devez avoir :
1. ✔ Une branche créée
2. ✔ Des commits propres
3. ✔ Une Pull Request
4. ✔ Une review réalisée
5. ✔ Un merge effectué
6. ✔ Un conflit résolu (si demandé par le professeur)