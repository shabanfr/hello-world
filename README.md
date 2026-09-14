# hello-world
just another repository
Dans ce tuto, nous allons apprendre à comment configurer son serveur Ubuntu.

## 🪟 Métré Châssis & Fenêtres

Application web pour prendre rapidement les mesures de châssis, fenêtres et
portes sur chantier (rénovation), optimisée pour iPhone.

- Fichier unique `index.html`, aucune installation ni build.
- Formulaire tactile : type d'ouvrage (fenêtre / porte / châssis combiné),
  dimensions (L x H), sens d'ouverture, sens de la porte, matériau, vitrage.
- Châssis combiné : composez plusieurs éléments (fixe / fenêtre / porte)
  côte à côte avec leur propre sens d'ouverture.
- Aperçu schématique en direct, légèrement animé, avec les cotes.
- Sauvegarde locale (JSON dans le navigateur) + boutons **Exporter** /
  **Importer** pour sauvegarder ou transférer vos mesures entre appareils.
- Récupération, modification et suppression de chaque mesure depuis la liste.

### Utilisation

Ouvrez la page publiée par GitHub Pages sur votre iPhone, puis
**Partager → Sur l'écran d'accueil** pour l'utiliser comme une app.

### Activer GitHub Pages (une seule fois)

Dans les paramètres du dépôt : **Settings → Pages → Source : GitHub Actions**.
Le workflow `.github/workflows/pages.yml` publie ensuite le site
automatiquement à chaque mise à jour de la branche `master`.
