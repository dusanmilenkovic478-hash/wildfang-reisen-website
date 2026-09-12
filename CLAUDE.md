# Design-Regeln für wildfangreisen-jugendhilfe.de

## Ziel

Die Seite soll seriös, spezifisch und handgemacht wirken — wie eine Agentur sie
für einen Jugendhilfeträger gebaut hätte, nicht wie eine generische KI-Landingpage.
Vermeide die unten genannten Muster konsequent, auch wenn sie "sicher" und
"aufgeräumt" wirken — genau das macht sie generisch.

## Konkret vermeiden (aktuell auf der Seite vorhanden — bei nächster Überarbeitung ersetzen)

**1. Eyebrow-Label mit Strich** ("— PARTNERUNTERNEHMEN DER...", "— UNSERE RESSOURCEN")
Dieses Muster (kurzer Farbstrich + Großbuchstaben-Kicker vor jeder Überschrift)
ist eines der erkennbarsten Webflow/Framer-Template-Signale. Ersetzen durch:
- entweder ganz weglassen und die Überschrift für sich stehen lassen,
- oder ein Label, das etwas Eigenes transportiert (z. B. eine Fallnummer-Ästhetik,
  ein Aktenzeichen-Look, oder Text, der aus der Fachsprache der Jugendhilfe kommt
  statt aus dem Marketing-Baukasten).

**2. Wörtliche Metapher-Illustrationen** (Kompass + wegfliegende Vögel für
"neuen Weg gehen")
Zu generisch/Stock-artig. Besser: echte Fotos aus der Praxis (Boote, Fahrzeuge,
Einsatzorte — die gibt es ja schon auf der Konzept-Seite), eine Karte mit echten
Einsatzregionen, oder eine reduzierte grafische Sprache, die sich auf das Kompass-
Logo bezieht statt eine neue Illustration draufzusetzen.

**3. Nummerierte schwarze Kreise mit gelber Zahl** (01/02/03 bei "Ablauf einer
Maßnahme")
Der Prozess selbst ist real und die Nummerierung inhaltlich gerechtfertigt — nur
die Kreis-Optik ist Standard-Template-Ware. Alternativen: Nummern als große,
transparente Hintergrundzahlen hinter dem Text, eine horizontale Zeitleiste statt
gestapelter Karten, oder Nummern im Stil einer Aktenverlaufsnummer (§-Referenz-Optik).

## Generell vermeiden (auch bei neuen Seiten/Unterseiten)

- Cremeweiß + Terrakotta-Akzent, Lila/Blau-Gradient-Hero, Inter oder Space Grotesk
  als "sichere" Schrift, Emoji als Abschnittsmarker, alles zentriert,
  `rounded-lg` auf jeder Karte, Akzentbalken am Kartenrand
- Standard-SaaS-Hero-Layout (Headline links, Illustration rechts, zwei CTA-Buttons
  nebeneinander) ohne Bezug zum eigentlichen Thema — wenn dieses Layout bleibt,
  muss die rechte Seite etwas Reales zeigen (Foto, Karte, Zitat), keine Icon-Grafik
- Lorem-Ipsum oder generische Platzhaltertexte — bisher nicht vorhanden, so beibehalten

## Was funktioniert und beibehalten werden soll

- Schriftpaarung: fette Slab-Serif-Headline + graue Sans-Serif-Fließtext — bereits
  unterscheidbar von der Standard-KI-Optik, nicht durch Inter/Space Grotesk ersetzen
- Echte Fotos von Ressourcen (Boote, KIM-Mobil, Team) statt Stock-Bildern —
  dieses Prinzip auf neue Abschnitte ausweiten
- Klare Zielgruppentrennung in der Navigation (Jugendämter/Eltern/Partner) — inhaltlich
  stark, nicht antasten

## Vorgehen bei neuen Seiten/Komponenten

Vor dem Bauen kurz prüfen: "Könnte dieser Abschnitt genauso auf einer x-beliebigen
B2B-SaaS-Seite stehen?" Wenn ja, mindestens ein Element austauschen, das nur zu
Wildfang Reisen passt (echtes Foto, echte Zahl/Fallbeispiel, Fachbegriff aus der
Jugendhilfe, echtes Zitat).
