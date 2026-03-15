# [ din5008-generator ]

> An offline, privacy-first, zero-dependency HTML generator for professional German business letters complying with strict DIN 5008 (Form A) standards.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Format](https://img.shields.io/badge/standard-DIN%205008%20Form%20A-success.svg)]()
[![Status](https://img.shields.io/badge/status-offline%20ready-brightgreen.svg)]()

[ EN ](#english) | [ DE ](#deutsch)

---

<a name="english"></a>
## / en

### Abstract
A minimal, client-side only tool to generate pixel-perfect, print-ready PDFs for German business correspondence. No trackers, no external assets, no server-side processing.

### Demo
**[`[ Launch Live Instance ]`](https://LinyingL.github.io/din5008-generator/)**

### Core Specifications
* **Architecture:** Strict single-file structure (`index.html`).
* **Privacy Engine:** 100% offline. In-browser sandbox data processing.
* **Standard Compliance:** Absolute millimeter positioning (`mm`) for Form A address windows. Mathematically accurate folding/punching metrics.
* **Typography:** Precision justified rendering with native `hyphens: auto`.
* **State Persistence:** Local storage retention. Full support for JSON payload import/export.
* **Rendering Engine:** Pure CSS `@media print` directives for native A4 PDF generation.

### Render Output
![Detailed Print Render](assets/pdf-preview.png)
*> Print-ready PDF output showcasing folding marks and window structural alignment.*

### Local Deployment
```bash
# 1. Clone repository
$ git clone https://github.com/LinyingL/din5008-generator.git

# 2. Open deployment file
$ open din5008-generator/index.html
```

> **[!] Print Directive:** 
> Hardware layout accuracy requires scaling set strictly to `100%` / Default. System "Headers and footers" must be disabled in the print dialog.

---

<a name="deutsch"></a>
## / de

### Zusammenfassung
Ein minimalistisches, rein client-seitiges Werkzeug zur Erstellung pixelgenauer, druckfertiger PDFs für deutsche Geschäftskorrespondenz. Keine Tracker, keine externen Assets, keine Serververarbeitung.

### Demo
**[`[ Live-Instanz ausführen ]`](https://LinyingL.github.io/din5008-generator/)**

### Kernspezifikationen
* **Architektur:** Strikte Einzeldateistruktur (`index.html`).
* **Privacy Engine:** 100% offline. Datenverarbeitung erfolgt lokal in der Browser-Sandbox.
* **Standardkonformität:** Absolute Millimeterpositionierung (`mm`) für Form A Adressfenster. Exakte Falt- und Lochkennzahlen.
* **Typografie:** Präziser Blocksatz mit nativer Silbentrennung (`hyphens: auto`).
* **Zustandsspeicherung:** Lokale Datensicherung. Volle Unterstützung für JSON Import/Export.
* **Rendering-Engine:** Reine CSS `@media print` Direktiven für die native A4 PDF-Generierung.

### Render-Ausgabe
![Detailliertes PDF Render](assets/pdf-preview.png)
*> Druckfertiges Render-Ergebnis mit exakten Faltmarken und struktureller Fensteranordnung.*

### Lokales Deployment
```bash
# 1. Repository klonen
$ git clone https://github.com/LinyingL/din5008-generator.git

# 2. Deployment-Datei öffnen
$ open din5008-generator/index.html
```

> **[!] Druckanweisung:** 
> Um das exakte Layout (mm) zu erhalten, muss die Skalierung zwingend auf `100%` (Standard) gesetzt sein. "Kopf- und Fußzeilen" müssen im Druckdialog zwingend deaktiviert werden.

---

<br>

`License:` [MIT](LICENSE)
