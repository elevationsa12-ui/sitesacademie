# 🎓 Elevation Académie - Site Web

Plateforme éducative moderne pour formations en ligne.

## 📋 Prérequis

- Git installé
- Compte GitHub
- Les fichiers images doivent être dans le dossier `./images/`

## 🚀 Déployer sur GitHub Pages

### Étape 1 : Initialiser le dépôt Git

```bash
cd "c:\Users\PC\Documents\New folder"
git init
git config user.name "Votre Nom"
git config user.email "votre.email@gmail.com"
git add .
git commit -m "Initial commit - Elevation Académie"
```

### Étape 2 : Créer un dépôt sur GitHub

1. Allez sur https://github.com/new
2. Nommez le dépôt : `elevation-academie` (ou autre)
3. Cliquez "Create repository"
4. Copiez l'URL HTTPS

### Étape 3 : Pousser le code

```bash
git remote add origin https://github.com/VOTRENOM/elevation-academie.git
git branch -M main
git push -u origin main
```

### Étape 4 : Activer GitHub Pages

1. Allez dans **Settings** → **Pages**
2. Sélectionnez `main` comme branche
3. Votre site sera en ligne à : `https://VOTRENOM.github.io/elevation-academie`

## 📁 Structure des dossiers

```
elevation-academie/
├── index.html          (page principale)
├── logo.png           (votre logo)
├── presentation.mp4   (vidéo de présentation)
├── images/            (dossier des images)
│   ├── informatique.jpg
│   ├── montage.jpg
│   ├── live.jpg
│   ├── marketing.jpg
│   ├── entrepreneuriat.jpg
│   └── retouche.jpg
└── README.md
```

## ⚙️ Fichiers à préparer

Assurez-vous que les fichiers suivants sont dans le dossier :
- ✅ `index.html` (prêt)
- ⏳ `logo.png` (placez votre logo)
- ⏳ `presentation.mp4.mp4` (vidéo de présentation)
- ⏳ Dossier `images/` avec 6 images JPG

## 🔄 Mettre à jour le site

Après modification :
```bash
git add .
git commit -m "Description de la modification"
git push
```

---

**Contact** : elevationsa12@gmail.com | +509 3862-9690
