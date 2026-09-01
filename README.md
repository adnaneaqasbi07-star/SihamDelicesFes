# Siham Délice de Fès

Application de gestion de recettes marocaines — 120 recettes trilingues
(arabe, français, anglais) : gâteaux et pâtisseries marocaines,
préparations traditionnelles, gâteaux modernes, glaces et sorbets.

## Utilisation

Ouvrir `index.html`. Sur iPhone : ouvrir l'adresse dans Safari,
puis **Partager → Sur l'écran d'accueil**.

## Fonctions

- Interface trilingue avec bascule droite-à-gauche pour l'arabe
- Recherche par nom, catégorie ou ingrédient, dans les trois langues
- Calcul automatique des quantités selon le nombre de personnes,
  avec trois modes d'échelle (proportionnel, fixe, atténué)
- Liste de courses agrégée, avec conversion des unités
- Suivi du stock
- Fiches imprimables au format A4, dans la langue de votre choix
- Photos depuis la pellicule, réduites automatiquement
- Export CSV vers Numbers ou Excel, sauvegarde JSON restaurable
- Fonctionne hors ligne

## Fichiers

| Fichier | Rôle |
| --- | --- |
| `index.html` | L'application entière, autonome |
| `sw.js` | Service worker, fonctionnement hors ligne |
| `manifest.webmanifest` | Déclaration d'application installable |
| `icon-*.png` | Icônes d'écran d'accueil |

## Données

Les recettes sont enregistrées dans le stockage local du navigateur,
sur chaque appareil. Pour les transférer d'un appareil à l'autre :
Réglages → Sauvegarde complète (JSON), puis Restaurer une sauvegarde.
