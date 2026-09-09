# Cocci Brunch Store — site vitrine

Squelette technique en attente de contenu (photos des plats et du lieu, animation hero).

## Structure

```
cocci-brunch-store/
├── index.html          # squelette sémantique (header, hero, à propos, menu, avis, contact, footer)
├── css/style.css        # palette (crème / terracotta / vert sauge) + typographie + responsive
├── js/main.js            # toggle du menu mobile
└── assets/images/
    ├── hero/             # média hero (animation Higgsfield ou photo/vidéo fournie)
    ├── menu/              # photos des plats
    └── lieu/               # photos du lieu / concept store
```

## Ce qu'il reste à faire une fois les photos reçues

- Déposer les photos dans `assets/images/{hero,menu,lieu}`
- Intégrer le média hero dans `.hero-media` (section Hero, `index.html`)
- Rédiger le texte "À propos" (concept store / brunch restaurant)
- Construire les catégories du menu à partir des photos (ex : brunchs salés, sucré, boissons)
- Ajouter 2-3 témoignages neutres dans la section Avis
- Intégrer l'iframe Google Maps dans `.contact-map`
- Ajouter les vrais liens réseaux sociaux dans le footer
- Ajuster la palette/typographie selon l'ambiance des photos reçues
