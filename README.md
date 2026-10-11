# EA 3: Farbig gefüllte 2D Geometrie

Einsendeaufgabe 3, Modul Graphical Visualisation Technologies, TH Lübeck, Wintersemester 2026/27.

Eine einseitige Web-App mit derselben Mandala-Rosette wie in EA 2, nun aus farbig
gefüllten Dreiecken (`TRIANGLES`) mit Vertex-, Color- und Index-Array und einem
`drawElements`-Aufruf. Es gibt einfarbige Flächen und Farbverläufe über die Vertexfarben.

## Live-Demo

Öffentlich erreichbar unter:
<https://merganh.github.io/gvt-ea3-farbig-gefuellte-2d-geometrie/>

## Lokal ausführen

Kein Build-Schritt. Die Seite lässt sich über einen lokalen Server öffnen:

```bash
python3 -m http.server 8000
# dann im Browser: http://localhost:8000
```

## Deployment via GitHub Pages

Im Repo liegt ein Workflow unter `.github/workflows/pages.yml`, der die Seite bei
jedem Push auf `main` automatisch nach GitHub Pages deployt. Einmalig im Repo
unter **Settings → Pages → Build and deployment → Source** `GitHub Actions`
wählen.

## Aufbau

- `index.html`: gesamte Anwendung in einer Datei (HTML, CSS, JS inline)

Das Motiv ist selbst entworfen (aufbauend auf EA 2), es werden keine externen Bibliotheken oder Bilder verwendet.

## Bedienung

Die Aufgabe verlangt keine Interaktion. Die Grafik wird beim Laden gezeichnet.

## Quelltext-Markierung

Die für die Aufgabe geschriebenen JavaScript-Stellen sind mit
`// START EA3_GEFUELLTE_GEOMETRIE` und `// END EA3_GEFUELLTE_GEOMETRIE` markiert.
