
# 🚚 DHL Suivi d'Expédition

Ce projet est une simulation de site DHL pour suivre des expéditions, les créer et les gérer en ligne, avec un design fidèle aux couleurs officielles (jaune, rouge, blanc) et une structure responsive.

---

## 🌍 Fonctionnalités

- 🔎 **Suivi d'expéditions** via code de suivi (ex : `suivi.html?code=ABC123`)
- 📦 **Création d’expéditions** avec enregistrement automatique dans Supabase
- 🖼️ **Upload de photos du colis**
- 🔐 **Sécurité par mot de passe** pour les pages sensibles (`expedition.html`, `admin.html`)
- 🧾 **Tableau d’administration** pour voir et modifier toutes les expéditions
- 🌐 **Traduction automatique** selon la langue du téléphone

---

## 🔧 Pages incluses

| Fichier             | Description                              | Protégé par mot de passe |
|---------------------|------------------------------------------|---------------------------|
| `index.html`        | Accueil + champ de code de suivi         | ❌ Non                    |
| `suivi.html`        | Affichage dynamique du colis             | ❌ Non                    |
| `expedition.html`   | Formulaire de création d'expédition      | ✅ Oui (`91158846`)       |
| `admin.html`        | Gestion complète des expéditions         | ✅ Oui (`91158846`)       |

---

## 🗄️ Supabase

Les données sont stockées dans une base Supabase :
- Table : `expeditions`
- Colonnes : `code`, `expediteur`, `destinataire`, `adresse`, `colis`, `date_envoi`, `date_arrivee`, `trajet`, `photos[]`

Les photos sont stockées dans Supabase **Storage** (`colis`).

---

## 🛠️ Déploiement

1. Place tous les fichiers dans un dépôt GitHub.
2. Active GitHub Pages depuis les paramètres du dépôt.
3. Visite ton site via l’URL : `https://TON_UTILISATEUR.github.io/NOM_DU_DEPOT/`

---

## 🔐 Mot de passe

Certaines pages sont protégées par mot de passe :
```
Mot de passe administrateur : 91158846
```

---

## 👨‍💻 Développement

Site réalisé avec HTML, CSS, JavaScript + Supabase.  
Aucun framework nécessaire, tout est en pur HTML/JS.

---

## © 2025 – Projet de simulation pédagogique
