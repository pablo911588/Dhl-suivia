
# DHL - Suivi d'expéditions

Ce projet est une simulation de site DHL permettant :
- D'enregistrer des expéditions
- De suivre un colis par code de suivi
- De consulter/modifier les envois depuis une interface admin

## Fonctionnalités

- **Page d'accueil (`index.html`)**
  - Entrée d'un code de suivi
  - Accès au suivi en temps réel via Supabase
  - Design DHL (rouge, jaune, blanc)

- **Page de suivi (`suivi.html`)**
  - Affiche les détails d'une expédition à partir du code
  - Statut de l'envoi en étapes : Prise en charge, En transit, Arrivé à la poste

- **Page d'expédition (`expedition.html`)**
  - Formulaire sécurisé (mot de passe : `91158846`)
  - Enregistre une nouvelle expédition dans Supabase
  - Upload de plusieurs photos dans Supabase Storage

- **Page admin (`admin.html`)**
  - Accès protégé par mot de passe (`91158846`)
  - Affichage et modification de toutes les expéditions

## Technologies utilisées

- HTML, CSS (design simple et responsive)
- Supabase (base de données + stockage)
- JavaScript (appel API, protection)

## Déploiement avec GitHub Pages

1. Dépose tous les fichiers du site dans le dépôt GitHub
2. Va dans `Settings > Pages`
3. Choisis la branche `main` et dossier `/root`
4. Clique sur "Save"
5. Le site sera accessible sur : `https://votre-nom.github.io/dhl-suivi/`

## Auteur

Projet réalisé avec assistance IA, inspiré du site officiel de DHL.
