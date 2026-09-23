# Zabiegowo i Tlenowo — mockup strony

Statyczny mockup (HTML/CSS, bez zależności) strony dla gabinetu "Zabiegowo i Tlenowo" w Strzegowie.

## Pliki
- `index.html` — strona główna
- `zabiegi.html` — opis zabiegów
- `cennik.html` — cennik (ceny to placeholdery `[CENA]` — do uzupełnienia)
- `o-nas.html` — o nas
- `kontakt.html` — kontakt / godziny
- `style.css` — wspólne style

## Jak wrzucić na GitHub Pages (3 kroki)

1. Na github.com utwórz nowe, puste repozytorium (np. `zabiegowo-tlenowo`), bez README.
2. W folderze z tymi plikami:
   ```
   git init
   git add .
   git commit -m "Mockup strony Zabiegowo i Tlenowo"
   git branch -M main
   git remote add origin https://github.com/TWOJA-NAZWA/zabiegowo-tlenowo.git
   git push -u origin main
   ```
3. W repo na GitHubie: Settings → Pages → Source: wybierz branch `main`, folder `/ (root)` → Save.
   Po chwili strona będzie dostępna pod `https://TWOJA-NAZWA.github.io/zabiegowo-tlenowo/`.

Nie trzeba żadnego hostingu ani serwera — to czysty HTML/CSS, działa od razu.
