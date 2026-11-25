# VipPa Team – NFC landing stranice

Jedan Vercel projekat, posebna stranica za svakog člana tima.

| Osoba | Link |
|---|---|
| Dušan Cocić | `/dusan` |
| Aleksandar Trajković | `/aleksandar` |
| Dragan Vasiljević | `/dragan` |

## Struktura

```
favicon.svg      zajednički VipPa logo
vercel.json      podešavanja (čisti linkovi, .vcf kao kontakt)
index.html       početna – preusmerava na vippa-group.com
dusan/
  index.html     stranica
  dusan.jpg      slika
  dusan.vcf      kontakt fajl za dugme "Sačuvaj kontakt"
```

## Nova osoba

1. Kopiraj folder `dusan/` i preimenuj ga (npr. `dragan/`).
2. Preimenuj sliku i .vcf fajl i promeni putanje u `index.html` (`/dragan/dragan.jpg`, `/dragan/dragan.vcf`).
3. Promeni ime, titulu, brojeve, mejl i linkove u `index.html` i `.vcf`.
4. Commit – Vercel sam objavi novu verziju.
