# Cocci Brunch Store — site vitrine

Site construit à partir des photos réelles fournies par le client (logo, menu, terrasse, concept store), récupérées depuis le dossier Google Drive partagé.

## Structure

```
cocci-brunch-store/
├── index.html          # header, hero, à propos, menu, avis, contact, footer
├── css/style.css        # palette dérivée du logo (crème / bordeaux / noir) + typographie + responsive
├── js/main.js            # toggle du menu mobile
└── assets/images/
    ├── logo/
    │   ├── cocci-logo.png        # logo fond transparent (header + hero)
    │   ├── favicon-16.png, favicon-32.png, apple-touch-icon.png
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

## Hero simplifié

À la demande du client (page d'accueil "plus blanche et simple"), le hero n'utilise plus de photo en fond : logo centré sur fond blanc, accroche et boutons d'action. Le logo a été nettoyé (fond transparent) à partir de la capture reçue, et recadré pour le header, le hero et le favicon (coccinelle seule).

## Palette (couleur exacte du logo)

- Beige (fond, échantillonné sur le fond du logo) : `#FEF9F0`
- Bordeaux (accent principal, texte du logo, mobilier terrasse) : `#7A2B1B`
- Bordeaux foncé (hover) : `#5C1F12`
- Encre quasi-noire (texte, détails coccinelle) : `#241C17`

## Curseur personnalisé

Le curseur de la souris est une petite coccinelle (`assets/images/logo/cursor-ladybug.png`, 32×32, recadrée depuis le logo), appliquée sur tout le site via `cursor: var(--cursor-ladybug)`.

## Ce qu'il reste à faire

- Intégrer l'iframe Google Maps dans `.contact-map`.
- Ajouter les vrais liens réseaux sociaux dans le footer.
- Relire/valider les textes et noms de plats avec le client (descriptions rédigées à partir des photos, pas de la carte officielle).
- Compléter le menu si d'autres catégories/plats existent (boissons notamment, actuellement sans photo).
- Si un fichier logo vectoriel (SVG) existe, il pourrait remplacer le PNG pour une netteté parfaite à toutes les tailles.
