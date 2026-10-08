# CalorySnap V1

Application personnelle de suivi nutritionnel, sans abonnement, utilisable depuis Safari sur iPhone et hébergeable sur GitHub Pages.

## Fonctions
- Journal quotidien : calories, protéines, glucides et lipides, objectif calorique.
- Favoris personnalisés (Clear Whey, collations, repas) avec ajout rapide.
- Bibliothèque de contenants et calcul du poids net = poids total − tare.
- Photo locale de référence, sélection manuelle des aliments, curseurs de grammage.
- Estimation centrale et fourchette illustrative ±25 %, historique 14 jours.
- Export/import JSON pour sauvegarder les données.

## Limites importantes
La V1 **ne reconnaît pas automatiquement les aliments ni les contenants** : aucune IA locale fiable n'a encore été intégrée ni validée sur iPhone 15. Les valeurs alimentaires intégrées sont des approximations pour 100 g, pas une base nutritionnelle officielle. Les fourchettes ne sont pas des intervalles de confiance validés. La photo n'est pas envoyée sur un serveur ni sauvegardée dans le journal.

Les données sont stockées localement dans le navigateur (localStorage). L'effacement des données Safari ou l'utilisation d'un autre navigateur/appareil peut faire perdre le journal : exporter régulièrement une sauvegarde.

## Mise en ligne
Dans GitHub : Settings → Pages → Build and deployment → Deploy from a branch → main → /(root) → Save.
Adresse attendue : https://matthieudrazic.github.io/calorysnap/
Ouvrir avec Safari puis Partager → Sur l'écran d'accueil.

## Confidentialité
Aucun compte, aucun serveur d'IA, aucune clé API et aucun abonnement. Ne pas considérer ces estimations comme des mesures médicales.
