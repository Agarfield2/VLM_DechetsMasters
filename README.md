# ♻️ DechetsMasters

> **DechetsMasters** est un projet d'application web ludique et participative qui encourage les citoyens à ramasser, identifier et recycler les déchets grâce à un système de collection de cartes, de récompenses et d'échanges.

## 📌 Présentation du projet

DechetsMasters est une application inspirée du principe de collection de cartes de jeux comme Wikimasters. Son objectif est de transformer le ramassage des déchets en une expérience ludique, motivante et éducative.

Les utilisateurs pourront photographier les déchets qu'ils ramassent afin de les identifier et de récupérer des cartes virtuelles associées. Chaque carte possédera ses propres caractéristiques : famille de déchets, rareté, informations sur l'objet, temps de dégradation, impact environnemental et consignes de recyclage.

L'application reposera sur un système de points et de monnaie virtuelle (coins), permettant aux utilisateurs de développer leur collection, d'échanger des cartes et de participer à un marché virtuel.

**L'objectif principal : rendre la collecte des déchets plus attractive tout en sensibilisant les citoyens à la protection de l'environnement.**

## 🎯 Objectifs du projet

- Encourager les citoyens à ramasser les déchets dans leur environnement.
- Sensibiliser les utilisateurs au tri et au recyclage.
- Transformer les actions écologiques en récompenses ludiques.
- Créer une communauté autour de la protection de l'environnement.
- Permettre aux collectivités et associations de mobiliser les citoyens.
- Valoriser les actions réalisées grâce à un système de points et de statistiques.

## 👥 Équipe projet

| Rôle | Membre |
|---|---|
| Product Owner (PO) | Maël Tournus |
| Scrum Master (SM) | Vanille Le Ven |
| Équipe de réalisation | Armand Beharel |
| Équipe de réalisation | Elina Maugis |

## 👤 Utilisateurs et acteurs

### Utilisateur principal : le citoyen / collecteur

Le citoyen est l'utilisateur principal de l'application. Il souhaite rendre son environnement plus propre tout en gagnant des récompenses grâce à ses actions.

Ses principales actions seront :
- Créer un compte et se connecter.
- Consulter une carte interactive pour repérer les déchets signalés.
- Participer à des collectes individuelles ou collectives.
- Photographier les déchets ramassés.
- Déclarer et localiser ses collectes.
- Obtenir des points et des cartes.
- Développer sa collection et échanger ses cartes.
- Utiliser ses points pour obtenir des récompenses.

### Autres acteurs

- **Mairies et collectivités :** encourager les habitants et accompagner la gestion des déchets.
- **Commerçants :** proposer des récompenses aux utilisateurs.
- **Administrateurs :** vérifier les collectes, gérer les comptes et contrôler les points.
- **Associations environnementales :** organiser des événements, des collectes et des défis collectifs.

## 🃏 Fonctionnalités envisagées

### 1. Gestion des utilisateurs
- Création de compte.
- Connexion et déconnexion.
- Gestion du profil utilisateur.
- Consultation du score et de la progression.

### 2. Collection de cartes
- Identification des déchets à partir de photographies.
- Obtention de cartes virtuelles.
- Classement des cartes par familles :
  - Plastiques.
  - Déchets alimentaires.
  - Verre.
  - Métaux.
  - Papier et carton.
  - Autres catégories.
- Système de rareté des cartes.
- Consultation de sa collection personnelle.

### 3. Informations environnementales

Chaque carte devra présenter :
- Le nom et la description de l'objet.
- Sa famille de déchets.
- Son niveau de rareté.
- Son temps de dégradation.
- Son impact sur l'environnement.
- Les consignes de tri et de recyclage.
- La poubelle dans laquelle il doit être déposé.

### 4. Système de récompenses
- Attribution de points après validation d'une collecte.
- Système de monnaie virtuelle (coins).
- Score total de l'utilisateur.
- Catalogue de récompenses.
- Possibilité d'échanger ses points contre des avantages.

### 5. Marché et interactions sociales
- Marché virtuel de cartes.
- Achat et vente de cartes avec des coins.
- Ajout d'amis.
- Échanges de cartes entre utilisateurs.
- Classement des joueurs.

### 6. Carte interactive et collectes
- Visualisation des déchets signalés à proximité.
- Localisation des zones de collecte.
- Déclaration d'une collecte.
- Ajout de photographies comme preuve.
- Possibilité de participer à des opérations collectives.

### 7. Intelligence artificielle
- Analyse des photographies envoyées par les utilisateurs.
- Reconnaissance automatique des déchets.
- Identification de l'objet photographié.
- Association du déchet identifié à une carte de la base de données.

## 🗺️ Parcours utilisateur principal

Le parcours envisagé pour un citoyen sera le suivant :

1. S'inscrire sur le site web.
2. Repérer les déchets sur la carte.
3. Ramasser les déchets.
4. Photographier et déclarer sa collecte.
5. Recevoir des points et éventuellement des cartes.
6. Échanger ses points contre des récompenses.

## 📋 Product Backlog

Les fonctionnalités suivantes constituent le backlog initial du projet.

| Fonctionnalité | Priorité envisagée | Story Points |
|---|---|---:|
| Création de compte et connexion | Must | 5 |
| Page d'accueil et navigation | Must | 3 |
| Base de données des cartes | Must | 5 |
| Affichage des cartes | Must | 3 |
| Recherche et scan des déchets | Must | 8 |
| Collection personnelle | Must | 5 |
| Système de rareté | Should | 2 |
| Score utilisateur | Should | 3 |
| Système de coins | Should | 3 |
| Marché des cartes | Could | 8 |
| Amis et échanges | Could | 8 |
| Reconnaissance des déchets par IA | Could | 13 |
| **Total** | | **66** |

*Les priorités pourront être réévaluées en fonction de l'avancement du projet et des contraintes techniques.*

### Valeur apportée

- **Pour les citoyens :** plaisir de collectionner, reconnaissance des efforts et apprentissage du tri.
- **Pour les associations et les mairies :** mobilisation des habitants et données sur les déchets collectés.
- **Pour l'environnement :** réduction des déchets présents dans l'espace public.
- **Pour l'équipe :** identification rapide des risques techniques, notamment autour de la reconnaissance d'images, et réalisation d'une démonstration convaincante.

## 🚀 MVP – Minimum Viable Product

Le MVP correspond à une première version fonctionnelle du projet, centrée sur les fonctionnalités essentielles.

### Capacité prévisionnelle de l'équipe

L'hypothèse de travail retenue est de 8 points par sprint de 2 heures, avec une adaptation selon les besoins et la complexité des fonctionnalités.

| Sprint | Capacité prévue |
|---|---:|
| Sprint 1 | 8 points |
| Sprint 2 | 12 points |
| Sprint 3 | 12 points |
| Sprint 4 | 8 points |
| **Total** | **40 points** |

La capacité prévisionnelle est donc de 40 points sur les 66 points estimés, soit environ 60 % du backlog initial.

### Objectif du premier sprint

Mettre en place les fondations techniques du projet et obtenir une première version structurée du site web.

**Tâches prévues :**
- Initialiser le projet React avec TypeScript.
- Configurer le dépôt GitHub et le travail collaboratif.
- Préparer la base de données PostgreSQL.
- Développer la première page d'accueil.
- Mettre en place la structure de navigation du site.

**Livrable attendu :** une première structure de site web fonctionnelle avec un environnement de développement configuré.

## 🛠️ Architecture technique

Le projet reposera sur plusieurs technologies complémentaires.

| Technologie | Utilisation |
|---|---|
| React.js | Développement de l'interface utilisateur et gestion des interactions. |
| TypeScript | Typage du code frontend et réduction des erreurs. |
| HTML5 | Structure des pages web. |
| CSS3 | Design, animations et responsive design. |
| PHP | Backend, gestion des utilisateurs, transactions et communication avec la base de données. |
| Python | Développement du service d'intelligence artificielle pour la reconnaissance des déchets. |
| PostgreSQL | Stockage des utilisateurs, cartes, collections, coins et transactions. |
| Git | Gestion des versions du code. |
| GitHub | Centralisation du projet et collaboration entre les membres de l'équipe. |

### Communication entre les technologies

Le fonctionnement prévu lors de la reconnaissance d'un déchet sera le suivant :

1. L'utilisateur photographie un déchet depuis le site web.
2. React transmet la photographie au backend PHP.
3. PHP transmet l'image au service Python.
4. Python analyse l'image et identifie le déchet.
5. PHP récupère le résultat et recherche la carte correspondante dans PostgreSQL.
6. React affiche la carte obtenue dans la collection de l'utilisateur.

### Schéma simplifié de l'architecture

```text
             UTILISATEUR
                  |
                  v
          REACT + TYPESCRIPT
             (Frontend)
                  |
                  v
             BACKEND PHP
                  |
          +-------+-------+
          |               |
          v               v
     POSTGRESQL        SERVICE PYTHON
     (Base de données)  (IA / Analyse)
          |               |
          +-------+-------+
                  |
                  v
          RÉSULTAT DE L'ANALYSE
                  |
                  v
          AFFICHAGE SUR REACT
```

## 🔐 Sécurité et protection des données

Le projet devra respecter les principes essentiels de sécurité et de protection des données personnelles.

Les points de vigilance identifiés sont :
- Respect du RGPD.
- Consentement explicite pour l'utilisation des photographies et de la localisation.
- Stockage sécurisé des mots de passe sous forme de hachage adapté.
- Protection des données personnelles des utilisateurs.
- Limitation de la conservation des photographies au strict nécessaire.
- Sécurisation des échanges entre le frontend et le backend.
- Contrôle des transactions et des échanges de cartes.

## 🎨 Conception et design

La conception graphique sera réalisée selon une approche **Mobile First**, afin de garantir une utilisation optimale sur smartphone.

Les éléments à prévoir :
- Maquettes des principales pages.
- Charte graphique.
- Interface de collection de cartes.
- Page de profil utilisateur.
- Interface de scan des déchets.
- Interface du marché virtuel.
- Navigation simple et intuitive.
- Design responsive pour ordinateur, tablette et mobile.

## 📅 Méthodologie de travail

Le projet sera développé selon la méthodologie **Agile Scrum**.

Les rôles seront répartis de la manière suivante :
- Le Product Owner définit les besoins et priorise le Product Backlog.
- Le Scrum Master facilite l'organisation des sprints et veille au respect de la méthodologie Scrum.
- L'équipe de réalisation développe, teste et améliore les fonctionnalités.

Le travail sera organisé en plusieurs sprints avec des objectifs et des livrables définis.

## 📈 État d'avancement

**État actuel : phase de préparation, avant le début du développement.**

| Étape | État |
|---|---|
| Constitution de l'équipe | Préparée |
| Vision produit | Définie |
| Histoires utilisateurs | Identifiées |
| Product Backlog | Initialisé |
| Estimation des fonctionnalités | Réalisée |
| Définition du MVP | Préparée |
| Choix de l'architecture technique | Définis |
| Maquettes et charte graphique | À réaliser |
| Initialisation technique | À réaliser |
| Développement | À réaliser |
| Tests | À réaliser |

## 🔮 Perspectives d'évolution

Après la réalisation du MVP, plusieurs améliorations pourront être envisagées :

- Développement d'un système de défis écologiques.
- Organisation de collectes collectives.
- Mise en place de classements entre utilisateurs.
- Partenariats avec des commerçants locaux.
- Statistiques sur les déchets ramassés.
- Amélioration de la reconnaissance des déchets par intelligence artificielle.
- Extension du système de récompenses.

---

## 🌍 DechetsMasters : chaque déchet ramassé compte !

**Notre ambition est de transformer un geste écologique en une expérience collective, ludique et valorisante.**