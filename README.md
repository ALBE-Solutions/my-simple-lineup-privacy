# Datenschutzerklärung / Privacy Policy — My Simple Lineup

Öffentlich gehostete Rechtsseite für die Android-App **My Simple Lineup** (Albe Solutions).
Diese URL wird in der Google Play Console unter *App-Inhalte → Datenschutzerklärung* hinterlegt.

`index.html` enthält **beide Sprachfassungen** (Deutsch und Englisch) auf einer einzigen Seite,
weil in der Play Console nur eine URL eingetragen werden kann. Die Seite wählt beim Laden
automatisch die Sprache des Besuchers und lässt sich oben umschalten. Ohne JavaScript bleiben
beide Fassungen sichtbar — die Erklärung ist also immer lesbar, auch für Crawler und für das
Play-Store-Review.

## Veröffentlichen mit GitHub Pages

1. `index.html` und diese `README.md` in ein **öffentliches** Repository legen
   (das Repository muss öffentlich sein, sonst ist GitHub Pages kostenpflichtig).
2. *Settings → Pages → Source*: Branch `main`, Ordner `/ (root)`.
3. Nach etwa einer Minute erreichbar unter `https://<konto>.github.io/<repo>/`.

Liegen die Dateien stattdessen in einem Unterordner `docs/`, dort `/docs` als Ordner wählen.

Alternativ den Ordner mit der `index.html` auf <https://app.netlify.com/drop> ziehen.

## Anforderungen von Google Play

Die URL muss dauerhaft erreichbar sein, darf nicht geoblockt werden, kein PDF sein und für
Nutzer nicht bearbeitbar sein. Statisches HTML erfüllt das. Wichtig: Der Link darf nach der
Veröffentlichung nicht sterben — eine tote Datenschutz-URL kann zur Sperrung der App führen.

## Änderungen

Bei inhaltlichen Änderungen **beide Sprachfassungen** anpassen und das Datum in
`Stand:` / `Last updated:` in beiden Abschnitten hochziehen.
