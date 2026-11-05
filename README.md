# IG Klima Kürten – Newsletter-Archiv

Startseite mit Ablage der monatlichen Ausgaben. Oktober 2026 liegt unter `ausgaben/2026-10/`. Der Wortlaut dieser Ausgabe entspricht der Druckfassung v14.

Eine weitere Ausgabe wird ein Ordner `ausgaben/jahr-monat/index.html` und ein Eintrag in der Liste auf `index.html`.

## Seiten

- `index.html` – Archiv
- `ausgaben/2026-10/` – Oktober 2026, mit Inhaltsverzeichnis
- `impressum/`, `datenschutz/`, `streitschlichtung/`
- `css/styles.css`, `js/nav.js`, `img/`

## Lokal ansehen

```bash
python3 -m http.server 8080
```

Dann `http://localhost:8080` öffnen.

## Veröffentlichung

`git push igk2 main` aktualisiert https://dna-dieter.github.io/igk2/ .

`git push` ohne Ziel schreibt nach `origin` (https://dna-dieter.github.io/ig-klima-idee/). Das ist die ältere Einzelseite, solange dieser Stand nicht dorthin geschoben wird.
