# EquiTable 🥦

> Le savoir nutritionnel appartient à tout le monde.

EquiTable est un site de référence pour les recommandations nutritionnelles, personnalisé selon le profil social, culturel et de santé de chaque utilisateur. Gratuit, sans publicité, sans revente de données.

## Mission

Réduire les inégalités d'accès à l'information nutritionnelle scientifique en France.

## Fonctionnalités

- Profil personnalisé (questionnaire en 7 étapes, anonyme si souhaité)
- Tableau de bord adapté au profil + membres du foyer
- Rubriques scientifiques sourcées (ANSES, INSERM, INRAE, HAS)
- Carte des ressources locales (producteurs, marchés, épiceries sociales)
- Communauté et événements locaux
- Module épidémiologique (cohorte de recherche)

## Structure du projet

```
EquiTable/
├── index.html                  ← Page d'accueil
├── README.md
├── css/
│   └── style.css               ← Styles principaux (partagés par toutes les pages)
├── data/                       ← Données du site (JSON)
│   ├── locations.json          ← Ressources locales (carte)
│   ├── evenements.json         ← Événements locaux
│   ├── recettes.json           ← Recettes (semainier)
│   └── rubriques.json          ← Rubriques nutritionnelles (recherche)
└── pages/                      ← Pages de contenu
    ├── questionnaire.html      ← Création de profil (7 étapes)
    ├── dashboard.html          ← Tableau de bord personnalisé
    ├── rubriques.html          ← Rubriques nutritionnelles par thème
    ├── recherche.html          ← Recherche dans les rubriques
    ├── carte.html              ← Carte des ressources locales (Leaflet)
    ├── semainier.html          ← Semainier de recettes
    ├── evenements.html         ← Événements locaux
    ├── bases-essentielles.html ← Bases de la nutrition
    ├── pathologies.html        ← Index des pathologies
    └── diabete-type2.html      ← Fiche pathologie : diabète de type 2
```

> Note : le JavaScript est pour l'instant inclus directement dans chaque page HTML
> (pas de fichier `.js` séparé). Les données sont chargées dynamiquement depuis `data/`.

## Déploiement

Ce projet est déployé via Vercel depuis GitHub.

1. Cloner le dépôt
2. Connecter à Vercel
3. Déploiement automatique à chaque modification

## Partenaires scientifiques

ANSES · INSERM · INRAE · NutriNet-Santé · Université Toulouse III · HAS · Santé Publique France · Certificat NUTRIvie

## Éthique & données

- Aucune donnée vendue à des tiers
- Conformité RGPD
- Mode anonyme disponible
- Données de santé jamais transmises à des IA externes

## Équipe

Projet étudiant — Certificat NUTRIvie, Toulouse 2025.

---

*EquiTable est un projet à but non lucratif.*
