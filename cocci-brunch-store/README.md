# Cocci Brunch Store — site vitrine

Site construit à partir des photos réelles fournies par le client (menu, terrasse, concept store), récupérées depuis le dossier Google Drive partagé.

## Structure

```
cocci-brunch-store/
├── index.html          # header, hero, à propos, menu, avis, contact, footer
├── css/style.css        # palette dérivée du logo (crème / bordeaux / noir) + typographie + responsive
├── js/main.js            # toggle du menu mobile
└── assets/images/
    ├── logo/               # logo officiel (PNG/SVG) — pas encore reçu en fichier autonome
    ├── hero/hero.jpg        # visuel principal du hero
    ├── lieu/
    │   ├── terrasse.jpg       # terrasse extérieure (mobilier bordeaux)
    │   └── concept-store.jpg  # coin boutique / céramiques
    └── menu/
        ├── salade-burrata-fraises.jpg
        ├── tartine-burrata-jambon.jpg
        ├── tartine-saumon.jpg
        ├── croque-burger.jpg     (recadrée depuis une capture combinée)
        ├── eclair-pistache.jpg
        └── pain-perdu.jpg
```

## Palette (dérivée du logo, confirmée sur les photos du lieu)

- Crème (fond) : `#FAF4E6`
- Bordeaux (accent principal, texte du logo, mobilier terrasse) : `#7A2B1B`
- Bordeaux foncé (hover) : `#5C1F12`
- Encre quasi-noire (texte, détails coccinelle) : `#241C17`

## Ce qu'il reste à faire

- **Logo** : je n'ai que des photos où le logo apparaît en petit sur des cartes de menu — il faudrait le fichier logo autonome (PNG/SVG haute résolution) pour l'intégrer dans le header et en favicon (actuellement toujours en logo texte).
- Choisir la photo hero définitive si celle par défaut (éclairs pistache + carte Cocci) ne convient pas.
- Intégrer l'iframe Google Maps dans `.contact-map`.
- Ajouter les vrais liens réseaux sociaux dans le footer.
- Relire/valider les textes et noms de plats avec le client (descriptions rédigées à partir des photos, pas de la carte officielle).
- Compléter le menu si d'autres catégories/plats existent (boissons notamment, actuellement sans photo).
