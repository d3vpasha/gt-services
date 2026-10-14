# GT Services – site vitrine

Site vitrine de GT Services, l'entreprise de ramonage, petits travaux et motoculture de Gaël Tijou à Clessé (Deux-Sèvres).
HTML, CSS et JS natifs : aucune étape de build, aucune dépendance.

Production : https://gt-services-one.vercel.app

## Arborescence

```
index.html                     page unique, sprite d'icônes inline, JSON-LD LocalBusiness
assets/css/styles.css          styles, variables de couleur, mode sombre
assets/js/main.js              menu mobile, apparition au défilement, année, formulaire mailto
assets/img/logo.svg            logo couleur (écusson bordeaux GT + SERVICES)
assets/img/logo-mono-blanc.svg logo blanc (footer, carte du hero, en-tête en mode sombre)
assets/img/favicon.svg         écusson carré
robots.txt                     autorise tout, pointe vers le sitemap
sitemap.xml                    une seule URL
```

## Lancer en local

```sh
python3 -m http.server 8000
```

Puis ouvrir http://localhost:8000.

## TODO

- Assurance : préciser l'assurance réellement souscrite (bandeau de réassurance).
- Email : remplacer `gt.servicesdu79@gmail.com` par une adresse professionnelle (contact, formulaire, JSON-LD).
- Petits travaux et motoculture : faire préciser les prestations.
- Secteur : faire confirmer la liste des communes.

## Versions

| Version | Date | Direction visuelle |
|---|---|---|
| v1 | 2026-10-14 | Bordeaux et anthracite du camion, hero clair en deux colonnes avec carte de visite, services en rangées alternées |
