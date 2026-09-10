# Habit Score

Ein Selbsttest zu Gewohnheiten: 106 konkrete Verhaltensweisen in 15 Verhaltensdomaenen,
ausgewertet als Stand je Bereich, groesste Hebel, Anspruch gegen gelebtes Verhalten und
168-Stunden-Wochenbilanz.

**Der Test laeuft vollstaendig im Browser des Nutzers.** Es gibt kein Backend, kein
Konto und keine Datenuebertragung — Antworten und Verlauf liegen ausschliesslich im
`localStorage` des jeweiligen Geraets.

`index.html` ist eine einzelne, eigenstaendige Datei: Schriften, Logo und Testdaten
sind eingebettet, es werden keine externen Ressourcen geladen.

## Nicht hier bearbeiten

Die Datei wird gebaut, nicht geschrieben:

    python3 scripts/baue_habitscore.py        (im Repo "Claude AIOS")

Quellen sind `Habit Score/vorlage/habitscore_template.html` (Aussehen und Auswertung)
und `Habit Score/Prototyp/testset_v10.json` (die Fragen). Der Runner prueft den
eingefrorenen Fragensatz, rechnet die JS-Auswertung gegen die Python-Nachrechnung und
klickt sich durch zehn vollstaendige Durchlaeufe.

Ob die hier liegende Datei wirklich aus dieser Kette stammt:

    python3 scripts/habitscore_seite_bauen.py --pruefen

Fragensatz eingefroren am 10.09.2026 (106 Items). Aenderungen an den Fragen gehen in eine
neue Fassung nach einer vollstaendigen Messrunde, sonst sind Messungen ueber die Zeit
nicht mehr vergleichbar.

© If You Change · High Performance Mentoring
