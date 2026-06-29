# Fachrichtungsspezifische Datenfelder

Pro Fachrichtung die typischen, fachgerecht erwarteten Datenfelder. **Wichtige
Regel:** Diese Felder steuern nur Gewichtung, Reihenfolge und Sprache. Sie werden
**nur verwendet, wenn der Arzt die Daten geliefert hat.** Kein Feld wird erfunden
oder „zur Vollständigkeit" ergänzt. Fehlt ein erwartetes, relevantes Feld, wird es
als `[FEHLEND: bitte ergänzen]` markiert oder erfragt.

## Kardiologie
- kardiale Anamnese, NYHA-Stadium
- EF (Ejektionsfraktion), Echokardiografie-Befund
- Rhythmus (EKG, ggf. Langzeit-EKG), Herzfrequenz
- Antikoagulation / antithrombotische Therapie
- Biomarker: Troponin-Verlauf, BNP/NT-proBNP
- Koronarstatus / Intervention (sofern erfolgt)

## Pneumologie
- Atemfrequenz, SpO2, Sauerstoffbedarf
- Auskultationsbefund
- Blutgasanalyse (pH, pCO2, pO2, HCO3, BE)
- Lungenfunktion (Spirometrie, Bodyplethysmographie, Diffusion), ggf. 6-MWT
- Kapnometrie (tcpCO2), Polygraphie/Polysomnographie (AHI)
- NIV-Einstellungen (Modus, IPAP/EPAP, Frequenz), Maskentyp
- Weaning-Status, Trachealkanüle/Dekanülierung (siehe Weaning-Brief in
  `struktur-vorlagen.md`)
- Bildgebung (Röntgen/CT-Thorax)
- Entzündungswerte (CRP, Leukozyten, ggf. PCT)
- relevante Diagnosen wie COPD, Asthma, ACOS (Asthma-COPD-Overlap),
  respiratorische Insuffizienz — nur wie vom Arzt angegeben, nicht selbst zuordnen

## Gastroenterologie
- abdomineller Untersuchungsbefund
- Endoskopiebefund (ÖGD/Koloskopie)
- Sonografie/Bildgebung Abdomen
- Leberwerte, Lipase, relevante Labore

## Nephrologie
- Kreatinin/eGFR-Verlauf, Elektrolyte
- Urinbefund, Bilanz/Gewicht
- Dialysestatus (sofern zutreffend)

## Neurologie
- strukturierter neurologischer Status
- Bildgebung (CT/MRT), Gefäßstatus
- ggf. Liquor, Elektrophysiologie (EEG/ENG/EMG)
- bei Schlaganfall: NIHSS, Lyse/Thrombektomie, Sekundärprophylaxe

## Psychiatrie / Psychosomatik
- psychopathologischer Befund
- Eigen-/Fremdgefährdung (sofern dokumentiert)
- Therapie: medikamentös und psychotherapeutisch
- Verlauf; besondere Datenschutz-Sensibilität (siehe „Sensible Fälle" in SKILL.md)

## Chirurgie / Orthopädie / Unfallchirurgie
- OP-Datum, OP-Verfahren/Eingriff
- intraoperative Besonderheiten, Komplikationen
- postoperativer Verlauf, Wundstatus, Mobilisation
- bei Trauma: Unfallmechanismus, Frakturklassifikation (sofern geliefert)
- OP-Bericht referenzieren, nicht komplett einfügen

## Gynäkologie / Geburtshilfe
- zyklus-/schwangerschaftsbezogene Angaben (SSW sofern geliefert)
- gynäkologischer/sonografischer Befund
- relevante Voroperationen

## Pädiatrie
- Alter präzise (Monate/Jahre), Gewicht/Perzentile (sofern geliefert)
- gewichtsbasierte Dosierungen **nie selbst berechnen**, nur übernehmen
- Impf-/Entwicklungsanamnese, sofern relevant und geliefert

## Innere Medizin (allgemein)
- Labor- und Verlaufsschwerpunkt
- Medikationsänderungen klar dokumentieren (Begründung nur, wenn geliefert)
- Komorbiditäten strukturiert als Nebendiagnosen

## Multidisziplinäre Fälle
Bei mehreren beteiligten Fachrichtungen kurz klären, welche die Federführung hat;
Befunde zusammenführen; kennzeichnen, welcher Bereich welchen Anteil beigetragen
hat. Keine inhaltliche Vermischung erfinden.
