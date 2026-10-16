# Bit Group – Astro-verkkosivusto

Suomenkielinen responsiivinen sivusto. Astro 5, staattinen julkaisu Cloudflare Pagesiin.

## Käyttö

```bash
npm install
npm run dev
npm run build
```

## GitHub + Cloudflare Pages

1. Luo GitHubiin yksityinen repository (esim. `bitgroup-website`).
2. Siirrä projektin tiedostot repositoryyn (säilytä hakemistorakenne).
3. Cloudflare Dashboard → Workers & Pages → Create → Pages → Connect to Git.
4. Valitse repository. Build command: `npm run build`, output directory: `dist`.
5. Julkaise ja lisää oma verkkotunnus vasta tarkistuksen jälkeen.

## Ennen julkaisua

- Nykyinen logo on koodilla toteutettu väliaikainen tekstilogo; korvaa hyväksytyllä V2-logotiedostolla.
- Tarkista tekstit, palvelut ja brändin yksityiskohdat.
- Lisää vahvistetut yhteystiedot ja toimiva yhteydenottotapa; etusivun linkki ohjaa toistaiseksi nykyiselle sivustolle.
- Testaa mobiili, saavutettavuus ja hakukonenäkyvyys.
- Cloudflaren custom domain vasta kun sivusto on valmis.

## Päivitys V2
Valittu V2-geometrinen logo on rajattu aiemmasta brändiesityskuvasta. Korvaa PNG-tiedostot lopullisilla läpinäkyvillä vektoritiedostoilla, kun ne valmistuvat. Logo on tässä esikatselulaatuinen.
