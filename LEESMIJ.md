# Zeldzaamheidsklassen vogels Nederland

Meetmethode en doorgerekende cijfers voor de klassen algemeen, vrij algemeen, zeldzaam en
zeer zeldzaam op waarneming.nl.

Alles zit in `index.html` — één zelfstandig bestand, geen build, geen afhankelijkheden
behalve de mermaid-bibliotheek voor de beslisboom (wordt van een CDN geladen).

## Aanpassen
Rechtstreeks in `index.html`. Op github.com kan dat in de webeditor: bestand openen,
potloodje, wijzigen, "Commit changes". Binnen een minuut staat het live.

## Publiceren
Repo → Settings → Pages → Source: "Deploy from a branch" → branch `main`, map `/ (root)`.

## Bronnen achter de cijfers
- Broedparen: Sovon-jaarrapporten, laatst *Broedvogels in Nederland 2025* (rapport 2026/41)
- Telpostcijfers: trektellen.nl
- Ontdubbelde aantallen: waarneming.nl-API, 2021–2025
- De onderliggende databestanden staan niet in deze repo maar in de werkmap `vogelzeldzaamheid/`
