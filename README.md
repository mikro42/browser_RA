# browser_RA

Ein einfacher OpenRA‑Clone im Browser.
Wer's noch nicht kennt: Ein Echtzeitstrategie-Spiel, Basis bauen, kämpfen, mit Sicht von oben.
Meine Art, die aktuellen Konflikte zu verarbeiten.

Alles steckt in einer einzigen `.html`‑Datei und bleibt dicht am Original.  
Die Bedienung erfolgt hier komplett per Linksklick.

---
## Live-Demo

v0.5 + AI State-Machine Notfallsituationen erweitert; Angriffscursor eingeführt
<a href="https://mikro42.github.io/browser_RA/browser_RA5.html" target="_blank">▶️ browser_RA ausführen</a>

- Die AI State-Machine produziert nach jeweils höchstem Bedarf Harvester, MCV, ...
- Wenn Einheit ausgewählt und Mauscursor über gegnerischer Einheit dann Angriffscursor.
- Spielendeerkennung mit automatischem Wechsel ins Einstellungsmenü hinzugefügt.

v0.4 + mobile Einheiten und Gebäude haben nun militärische Eigenschaften
<a href="https://mikro42.github.io/browser_RA/browser_RA4.html" target="_blank">▶️ browser_RA ausführen</a>

- Militärische Eigenschaften wie Panzerung, Reichweite, Schlagkraft, Schussfrequenz  sind hinzugefügt
- Schadensstatus der Gebäude wird angezeigt
- Repair_Facility hinzugefügt. Verkauf von Fahrzeugen (halber Neupreis) möglich
- Erkennung besiegter AI Spieler

v0.3 + mobile Einheiten AI Spieler auf Spielfeld
<a href="https://mikro42.github.io/browser_RA/browser_RA3.html" target="_blank">▶️ browser_RA ausführen</a>

- Mobile Einheiten der KI Spieler werden bereitgestellt

v0.2 + Basisaufbau AI Spieler
<a href="https://mikro42.github.io/browser_RA/browser_RA2.html" target="_blank">▶️ browser_RA ausführen</a>

- KI Spieler bauen ihre Basis auf


v0.1 Basisaufbau menschlicher Spieler
<a href="https://mikro42.github.io/browser_RA/browser_RA.html" target="_blank">▶️ browser_RA ausführen</a>

- Eine einzige HTML‑Datei
- Bedienung vollständig per Linksklick
- Basisbau weitgehend implementiert
- Erste Gebäude und Einheiten vorhanden
- Funktionierende Abhängigkeitsketten
- Gegner im Startmenü auswählbar
Soweit also ein guter Startpunkt für Branches 😉

---

## Nächste Schritte

2. **Militärische Eigenschaften vervollständigen**
   - Schadensstatus mobile Einheiten
   - Reparatur von Gebäude
   - Strategie KI Spieler im Krisenfall: Was zuerst produzieren? (Harester, MCV, Rafinerie, mobile Einheiten)
   - Gruppierung und Strategie mobiler Einheiten der KI Spieler (stehen aktuell nur herum)


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

Pull Requests, Ideen und Erweiterungen sind willkommen. Öffne einfach ein Issue.
