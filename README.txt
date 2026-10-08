GRAVEL GROUNDS — gratis PWA prototype
=================================

Wat werkt nu:
- Home + route discovery
- Zoeken en filters
- Route detailpagina
- Favorieten via localStorage
- Demo GPX download
- Kaart met demo-routepunten
- Coffee & Stops
- PWA manifest + service worker

Belangrijk:
De routes, GPX-punten en stops zijn DEMO-DATA. Niet gebruiken voor echte navigatie.
De kaart gebruikt Leaflet + OpenStreetMap en vereist internet voor kaarttegels.

SMARTPHONE TESTEN (gratis):
1. Zet deze bestanden op een gratis HTTPS-host, bijvoorbeeld GitHub Pages.
2. Open de HTTPS-link op je smartphone.
3. Kies in je browser "Zet op beginscherm" / "Add to Home Screen".
4. De app opent daarna als een PWA.

Lokaal testen op computer:
- In deze map: python -m http.server 8080
- Open http://localhost:8080
Voor smartphone moet de site via HTTPS publiek bereikbaar zijn.

Volgende stap:
- echte GPX-routebestanden
- echte stops
- routevalidatie
- privacy/cookiebeleid
- analytics
- advertenties/affiliate
- iOS/Android verpakking wanneer de PWA bewezen gebruikers heeft
