# 🧩 Block Blaster

> Un clone fidèle, ultra-fluide et entièrement personnalisable du célèbre jeu *Block Blast*, optimisé pour les smartphones (iOS/Android) et les ordinateurs.

🎮 **Jouer immédiatement dans votre navigateur :** [https://leanuhq.github.io/block-blaster/](https://leanuhq.github.io/block-blaster/)

---

## ✨ Fonctionnalités du jeu

- **Grille fidèle de $8\times8$ :** Remplissez des lignes ou des colonnes pour vider la parcelle de jeu.
- **Système de points précis :**
  - Pose d'un bloc : $1$ point par petit carré (ex: un bloc de $1\times1$ rapporte $1$ point).
  - Ligne ou colonne complétée : $1\,000$ points de base.
  - **Bonus de Parcelle Vide (Board Clear) :** $+5\,000$ points bonus si vous réussissez à vider complètement la grille !
- **Multiplicateur de Combo Dynamique :**
  - Le combo augmente de $+0.1$ à chaque ligne enchaînée ($x1.1$, $x1.2$, $x1.3$, etc.).
  - ⚠️ **Reset de combo :** Si vous posez $5$ blocs d'affilée sans réussir à détruire de ligne, le multiplicateur retombe à $x1.0$.
- **Mode Classique & Personnalisation :**
  - **Mode Classique :** Pièces de couleurs aléatoires (Rouge, Violet, Jaune, Vert, Bleu, Rose).
  - **Paramètres Avancés :** Choisissez vos propres emojis sur les blocs, importez une image de fond personnalisée via URL ou modifiez la couleur de fond unie.
- **Compatibilité Totale (iOS / Android / Desktop) :** Un affichage adaptatif (*responsive*) avec support complet du glisser-déposer tactile sur mobile.

---

## 📱 Comment installer le jeu sur l'écran d'accueil de votre téléphone (PWA)

Pour une expérience de jeu plein écran comme une véritable application (sans la barre de recherche du navigateur), vous pouvez ajouter **Block Blaster** à l'écran d'accueil de votre téléphone.

### 🍏 Sur iPhone / iPad (iOS & Safari)
1. Ouvrez le lien du jeu dans **Safari** : `https://leanuhq.github.io/block-blaster/`.
2. Appuyez sur le bouton **Partager** (l'icône de carré avec une flèche vers le haut en bas de votre écran).
3. Faites défiler le menu vers le bas et sélectionnez **Sur l'écran d'accueil** (ou *Sur l'écran d'acc.*).
4. Nommez l'application "Block Blaster" et appuyez sur **Ajouter**.
5. L'icône apparaîtra directement sur votre écran d'accueil !

### 🤖 Sur Android (Chrome / Firefox / Edge)
1. Ouvrez le lien du jeu dans votre navigateur (ex: **Chrome**) : `https://leanuhq.github.io/block-blaster/`.
2. Appuyez sur les **trois petits points verticaux** (en haut à droite ou en bas à droite).
3. Sélectionnez l'option **Ajouter à l'écran d'accueil** ou **Installer l'application**.
4. Validez en cliquant sur **Ajouter** ou **Installer**.
5. Le jeu s'installera sur votre écran comme une application native.

---

## 🛠️ Installation locale et développement

Si vous souhaitez modifier le jeu ou y jouer localement :

1. Clonez ce dépôt sur votre machine :
   ```bash
   git clone [https://github.com/leanuhq/block-blaster.git](https://github.com/leanuhq/block-blaster.git)
