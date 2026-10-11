# ChatGPT-Work-Startauftrag: Story-Schleife für Taugt's

Führe mit dem bewusst installierten und freigegebenen ChatGPT-Skill **story-loop** einen vollständigen autonomen Story-Arbeitslauf aus.

- **Zielrepository:** `Huluvu424242/taugts`
- **Zielbranch:** `master`
- **Maßgebliche Harness-Datei:** `AGENTS.md` (Repository-Stamm)
- **Stories:** alle offenen Issues mit Label `story` ohne Label `human-only`; nach jeder Iteration frisch ermitteln.
- **Laufende Story:** eigener Branch und PR, gegebenenfalls gestapelt; **keinen PR mergen**.
- **Abschluss:** nur bei erfolgreich nachgewiesenen vorgeschriebenen GitHub-Actions-Prüfungen auf dem einschlägigen Commit.
- **Fehler:** begrenzte Reparaturversuche, bei fortdauernder Blockade dokumentiert zurückstellen und unabhängige Stories weiterbearbeiten.
- **Fortsetzung:** den tatsächlichen GitHub-Zustand einschließlich offener PRs, Abhängigkeiten und Checks rekonstruieren; erfolgreich validierte PRs unangetastet lassen.
- **Ende:** erst wenn keine ausführbaren Stories mehr verbleiben oder die Work-Umgebung eine technische Grenze erreicht.
- **Ergebnis:** ausführlicher Bericht mit Issue- und PR-Links, Checks, SHAs, Abhängigkeiten, Merge-Reihenfolge, Reparaturen, neuen Defect-Issues und Blockaden.

Lies zunächst `AGENTS.md` und **alle darin verbindlich referenzierten Regeldateien vollständig**. Halte die projektseitigen Berechtigungs-, Workflow- und Qualitätsregeln ein, insbesondere die ausdrücklichen Freigaben für konkrete GitHub-Action-Versionen. Bei Widersprüchen in Arbeitsregeln hat der Harness Vorrang, ohne Sicherheits- oder Berechtigungsgrenzen zu überschreiten. Stelle keine wiederholten Routine-Rückfragen; falls eine Aktion nicht autorisiert ist, stelle die betroffene Story zurück.

Dieser Startauftrag erteilt **keine** Berechtigung zum Mergen, Verändern von Repository-Einstellungen oder Ausführen nicht freigegebener Werkzeugketten.