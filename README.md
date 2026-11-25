# Portfolio – Alexandre Filipowitz

Statische Webseite aus HTML und CSS, ohne Build-Schritt. Läuft direkt auf GitHub Pages.

## Aufbau

| Datei | Seite |
|---|---|
| `index.html` | Startseite |
| `projekte.html` | Projektübersicht |
| `eco-island.html` | Case Study Eco Island (Migros) |
| `abo-manager.html` | Case Study Abo-Manager (SGKB) |
| `ueber-mich.html` | Über mich |
| `skills.html` | Skills (Fähigkeiten, Tools, Ausbildung) |
| `kontakt.html` | Weiterleitung zur Kontakt-Leiste |
| `404.html` | Seite für falsche Adressen |
| `css/style.css` | Gestaltung aller Seiten |
| `images/` | Bilder aus den Case Studies |
| `fonts/` | Hier kommt `aachen-bold.woff2` hin |

Kopfbereich und Fusszeile stehen in jeder HTML-Datei. Wenn du dort etwas änderst (z.B. den LinkedIn-Link), änderst du es in allen Dateien.

## Noch offen

- Lebenslauf: gelb markierte Platzhalter ersetzen
- LinkedIn-Link: `DEIN-PROFIL` in allen Dateien ersetzen
- Eco Island: Zeitraum und Anzahl Interviews
- Schrift Aachen Bold als `fonts/aachen-bold.woff2` ablegen

## Lokal ansehen

`index.html` doppelklicken, dann im Browser durch die Seiten klicken.

## Veröffentlichen

Repository `portfolio`, Adresse: https://alexxs360.github.io/portfolio/

Settings → Pages → Source: *Deploy from a branch*, Branch `main`, Ordner `/ (root)`.

## Designsystem (in `css/style.css` unter `:root`)

| Stufe | Variable | Grösse | Schrift | Verwendung |
|---|---|---|---|---|
| Display | `--fs-display` | 42–86 px | Source Serif 4, 700 | Name im Hero, Seitentitel |
| H2 | `--fs-h2` | 28–48 px | Source Serif 4, 700 | Abschnittstitel, Fussleiste |
| H3 | `--fs-h3` | 20–24 px | Inter, 600 | Projekt- und Kartentitel, Skills |
| Lead | `--fs-lead` | 19–26 px | Montserrat 300 / Inter 500 | Einleitungen, Band, Zitate |
| Body | `--fs-body` | 18 px (mobil 17) | Inter, 400 | Fliesstext |
| Body S | `--fs-body-s` | 16 px | Inter | Kartentext, Kontakt |
| Small | `--fs-small` | 15 px | Inter | Navigation, Bildlegenden, Meta |
| Label | `--fs-label` | 14 px | Montserrat/Inter | Abschnitts-Labels, Fusszeile |
| Button | `--fs-button` | 15–18 px | Montserrat, 500 | alle Buttons |

Abstände: `--space-top`, `--space-title`, `--space-section`. Farben: `--accent` (Lila), `--band` (Lavendel), `--logo-shadow` (Neon-Violett).
