# 🇺🇸 Hip-Hop Labels USA — Dashboard Stratégique Interactif

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Version](https://img.shields.io/badge/version-2.0.0-B22234?style=for-the-badge)
![Status](https://img.shields.io/badge/status-active-3C3B6E?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-blue?style=for-the-badge)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=for-the-badge)

![Labels](https://img.shields.io/badge/labels-7-B22234?style=for-the-badge)
![Artists](https://img.shields.io/badge/artists-49-3C3B6E?style=for-the-badge)
![Albums](https://img.shields.io/badge/albums-190+-B22234?style=for-the-badge)
![Data Points](https://img.shields.io/badge/data_points-500+-3C3B6E?style=for-the-badge)

**Un dashboard interactif complet pour explorer, analyser et comparer 7 des labels hip-hop les plus influents de l'histoire américaine.**

[🚀 Démo en ligne](#-démo) · [📊 Fonctionnalités](#-fonctionnalités) · [🏷️ Labels](#️-labels-inclus) · [🎯 Utilisation](#-utilisation) · [🛠️ Installation](#️-installation)

</div>

---

## 📖 À propos

Ce projet est un **dashboard stratégique interactif** qui regroupe et analyse les données de **7 labels hip-hop légendaires** :

- 🎤 **Def Jam Recordings** (1984)
- 💀 **Soul Assassins** (1997)
- 🎧 **Aftermath Entertainment** (1996)
- 👻 **Shady Records** (1999)
- 👑 **Bad Boy Records** (1993)
- ⚡ **Ruthless Records** (1987)
- 🏴 **Death Row Records** (1991)

Inspiré par les couleurs du **drapeau américain** 🇺🇸 (rouge #B22234, blanc #FFFFFF, bleu #3C3B6E), le dashboard offre une expérience visuelle premium avec des interactions temps réel, des graphiques comparatifs avancés et un maximum de données historiques.

---

## 🎨 Palette de couleurs

| Couleur | Hex | Utilisation |
|:---:|:---:|:---|
| 🔴 **Rouge USA** | `#B22234` | Accents principaux, labels, alertes |
| ⚪ **Blanc USA** | `#FFFFFF` | Texte principal, bordures, contrastes |
| 🔵 **Bleu USA** | `#3C3B6E` | Secondaire, headers, tableaux |
| ⚫ **Noir** | `#0A0A0A` | Background principal |
| ⚪ **Gris foncé** | `#141414` | Cartes, conteneurs |

---

## ✨ Fonctionnalités

### 🔍 Recherche et filtrage dynamiques

- 🔎 **Barre de recherche** en temps réel sur chaque label et artiste
- 🎛️ **Filtres multi-critères** : ventes, revenus, ROI, influence, albums, année
- 🔄 **Tri croissant/décroissant** via boutons toggle
- ↺ **Bouton reset** pour réinitialiser tous les filtres en un clic

### 🎛️ Filtres interactifs

Le dashboard propose un **panneau de contrôle** sur chaque onglet avec plusieurs filtres combinables.

#### 🔎 Recherche textuelle

    ┌─────────────────────────────────────────────────────┐
    │  🔍 Rechercher un label ou un artiste...            │
    └─────────────────────────────────────────────────────┘

- Recherche **instantanée** sur le nom, le genre, les fondateurs
- Résultats filtrés en temps réel à chaque frappe
- Message "Aucun résultat trouvé" si la recherche ne retourne rien

#### 📊 Tri par métrique

    ┌─────────────────────────────────────────────────────┐
    │  Trier par :  ▼                                     │
    │  ├─ Ventes                                          │
    │  ├─ Revenus                                         │
    │  ├─ Artistes                                        │
    │  ├─ Albums                                          │
    │  ├─ Influence                                       │
    │  └─ Année de fondation                              │
    └─────────────────────────────────────────────────────┘

- 6 métriques de tri disponibles
- Tri appliqué immédiatement aux cartes et graphiques

#### 🔄 Ordre de tri

    ┌─────────────────────────────────────────────────────┐
    │  [↓ Décroissant]  [↑ Croissant]                     │
    └─────────────────────────────────────────────────────┘

- Boutons toggle pour inverser l'ordre
- État actif visuellement mis en évidence (rouge USA)

#### 🎯 Sélection de graphique

    ┌─────────────────────────────────────────────────────┐
    │  [Ventes]  [Revenus]  [Influence]                   │
    └─────────────────────────────────────────────────────┘

- Change dynamiquement la métrique du graphique principal
- 3 modes disponibles sur la vue d'ensemble

#### ↺ Réinitialisation

    ┌─────────────────────────────────────────────────────┐
    │  ↺ Réinitialiser                                    │
    └─────────────────────────────────────────────────────┘

- Remet à zéro **tous les filtres** de l'onglet actif
- Restaure les paramètres par défaut

#### 🎴 Filtres par carte cliquable

- Clic sur une **carte de label** → Navigue vers son onglet détaillé
- Clic sur une **carte métrique** → Trie automatiquement par cette métrique
- Clic sur une **ligne du tableau** → Ouvre la modale détaillée de l'artiste

#### 🏷️ Filtres par onglet

Chaque onglet de label possède **son propre système de filtres indépendant** :

| Filtre | Description |
|:---|:---|
| 🔍 Recherche | Par nom d'artiste ou genre |
| 📊 Tri | 6 critères (ventes, revenus, ROI, influence, albums, début) |
| 🔄 Ordre | Croissant ou décroissant |
| ↺ Reset | Réinitialisation complète |

### 📊 Visualisations interactives (Plotly)

- 📈 **Graphiques en barres** dynamiques avec métrique commutable
- 🎯 **Scatter plots** avec taille de bulle proportionnelle
- 🥧 **Pie charts** avec isolation au clic
- 🕸️ **Radar charts** pour comparaisons multi-dimensionnelles
- 📅 **Timelines interactives**
- 📉 **Courbes ROI vs Influence**
- 💡 **Tooltips enrichis** au survol

### 🎴 Interactions utilisateur

- 👆 **Cartes cliquables** pour navigation rapide
- 📋 **Tableaux triables** avec colonnes cliquables
- 🔔 **Modale détaillée** au clic sur un artiste
- ⌨️ **Support clavier** (Échap pour fermer les modales)
- 🎬 **Animations fluides** (fadeIn, slideIn, hover effects)

### ⚖️ Comparateur avancé

- Sélection de **2 labels** à comparer simultanément
- **4 graphiques comparatifs** (radar, barres, timeline, scatter)
- Tableau à **14 métriques** côte à côte
- Mise à jour **instantanée** au changement de sélection

### 📱 Responsive Design

- ✅ **Desktop** (1800px+)
- ✅ **Tablette** (768px - 1100px)
- ✅ **Mobile** (< 768px)

---

## 🏷️ Labels inclus

| Label | Année | Fondateur | Ventes | Revenus | Artistes |
|:---|:---:|:---|:---:|:---:|:---:|
| 🔴 **Def Jam** | 1984 | Rick Rubin, Russell Simmons | 269M | $2.05B | 9 |
| 🔵 **Soul Assassins** | 1997 | DJ Muggs | 21.25M | $61.8M | 7 |
| 🔴 **Aftermath** | 1996 | Dr. Dre | 325M | $915M | 7 |
| 🔵 **Shady** | 1999 | Eminem, Paul Rosenberg | 262.3M | $706M | 7 |
| 🔴 **Bad Boy** | 1993 | Sean 'Puffy' Combs | 66M | $375M | 7 |
| 🔵 **Ruthless** | 1987 | Eazy-E, Jerry Heller | 30.2M | $132M | 6 |
| 🔴 **Death Row** | 1991 | Suge Knight, Dr. Dre | 34.3M | $153M | 6 |

**Total cumulé** : ~1 milliard d'albums vendus · ~$4.4 milliards de revenus · 49 artistes légendaires

---

## 🎯 Utilisation

### 🖱️ Navigation

1. **Onglet Vue d'ensemble** : métriques globales + cartes de tous les labels
2. **Onglets par label** : analyse détaillée avec artistes, graphiques et timeline
3. **Onglet Comparateur** : sélectionnez 2 labels pour les comparer

### ⌨️ Raccourcis clavier

| Touche | Action |
|:---:|:---|
| `Échap` | Fermer la modale |
| `Tab` | Navigation entre éléments |
| `Entrée` | Activer l'élément sélectionné |

---

## 📊 Métriques analysées

### 📈 Par label

- 💿 **Ventes totales** (albums vendus)
- 💰 **Revenus** (chiffre d'affaires)
- 🎤 **Artistes** (nombre de légendes)
- 🎵 **Albums** (productions classiques)
- 🌟 **Influence** (score culturel /70)
- 📅 **Année de fondation**
- 🏢 **Siège et distribution**
- 📊 **Pic de revenus annuels**

### 📈 Par artiste

- 📅 Année de début
- 🎼 Genre musical
- 💿 Nombre d'albums
- 💵 Ventes et revenus
- 📈 ROI (%)
- ⭐ Score d'influence (/10)
- 📝 Note biographique détaillée

### ⚖️ Comparatif

- 🎯 **14 métriques** comparées côte à côte
- 📊 **4 graphiques** simultanés
- 🏆 Mise en évidence des différences

---

## 🛠️ Installation

### 📦 Option 1 : Utilisation directe

Aucune installation nécessaire ! Ouvrez simplement le fichier `index.html` dans votre navigateur :

    # Cloner le repository
    git clone https://github.com/votre-username/hiphop-labels-dashboard.git

    # Ouvrir dans le navigateur
    cd hiphop-labels-dashboard
    open index.html  # ou double-clic

### 🌐 Option 2 : Serveur local

    # Avec Python
    python -m http.server 8000

    # Avec Node.js
    npx serve .

    # Avec PHP
    php -S localhost:8000

Puis ouvrez [http://localhost:8000](http://localhost:8000)

### 📄 Option 3 : Version Streamlit (Python)

    # Installer les dépendances
    pip install streamlit plotly pandas numpy

    # Lancer le dashboard
    streamlit run dashboard.py

---

## 🏗️ Architecture

    hiphop-labels-dashboard/
    │
    ├── 📄 index.html              # Dashboard principal (HTML/CSS/JS)
    ├── 📄 dashboard.py            # Version Streamlit
    ├── 📄 README.md               # Documentation
    │
    ├── 📁 assets/
    │   ├── 🖼️ preview.png         # Capture d'écran
    │   └── 🎨 logo.svg            # Logo du projet
    │
    └── 📁 data/
        ├── 📊 labels.json         # Données des labels
        └── 📊 artists.json        # Données des artistes

### 🧩 Stack technique

| Technologie | Utilisation |
|:---|:---|
| ![HTML5](https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square) | Structure |
| ![CSS3](https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square) | Styling, animations |
| ![JavaScript](https://img.shields.io/badge/-JS-F7DF1E?logo=javascript&logoColor=black&style=flat-square) | Interactivité |
| ![Plotly](https://img.shields.io/badge/-Plotly-3F4F75?logo=plotly&logoColor=white&style=flat-square) | Graphiques |
| ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white&style=flat-square) | Version Streamlit |

---

## 🎨 Aperçu

### 🖼️ Vue d'ensemble

    ┌──────────────────────────────────────────────────────────┐
    │  🇺🇸 HIP-HOP LABELS USA - DASHBOARD INTERACTIF          │
    ├──────────────────────────────────────────────────────────┤
    │  📊 Vue d'ensemble │ Def Jam │ Soul Assassins │ ...      │
    ├──────────────────────────────────────────────────────────┤
    │  [Ventes] [Revenus] [Artistes] [Albums] [Influence]     │
    │                                                          │
    │  ┌─────────────┬─────────────┬─────────────┐            │
    │  │ 1B albums   │ 49 artistes │ $4.4B       │            │
    │  └─────────────┴─────────────┴─────────────┘            │
    │                                                          │
    │  [📊 Ventes] [📈 Revenus]                               │
    │  [🥧 Répartition] [📅 Timeline]                         │
    └──────────────────────────────────────────────────────────┘

### 📊 Analyse par label

    ┌──────────────────────────────────────────────────────────┐
    │  Def Jam Recordings - 1984                              │
    ├──────────────────────────────────────────────────────────┤
    │  🔍 Rechercher │ Trier par ▼ │ ↺ Réinitialiser          │
    │                                                          │
    │  [269M ventes] [9 artistes] [75 albums] [$2.05B]        │
    │                                                          │
    │  [📊 Ventes/Artiste] [📈 ROI vs Influence]              │
    │  [💰 Revenus] [🎯 Albums vs ROI]                        │
    │                                                          │
    │  👑 Artistes Légendaires (9/9)                          │
    │  ┌────────────────────────────────────────────────┐    │
    │  │ RICK RUBIN │ 1984 │ Hip-hop │ 30 │ 50M │ ...  │    │
    │  │ JAY-Z      │ 1996 │ Hip-hop │ 11 │ 50M │ ...  │    │
    │  └────────────────────────────────────────────────┘    │
    └──────────────────────────────────────────────────────────┘

---

## 🚀 Fonctionnalités futures

- [ ] 🌙 Mode clair/sombre automatique
- [ ] 🎵 Intégration Spotify/Apple Music API
- [ ] 📱 Application mobile native (React Native)
- [ ] 🌍 Support multilingue (EN, ES, FR)
- [ ] 📤 Export PDF des rapports
- [ ] 🔐 Système d'authentification
- [ ] 📊 Plus de labels (Roc-A-Fella, G-Unit, TDE, etc.)
- [ ] 🎥 Intégration clips vidéo YouTube
- [ ] 📈 Prédictions ML sur les tendances

---

## 🤝 Contribution

Les contributions sont **les bienvenues** ! Voici comment participer :

    # 1. Fork le projet
    # 2. Créer une branche
    git checkout -b feature/ma-nouvelle-fonctionnalite

    # 3. Commit vos changements
    git commit -m "✨ Ajout d'une nouvelle fonctionnalité"

    # 4. Push
    git push origin feature/ma-nouvelle-fonctionnalite

    # 5. Ouvrir une Pull Request

### 📝 Convention de commit

| Emoji | Type | Description |
|:---:|:---|:---|
| ✨ | `feat` | Nouvelle fonctionnalité |
| 🐛 | `fix` | Correction de bug |
| 📝 | `docs` | Documentation |
| 🎨 | `style` | Formatage |
| ♻️ | `refactor` | Refactoring |
| ⚡ | `perf` | Performance |
| ✅ | `test` | Tests |

---

## 📜 Licence

Ce projet est sous licence **MIT** - voir le fichier [LICENSE](LICENSE) pour plus de détails.

    MIT License

    Copyright (c) 2024 Hip-Hop Labels Dashboard

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction...

---

## ⚠️ Avertissement

Ce dashboard est créé **à des fins éducatives uniquement**. Les données sont compilées à partir de sources publiques et d'estimations. Certains chiffres peuvent être approximatifs.

- 🎓 **Usage éducatif uniquement**
- 📚 **Sources** : Billboard, RIAA, Wikipedia, interviews, documentaires
- 💡 **Aucune affiliation** avec les labels mentionnés
- 🎵 **Hommage** à la culture hip-hop américaine

---

## 🙏 Remerciements

Un grand merci à tous les **artistes, producteurs et visionnaires** qui ont façonné l'histoire du hip-hop :

> *"Le hip-hop a fait plus pour le dialogue racial que la politique."*
> — **Jay-Z**

> *"Def Jam n'est pas juste un label, c'est une culture."*
> — **Russell Simmons**

> *"Quality over quantity."*
> — **Dr. Dre**

---

## 📞 Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/gunout)


</div>

---

<div align="center">

### 🌟 Si ce projet vous plaît, n'oubliez pas de lui donner une étoile ! ⭐

![Made with Love](https://img.shields.io/badge/Made_with-❤️-B22234?style=for-the-badge)
![For Hip-Hop](https://img.shields.io/badge/For_Hip--Hop-🎤-3C3B6E?style=for-the-badge)
![USA](https://img.shields.io/badge/USA-🇺🇸-B22234?style=for-the-badge)

**🇺🇸 Hip-Hop Labels USA Dashboard — 1984-2024 🇺🇸**

*Célébrons 40 ans de culture hip-hop américaine*

</div>

---

<div align="center">

### 🇫🇷 Gunout · 2026

![Made in France](https://img.shields.io/badge/Made_in-France-002395?style=flat-square&labelColor=FFFFFF&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA5MDAgNjAwIj48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjYwMCIgZmlsbD0iIzAwMjM5NSIvPjxyZWN0IHdpZHRoPSI5MDAiIGhlaWdodD0iNDAwIiB5PSIxMDAiIGZpbGw9IiNmZmYiLz48cmVjdCB3aWR0aD0iOTAwIiBoZWlnaHQ9IjIwMCIgeT0iNDAwIiBmaWxsPSIjZWQyOTM5Ii8+PC9zdmc+)
![GitHub](https://img.shields.io/badge/GitHub-gunout-181717?style=flat-square&logo=github&logoColor=white)
![Year](https://img.shields.io/badge/2026-ED2939?style=flat-square&labelColor=FFFFFF)

<sub>© 2026 <strong>Gunout</strong> — Tous droits réservés.</sub>

</div>
