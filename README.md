# Company Website

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![Status](https://img.shields.io/badge/Status-En%20cours-yellow?style=flat)

Site vitrine multipage réalisé dans le cadre de ma formation pratique en Développement Web chez FHC Groupe Sarl.

## Aperçu

[Cliquez sur moi pour voir le site web de Company Website](https://docaridr.github.io/company-fhc-group/)

## À propos

Ce projet a été réalisé à partir d'un brief donné à l'oral par mon formateur, illustré par des maquettes dessinées au tableau pour chaque page. L'objectif : intégrer un site vitrine multipage (Accueil, À propos, Contact) en HTML5 sémantique et CSS3, en autonomie à partir de ces indications visuelles et verbales.

C'est une première version du projet, des améliorations sont prévues, notamment l'ajout de JavaScript (voir section *Améliorations futures*).

## Fonctionnalités

- Site multipage : Accueil, À propos, Contact
- Navigation sticky avec menu hamburger responsive (CSS pur, via `:has()` et une checkbox)
- Page À propos avec section "Nos membres" en grille flexible
- Formulaire de contact complet (nom, prénom, email, sujet, message)
- Design responsive (media queries pour mobile)

## Technologies utilisées

- **HTML5** sémantique
- **CSS3** (Flexbox, transitions, sélecteur `:has()`, media queries)

## Structure du projet

```
company-website/
├── index.html
├── a-propos.html
├── contact.html
├── style.css
└── images/
    └── images1.jpg
```

## Installation / Utilisation

Aucune dépendance ni serveur nécessaire :

```bash
git clone https://github.com/DocariDR/company-website.git
cd company-website
```

Puis ouvrir `index.html` directement dans un navigateur.

## Améliorations futures

### 1. JavaScript
- [ ] État actif du menu : ajout/retrait dynamique de la classe `.active` sur le lien de navigation correspondant à la page courante
- [ ] Validation du formulaire de contact côté client (messages d'erreur personnalisés)
- [ ] Menu hamburger en JS (remplace le hack CSS `:has()` + checkbox actuel)
- [ ] Animations légères au scroll sur la page d'accueil

### 2. Contenu & design
- [ ] Remplacement des placeholders "Nos membres" (cercles numérotés) par de vraies images
- [ ] Remplacement du texte Lorem ipsum par du contenu réel
- [ ] État `:focus` personnalisé sur les champs du formulaire
- [ ] Feedback visuel après soumission du formulaire

### 3. Accessibilité
- [ ] `aria-label` sur le bouton hamburger
- [ ] Lien d'évitement ("aller au contenu principal") pour la navigation clavier
- [ ] Vérification des contrastes texte/fond (WebAIM)

### 4. SEO / Métadonnées
- [ ] Meta description et Open Graph sur les 3 pages
- [ ] Favicon


## Auteur

**Ricardo Dovonou (DocariDR)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ricardo-dovonou)
[![X](https://img.shields.io/badge/X-000000?style=flat&logo=x&logoColor=white)](https://x.com/DocariRD)
[![Bluesky](https://img.shields.io/badge/Bluesky-0285FF?style=flat&logo=bluesky&logoColor=white)](https://bsky.app/profile/docaridr.bsky.social)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/DocariDR)
