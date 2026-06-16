# browser_RA

Ein einfacher OpenRA‑Clone im Browser.
Wer's noch nicht kennt: Ein Echtzeitstrategie-Spiel, Basis bauen, kämpfen, mit Sicht von oben.
Meine Art, die aktuellen Konflikte zu verarbeiten.

Alles steckt in einer einzigen `.html`‑Datei und bleibt dicht am Original.  
Die Bedienung erfolgt komplett per Linksklick.

Die eigene Basis aufzubauen ist weitgehend implementiert.  
Aktuell gibt es nur wenige Gebäude und Einheiten, aber die Abhängigkeitsketten funktionieren.  
Erweiterungen sind leicht machbar.

Gegner lassen sich im Startmenü bereits einstellen. Auf dem Spielfeld existieren sie noch nicht.  
Eigene Einheiten besitzen ebenfalls noch keine militärischen Eigenschaften.

---
## Live-Demo

v0.3 + mobile Einheiten AI Spieler auf Spielfeld (todo: noch etwas verbugt)
<a href="https://mikro42.github.io/browser_RA/browser_RA3.html" target="_blank">▶️ browser_RA im Browser ausführen</a>

v0.2 + Basisaufbau AI Spieler
<a href="https://mikro42.github.io/browser_RA/browser_RA2.html" target="_blank">▶️ browser_RA im Browser ausführen</a>

v0.1 Basisaufbau menschlicher Spieler
<a href="https://mikro42.github.io/browser_RA/browser_RA.html" target="_blank">▶️ browser_RA im Browser ausführen</a>
Soweit also ein guter Startpunkt für Branches 😉

---

## Features (bisher)

- Eine einzige HTML‑Datei
- Bedienung vollständig per Linksklick
- Basisbau weitgehend implementiert
- Erste Gebäude und Einheiten vorhanden
- Funktionierende Abhängigkeitsketten
- Gegner im Startmenü auswählbar

---

## Nächste Schritte

1. **Gegner‑KI**
   - Gegner bauen ihre Basis selbstständig auf  
   - Produktion eigener mobiler Einheiten  
   - Verhaltenslogik für verschiedene Einheitentypen  

2. **Militärische Eigenschaften**
   - Panzerung  
   - Reichweite  
   - Schlagkraft gegen See, Land‑Infanterie, Land‑Fahrzeuge, Luft  
   - Schussfrequenz  
   - Angriffsfähigkeit  
   - Heilung & Reparatur  

3. **Spielfeld vergrößern**
   - Von 32×32 auf 64×64  
   - Nur ein Ausschnitt sichtbar → Scrollen notwendig  
   - Radar als Übersicht und Navigation  

4. **Karten**
   - kleine Auswahl von Geländekarten um nicht nur auf dem Rasen zu spielen

5. **Spielfeld-Layer**
   - Nach Einführung von Karten kann auch die Marine umgesetzt werden, die aktuell über den Rasen fahren müsste.
   - Auch die Luftstreitkräfte sollten ihre eigene Flugebene bekommen um über Gebäude zu fliegen statt drumherum fahren zu müssen.
---

## Mitmachen

Pull Requests, Ideen und Erweiterungen sind willkommen.  
