# tracker-depenses
Petite application web pour suivre mes dépenses semaine par semaine, voir où part l'argent par catégorie et garder un œil sur mon budget.

➡️ **[Ouvrir l'application](https://jonathan-ouattara.github.io/tracker-depenses/)**

## Fonctionnalités

- Saisie rapide d'une dépense (montant, jour, catégorie, note)
- Budget par catégorie avec calcul automatique du **reste**
- Vue du budget total et du reste global de la semaine
- Navigation semaine par semaine (chaque lundi repart à zéro, l'historique est conservé par dates réelles)
- Répartition par catégorie avec barres de progression
- Détail jour par jour
- Export / import des données en JSON (sauvegarde et transfert entre appareils)
- Installable sur mobile et ordinateur (PWA, fonctionne plein écran)

## Installation comme application

- **Mobile** : ouvrir le site, puis « Ajouter à l'écran d'accueil ».
- **Ordinateur** : ouvrir le site dans Chrome ou Edge, puis cliquer sur « Installer » dans la barre d'adresse.

## Confidentialité des données

Toutes les données sont stockées **localement** dans le navigateur de l'appareil (`localStorage`). Rien n'est envoyé sur un serveur, rien n'est enregistré dans ce dépôt. Le code publié est uniquement l'application vide.

## Stack technique

HTML / CSS / JavaScript natif, sans dépendance ni build. Stockage via `localStorage`, manifest PWA inline pour l'installation. Un seul fichier : `index.html`.

---

Projet personnel — Jonathan Ouattara

