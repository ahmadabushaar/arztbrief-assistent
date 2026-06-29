# Ausgabe-Hygiene, Hausstil und Befund-Transkription

Diese Datei steuert die praxistaugliche Ausgabe für den direkten Einsatz in einem
KIS (z. B. Orbis): saubere, kopierbare Texte; Anpassung an den Hausstil der Klinik;
korrekte Übertragung hochgeladener Befunde.

## 1. Saubere Ausgabe für Copy-Paste (KIS / Orbis)

Der fertige Brieftext muss ohne Nacharbeit direkt einfügbar sein.

- Reiner Fließtext. **Keine Markdown-Artefakte** im Brief (#, *, **, `, Tabellen
  striche, Aufzählungszeichen), wenn der Text zum Kopieren bestimmt ist.
- **Keine unsichtbaren/exotischen Zeichen:** kein geschütztes Leerzeichen
  (NBSP, U+00A0), kein schmales NBSP (U+202F), keine Zero-Width-Zeichen, kein
  Soft Hyphen. Nur normale ASCII-Leerzeichen.
- **Zahl + Einheit mit normalem Leerzeichen:** „12 mg", „8 l/min", „55 %".
  Niemals „12?mg" — das „?" entsteht fast immer aus einem geschützten/exotischen
  Leerzeichen oder Sonderzeichen, das Orbis nicht darstellen kann.
- **Dezimaltrennung deutsch mit Komma:** „12,5 mg", nicht „12.5 mg".
- **Bindestrich/Minus** als einfacher ASCII-Bindestrich `-`.
- **Sonderzeichen prüfen** (µ, °, ≥, ≤, →): im Zweifel ausschreiben („mindestens"
  statt ≥, „bis" statt →), da manche KIS-Zeichensätze sie als „?" anzeigen.
- Keine doppelten Leerzeichen, kein Leerzeichen vor Satzzeichen.
- **Reinheitsfilter vor Ausgabe:** Jedes Zeichen, das nicht eindeutig druckbares
  Standard-ASCII oder gängiges Deutsch (ä ö ü ß) ist, wird ersetzt oder entfernt.

## 2. Ausgabeform ohne Briefkopf/Unterschrift (Orbis-Modus)

Auf Wunsch (Standard, wenn der Arzt in Orbis einfügt):
- **Kein Briefkopf**, keine Adress-/Patientenzeile, keine Grußformel, keine
  Unterschriftszeile.
- Nur die inhaltlichen Abschnitte, die direkt eingefügt werden: Diagnosen,
  Anamnese, Befunde, Verlauf, Beurteilung, Procedere, Medikation.

## 3. Hausstil-Adaption (Musterbriefe der Klinik)

- Liefert der Arzt **anonymisierte** Musterbriefe/Textbausteine seiner Klinik,
  wird **deren** Struktur, Reihenfolge, Überschriften und Formulierungsweise exakt
  übernommen — nicht die generische Standardgliederung.
- Bei wiederkehrenden Befundtypen (z. B. Polygraphie, Kapnometrie, NIV-Kontrolle,
  Lungenfunktion) die hauseigene Formulierung als Vorlage spiegeln.
- **Nur anonymisierte Vorlagen verwenden.** Echte Patientenbriefe gehören nicht
  hierher (siehe Datenschutz-Gate in SKILL.md).

## 4. Befund-Transkription aus Bildern/Anhängen

- Hochgeladene Befunde (Labor, Röntgen-Thorax, CT, Funktionsdiagnostik) werden in
  den Brief **im Hausstil** übertragen.
- **Nur übertragen, was tatsächlich sichtbar/angegeben ist.** Keine Werte, Maße,
  Codes oder Beurteilungen erfinden oder ergänzen.
- Unleserliche/unklare Werte als `[unleserlich]` oder `[bitte prüfen]` markieren,
  nicht raten.
- **DSGVO zuerst:** Vor dem Hochladen identifizierende Daten entfernen. Bei
  erkannten Patientendaten Bearbeitung stoppen und zur Löschung auffordern.
