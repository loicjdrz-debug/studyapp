# StudyApp - Version Vercel

Application d'apprentissage avec IA intégrée via backend Vercel.

## 🚀 Déploiement sur Vercel

### 1. Préparer GitHub

1. Va sur ton repo GitHub
2. Crée un nouveau dossier ou remplace tout le contenu par ces fichiers :
   - `api/generate.js`
   - `api/analyze-image.js`
   - `public/index.html`
   - `vercel.json`

### 2. Connecter à Vercel

1. Va sur https://vercel.com
2. Clique "New Project"
3. Importe ton repo GitHub
4. Vercel détectera automatiquement la configuration
5. Clique "Deploy"

### 3. Obtenir l'URL

1. Une fois déployé, tu auras une URL comme : `https://ton-app.vercel.app`
2. Copie cette URL

### 4. Mettre à jour l'app

1. Va dans `public/index.html`
2. Trouve la ligne : `this.backendUrl = 'YOUR_VERCEL_URL_HERE';`
3. Remplace par : `this.backendUrl = 'https://ton-app.vercel.app';`
4. Commit et push sur GitHub
5. Vercel redéploiera automatiquement !

### 5. Utiliser l'app

1. Va sur `https://ton-app.vercel.app`
2. Entre ton prénom et ta clé API Gemini
3. Profite de toutes les fonctionnalités IA ! 🎉

## ✨ Fonctionnalités

- 📚 Organisation de cours (années, matières, chapitres)
- 📸 Scan de cours avec OCR
- 📄 Génération de résumés
- 🗺️ Cartes mentales
- 🌍 Apprentissage de vocabulaire avec traduction auto
- 🌙 Mode sombre
- 💾 Sauvegarde locale

## 💡 Important

- Vercel est **100% gratuit** pour ce type d'app
- Tes données restent sur ton téléphone
- Seule la clé API Gemini transite par le backend (pour éviter CORS)
