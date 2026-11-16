# openemployed.de

Webseite von [OpenEmployed](https://github.com/schlummer13/openemployed): selbst gehostete Buchhaltung, Rechnungen, Lohn und Personal für Selbstständige, UG und GmbH.

Die Seite ist rein statisch: HTML und CSS, ohne externe Schriften, Skripte oder Tracker.

| Datei | Zweck |
|---|---|
| `index.html`, `style.css`, `bilder/` | die Seite |
| `.htaccess` | Apache: HTTPS ohne www, URLs ohne `.html`, Sicherheits-Header, Caching |
| `sitemap.xml`, `robots.txt` | für Suchmaschinen |

**Veröffentlichen:** Den Inhalt des Repos auf den Webspace laden (Apache mit `mod_rewrite`). `README.md` und `.git` werden über die `.htaccess` gesperrt.

**Neue Unterseite**, z. B. `impressum.html`: Sie ist automatisch unter `/impressum` erreichbar. Danach in `sitemap.xml` eintragen.
