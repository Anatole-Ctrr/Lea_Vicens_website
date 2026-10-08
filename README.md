# Lea Vicens — Site Officiel (Refonte Moderne & Responsive)

Site web officiel moderne, responsive et performant de la torera de rejoneo française **Lea Vicens**, cheffe de file mondiale de l'Escalafón.

Refonte fidèle à la charte graphique d'origine (Rouge Torero `#c81d25`, Or Albero `#c59b27`, Noir Noble `#101114`, Sable Chaud & Blanc Pur) avec des technologies web légères et modernes (HTML5, CSS3 Custom Properties, Vanilla JavaScript).

---

## 🌟 Caractéristiques & Fonctionnalités

- **Navigation Moderne & Header Dépoli** :
  - Header sticky avec effet *glassmorphism* au scroll.
  - Menu tiroir mobile fluide avec bouton burger accessible.
  - Sélecteur de langue instantané **Trilingue (Français, Espagnol, Anglais)** avec sauvegarde dans le `localStorage`.
- **Hero Section Immersive** :
  - Visuel plein écran dans les arènes de Ronda.
  - Titre monumental, badge animé N°1 de l'Escalafón et CTA vers la temporada et la cuadra.
  - Compteurs clés en encadré moderne.
- **Actualités & Derniers Triomphes** :
  - Grille responsive avec effets de zoom au survol et badges de date.
  - **Lecteur d'article en modale** intégrée.
- **Agenda & Temporada Interactif** :
  - Filtrage dynamique en un clic (*Tous*, *Triomphes récents*, *Espagne*, *France*).
  - Moteur de recherche instantané par nom d'arène ou ville.
  - Générateur d'événements calendrier **iCal (.ics)** téléchargeables.
- **Biographie & Héritage Peralta** :
  - Récit illustré du parcours de Nîmes à l'Andalousie (Rancho El Rocío).
  - Frise chronologique interactive retraçant les jalons majeurs de 2007 à 2026.
- **Écurie d'Artistes (La Cuadra)** :
  - Filtre par tiers (*Sortie*, *Banderilles*, *Mise à mort*).
  - Fiches interactives pour chaque monture de légende (*Bético, Gacela, Bach, Diluvio, Desafío, Guitarra, Jazmín, Bazuka, Espontáneo, Greco*).
  - Modale dédiée affichant les détails, la robe, le fer et la photo en action.
- **Statistiques Mondiales** :
  - Compteurs animés déclenchés à l'apparition à l'écran (+850 corridas, +1 480 oreilles, +85 queues).
- **La Cuadrilla & L'Équipe** :
  - Présentation soignée des membres clés de l'équipe (Simón Casas, José Domingo Parrado, auxiliaires, responsable cuadra, chauffeur).
- **Expérience VIP au Domaine** :
  - Découverte des visites privées en Andalousie (tentaderos, démonstrations de dressage, déjeuners au rancho).
- **Galerie Photographique & Lightbox** :
  - Grille responsive de photographies haute définition.
  - Lightbox plein écran avec support des touches clavier (`Échap`, flèches `Gauche`/`Droite`) et gestes tactiles *swipe*.
- **Espace Presse & Contact** :
  - Dossier de presse officiel téléchargeable.
  - Formulaire de contact moderne avec validation et notification *toast*.
  - Remerciements authentiques de Lea Vicens.

---

## 📁 Structure du Projet

```text
├── index.html              # Page principale sémantique et optimisée SEO
├── README.md               # Documentation du projet
├── .gitignore              # Fichiers ignorés par Git
└── assets/
    ├── css/
    │   └── style.css       # Design responsive, variables et animations
    ├── js/
    │   └── main.js         # Multilingue, modales, lightbox, filtres et interactions
    └── img/                # Médias officiels haute définition
        ├── logo.png
        ├── logo-white.png
        ├── logo-lea.png
        ├── hero-ronda.jpg
        ├── experience-cover.jpg
        ├── horses/         # Photos de la cavalerie
        ├── news/           # Photos des triomphes récents
        ├── team/           # Photos de la cuadrilla
        ├── experience/     # Photos des installations
        └── gallery/        # Photos de la galerie
```

---

## 🚀 Lancement Local

Vous pouvez ouvrir directement `index.html` dans n'importe quel navigateur moderne, ou lancer un serveur local :

```bash
# Avec Python
python -m http.server 8080

# Avec Node.js (npx)
npx serve .
```

Puis accédez à `http://localhost:8080/`.

---

© 2026 Lea Vicens. Tous droits réservés.
