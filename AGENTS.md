```md
# AGENTS.md

## Zweck
Dieses Repository enthält die Sneaked In Academy auf Basis von MkDocs.

## Allgemeine Regeln
- Antworte und schreibe Änderungen standardmäßig auf Deutsch.
- Halte Texte klar, knapp und gut lesbar.
- Bevorzuge kleine, nachvollziehbare Änderungen statt großer ungefragter Umbauten.
- Bestehende Struktur und Benennungen beibehalten, sofern nichts anderes verlangt wird.

## Inhaltliche Regeln
- Markdown-Dateien sauber formatieren.
- Interne Links und Pfade nach Änderungen immer mitprüfen.
- Navigation in `mkdocs.yml` nur anpassen, wenn es für neue Seiten nötig ist.
- Keine Platzhalter oder Dummy-Inhalte einfügen, außer wenn ausdrücklich gewünscht.

## Lokale Befehle
- Lokale Vorschau:
  `python -m mkdocs serve`
- Deployment:
  `python -m mkdocs gh-deploy --force`

## Commit-Regeln
- Commit-Messages auf Deutsch schreiben.
- Commit-Messages kurz und klar halten.
- Beispiel:
  - `docs: fw-sites ergänzt`
  - `fix: interne links korrigiert`
  - `docs: mining-seiten überarbeitet`

## Bei Änderungen an Inhalten
- Prüfe, ob neue Seiten in die Navigation aufgenommen werden müssen.
- Prüfe, ob Querverlinkungen zu anderen Seiten ergänzt werden sollten.
- Prüfe, ob das `CHANGELOG.md` beim nächsten Deploy aktualisiert werden sollte.

## Was vermieden werden soll
- Keine unnötigen Umbenennungen von Dateien.
- Keine großen Strukturänderungen ohne ausdrückliche Anweisung.
- Keine englischen Commit-Messages, sofern nicht ausdrücklich gewünscht.
```