#  Les Tresses Dorées - Site Vitrine

## 📌 Description

**Les Tresses Dorées** est un site vitrine professionnel développé pour un salon de coiffure situé à Brazzaville, République du Congo. Ce projet a été réalisé dans le cadre de la formation Akieni Academy (Full Stack) et constitue une démonstration complète des compétences en HTML5, CSS3, et Git/GitHub. Le site présente l'entreprise locale, ses services, et permet aux clients potentiels de prendre contact facilement. Il s'agit d'un projet pédagogique qui simule la création d'un site web d'entreprise locale congolaise.

## 🎯 Objectifs du projet

Ce projet visait à mettre en pratique les compétences fondamentales du développement web front-end : maîtrise du HTML5 sémantique pour structurer correctement les pages web, utilisation avancée de CSS3 avec Flexbox et Grid pour créer des mises en page modernes et responsives, gestion complète de versions avec Git et GitHub (10+ commits), compréhension des principes de design cohérent (couleurs, typographie, espacement), et déploiement d'un site statique sur GitHub Pages. Le projet a également permis de travailler la structuration d'un projet web avec une architecture de dossiers claire et professionnelle.

## 🛠️ Technologies utilisées

- **HTML5** (structuration sémantique des pages)
- **CSS3** (Flexbox, Grid, animations, media queries pour le responsive design)
- **Git** (gestion de versions)
- **GitHub** (hébergement du code et déploiement via GitHub Pages)
- **Visual Studio Code** (environnement de développement)

##  Fonctionnalités

Le site se compose de trois pages interconnectées : une page d'accueil avec une section Hero visuellement impactante utilisant une image de fond en dégradé et un message d'accueil, une présentation détaillée du salon avec une mise en page en deux colonnes. La page services présente quatre prestations sous forme de cartes interactives (coupe et coiffure à 15 000 FCFA, tresses africaines à 25 000 FCFA, soins capillaires à 10 000 FCFA, maquillage à 20 000 FCFA) avec des effets de survol élégants. La page contact intègre un formulaire de contact fonctionnel avec des champs validés (nom, email, téléphone, sujet, message) et des informations complètes du salon (adresse, téléphone, email, horaires d'ouverture). La navigation est cohérente sur toutes les pages avec un menu sticky et des liens actifs. Le footer répète les informations de contact pour une meilleure expérience utilisateur. Le site est entièrement responsive avec deux breakpoints pour tablette et mobile, adaptant automatiquement la mise en page.

## 📂 Structure du projet

```
site-vitrine-brazzaville/
│
├── index.html              # Page d'accueil (Hero + présentation)
├── services.html           # Page des services (4 cartes)
├── contact.html            # Page de contact (formulaire + coordonnées)
├── css/
│   └── style.css          # Styles complets du site (responsive inclus)
├── images/                 # Images du site (hero-bg.jpg, service1-4.jpg)
└── README.md              # Documentation du projet
```

## ⚙️ Installation et utilisation

Pour installer et utiliser ce projet localement : Clonez d'abord le dépôt GitHub avec la commande `git clone https://github.com/thomas-issoko/site-vitrine-brazzaville.git`, puis ouvrez le dossier dans Visual Studio Code. Aucune dépendance n'est nécessaire car il s'agit d'un site statique en HTML/CSS pur. Ouvrez le fichier `index.html` dans votre navigateur pour visualiser le site. Pour une expérience de développement optimale, utilisez l'extension Live Server dans VS Code qui permet de visualiser les changements en temps réel. Le site peut être déployé gratuitement sur GitHub Pages en activant l'option dans les paramètres du dépôt.

##  Commandes utiles

Initialisation du dépôt Git : `git init`. Ajout des fichiers au staging : `git add .` ou `git add nom_du_fichier`. Sauvegarde des modifications avec commit : `git commit -m "message descriptif"`. Association au dépôt distant : `git remote add origin https://github.com/thomas-issoko/site-vitrine-brazzaville.git`. Envoi du code vers GitHub : `git push -u origin main`. Vérification de l'état des fichiers : `git status`. Visualisation des commits : `git log --oneline`. Création d'une branche : `git branch nom-branche`. Changement de branche : `git checkout nom-branche`.

## 👀 Aperçu

Le site arbore une identité visuelle forte avec une palette de couleurs élégante : noir profond (#1A1A1A) pour le fond, doré (#D4AF37) pour les accents et le logo, et blanc (#FFFFFF) pour le texte. La page d'accueil présente une bannière Hero avec le slogan "L'excellence de la coiffure à Brazzaville" et un appel à l'action vers les services. Les cartes de services s'animent au survol avec une translation vers le haut et une ombre renforcée. Le formulaire de contact dispose d'un focus doré sur les champs interactifs. Le design est moderne, épuré et professionnel, avec une navigation intuitive. Sur mobile, le menu se transforme en colonne verticale et les grilles passent à une seule colonne pour une lisibilité optimale. Les polices utilisées (Segoe UI, Tahoma) assurent une excellente lisibilité sur tous les supports.

## 🔧 Améliorations possibles

Plusieurs améliorations pourraient enrichir ce projet : ajouter un système de réservation en ligne avec calendrier interactif, intégrer une carte Google Maps pour localiser plus facilement le salon, créer un blog pour partager des conseils capillaires et actualités, ajouter une galerie photos avant/après pour mettre en valeur les réalisations, implémenter un système de témoignages clients, intégrer des boutons de partage sur les réseaux sociaux fonctionnels (Facebook, Instagram, TikTok), ajouter une newsletter pour fidéliser la clientèle, optimiser les performances avec des images WebP, et améliorer le référencement naturel avec des balises meta plus complètes. Une version dynamique pourrait également être envisagée avec un backend pour gérer les messages du formulaire et une base de données pour les rendez-vous.

## 👨‍💻 Auteur

Réalisé par **ISSOKO Thomas** dans le cadre de la formation **Akieni Academy - Full Stack Web Development**.