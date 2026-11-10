# Handbücher – Quellen

© 2026 Christian Haake, alle Rechte vorbehalten.

- `app.html` → `../GravioLOG-Public-Handbuch.pdf`
- `dispo.html` → `../GravioLOG-Public-Dispo-Handbuch.pdf`
- Gestaltung: `handbuch.css`, Bildschirmfotos (Beispieldaten) in `bilder/`

PDF neu erzeugen (Chromium/Playwright):

    node handbuch/quelle/mkpdf.js "$PWD/handbuch/quelle/app.html" "$PWD/handbuch/GravioLOG-Public-Handbuch.pdf"
    node handbuch/quelle/mkpdf.js "$PWD/handbuch/quelle/dispo.html" "$PWD/handbuch/GravioLOG-Public-Dispo-Handbuch.pdf"

Danach die Vorschaubilder `../vorschau-app.jpg` und `../vorschau-dispo.jpg` (Seite 4) und die Seitenzahlen im Abschnitt „Handbücher“ der Webseite prüfen.
