# pages

Dies ist das Repository für deine Website, die mit GitHub Pages gehostet wird.

---

## Inhaltsverzeichnis

1. [Vorraussetzungen](#vorraussetzungen)
2. [Repository einrichten](#repository-einrichten)
3. [Website erstellen](#website-erstellen)
4. [GitHub Pages aktivieren](#github-pages-aktivieren)
5. [Optimale Einstellungen für GitHub Pages](#optimale-einstellungen-für-github-pages)
6. [Häufige Probleme und Lösungen](#häufige-probleme-und-lösungen)
7. [Weiterführende Links](#weiterführende-links)

---

## Vorraussetzungen

- GitHub-Account
- Grundlegende Kenntnisse in HTML/CSS/JS (optional, empfohlen zum Anpassen der Website)
- Dieses Repository (`pages`)

---

## Repository einrichten

1. **Repository clonen:**
   ```bash
   git clone https://github.com/AureliusCaelum/pages.git
   ```
2. **In das Verzeichnis wechseln:**
   ```bash
   cd pages
   ```
3. **Dateien für deine Website einfügen:**
   - Hauptdatei ist üblicherweise `index.html`.  
   - Weitere Dateien/Unterverzeichnisse können hinzugefügt werden (z.B. `assets/`, `css/`, `js/`).

---

## Website erstellen

1. **Erstelle eine Startseite:**  
   Lege die Datei `index.html` im Hauptverzeichnis an.
2. **Weitere Seiten und Ressourcen:**  
   Erstelle nach Bedarf weitere HTML-Dateien und Ordner.

Beispiel für eine einfache `index.html`:
```html
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <title>Meine Homepage</title>
</head>
<body>
  <h1>Willkommen zu meiner Webseite!</h1>
</body>
</html>
```

3. **Änderungen committen & pushen:**
   ```bash
   git add .
   git commit -m "Erste Website erstellt"
   git push origin main
   ```

---

## GitHub Pages aktivieren

1. **Gehe im Browser zu deinem Repository:**  
   [https://github.com/AureliusCaelum/pages](https://github.com/AureliusCaelum/pages)

2. **Öffne die Repository-Settings:**  
   - Klicke auf `Settings` (ganz rechts).

3. **Gehe zu „Pages“:**  
   - Scrolle nach unten zu `Pages` (Link im Seitenmenü oder Abschnitt „Code und Automation“).

4. **Source auswählen:**  
   - Wähle als Source: `Branch: main` und `/ (root)` (Wurzelverzeichnis)
   - Klicke auf `Save`.

5. **Deine Webseite ist nun online unter:**  
   - `https://AureliusCaelum.github.io/pages/`

---

## Optimale Einstellungen für GitHub Pages

- **Branch:**  
  Nutze am besten `main` als Source. Falls du einen Build-Prozess verwendest (z.B. mit Jekyll), kann `/docs` sinnvoll sein.

- **Custom Domain:**  
  Trage deine eigene Domain (optional) im Bereich „Custom domain“ ein. Folge dem GitHub-Guide für DNS-Setup.

- **HTTPS erzwingen:**  
  Aktiviere „Enforce HTTPS“, wenn du eine eigene Domain nutzt.

- **Build & Deployment (optional):**  
  Nutze die GitHub Actions für automatisiertes Deployment aus einer anderen Branch/mit Build-Schritten.

- **Privatsphäre/Historie:**  
  Aktiviere das automatische Löschen veralteter Deployments.

- **Jekyll deaktivieren:**  
  Falls du **kein** Jekyll verwenden möchtest, erstelle eine Datei `.nojekyll` im root-Verzeichnis.

---

## Häufige Probleme und Lösungen

- **Änderungen werden nicht angezeigt:**  
  Prüfe, ob die Änderungen auf dem `main`-Branch liegen und ob die Source-Einstellungen korrekt sind.
- **Eigene Domain wird nicht geladen:**  
  Überprüfe die DNS-Konfiguration sowie die Einträge im Bereich „Custom domain“.
- **CSS/JS wird nicht geladen:**  
  Prüfe die relativen Pfade zu den Ressourcen.

---

## Weiterführende Links

- [Offizielle GitHub Pages Dokumentation](https://docs.github.com/en/pages)
- [Jekyll auf GitHub Pages](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll)
- [Custom Domains für Pages](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)
- [Fehlersuche bei Pages](https://docs.github.com/en/pages/troubleshooting)

---

**Fragen oder Probleme?**  
Erstelle ein [Issue](https://github.com/AureliusCaelum/pages/issues), um Unterstützung zu erhalten!