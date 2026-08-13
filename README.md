# Wildfang Reisen GmbH — Website

Statische Website (HTML/CSS/JS, keine Build-Schritte) für **wildfangreisen-jugendhilfe.de**.

## Struktur

- `index.html`, `konzept.html`, `jugendaemter.html`, `eltern-vormuender.html`,
  `dienstleistungspartner.html`, `team.html`, `kontakt.html`, `danke.html`,
  `impressum.html`, `datenschutz.html` — die einzelnen Seiten.
- `css/styles.css` — komplettes Design-System (Farb-, Abstands- und Typografie-Tokens
  am Anfang der Datei).
- `js/main.js` — Navigation, Scroll-Reveal-Animationen.
- `assets/` — Bilder, Fotos, Logos, Schriftdateien.
- `CNAME` — bindet die Custom Domain in GitHub Pages ein, nicht löschen.

## Ändern & Veröffentlichen

Jede Text- oder Codeänderung wird direkt in den entsprechenden HTML-/CSS-Dateien
vorgenommen. Ein Push auf den Branch `main` löst automatisch das Deployment auf
GitHub Pages aus (siehe `.github/workflows/deploy-pages.yml`) — es gibt keine
separate Staging-Stufe, ein Push ist gleichbedeutend mit "live".

## Domain

Die Domain `wildfangreisen-jugendhilfe.de` ist bei Strato registriert; die
DNS-Einträge zeigen per A-Record auf GitHub Pages. Die eigentliche Verknüpfung
(Custom Domain + HTTPS) wird in den Repository-Einstellungen unter
**Settings → Pages** verwaltet.

## Verantwortlichkeit

Für die langfristige Pflege sollte dieses Repository einem firmeneigenen
GitHub-Account bzw. einer Organisation gehören, nicht einem privaten Account
einzelner Mitarbeitender.
