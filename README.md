# ETH-Aufnahmeprüfung · Lernplattform

Lernplattform für die reduzierte Aufnahmeprüfung der ETH Zürich: Mathematik, Physik, Chemie und Biologie. 112 Themen mit Erklärung, gerechnetem Beispiel und Übungsaufgaben.

Die Seite ist eine einzige statische Datei (`index.html`). Es gibt nichts zu installieren und keinen Build-Schritt.

## Online stellen

### 1. Auf GitHub hochladen
1. Auf github.com einloggen, oben rechts **+ → New repository**.
2. Namen vergeben (z. B. `eth-lernplattform`), **Private** oder **Public** wählen, **Create repository**.
3. Auf der leeren Repo-Seite **uploading an existing file** anklicken.
4. Die Dateien aus diesem Ordner (`index.html`, `vercel.json`, `README.md`, `.gitignore`) ins Fenster ziehen und **Commit changes** klicken.

Wichtig: die Dateien selbst hochladen, nicht den Ordner drumherum. `index.html` muss direkt im Hauptverzeichnis des Repos liegen.

### 2. Mit Vercel verbinden
1. Auf vercel.com mit dem GitHub-Konto einloggen.
2. **Add New… → Project**, das Repo `eth-lernplattform` auswählen, **Import**.
3. Einstellungen so lassen: Framework Preset **Other**, kein Build Command, Output Directory leer.
4. **Deploy**. Nach wenigen Sekunden bekommst du eine Adresse wie `eth-lernplattform.vercel.app`.

### Änderungen
Jede neue Version von `index.html`, die du auf GitHub hochlädst, geht automatisch online.

## Gut zu wissen
- **Fortschritt** (Häkchen, Notizen, Einstufungen) wird im Browser des jeweiligen Geräts gespeichert. Handy und Laptop haben also getrennte Stände.
- **Formeln** werden über MathJax aus dem Internet geladen, die Seite braucht also eine Internetverbindung.
- Lokal ansehen: `index.html` einfach doppelklicken.
