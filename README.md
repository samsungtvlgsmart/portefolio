# Portfolio Développeur Web

Un portfolio moderne et responsive pour présenter vos compétences et projets en développement web.

## 🚀 Fonctionnalités

- **Design moderne** : Interface épurée et professionnelle
- **Responsive** : S'adapte à tous les écrans (mobile, tablette, desktop)
- **Animations fluides** : Effets visuels pour une meilleure expérience utilisateur
- **Navigation fluide** : Menu hamburger pour mobile
- **Sections complètes** : Accueil, À propos, Projets, Compétences, Contact
- **Formulaire de contact** : Prêt à être connecté à votre backend

## 📁 Structure des fichiers

```
portfolio/
├── index.html          # Page principale
├── style.css           # Styles CSS
├── script.js           # JavaScript pour l'interactivité
└── README.md          # Ce fichier
```

## 🎨 Personnalisation

### 1. Informations personnelles

Modifiez le fichier `index.html` pour personnaliser :

- **Nom et titre** : Remplacez "Votre Nom" par votre nom
- **Description** : Modifiez la présentation dans la section hero
- **À propos** : Personnalisez votre bio
- **Contact** : Ajoutez vos vraies informations de contact

### 2. Projets

Dans la section projets, remplacez les exemples par vos vrais projets :

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-[icône]"></i>
    </div>
    <div class="project-content">
        <h3>Nom de votre projet</h3>
        <p>Description de votre projet</p>
        <div class="project-tech">
            <span class="tech-tag">Technologie 1</span>
            <span class="tech-tag">Technologie 2</span>
        </div>
        <div class="project-links">
            <a href="[lien-github]" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="[lien-demo]" class="project-link">
                <i class="fas fa-external-link-alt"></i> Demo
            </a>
        </div>
    </div>
</div>
```

### 3. Compétences

Ajustez les pourcentages dans `index.html` :

```html
<div class="skill-progress" style="width: 85%"></div>
```

### 4. Couleurs

Modifiez les variables CSS dans `style.css` :

```css
:root {
    --primary-color: #2563eb;    /* Couleur principale */
    --secondary-color: #1e40af;  /* Couleur secondaire */
    --accent-color: #3b82f6;     /* Couleur d'accent */
    /* ... autres couleurs */
}
```

## 🚀 Déploiement

### Option 1 : GitHub Pages (Gratuit)

1. Créez un repository GitHub
2. Uploadez vos fichiers
3. Allez dans Settings > Pages
4. Sélectionnez la branche main
5. Votre site sera disponible à `https://[username].github.io/[repository]`

### Option 2 : Netlify (Gratuit)

1. Créez un compte sur [Netlify](https://netlify.com)
2. Glissez-déposez votre dossier
3. Votre site sera déployé automatiquement

### Option 3 : Vercel (Gratuit)

1. Créez un compte sur [Vercel](https://vercel.com)
2. Importez votre projet
3. Déploiement automatique

## 📱 Responsive Design

Le portfolio s'adapte automatiquement à :
- **Mobile** : < 768px
- **Tablette** : 768px - 1024px
- **Desktop** : > 1024px

## 🛠️ Technologies utilisées

- **HTML5** : Structure sémantique
- **CSS3** : Styles modernes avec Flexbox et Grid
- **JavaScript** : Interactivité et animations
- **Font Awesome** : Icônes
- **Google Fonts** : Typographie

## 📝 Fonctionnalités JavaScript

- Menu hamburger responsive
- Animations au scroll
- Smooth scrolling
- Gestion du formulaire de contact
- Animations des barres de compétences
- Effets de parallaxe

## 🎯 Pour Bachelor 3 Développeur Web

Ce portfolio met en avant :

✅ **Compétences techniques** : HTML, CSS, JavaScript, PHP  
✅ **Projets concrets** : E-commerce, applications web  
✅ **Design moderne** : Interface professionnelle  
✅ **Code propre** : Structure claire et maintenable  
✅ **Responsive** : Compatible tous appareils  

## 📞 Contact

Pour personnaliser le formulaire de contact, modifiez le JavaScript dans `script.js` pour intégrer votre backend (PHP, Node.js, etc.).

## 🔧 Développement local

1. Ouvrez `index.html` dans votre navigateur
2. Ou utilisez un serveur local :
   ```bash
   # Avec Python
   python -m http.server 8000
   
   # Avec Node.js
   npx serve .
   ```

## 📄 Licence

Ce projet est libre d'utilisation pour votre portfolio personnel.

---

**Bon courage pour votre Bachelor 3 ! 🎓** 