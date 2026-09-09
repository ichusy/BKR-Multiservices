# Cocci Brunch Store — site vitrine

Squelette technique en attente de contenu (photos des plats et du lieu, animation hero).

## Structure

```
cocci-brunch-store/
├── index.html          # squelette sémantique (header, hero, à propos, menu, avis, contact, footer)
├── css/style.css        # palette dérivée du logo (crème / bordeaux / noir) + typographie + responsive
├── js/main.js            # toggle du menu mobile
└── assets/images/
    ├── logo/               # fichier logo officiel (PNG/SVG) — reçu en aperçu chat, fichier à fournir
    ├── hero/             # média hero (animation Higgsfield ou photo/vidéo fournie)
    ├── menu/              # photos des plats
    └── lieu/               # photos du lieu / concept store
```

## Palette (dérivée du logo)

- Crème (fond) : `#FAF4E6`
- Bordeaux (accent principal, texte du logo) : `#7A2B1B`
- Bordeaux foncé (hover) : `#5C1F12`
- Encre quasi-noire (texte, détails coccinelle) : `#241C17`

## Ce qu'il reste à faire une fois les photos reçues

- Récupérer le fichier logo (PNG/SVG) en pièce jointe et le déposer dans `assets/images/logo/`
- Intégrer le logo dans le header (à la place du logo texte) et en favicon
- Déposer les photos dans `assets/images/{hero,menu,lieu}`
- Intégrer le média hero dans `.hero-media` (section Hero, `index.html`)
- Rédiger le texte "À propos" (concept store / brunch restaurant)
- Construire les catégories du menu à partir des photos (ex : brunchs salés, sucré, boissons)
- Ajouter 2-3 témoignages neutres dans la section Avis
- Intégrer l'iframe Google Maps dans `.contact-map`
- Ajouter les vrais liens réseaux sociaux dans le footer
