# Auto škola START DNJ — sajt

Statički jednostranični sajt auto-škole START DNJ (Niš).

## Struktura
- `index.html` — cela stranica
- `support.js` — runtime potreban za prikaz
- `images/` — sve fotografije (logo, hero, galerija)

## Objavljivanje na GitHub Pages
1. Napravite novi repozitorijum i dodajte sve fajlove iz ovog foldera u koren (`index.html`, `support.js`, `images/`).
2. U repozitorijumu: **Settings → Pages → Build and deployment → Source: Deploy from a branch**, izaberite `main` i folder `/root`.
3. Sačekajte par minuta — sajt će biti dostupan na `https://<korisnik>.github.io/<repo>/`.

## Lokalni pregled
Otvorite `index.html` preko lokalnog servera (npr. `python3 -m http.server`) jer se `support.js` učitava kao skripta. Dvoklik na fajl takođe najčešće radi.

## Napomene za ažuriranje
- Fotografije zamenite fajlovima u `images/` (zadržite ista imena) ili izmenite putanje u `index.html`.
- Deo tekstova (cene, uslovi, radno vreme, FAQ) su predlog i treba ih potvrditi/izmeniti pre objave.
