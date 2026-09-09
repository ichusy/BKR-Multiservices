# Cocci Brunch Store — site vitrine

Contenu (menu, à propos, avis) rédigé à partir des photos vues en aperçu chat. Il manque encore les **fichiers réels** des images pour qu'elles s'affichent sur le site — voir la liste exacte ci-dessous.

## Structure

```
cocci-brunch-store/
├── index.html          # header, hero, à propos, menu, avis, contact, footer — contenu rédigé
├── css/style.css        # palette dérivée du logo (crème / bordeaux / noir) + typographie + responsive
├── js/main.js            # toggle du menu mobile
└── assets/images/
    ├── logo/
    ├── hero/
    ├── menu/
    └── lieu/
```

## Fichiers images attendus (noms exacts déjà câblés dans index.html)

| Emplacement | Fichier attendu | Contenu |
|---|---|---|
| `assets/images/logo/` | *(nom libre)* | Logo officiel PNG/SVG — à intégrer dans le header et en favicon |
| `assets/images/hero/` | `hero.jpg` | Visuel principal du hero (photo ou vidéo) |
| `assets/images/lieu/` | `terrasse.jpg` | Terrasse extérieure (mobilier bordeaux) |
| `assets/images/lieu/` | `concept-store.jpg` | Coin boutique / céramiques |
| `assets/images/menu/` | `salade-burrata-fraises.jpg` | Salade burrata, fraises, roquette, pignons |
| `assets/images/menu/` | `tartine-burrata-jambon.jpg` | Tartine burrata, jambon, fraises, pistaches |
| `assets/images/menu/` | `croque-cocci.jpg` | Croque-monsieur gratiné + salade |
| `assets/images/menu/` | `burger.jpg` | Burger + salade |
| `assets/images/menu/` | `eclair-pistache.jpg` | Duo d'éclairs pistache |
| `assets/images/menu/` | `pain-perdu.jpg` | Pain perdu, fruits rouges, glace vanille |

## Palette (dérivée du logo)

- Crème (fond) : `#FAF4E6`
- Bordeaux (accent principal, texte du logo) : `#7A2B1B`
- Bordeaux foncé (hover) : `#5C1F12`
- Encre quasi-noire (texte, détails coccinelle) : `#241C17`

## Ce qu'il reste à faire

- Récupérer les fichiers réels (logo + photos ci-dessus) via lien Drive/URL et les déposer aux emplacements indiqués
- Intégrer le logo dans le header (à la place du logo texte) et en favicon
- Choisir la photo hero définitive (actuellement `hero.jpg` générique)
- Intégrer l'iframe Google Maps dans `.contact-map`
- Ajouter les vrais liens réseaux sociaux dans le footer
- Relire/valider les textes (à propos, descriptions des plats) avec le client
