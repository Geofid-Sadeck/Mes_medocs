# 💊 Mes Médicaments — Suivi grossesse

Application web progressive (PWA) pour le suivi des médicaments pendant la grossesse. Fonctionne hors-ligne, s'installe sur l'écran d'accueil comme une vraie app.

## Fonctionnement

- **Dès la première prise** (Tot'hema au réveil), l'application calcule automatiquement les horaires de tous les médicaments suivants.
- **Alarmes et rappels** : notification 5 min avant + à l'heure exacte.
- **Confirmation précise** : l'heure de prise réelle est enregistrée et affichée.
- **Alternance Jour 1/2/3** pour Fifer sirop vs Fer + acide folique.
- Les données sont sauvegardées localement et remises à zéro automatiquement chaque matin.

## Déploiement sur GitHub Pages

1. Créer un nouveau repo GitHub (ex: `medoc-suivi`)
2. Uploader les 3 fichiers : `index.html`, `manifest.json`, `sw.js`
3. Aller dans **Settings → Pages → Source : main branch**
4. L'app sera accessible à `https://[username].github.io/medoc-suivi/`

## Installer sur téléphone (Android)

1. Ouvrir l'URL dans Chrome
2. Appuyer sur les 3 points ⋮ → "Ajouter à l'écran d'accueil"

## Installer sur téléphone (iPhone)

1. Ouvrir l'URL dans Safari
2. Appuyer sur le bouton Partager → "Sur l'écran d'accueil"

## Médicaments suivis

| Heure | Médicament | Délai |
|-------|-----------|-------|
| Réveil | Tot'hema | À jeun (ancre du planning) |
| Réveil + 30 min | Rotavit + Butylscopolamine + Calcium/Magnésium | Après petit-déjeuner |
| +2h | Fifer sirop OU Fer + acide folique | Selon alternance |
| +~9h | Butylscopolamine + Calcium/Magnésium | Après dîner |
| +2h30 | Tardyferon | Soir |
| Si besoin | Maloxine | Min. 2-3h après Tardyferon |

⚠️ **Ne jamais combiner** : Fer + Calcium · Fer + Maloxine
