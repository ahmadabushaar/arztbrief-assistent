# Strukturvorlagen je Dokumenttyp

Gliederungen sind Best Practice, keine gesetzliche Pflicht (siehe
rechtsrahmen.md). Klinikinterne Vorgaben haben Vorrang. Grundprinzip: das
Wichtigste zuerst, Diagnosen frueh, knapp und lesbar. Fachspezifische Pflichtfelder
stehen separat in fachrichtungen.md.

## Inhalt
1. Standardgliederung
2. Vorlagen je Dokumenttyp
3. Pflicht-Mindestinhalte und typische Luecken je Krankheitsbild

---

## 1. Standardgliederung (fachuebergreifend)

```
[Briefkopf: Adressat, Anrede, Patient (Platzhalter), Aufenthalt von-bis (Platzhalter)]

Diagnosen
  1. Hauptdiagnose            (ICD-10 nur wenn geliefert)
  2. Nebendiagnosen           (nach klinischer Relevanz)
  3. relevante Begleiterkrankungen

Anamnese / Aufnahmegrund
  Vorstellungsgrund, Leitsymptome, relevante Vorgeschichte, Risikofaktoren

Befunde
  Klinischer Untersuchungsbefund, Labor (nur relevante Werte), Bildgebung,
  Funktionsdiagnostik (EKG, Lufu, Endoskopie)

Therapie und Verlauf
  Massnahmen, medikamentoese Therapie, Interventionen/OP (Bericht referenzieren),
  Komplikationen, klinischer Verlauf

Epikrise / Beurteilung
  zusammenfassende Bewertung (nur aus gelieferten Daten ableitbar)

Procedere / Empfehlungen
  Kontrollen, Weiterbehandlung, Nachsorge

Medikation bei Entlassung
  Wirkstoff, Staerke, Schema   (vollstaendig, sofern geliefert)

[Grussformel, Unterschriftszeile Facharzt]
```

Priorisierung bei Kuerzung (Kurzbrief): immer vorhanden sein muessen
Hauptdiagnose, Entlassmedikation, Procedere. Wichtig: Anamnese, Befunde, Epikrise.
Optional: detaillierter Verlauf, referenzierter OP-Bericht.

## 2. Vorlagen je Dokumenttyp

Aufnahmebrief: Schwerpunkt vorne - Aufnahmegrund, Anamnese, Aufnahmebefund,
Aufnahmediagnose(n), geplantes Vorgehen. Verlauf/Epikrise entfallen oder nur als
Plan.

Entlassbrief vorlaeufig (Kurzbrief): wird dem Patienten mitgegeben; sehr knapp,
mindestens Diagnosen, kurze Beurteilung, formloses Procedere (Termine),
Entlassmedikation. Kennzeichnung "vorlaeufiger Arztbrief".

Entlassbrief endgueltig: vollstaendige Standardgliederung. Soll zuegig erstellt
und in der Regel spaetestens rund zwei Wochen nach Entlassung versandt sein
(Sorgfalt/Haftung, siehe rechtsrahmen.md). Kennzeichnung "endgueltiger
Entlassbrief".

Zwischenbericht: aktueller Stand bei laufender Behandlung - bisheriger Verlauf,
aktuelle Diagnostik, aktuelle Therapie, naechste Schritte. Keine abschliessende
Epikrise.

Konsilbericht: Antwort auf eine konkrete Fragestellung. Aufbau:
Fragestellung, relevanter Befund, Beurteilung, konkrete Empfehlung. Fragestellung
explizit wiederholen.

Befundbericht: auf einen Untersuchungsbefund fokussiert - Indikation/Fragestellung,
Methode, Befund, Beurteilung.

Ueberweisungsbrief/Einweisung: knapp und zielgerichtet - Fragestellung/Auftrag,
relevante Anamnese, aktuelle Befunde, aktuelle Medikation, konkrete Bitte.

Verlegungsbericht: wie Entlassbrief, Fokus auf aktuellen Status zum
Verlegungszeitpunkt, laufende Therapien, offene Punkte fuer die uebernehmende
Einrichtung.

## 3. Pflicht-Mindestinhalte und typische Luecken je Krankheitsbild

Fehlen diese Angaben und sind fuer den Dokumenttyp relevant: nachfragen oder
[FEHLEND: ...] markieren, nicht erfinden.

Pneumonie: Roentgen-/CT-Thorax-Befund; CRP/Leukozyten; Sauerstoffbedarf;
antibiotische Therapie (Substanz, Dauer); Verlauf.

Operation (allgemein): OP-Datum; OP-Verfahren; intraoperative Besonderheiten;
Komplikationen; postoperativer Verlauf/Mobilisation/Wundstatus.

Kardiale Dekompensation / Herzinsuffizienz: Echo (EF); BNP/NT-proBNP; diuretische
Therapie/Rekompensation; Gewichtsverlauf/Bilanz.

Akutes Koronarsyndrom: EKG-Befund; Troponin-Verlauf; Koronarangiografie/
Intervention; antithrombotische Therapie.

Diabetes mellitus: HbA1c; aktuelle antidiabetische Therapie; relevante
Folgeerkrankungen.

Schlaganfall: Bildgebung (CT/MRT), Gefaessstatus; Lyse/Thrombektomie;
neurologischer Status/NIHSS sofern dokumentiert; Sekundaerprophylaxe.

Generelle Luecken-Trigger ueber alle Bilder: fehlende Hauptdiagnose, fehlende
Entlassmedikation, fehlendes Procedere, fehlende Allergien, unklarer Verlauf -
diese fuenf immer aktiv pruefen.

## Spezielle pneumologische Briefe

**Weaning-Brief (Entwöhnung von der Beatmung)**
Eigener Entlass-/Verlegungsbrief-Subtyp. Charakteristisch: **Diagnosen und
Weaning-Verlauf** stehen prominent und werden vollständig und unverändert
wiedergegeben. Mindeststruktur:
- Diagnosen (Haupt: respiratorische Insuffizienz / Grunderkrankung;
  weaning-relevante Nebendiagnosen)
- Aufnahme-/Verlegungsgrund, Beatmungsanamnese
- Weaning-Verlauf (chronologisch: Beatmungsmodus, schrittweise Reduktion,
  Spontanatmungsphasen, NIV/Trachealkanüle, ggf. Dekanülierung, Komplikationen)
- aktueller respiratorischer Status (BGA, NIV-Einstellung, O2-Bedarf)
- Beurteilung
- Procedere (NIV-Fortführung, Kontrolltermine, Hilfsmittel)
- Medikation
Diagnosen und Weaning-Verlauf **immer exakt aus den Angaben übernehmen**, nie
zusammenfassen oder verfälschen. Liegt ein anonymisierter Hausmusterbrief vor,
dessen Struktur exakt spiegeln (siehe `ausgabe-hausstil.md`).

**NIV-Kontrolle**
- Indikation, aktuelle NIV-Einstellungen (Modus, IPAP/EPAP, Frequenz), Maskentyp
- Polygraphie/Polysomnographie-Befund, Kapnometrie (tcpCO2), BGA
- Therapieanpassung (nur wie angegeben)
- Beurteilung und nächster Kontrolltermin
