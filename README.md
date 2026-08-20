# MOVECOIN v4

⚡ Jeu plateforme 2D (React + Canvas) avec **Oasis** : monde parallèle, PNJ autonomes, commerce, VIP, comptes joueurs.

## 🚀 Déploiement Render

### Instructions rapides :

1. **Connecter le repo GitHub**
   - Allez sur [render.com](https://render.com)
   - Cliquez **New +** → **Static Site**
   - Sélectionnez `NWJack/MoveCoinP`

2. **Configurer le déploiement**
   - **Build Command** : laissez vide ou `echo static`
   - **Publish Directory** : `.` (racine)
   - **Branch** : `main`

3. **Deploy**
   - Cliquez **Create Static Site**
   - Render génère automatiquement une URL

### Lien du serveur :
```
https://movecoin.onrender.com
```
*(l'URL exacte sera fournie après création du service sur Render)*

## 🎮 Fonctionnalités

- **5 niveaux** + **Oasis** (niveau secret)
- **PNJ autonomes** avec IA (construction, apprentissage FR, couples)
- **Comptes joueurs** (localStorage)
- **VIP ranks** 1→33
- **Salle détente** multijoueur (WebSocket)
- **Avatars** : Spectre, Robot, Ninja, Alien, Chat, Crâne, Mage, Cosmonaute, **Musclé 💪, Pretty 💋**
- **Jukebox** (4 pistes)
- **Support tickets** + **Mode secret** (code: "3333" ou "movecoin")

## 📁 Structure

```
MoveCoinP/
├── index.html       # Jeu complet (React + Canvas)
├── package.json     # Dépendances Node
├── render.yaml      # Configuration Render
└── README.md        # Cette doc
```

## 🔧 Lancer en local

```bash
# Option 1 : Ouvrir directement
open index.html

# Option 2 : Avec serveur local
npx serve -s . -l 3000
```

## 🌐 WebSocket (optionnel)

Pour activer le multijoueur en ligne :
- Configurez un serveur WebSocket externe
- Entrez l'URL dans l'onglet **Menu** → **Babillard** → **WebSocket**

## 📝 Contrôles

- **←→** ou **A/D** : se déplacer
- **Espace** ou **↑** : sauter (2× = double saut)
- **Shift** ou **E** : dash
- **Échap** : pause / menu

---

**v4.0.0** — Oasis PNJ, avatars Musclé & Pretty, déploiement Render
