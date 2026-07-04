# Elise Marlowe — Life & Mindset Coach · szablon strony (HTML master)

Autorski, wielostronicowy design (biel / krem / piasek / czerń) — master do
dystrybucji na Canva, Wix i Squarespace. Zero JavaScriptu w layoucie
(tylko dekoracyjna animacja odznaki w CSS), więc importery nie mają czego zepsuć.

## Pliki
- `index.html` — Home (hero, o mnie + odznaka + karta z cytatem, pasek obszarów,
  3 pakiety, produkty, statystyki, freebie, ticker, opinia, blog, CTA)
- `about.html` — historia, wartości, cytat, kwalifikacje
- `work-with-me.html` — intro, pasek "w każdym planie", cennik 3 planów, proces, opinia
- `shop.html` — kategorie + 6 produktów + freebie
- `blog.html` — featured + grid 6 wpisów + newsletter
- `styles.css` — wspólny design system (kolory/typografia w zmiennych `:root`)

## Publikacja na GitHub Pages (Twój sprawdzony flow z "Newlywed Times")
1. Nowe repo → wgraj **5 plików .html + styles.css** (pliki `_*` i `build.py` to źródła, niepotrzebne).
2. Settings → Pages → Deploy from branch → main → root.
3. Po ~1 min strony żyją pod `https://TWOJLOGIN.github.io/REPO/` (+ `/about.html` itd.).

## Import
- **Canva:** przez connector — podajesz mi URL z GitHub Pages, importuję każdą podstronę osobno.
- **Wix:** analogicznie przez connector Wix (import z URL). Uwaga: trafi do Harmony.

## Podmiana treści
- Placeholdery zdjęć = beżowe bloki `✦ IMAGE` (klasa `.ph`) — podmień na Midjourney.
- Kolory: zmienne w `:root` w `styles.css` (jedna edycja = cała paleta).
- Fonty: Cormorant Garamond / Pinyon Script / Jost (Google Fonts — są też w Canvie).
