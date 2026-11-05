# bfz – Informationen zur Zusammenarbeit

Kompakte Textinformationen für selbstständige Dozenten. Die bisherigen Seitenpfade bleiben erhalten, damit bestehende Links weiterhin funktionieren.

## Lokal prüfen

Mit Python 3.12 oder neuer:

```sh
python -m venv .venv
# Virtuelle Umgebung aktivieren, dann:
pip install -r requirements.txt
mkdocs build --strict
mkdocs serve
```

Pull Requests werden mit einem strikten MkDocs-Build geprüft. Die bestehende Veröffentlichung über GitHub Pages läuft erst bei Änderungen auf main bzw. master.

## Inhalte pflegen

- Texte stehen unter `docs/content/`, die Navigation in `mkdocs.yml`.
- Methoden und Materialien als freiwillige Hilfen beschreiben. Konkrete Auftragsanforderungen und notwendige Nachweise müssen mit der tatsächlichen Vereinbarung übereinstimmen.
- Kurszeiten und Zuständigkeiten mit den aktuellen Kundeninformationen abgleichen.
- Neue Screenshots nur aus der aktuellen Oberfläche übernehmen; personenbezogene Daten und Zugangsinformationen vor der Veröffentlichung entfernen. Textalternativen ergänzen.
- Veraltete Screenshots bleiben im Quellbestand, werden aber über `exclude_docs` nicht in den neuen Website-Build übernommen.

## Zugriff

Der bestehende GitHub-Pages-Auftritt ist öffentlich. Ein vorgeschaltetes Formular im Browser bietet keine serverseitige Zugriffskontrolle. Zeitlich begrenzte Zugänge benötigen eine geeignete Hosting- oder Authentifizierungslösung; auch Dateien, Suchindex und direkte Ursprungs-URLs müssen geschützt sein.
