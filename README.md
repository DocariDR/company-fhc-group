# Company Website

![Version](https://img.shields.io/badge/version-2.0.0-blue?style=flat)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-En%20cours-yellow?style=flat)

Site vitrine multipage réalisé dans le cadre de ma formation pratique en Développement Web chez FHC Groupe Sarl.

## Aperçu

[Cliquez sur moi pour voir le site web de Company Website](https://docaridr.github.io/company-fhc-group/)

## À propos

Ce projet a été réalisé à partir d'un brief donné à l'oral par mon formateur, illustré par des maquettes dessinées au tableau pour chaque page. L'objectif : intégrer un site vitrine multipage en HTML5 sémantique et CSS3, en autonomie à partir de ces indications visuelles et verbales.

Le contenu met en scène un cabinet de conseil fictif, **Fidexa Conseil**, utilisé comme cas d'usage pour donner un rendu réaliste au projet (pas de Lorem ipsum ni de textes de remplissage).

## Fonctionnalités

- Site multipage : Accueil, À propos, Contact
- Page d'accueil avec section hero, présentation des domaines d'intervention et chiffres clés
- Navigation sticky avec menu hamburger responsive (CSS pur, via `:has()` et une checkbox)
- Page À propos avec section "Nos membres"
- Formulaire de contact fonctionnel, connecté à **Web3Forms** :
  - Envoi réel des messages par e-mail
  - Protection anti-spam (honeypot)
  - Redirection vers une page de confirmation (`merci.html`) après envoi
- Design responsive (media queries pour mobile)
- Typographie personnalisée (Google Fonts : Fraunces pour les titres, Inter pour le texte)

## Technologies utilisées

- **HTML5** sémantique
- **CSS3** (Flexbox, Grid, transitions, sélecteur `:has()`, media queries)
- **Web3Forms** (traitement du formulaire de contact, sans backend à héberger)

## Structure du projet

```
company-website/
├── index.html
├── a-propos.html
├── contact.html
├── merci.html
├── assets/
│   ├── css/
│   │   └── style.css
│   └── img/
│       └── favicon.svg
```

## Installation / Utilisation

Aucune dépendance ni serveur nécessaire :

```bash
git clone https://github.com/DocariDR/company-fhc-group.git
cd company-fhc-group
```

Puis ouvrir `index.html` directement dans un navigateur.

## Historique des versions

| Version | Contenu |
|---|---|
| `v1.0.0` | Version initiale : structure multipage (Accueil, À propos, Contact), contenu de démonstration |
| `v2.0.0` | Refonte : rebranding "Fidexa Conseil", contenu réel, sections hero et stats, formulaire connecté à Web3Forms (envoi, anti-spam, page de confirmation), réorganisation des fichiers (`assets/`), typographie personnalisée |

## Roadmap

Prochaines améliorations envisagées, dans l'ordre de priorité :

### 1. JavaScript
- [ ] État actif du menu géré dynamiquement en JS (actuellement en dur par page via `class="active"`)
- [ ] Validation du formulaire de contact côté client (messages d'erreur personnalisés)
- [ ] Animations légères au scroll sur la page d'accueil

### 2. Accessibilité
- [ ] Lien d'évitement ("aller au contenu principal") pour la navigation clavier
- [ ] Vérification des contrastes texte/fond (WebAIM)

### 3. Technique
- [ ] Minification CSS avant mise en production

## Auteur

**Ricardo Dovonou (DocariDR)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardo-dovonou)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/DocariRD)
[![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=flat&logo=bluesky&logoColor=white)](https://bsky.app/profile/docaridr.bsky.social)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/DocariDR)