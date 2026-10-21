# Bla Bla New — sajt

Isti responzivni sajt za desktop i mobilni (`index.html`).

## Sadržaj
- `index.html` — sajt
- `support.js`, `image-slot.js` — skripte koje sajt koristi
- `.image-slots.state.json` — fotografije iz hero i „O nama“ sekcije
- `gallery/` — svih 9 slika iz galerije
- `.nojekyll` — obavezno, da GitHub Pages ne sakrije fajl sa fotografijama
- `robots.txt`, `sitemap.xml`

## Objavljivanje na GitHub Pages
1. Napravite novi repozitorijum na GitHub-u.
2. Otpremite SVE fajlove iz ovog foldera u koren repozitorijuma (uključujući skrivene `.nojekyll` i `.image-slots.state.json`).
3. Settings → Pages → Source: „Deploy from a branch“, grana `main`, folder `/ (root)`.
4. Sajt će biti na `https://<korisnik>.github.io/<repo>/`.

Pre objave u `sitemap.xml`, `robots.txt` i `index.html` (og:url) zamenite `https://www.example.com/` pravim domenom.
