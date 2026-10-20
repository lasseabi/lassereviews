# LasseReviews

Kostenlose, statische Filmkritiker-Website in Schwarz und Gold, ohne eingeblendetes Hosting-Branding.

## Vor der Veröffentlichung anpassen
1. `index.html`: Ersetze `DEINE-EMAIL@BEISPIEL.DE` durch deine Kontakt-E-Mail (an beiden Stellen) und `https://www.imdb.com/` durch deinen IMDb-Profillink. Bearbeite die Biografie nach Wunsch.
2. `reviews.js`: Alle drei Rezensionen sind **fiktive Demo-Inhalte**. Ersetze sie durch deine echten Filmkritiken. Bewahre die Feldnamen und die JavaScript-Syntax. Einfache Anführungszeichen innerhalb von Texten müssen als `\'` geschrieben werden, wenn sie in einfachen Anführungszeichen stehen.
3. Optional: Lege einen Ordner `images` an und verwende nur Bilder, für die du Nutzungsrechte hast. Ohne Bilder erscheinen elegante Platzhalter.
4. Eine Datenschutz-/Impressumsprüfung kann je nach Wohnsitz, kommerziellem Zweck und Zielpublikum erforderlich sein. Die Website verwendet Google Fonts; wenn du externe Schriftanfragen vermeiden willst, entferne die `@import`-Zeile in `style.css` und verwende lokale Systemschriften.

## Veröffentlichung nur mit dem iPad (GitHub Pages)
1. Erstelle kostenlos ein GitHub-Konto auf https://github.com/ und melde dich in Safari an.
2. Erstelle ein **öffentliches** Repository mit dem Namen `lassereviews` (oder einem Namen deiner Wahl). GitHub Pages ist im GitHub-Free-Tarif für öffentliche Repositories verfügbar.
3. Öffne das Repository → `Add file` → `Upload files`. Lade **index.html**, **style.css**, **reviews.js**, **app.js** aus dem entpackten ZIP hoch (nicht den übergeordneten Ordner). Auf dem iPad kann `aA` → „Desktop-Website anfordern“ hilfreich sein.
4. Tippe auf `Commit changes`.
5. Öffne `Settings` → `Pages` → unter `Build and deployment` wähle `Deploy from a branch`, Branch `main`, Ordner `/(root)` → `Save`.
6. Nach einigen Minuten erscheint die öffentliche Adresse: `https://DEIN-GITHUB-NAME.github.io/lassereviews/`.
7. Für spätere Änderungen öffne eine Datei auf GitHub, tippe auf das Stiftsymbol, ändere den Text und speichere mit `Commit changes`.

**Hinweis:** Das Hosting ist kostenlos und blendet kein Wasserzeichen ein. Eine eigene Domain ist nicht enthalten. Die GitHub-Pages-URL und das Repository sind öffentlich. GitHub Pages ist statisches Hosting, deshalb gibt es kein Online-Redaktionssystem; neue Rezensionen werden in `reviews.js` eingetragen. Eine Kontaktformular-Backend-Funktion ist nicht enthalten: Der Kontaktbutton öffnet das Mailprogramm.
