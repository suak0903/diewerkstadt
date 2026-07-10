# DieWerkstadt — Redesign-Entwurf

Unverbindlicher Redesign-Demonstrator für DieWerkstadt, das Unternehmernetzwerk
für Solingen und das Rheinland (deine-werkstadt.de). Erstellt von Dr.-Ing. Suat Akyol.

Live (GitHub Pages): https://suak0903.github.io/diewerkstadt/

## Technik
- Vanilla HTML + CSS + JS, kein Build-Step nötig, kein npm
- Self-hosted Schriften (Anton Display + Be Vietnam Pro Body), kein Google-CDN
- Event-Aushang als Hero-Herzstück, Scrollspy, mobiles Menü, Hero-Parallaxe
- Design-System „Industrial Bold": Anthrazit + Signalrot aus der Marke
- Strukturierte Daten (Organization + Events JSON-LD), noindex (Entwurf)

## Chrome aus einer Quelle
Header, Footer und Demo-Leiste liegen in `partials/` und werden per `node build-site.mjs`
byte-identisch in jede Seite gesetzt (kein Drift). Nach Änderung an einem Partial:
`node build-site.mjs` ausführen, dann committen.

Inhalte und Bilder stammen von der öffentlichen Website deine-werkstadt.de. Kein offizieller Auftritt.
