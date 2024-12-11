# Barrierefreiheit Test-Playbook

## Inhaltsverzeichnis
1. [Grundlegende Analyse (Quick Check)](#1-grundlegende-analyse-quick-check)
2. [Automatische Vollanalyse](#2-automatische-vollanalyse)
3. [Vollständige manuelle Analyse](#3-vollständige-manuelle-analyse)
4. [Dokumentationsvorlagen](#4-dokumentationsvorlagen)

## 1. Grundlegende Analyse (Quick Check)

### 1.1 Vorbereitung (10 Min)
- [ ] Domain und Umfang der Website erfassen
- [ ] Hauptfunktionen identifizieren
- [ ] Sitemapzugriff prüfen
- [ ] robots.txt prüfen

### 1.2 Schnellcheck Hauptseiten (30 Min)
- [ ] Homepage
- [ ] Hauptnavigation
- [ ] Kontaktseite
- [ ] Eine typische Inhaltsseite
- [ ] Wenn vorhanden: Ein Formular
- [ ] Wenn vorhanden: Eine Transaktionsseite

### 1.3 Technische Basischecks (20 Min)
- [ ] Lighthouse Accessibility Score der Hauptseite
- [ ] HTML-Validierung der Hauptseite
- [ ] Responsive Design Check (3 Breakpoints)
- [ ] Tastaturnavigation Schnellcheck

### 1.4 Dokumentation Quick Check
```markdown
# Quick Check Barrierefreiheit
Datum: [DATUM]
Website: [URL]
Prüfer: [NAME]

## Zusammenfassung
- Gesamteindruck:
- Hauptprobleme:
- Empfohlene nächste Schritte:

## Lighthouse Score
- Performance: [X]
- Accessibility: [X]
- Best Practices: [X]
- SEO: [X]

## Gefundene Hauptprobleme
1. [Problem 1]
2. [Problem 2]
3. [Problem 3]

## Empfehlung
[ ] Keine weiteren Maßnahmen nötig
[ ] Automatische Vollanalyse empfohlen
[ ] Vollständige manuelle Prüfung empfohlen
```

## 2. Automatische Vollanalyse

### 2.1 Vorbereitung
- [ ] Sitemap XML herunterladen/generieren
- [ ] Crawler-Skript vorbereiten
- [ ] Test-Environment aufsetzen
- [ ] Logging-System vorbereiten

### 2.2 Automatische Tests

### 2.3 Zu prüfende Aspekte
- [ ] HTML Validierung aller Seiten
- [ ] Lighthouse Accessibility Scores
- [ ] Kontrast-Analyse
- [ ] Alt-Text Prüfung
- [ ] Heading-Struktur
- [ ] ARIA-Attribute
- [ ] Meta-Informationen
- [ ] Responsive Breakpoints
- [ ] Formularzugänglichkeit

### 2.4 Automatisierte Berichtserstellung
```markdown
# Automatische Vollanalyse
Datum: [DATUM]
Website: [URL]
Geprüfte URLs: [ANZAHL]

## Zusammenfassung
- Durchschnittlicher Lighthouse Score: [X]
- Kritische Probleme: [X]
- Warnungen: [X]
- Geprüfte Seiten: [X]

## Detaillierte Ergebnisse
### HTML-Validierung
- Fehler gesamt: [X]
- Warnungen gesamt: [X]
- Top 5 häufigste Probleme:
  1. [PROBLEM] ([ANZAHL]x)
  2. ...

### Accessibility-Probleme
- Kritisch: [Liste]
- Wichtig: [Liste]
- Moderat: [Liste]
- Gering: [Liste]

### Empfohlene manuelle Prüfungen
1. [BEREICH]
2. [BEREICH]
```

## 3. Vollständige manuelle Analyse

### 3.1 Vorbereitungen
- [ ] Testumgebungen einrichten
- [ ] Testgeräte vorbereiten
- [ ] Assistive Technologien installieren
- [ ] Testfälle definieren

### 3.2 Zu testende Assistive Technologien
- [ ] NVDA Screenreader
- [ ] JAWS Screenreader
- [ ] VoiceOver (iOS/macOS)
- [ ] Bildschirmlupe
- [ ] Sprachsteuerung
- [ ] Bildschirmtastatur

### 3.3 Manuelle Testszenarien
1. Navigation und Struktur
   - [ ] Keyboard-Navigation
   - [ ] Skip-Links
   - [ ] Landmarks
   - [ ] Heading-Struktur
   - [ ] Tabellen-Struktur

2. Inhalte und Medien
   - [ ] Alt-Texte
   - [ ] Videountertitel
   - [ ] Audiodeskription
   - [ ] Dokumente
   - [ ] Grafiken und Diagramme

3. Interaktive Elemente
   - [ ] Formulare
   - [ ] Buttons
   - [ ] Custom Controls
   - [ ] Error Handling
   - [ ] Modals/Overlays

4. Responsive Design & Zoom
   - [ ] 200% Zoom
   - [ ] 400% Zoom
   - [ ] Reflow
   - [ ] Touch Targets
   - [ ] Viewport Anpassungen

### 3.4 Dokumentation manuelle Prüfung
```markdown
# Manuelle Barrierefreiheitsprüfung
Datum: [DATUM]
Website: [URL]
Prüfer: [NAME]

## Getestete Umgebungen
### Browser
- [ ] Chrome [VERSION]
- [ ] Firefox [VERSION]
- [ ] Safari [VERSION]
- [ ] Edge [VERSION]

### Assistive Technologien
- [ ] NVDA [VERSION]
- [ ] JAWS [VERSION]
- [ ] VoiceOver [VERSION]

## Detaillierte Testergebnisse

### 1. Navigation & Struktur
#### Keyboard-Navigation
- Getestet: [JA/NEIN]
- Probleme gefunden: [JA/NEIN]
- Details: [BESCHREIBUNG]

[WEITERE KATEGORIEN...]

## Gefundene Probleme
### Kritisch
1. [PROBLEM]
   - Ort: [URL/ELEMENT]
   - WCAG-Referenz: [X.X.X]
   - Reproduktion: [SCHRITTE]
   - Empfehlung: [LÖSUNG]

[WEITERE PRIORITÄTEN...]

## Empfehlungen
1. Sofort umzusetzende Maßnahmen
   - [MAßNAHME]
   - [MAßNAHME]

2. Mittelfristige Maßnahmen
   - [MAßNAHME]
   - [MAßNAHME]

3. Langfristige Optimierungen
   - [MAßNAHME]
   - [MAßNAHME]
```

## 4. Dokumentationsvorlagen

### 4.1 WCAG Konformitätserklärung
```markdown
# Barrierefreiheits-Konformitätserklärung

## Allgemeine Angaben
- Website: [URL]
- Prüfdatum: [DATUM]
- Prüfmethodik: [METHODIK]
- Konformitätsziel: [LEVEL]

## Konformitätsstatus
[ ] Vollständig konform
[ ] Teilweise konform
[ ] Nicht konform

## Nicht barrierefreie Inhalte
1. [INHALT]
   - Grund: [GRUND]
   - Alternative: [ALTERNATIVE]
   - Behebung geplant: [DATUM]

## Erstellungsdatum
- Erstellt am: [DATUM]
- Letzte Überprüfung: [DATUM]
- Nächste Prüfung: [DATUM]
```

### 4.2 Maßnahmenplan
```markdown
# Maßnahmenplan Barrierefreiheit

## Sofortige Maßnahmen (1-4 Wochen)
1. [MAßNAHME]
   - Priorität: [PRIO]
   - Aufwand: [AUFWAND]
   - Verantwortlich: [PERSON]
   - Deadline: [DATUM]

## Mittelfristige Maßnahmen (1-3 Monate)
[...]

## Langfristige Maßnahmen (3+ Monate)
[...]

## Budget & Ressourcen
- Geschätztes Budget: [BETRAG]
- Benötigte Ressourcen: [LISTE]
- Schulungsbedarf: [JA/NEIN]
```

### 4.3 Testprotokolle
```markdown
# Testprotokoll Barrierefreiheit

## Testinformationen
- Testszenario: [BESCHREIBUNG]
- Tester: [NAME]
- Datum: [DATUM]
- Testumgebung: [DETAILS]

## Durchgeführte Tests
1. [TEST]
   - Erwartetes Ergebnis: [ERWARTUNG]
   - Tatsächliches Ergebnis: [ERGEBNIS]
   - Status: [BESTANDEN/FEHLGESCHLAGEN]
   - Screenshots: [LINKS]
   - Notizen: [NOTIZEN]

## Zusammenfassung
- Durchgeführte Tests: [ANZAHL]
- Bestanden: [ANZAHL]
- Fehlgeschlagen: [ANZAHL]
- Kritische Probleme: [ANZAHL]
```

---

## Anmerkungen zur Verwendung

- Dieses Playbook ist als lebendiges Dokument zu verstehen
- Regelmäßige Aktualisierungen basierend auf neuen Standards und Erfahrungen
- Anpassung an projektspezifische Anforderungen notwendig
- Dokumentation aller Anpassungen und Verbesserungen
- Schulung der Mitarbeiter im Umgang mit dem Playbook

## Rechtliche Hinweise

- Konformität mit BaFG (Barrierefreiheitsgesetz)
- Einhaltung der WCAG 2.1 Richtlinien
- Berücksichtigung der EN 301 549
- Dokumentation gemäß gesetzlicher Anforderungen
