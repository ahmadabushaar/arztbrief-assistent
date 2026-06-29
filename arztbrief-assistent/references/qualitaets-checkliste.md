# Qualitäts-Checkliste (Ausgabe-Gate)

Vor der Ausgabe jedes Arztbriefs durchlaufen. Angelehnt an die Dortmunder
Arztbrief-Checkliste (Unnewehr et al. 2013). Nicht erfülltes Kriterium:
korrigieren oder beim Arzt nachfragen, nicht stillschweigend ausgeben.

## A. Datenschutz (hartes Stopp-Kriterium)
- [ ] Keine personenidentifizierenden Daten (Name, Adresse, Geburtsdatum,
      Fallnummer, Versichertennummer, Kontaktdaten).
- [ ] Identifikatoren nur als Platzhalter (`[Name]`, `[Fallnr.]` …).
- [ ] Bei versehentlich gelieferten Patientendaten wurde der Lösch-Hinweis
      ausgegeben.

## B. Inhaltliche Integrität (hartes Stopp-Kriterium)
- [ ] Keine erfundenen Diagnosen, Befunde, Medikamente, Dosierungen, Laborwerte,
      ICD-10-/OPS-Codes.
- [ ] **Keine Verschönerung/Verschlechterung:** klinische Aussage unverändert; AZ,
      Belastbarkeit, Prognose nicht verschoben.
- [ ] Fehlende Angaben als `[FEHLEND: bitte ergänzen]` markiert, nicht geglättet.
- [ ] Keine eigenständige Beurteilung/Therapieempfehlung hinzugefügt.
- [ ] Sicherheitsgrade korrekt (gesichert / anamnestisch / V. a. / unklar).

## C. Begriffspräzision
- [ ] Medizinisch/juristisch trennscharfe Begriffe korrekt verwendet, insbesondere
      „ausgeschlossen" vs. „kein Hinweis auf", „Z. n." vs. „aktuell", „V. a." vs.
      „gesichert". Bei Unklarheit Rückfrage statt eigenmächtiger Wahl.

## D. Chronologie-Check
- [ ] Ereignisreihenfolge nachvollziehbar:
      Aufnahme -> Diagnostik -> Therapie -> Verlauf -> Entlassung.
- [ ] Keine widersprüchlichen Datums-/Zeitangaben (z. B. Entlassung vor Aufnahme,
      Befund vor Aufnahme). Bei Unklarheit nachfragen.

## E. Widerspruchsprüfung
Auffälligkeiten dem Arzt **benennen**, nicht eigenmächtig auflösen:
- [ ] Diagnose ohne passenden Befund (z. B. „Pneumonie" ohne Bildgebung/Labor).
- [ ] Medikation ohne erkennbare Indikation in den gelieferten Daten.
- [ ] **Allergie und gleichzeitige Verordnung des Allergens** (Sicherheitsflag).
- [ ] Sich widersprechende Angaben im Verlauf.

## F. Medikationssicherheit
- [ ] Je Medikament Vollständigkeit geprüft: Wirkstoff/Präparat, Stärke, Schema.
- [ ] Fehlende Angabe (Name, Dosis, Dauer) als `[FEHLEND: bitte ergänzen]`
      markiert. **Niemals Dosis oder Präparat ergänzen oder vorschlagen.**
- [ ] Keine doppelten/kollidierenden Einträge in den gelieferten Daten (falls doch,
      Hinweis an den Arzt).

## G. Struktur und Logik
- [ ] Hauptdiagnose erkennbar zuerst; Nebendiagnosen nach Relevanz.
- [ ] Prinzip „das Wichtigste zuerst" eingehalten.
- [ ] Befunde vollständig und übersichtlich; OP-Bericht referenziert statt
      komplett eingefügt.
- [ ] Procedere vorhanden (sofern Dokumenttyp es erfordert).
- [ ] Entlassmedikation vorhanden oder als fehlend gekennzeichnet.

## H. Sprache und Form
- [ ] Durchgehend medizinisches Register, keine Alltagssprache.
- [ ] Keine leeren Floskeln/Füllwörter.
- [ ] Keine unerklärten/erfundenen Abkürzungen (Erstnennung ausgeschrieben).
- [ ] Rechtschreibung/Grammatik korrekt; einheitliche Werte und Einheiten.
- [ ] Fachrichtung und Dokumenttyp in Gewichtung/Aufbau berücksichtigt.

## I. Ausgabeprotokoll
Nach der Checkliste eine **kurze Qualitätsnotiz** ausgeben: erfüllte Kriterien,
fehlende/zu ergänzende Angaben, markierte Widersprüche. Danach der Abschluss:

> **Ärztliche Freigabe erforderlich.** Bitte vor Verwendung medizinisch prüfen:
> Diagnosen · Medikamente · Dosierungen · Empfehlungen · personenbezogene Daten.

So bleibt transparent, was die Skill geleistet hat und wo die ärztliche
Verantwortung zwingend ansetzt.
