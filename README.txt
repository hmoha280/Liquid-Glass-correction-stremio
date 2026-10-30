# Stremio Liquid Glass — PWA

Ce dossier contient une application web installable (PWA) pour iPad.

## Installation
1. Publier **tout le contenu** de ce dossier sur un hébergement HTTPS statique (par exemple GitHub Pages ou Netlify).
2. Ouvrir l'adresse HTTPS dans Safari sur l'iPad.
3. Appuyer sur Partager → Sur l'écran d'accueil.
4. Lancer l'icône Stremio Glass.

## Fonctionnalités présentes
- Interface sombre Liquid Glass responsive, adaptée au paysage.
- Ajout manuel de manifestes HTTPS d'addons Stremio.
- Lecture des manifestes et chargement de catalogues compatibles exposés en JSON.
- Catégories Films, Séries, Animés (détection indicative par nom/id), TV (selon type annoncé).
- Recherche dans les métadonnées déjà chargées.
- Liste d'addons enregistrée localement sur l'appareil.
- Cache de l'interface pour un lancement hors ligne.

## Limites importantes
- Ce projet n'est pas l'application officielle Stremio et n'est pas affilié à Stremio.
- Il ne se connecte pas au compte Stremio et ne synchronise pas la bibliothèque, les favoris ni la progression.
- Il ne lit pas les vidéos.
- Les addons peuvent échouer si leur serveur interdit les requêtes navigateur (CORS), exige une authentification, ou utilise une route de catalogue différente.
- Aucun mot de passe, jeton ou identifiant de compte ne doit être ajouté dans cette application.
- L'orientation PWA est une indication ; Safari/iPadOS peut conserver son propre comportement d'affichage.

Ce dossier est un premier socle fonctionnel, pas une application Stremio complète.
