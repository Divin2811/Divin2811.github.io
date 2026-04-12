# KD Agency — Site Web
## Photography & Videography | Pointe-Noire, Congo

---

## 📁 Structure du projet

```
kd-agency/
├── index.html          ← Page principale
├── css/
│   └── style.css       ← Tous les styles
├── js/
│   └── main.js         ← Animations & interactions
├── images/
│   ├── logo.png        ← ⚠️ Mettez votre logo ici
│   ├── photo1.jpg      ← Photo galerie 1 (grande)
│   ├── photo2.jpg      ← Photo galerie 2
│   ├── photo3.jpg      ← Photo galerie 3
│   ├── photo4.jpg      ← Photo galerie 4
│   └── photo5.jpg      ← Photo galerie 5
└── README.md
```

---

## 🚀 Comment ouvrir dans VS Code

1. Ouvrir VS Code
2. `Fichier` → `Ouvrir le dossier` → choisir le dossier `kd-agency`
3. Installer l'extension **Live Server** (si pas encore installée)
4. Clic droit sur `index.html` → **Open with Live Server**
5. Le site s'ouvre dans votre navigateur !

---

## ✏️ Modifications importantes

### 1. Votre logo
- Copiez votre fichier logo dans `images/logo.png`

### 2. Vos photos de portfolio
Dans `index.html`, remplacez les blocs `gallery-placeholder` par :
```html
<img src="images/photo1.jpg" alt="Description de la photo"/>
```

### 3. Vos coordonnées
Dans `index.html`, cherchez et remplacez :
- `+242 06 XXX XX XX` → votre vrai numéro
- `contact@kdagency.cg` → votre vrai email
- `@kdagency.cg` → vos vrais réseaux sociaux

### 4. Vos tarifs
Dans `index.html`, section `#tarifs`, modifiez les prix selon vos tarifs réels.

### 5. Vos statistiques
Dans `index.html`, section `#about`, modifiez :
- `200+` Événements couverts
- `150+` Mariages filmés
- `5+` Années d'expérience

---

## 🎨 Couleurs du site

| Couleur | Code       | Usage                  |
|---------|------------|------------------------|
| Or      | `#c9a84c`  | Titres, accents, boutons |
| Rouge   | `#cc0000`  | Labels, badge populaire |
| Noir    | `#050505`  | Fond principal          |

Pour changer une couleur, modifiez les variables au début de `css/style.css` :
```css
:root {
  --gold: #c9a84c;
  --red:  #cc0000;
  --black: #050505;
}
```

---

## 📱 Le site est responsive
Il s'adapte automatiquement aux téléphones et tablettes.

---

*© 2026 KD Agency*
