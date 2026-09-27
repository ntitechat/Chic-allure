# Fassions Mode

Prototype fonctionnel d'une application de mode personnalisée.

## Fonctionnalités incluses
- Météo du jour via Open-Meteo (sans clé API) avec géolocalisation navigateur et fallback Paris.
- Recommandation de tenue selon température et pluie.
- Garde-robe locale avec ajout d'images depuis téléphone/ordinateur.
- Catégories : jupes, pantalons, robes, hauts, manteaux, chaussures, boucles d'oreilles, colliers, bracelets, sacs.
- Reconnaissance de catégorie simple à partir du nom du fichier lors de l'import.
- Recherche, filtres et suppression d'articles.
- Looks selon ambiance : Chic, Élégante, Décontractée, Soirée, Travail, Romantique.
- Cinq ambiances : Glamour, Sophistiquée, Chic, Féminine, Audacieuse.
- Profil et persistance de la garde-robe dans localStorage.
- Visuels de démonstration utilisant les photos fournies comme modèle.

## Lancer le projet
Prérequis : Node.js 18+.

```bash
npm install
npm run dev
```
Puis ouvrir l'adresse affichée par Vite.

## Build production
```bash
npm run build
npm run preview
```

## À prévoir pour une vraie mise en production
- Backend/authentification et stockage cloud des vêtements.
- Suppression automatique du fond des photos et vraie classification IA des vêtements.
- API météo plus complète et recherche de ville.
- Base de données des tailles/couleurs/matières.
- Comptes utilisateurs, synchronisation multi-appareils et notifications.
- Publication App Store/Google Play via React Native, Expo ou Capacitor.
