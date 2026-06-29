# Rechtsrahmen, Datenschutz und Evidenzlage

Referenz für den Arztbrief-Assistenten. Bei rechtlichen oder Datenschutzfragen
hier nachschlagen. **Wichtig:** Diese Datei fasst den Rahmen zusammen - sie
ersetzt keine Rechtsberatung. Bei konkreten Haftungs- oder Aufbewahrungsfragen ist
die jeweilige Landesärztekammer bzw. ein Justiziar maßgeblich.

## Inhalt
1. Verpflichtung zur Erstellung
2. Form und Aufbau - rechtlicher Status
3. Haftung und juristische Bedeutung
4. Aufbewahrungsfristen
5. Datenschutz, Schweigepflicht, Versand
6. Elektronischer Arztbrief (eArztbrief / TI)
7. Evidenz und Studien

---

## 1. Verpflichtung zur Erstellung

Die Pflicht zur ärztlichen Dokumentation und zur Zusammenführung der wesentlichen
Behandlungsdaten ergibt sich u. a. aus **§ 73 Abs. 1b SGB V** (Dokumentation,
Zusammenführung, Bewertung und Aufbewahrung der wesentlichen Behandlungsdaten,
Befunde und Berichte aus ambulanter und stationärer Versorgung) und der
allgemeinen Behandlungsdokumentation nach **§ 630f BGB**.

Praktisch gilt: Zu jeder stationären Behandlung gehört ein Arztbrief; ebenso sind
Briefe bei ambulanter Behandlung, klinikinterner Verlegung und tagesklinischer
Behandlung üblich. Eigentümer der personenbezogenen Information im Arztbrief ist
der Patient.

## 2. Form und Aufbau - rechtlicher Status

**Es gibt in Deutschland keine verbindliche gesetzliche Vorgabe und keine
offizielle Leitlinie/Fachgesellschafts-Empfehlung für Aufbau und Form des
Arztbriefs.** Das ist die zentrale, ehrliche Ausgangslage (so ausdrücklich
Unnewehr et al. 2013 und mehrere Folgequellen). Was existiert, ist ein durch
Praxis und Fachliteratur **etablierter Standard** sowie Gestaltungsnormen:

- **DIN 5008** - Schreib- und Gestaltungsregeln für Text- und
  Informationsverarbeitung (formale Gestaltung).
- **ONR 112203** (Austrian Standards) - Patientenbrief und Arztbrief (Österreich).
- **ISO/HL7 27932 (CDA R2)** und **LOINC 11490-0** (Discharge summarization note)
  - für den strukturierten/elektronischen Austausch.

Konsequenz für die Skill: Der Aufbau in `struktur-vorlagen.md` ist "Best Practice",
nicht "Gesetz". Klinikinterne Vorgaben (Chefarzt, Abteilung) haben Vorrang und
werden, wenn genannt, übernommen.

## 3. Haftung und juristische Bedeutung

Nach gängiger Rechtsprechung darf sich der weiterbehandelnde Arzt auf die
Richtigkeit des Arztbriefs verlassen, und der vorbehandelnde Arzt darf von der
Befolgung seiner Empfehlungen ausgehen. Ist der Brief **falsch, unklar,
unvollständig oder zu spät** erstellt, kann der Ersteller haften, falls dem
Patienten dadurch ein Schaden entsteht.

Daraus folgt für die Skill direkt:
- Erfundene oder geglättete Inhalte sind ein **Haftungsrisiko**, kein Stilthema.
- Unsicherheiten werden gekennzeichnet, nicht kaschiert.
- Zeitnahe Erstellung gehört zur Sorgfalt (siehe Fristen unten).

## 4. Aufbewahrungsfristen

- **Allgemeine Behandlungsdokumentation:** mindestens **10 Jahre** nach Abschluss
  der Behandlung (§ 630f Abs. 3 BGB), sofern keine längere Frist gilt.
- **Nach stationärer Behandlung** wird die Krankenakte (inkl. Arztbrief-Kopie) in
  Deutschland in der Regel **30 Jahre** archiviert; für einzelne Bereiche
  (z. B. Röntgen, Transfusion, Strahlentherapie) gelten gesonderte, teils längere
  Fristen.
- Eine Kopie des Arztbriefs verbleibt als Teil der Patientenakte.

Bei konkreten Fristen im Einzelfall: Landesärztekammer / Berufsordnung prüfen.

## 5. Datenschutz, Schweigepflicht, Versand

- Die ärztliche **Schweigepflicht** ist berufsrechtlich (Berufsordnung der
  (Landes-)Ärztekammern, MBO-Ä) und strafrechtlich (**§ 203 StGB**) verankert.
- Es gelten **DSGVO** und die Empfehlungen der Bundesärztekammer/KBV zu
  Schweigepflicht, Datenschutz und Datenverarbeitung (auch beim Versand von
  Arztbriefen).
- Für die Skill gilt das **Datenschutz-Gate** aus der SKILL.md: keine
  Verarbeitung oder Speicherung personenidentifizierender Daten; bei
  versehentlicher Eingabe Hinweis auf Löschung der Unterhaltung; Identifikatoren
  im Output nur als Platzhalter.

## 6. Elektronischer Arztbrief (eArztbrief / TI)

Der elektronische Arztbrief war ursprünglich nach **§ 291a ff. SGB V** als
freiwillige Anwendung der elektronischen Gesundheitskarte konzipiert. Inzwischen
läuft der strukturierte Austausch über die **Telematikinfrastruktur (TI)**, u. a.
per **KIM** (Kommunikation im Medizinwesen) und auf Basis von **HL7 CDA / "Arztbrief
Plus"**. Identifikatoren im strukturierten eArztbrief sind dort u. a. KVNR
(Patient), LANR (Arzt), BSNR (Betriebsstätte), IKNR (Institution) - **genau die
Felder, die in dieser Skill nie verarbeitet werden.**

Konsequenz: Die Skill erzeugt den **textlich-inhaltlichen** Brief (Fließtext nach
Standardgliederung). Das Einsetzen identifizierender Strukturdaten und der Versand
erfolgen im PVS/KIS des Arztes, nicht hier.

## 7. Evidenz und Studien

Belege für die Arbeitsweise der Skill (Prinzip "das Wichtigste zuerst", Lesbarkeit,
Strukturierung, Vermeidung von Floskeln/Abkürzungen):

- **Unnewehr M, Schaaf B, Friederichs H (2013): "Arztbrief: Die Kommunikation
  optimieren." Dtsch Arztebl 110(37): A1672-A1676.** Zentrale deutsche Arbeit;
  Quelle der "Dortmunder Arztbrief-Checkliste" und der Tabelle typischer
  sprachlicher Schwierigkeiten. Kernaussagen: keine verbindlichen Leitlinien
  vorhanden; Lesbarkeit als übergeordnetes Ziel; juristische Bedeutung des Briefs.
- **Bechmann S (2019), Heinrich-Heine-Universität Düsseldorf: "Epikrise in der
  Krise?"** Befragung von 197 Hausärzten zur Qualität klinischer
  Entlassungsbriefe; bemängelt v. a. Sprache und Inhalt, fehlende Ausbildung im
  Studium, Zeitmangel; empfiehlt stärkere Strukturierung/Standardisierung.
- **Spießl H, Cording C (2001): "Der 'optimale' Arztbrief." Dtsch Med Wochenschr
  126: 184-187.** Frühe Empfehlung: kurz, strukturiert, rasch übermittelt.
- **Weitz G, Friederichs H et al. (2015):** curriculare Übung zum Verfassen von
  Arztbriefen im Medizinstudium (Wien Med Wochenschr 165: 88-90).
- **DGIM, "Kurzanleitung zum Schreiben von Arztbriefen"** (eMedpedia, Springer).
- **Schmidt-Wilcke T, Sturm D (Hrsg., 2023): "Arztbriefe in der Neurologie."**
  Springer - u. a. Kapitel zu Aufbau/Stil und kommunikationstheoretischer Sicht.
- Internationale Belege zur Versorgungsrelevanz: Kripalani et al. (JAMA 2007) zu
  Kommunikationsdefiziten zwischen Klinik und Hausarzt; van Walraven et al. (1998)
  zu standardisierten vs. narrativen Entlassbriefen.

Quantitativer Kontext aus diesen Arbeiten: Hausärzte lesen mehrere Arztbriefe pro
Tag (in Summe bis zu rund einer Stunde), Klinikärzte verbringen erheblichen Teil
ihrer Arbeitszeit mit dem Verfassen - ein starkes Argument für Kürze, Struktur und
Wiederverwendbarkeit, **nicht** für Fülle.
