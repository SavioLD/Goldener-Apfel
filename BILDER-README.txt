BILDER FÜR DIE WEBSITE „GOLDENER APFEL"
=======================================

So einfach geht's:
Lade die Fotos mit GENAU den unten genannten Dateinamen in diesen Ordner
(kunden/goldener-apfel/assets/). Sobald eine Datei da ist, erscheint sie
automatisch an der richtigen Stelle. Fehlt eine Datei, zeigt die Seite einen
dezenten Platzhalter – es „bricht" also nichts.

Format-Tipp:  .jpg,  querformat wo möglich,  ca. 1600–2000 px breite Kante,
              unter ~400 KB pro Bild (für schnelle Ladezeiten).


BENÖTIGTE DATEIEN & PLATZIERUNG
-------------------------------
terrasse-1.jpg          Hero (ganz oben rechts) – Gastgarten von oben mit Schirmen
terrasse-2.jpg          Sektion „Terrasse & Biergarten" – Garten mit Rasenfläche
terrasse-schild.jpg     Galerie (breit) – Gastgarten mit „Goldener Apfel"-Schild

samuel-portrait.jpg     „Über uns" – Porträt von Samuel Haftstein (Arme verschränkt)
samuel-kueche.jpg       Galerie – Samuel bei der Arbeit in der Küche

kueche-panieren.jpg     Speisekarte (Fotoband) – Schnitzel wird paniert
kueche-braten.jpg       Speisekarte (Fotoband) – Schnitzel in der Pfanne
kueche-pass.jpg         Speisekarte (Fotoband) – fertige Schnitzel am Pass

feier-gedeck.jpg        „Feiern" (Fotoband) – festliches Gedeck mit Goldbesteck
feier-planung.jpg       „Feiern" (Fotoband) – Team bei der Planung am Tisch
feier-tafel.jpg         „Feiern" (Fotoband) – gedeckte Tafel / weiteres Gedeck

bar.jpg                 Galerie – an der Bar mit regionalen Bieren (Ganter/Fürstenberg)
stube-bar-detail.jpg    Galerie – Lampe & historische Rottweil-Postkarten
stube-detail-glueck.jpg Galerie – Glücksbringer-Deko (Hufeisen/Schlüssel) unter der Decke
team.jpg                Galerie – Team am Tisch (z. B. Besprechung)
deko-fenster.jpg        Galerie (breit) – Blumenvase am Fenster


HINTERGRUND (für Entwickler)
----------------------------
- Hero & „Über uns" & „Terrasse": <img class="media__photo"> in der .media-Kachel.
- Speisekarte & Feiern: je drei Bilder im .photo-trio.
- Galerie: .gallery mit .photo / .photo--wide (breite Kacheln).
- Jedes <img> hat onerror-Fallback, damit fehlende Bilder sauber verschwinden.
- Weitere/andere Motive? Einfach denselben Dateinamen verwenden oder im
  index.html den src="assets/…" anpassen.
