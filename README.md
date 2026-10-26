# Lamm & Apfel – Olaf Willert

Vorhandene statische Website, vorbereitet für GitHub Pages im Repository `VitamapAI/Lammundapfel.de`.

## Veröffentlichen

1. Das ZIP-Archiv entpacken. Die entpackten Dateien hochladen, nicht die ZIP-Datei selbst.
2. `index.html`, `.nojekyll`, `README.md` und die Ordner `assets` und `Bio-Landwirtschaft` direkt in das Hauptverzeichnis des Repositorys hochladen. Die vorhandene Ordnerstruktur beibehalten. Kein zusätzlicher Ordner `Olaf-Willert` zwischen Repository und `index.html`.
3. In GitHub unter **Settings → Pages → Build and deployment** als Source **Deploy from a branch** wählen.
4. Branch **main** und Ordner **/(root)** auswählen und speichern.
5. Nach der erfolgreichen Veröffentlichung unter **Settings → Pages → Visit site** die Website öffnen.

Erwartete GitHub-Pages-Adresse: `https://vitamapai.github.io/Lammundapfel.de/`

Eine eigene Domain wird separat unter **Settings → Pages → Custom domain** und beim Domainanbieter eingerichtet. In diesem Paket ist noch keine Domain-Zuordnung enthalten.

## Aufbau

- `index.html`: Startseite und Inhalte.
- `assets/css/main.css`: Gestaltung.
- `assets/js/`: vorhandene JavaScript-Dateien.
- `Bio-Landwirtschaft/`: Fotos einschließlich der zusätzlich mitgelieferten, derzeit nicht eingebundenen Bilder.
- `.nojekyll`: veröffentlicht die statischen Dateien ohne Jekyll-Verarbeitung.

Die Website benötigt weder PHP noch Datenbank, Installation, Build-Befehl oder kostenpflichtige Serverfunktionen. Bilder und Skripte werden über relative Pfade geladen. Fira Sans und Simonetta werden wie in der Vorlage über Google Fonts eingebunden.

## Technische Anpassungen am 26. Oktober 2026

- Falschen Verweis auf das Marktstandfoto durch die vorhandene Datei `Bio-Landwirtschaft/Marktstand.jpg` ersetzt.
- Fehlende HTML-Abschlüsse ergänzt und einen überzähligen Absatzabschluss entfernt.
- Fehlerhaft geschriebene Link-Ziele korrigiert; externe Links mit neuem Tab abgesichert.
- Ungenutzten Lightbox-Aufruf entfernt, der auf ein nicht geladenes Plugin zugriff.
- Leere Hintergrundbild-Referenz im CSS entfernt.
- Dokumentensprache auf Deutsch gesetzt und Vergrößern auf Mobilgeräten ermöglicht.

Texte, Kontaktdaten, Verkaufszeiten, Zertifizierungsangaben und Bildnachweise stammen aus der bereitgestellten Vorlage. Ihre Aktualität wurde bei der technischen Vorbereitung nicht extern überprüft.

## Quellen zur Einrichtung

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site
- https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Rechte

Die bestehenden Namens-, Agentur- und Fotografieangaben in der Website wurden beibehalten. Dieses Repository erteilt keine zusätzliche Nutzungslizenz für Texte, Fotos oder Gestaltung.
