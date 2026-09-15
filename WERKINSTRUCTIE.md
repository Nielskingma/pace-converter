# pace-converter — WERKINSTRUCTIE

## Doel
PWA voor hardlopers om tempo (pace) en snelheid om te rekenen, inclusief splitstijden.

## Huidige staat
Stabiel en werkend. Geen actieve ontwikkeling.

## Architectuur
Volledig client-side PWA — geen server.
HTML + CSS + JavaScript + Service Worker (offline werking).

## Bestanden
| Bestand | Rol |
|---------|-----|
| index.html | Hoofdpagina met calculator |
| sw.js | Service worker voor offline werking |
| manifest.json | PWA manifest |
| icon.svg | App-icoon |

## Starten
Open index.html in browser, of:
`cd ~/pace-converter && python3 -m http.server 8081`
→ http://localhost:8081
