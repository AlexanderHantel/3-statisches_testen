### Rollen und Verantwortlichkeiten im Reviewprozess

Die erfolgreiche Durchführung von <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Reviews**</a> erfordert eine klare Rollenverteilung mit definierten Verantwortlichkeiten. Die Rollenstruktur gewährleistet sowohl die fachliche Qualität als auch die prozessuale Effizienz der <a href="./Glossar.md#qualitaetssicherung" title="→ Glossar öffnen" class="glossary-term">**Qualitätssicherung**</a>.

### Grundprinzipien der Rollenverteilung

#### Flexible Rollenzuordnung

> Nicht jede Rolle muss von einer separaten Person ausgefüllt werden - Überschneidungen bei den Verantwortlichkeiten rechtfertigen ein Zusammenlegen von Rollen.

**Rollenkombinationen:**
* **<a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">Moderator</a> und <a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">Reviewleiter</a>**: Bei kleineren <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Reviews**</a> praktikabel
* **<a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">Autor</a> und <a href="./Glossar.md#protokollant" title="→ Glossar öffnen" class="glossary-term">Protokollant</a>**: Pragmatische Lösung für detaillierte Dokumentation
* **<a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">Reviewer</a> und Fachexperte**: Spezialisierte Bewertung

**Entscheidungsfaktoren für Rollenkombination:**
* **Projektumfeld**: Größe und Komplexität des Projekts
* **Qualitätskriterien**: Erforderliche Bewertungstiefe
* **Verfügbare Ressourcen**: Personelle Kapazitäten
* **<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">Review</a>-Art**: Formalitätsgrad und Umfang

*Beispiel:* Bei einem informellen Pixel Leap Code-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> könnte ein Senior-Entwickler sowohl als <a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">**Reviewleiter**</a> als auch als <a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">**Moderator**</a> fungieren, während bei einem formalen Sicherheits-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> alle Rollen separat besetzt werden sollten.

### Management-Rolle

#### Strategische Verantwortung und Ressourcensteuerung

Das Management trägt die übergeordnete Verantwortung für die <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Strategie:

**Kernaufgaben des Managements:**

1. **Auswahl der Prüfobjekte**
   - Identifikation kritischer Dokumente und Arbeitsergebnisse
   - Priorisierung basierend auf Risiko und Geschäftswert
   - Berücksichtigung von Compliance-Anforderungen
   - Abstimmung mit Projektzielen

2. **<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">Review</a>-Art-Entscheidung**
   - Bestimmung des Formalitätsgrades
   - Auswahl geeigneter <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Techniken
   - Definition der Qualitätsziele
   - Festlegung der <a href="./Glossar.md#endekriterien" title="→ Glossar öffnen" class="glossary-term">**Endekriterien**</a>

3. **Ressourcenbereitstellung**
   - Personelle Kapazitäten zuweisen
   - Budget für <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Aktivitäten bereitstellen
   - Zeitfenster für <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Reviews**</a> einplanen
   - Technische Infrastruktur sicherstellen

4. **Kosteneffizienz-Überwachung**
   - Aufwand-Nutzen-Verhältnis bewerten
   - <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Metriken analysieren
   - Prozessoptimierungen initiieren
   - ROI der <a href="./Glossar.md#qualitaetssicherung" title="→ Glossar öffnen" class="glossary-term">**Qualitätssicherung**</a> messen

*Beispiel:* Das Pixel Leap Management entscheidet, dass alle sicherheitskritischen API-Spezifikationen einem formalen <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> unterzogen werden müssen, stellt dafür 20% der Entwicklungszeit bereit und definiert als Qualitätsziel "null kritische Sicherheitslücken".

#### Management-Teilnahme-Richtlinien

> Vertreter des Managements sollen nicht an <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>sitzungen teilnehmen, wenn sie zum <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> in einer Vorgesetzten-Beziehung stehen.

**Ausschlussgründe für Management-Teilnahme:**
* **Bewertungsverzerrung**: Risiko der Personenbewertung statt Dokumentenbewertung
* **Diskussionshemmung**: Eingeschränkte "freie" Kommunikation
* **Fachliche Distanz**: Möglicherweise fehlendes detailliertes IT-Fachwissen
* **Hierarchische Dynamik**: Beeinflussung der objektiven Bewertung

**Ausnahmen für Management-Teilnahme:**
* **Managementlastige Dokumente**: Projektpläne, Strategiepapiere
* **Geschäftskritische Entscheidungen**: Architekturentscheidungen mit hohem Impact
* **Compliance-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">Reviews</a>**: Regulatorische Anforderungen
* **Stakeholder-Abstimmung**: Externe Schnittstellen und Verträge

### Reviewleiter-Rolle

#### Gesamtverantwortung und Koordination

> Der <a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">**Reviewleiter**</a> trägt die Gesamtverantwortung für das <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> - von der Planung bis zur Nachbereitung.

**Detaillierte Aufgaben des <a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">**Reviewleiters**</a>:**

1. **Strategische Planung**
   - <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Ziele definieren und kommunizieren
   - Erfolgskriterien festlegen
   - Risikobewertung durchführen
   - Zeitplan entwickeln

2. **Teilnehmerauswahl und -koordination**
   - Fachexperten identifizieren und einladen
   - Rollenzuweisungen vornehmen
   - Verfügbarkeiten koordinieren
   - Kompetenzabdeckung sicherstellen

3. **Logistische Organisation**
   - Termine koordinieren und kommunizieren
   - Räumlichkeiten oder virtuelle Meetings organisieren
   - Technische Infrastruktur bereitstellen
   - Dokumentenverteilung sicherstellen

4. **Qualitätssicherung des Prozesses**
   - Einhaltung der <a href="./Glossar.md#eintrittskriterien" title="→ Glossar öffnen" class="glossary-term">**Eintrittskriterien**</a> prüfen
   - Prozesskonformität überwachen
   - Zielerreichung bewerten
   - <a href="./Glossar.md#endekriterien" title="→ Glossar öffnen" class="glossary-term">**Endekriterien**</a>-Erfüllung verifizieren

*Beispiel:* Für ein Pixel Leap Multiplayer-Protokoll-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> wählt der <a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">**Reviewleiter**</a> Experten für Netzwerkprotokolle, Sicherheit, Performance und Client-Server-Architektur aus, koordiniert einen 3-stündigen Workshop und stellt sicher, dass alle Teilnehmer Zugang zu Referenzdokumenten haben.

### Moderator-Rolle (Facilitator)

#### Sitzungsleitung und Prozesssteuerung

> Der Erfolg eines <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Reviews**</a> hängt oft vom <a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">**Moderator**</a> ab.

**Kernkompetenzen des <a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">**Moderators**</a>:**

1. **Exzellente Sitzungsleitung**
   - Strukturierte Agenda-Führung
   - Zeitmanagement und Fokussierung
   - Partizipation aller Teilnehmer sicherstellen
   - Ergebnisorientierte Diskussionsführung

2. **Diplomatische Vermittlung**
   - Gegensätzliche Standpunkte moderieren
   - Konflikte konstruktiv lösen
   - Konsensbildung fördern
   - Respektvolle Kommunikation gewährleisten

3. **Durchsetzungsfähigkeit und Sensibilität**
   - Unnütze Diskussionen beenden
   - Auf "Untertöne" und nonverbale Signale achten
   - Verletzungen und Kränkungen vermeiden
   - Autorität ohne Dominanz ausüben

4. **Neutralität und Objektivität**
   - Keine eigene Meinung zum Arbeitsergebnis äußern
   - Unvoreingenommene Prozessführung
   - Gleichberechtigte Behandlung aller Teilnehmer
   - Fokus auf Prozess statt Inhalt

**Operative Aufgaben:**
* **Datensammlung**: Metriken und Kennzahlen erfassen
* **Protokollerstellung**: Vollständige Dokumentation sicherstellen
* **Zeitkontrolle**: Einhaltung der geplanten Dauer
* **Qualitätskontrolle**: Vollständigkeit der Befundbearbeitung

*Beispiel:* Bei einem kontroversen Pixel Leap Architektur-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> moderiert der <a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">**Moderator**</a> zwischen einem Entwickler, der eine Microservice-Architektur bevorzugt, und einem Architekten, der eine monolithische Lösung vorschlägt, indem er beide Positionen strukturiert diskutieren lässt und auf objektive Bewertungskriterien fokussiert.

### Autor-Rolle

#### Dokumentenverantwortung und Korrekturumsetzung

> Der <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> ist der Ersteller des zu prüfenden Arbeitsergebnisses und trägt die Hauptverantwortung für dessen Qualität.

**Verantwortlichkeiten des <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autors**</a>:**

1. **Vorbereitung des <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Reviews**</a>**
   - Sicherstellung der <a href="./Glossar.md#eintrittskriterien" title="→ Glossar öffnen" class="glossary-term">**Eintrittskriterien**</a>-Erfüllung
   - Dokument in "reviewfähigen" Zustand bringen
   - Basisdokumente und Referenzen bereitstellen
   - Kontext und Hintergrundinformationen kommunizieren

2. **Teilnahme am <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>**
   - Fragen zu Dokumenteninhalten beantworten
   - Designentscheidungen erläutern (ohne Verteidigung)
   - Klarstellungen zu mehrdeutigen Stellen geben
   - Konstruktive Diskussion unterstützen

3. **Nachbearbeitung und Korrektur**
   - Identifizierte <a href="./Glossar.md#fehlerzustand" title="→ Glossar öffnen" class="glossary-term">**Fehlerzustände**</a> systematisch beheben
   - Verbesserungsvorschläge umsetzen
   - <a href="./Glossar.md#endekriterien" title="→ Glossar öffnen" class="glossary-term">**Endekriterien**</a> erfüllen
   - Überarbeitete Version bereitstellen

**Mehrautoren-Konstellation:**
> Sind mehrere Personen an der Erstellung beteiligt, ist ein Hauptverantwortlicher zu benennen, der die <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a>-Rolle übernimmt.

**Psychologische Aspekte:**
> Der <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> soll die Kritik nicht als Kritik an seiner Person auffassen, sondern als Beitrag zur Qualitätsverbesserung.

*Beispiel:* Der <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> einer Pixel Leap Datenbank-Spezifikation stellt sicher, dass alle Entity-Relationship-Diagramme vollständig sind, beantwortet während des <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Reviews**</a> Fragen zur Normalisierungsstrategie und implementiert anschließend die empfohlenen Index-Optimierungen.

### Reviewer-Rolle (Gutachter/Inspektoren)

#### Fachliche Bewertung und Qualitätsprüfung

> <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a> sind mehrere (meist nicht mehr als fünf) Fachexperten, die nach entsprechender Vorbereitung am <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> teilnehmen.

**Zusammensetzung des <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a>-Teams:**

1. **Projektinterne Experten**
   - Entwickler mit Domänenwissen
   - Architekten und Systemdesigner
   - Tester und Qualitätssicherungsexperten
   - Business-Analysten und Fachexperten

2. **Stakeholder-Vertreter**
   - Endanwender-Repräsentanten
   - Betreiber und Administratoren
   - Kunden und Auftraggeber
   - Compliance-Verantwortliche

3. **Spezialisierte Fachexperten**
   - Sicherheitsexperten
   - Performance-Spezialisten
   - Usability-Experten
   - Technologie-Spezialisten

**Kernaufgaben der <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a>:**

1. **Problemidentifikation**
   - Systematische Analyse des Arbeitsergebnisses
   - Identifikation von <a href="./Glossar.md#fehlerzustand" title="→ Glossar öffnen" class="glossary-term">**Fehlerzuständen**</a> und <a href="./Glossar.md#anomalie" title="→ Glossar öffnen" class="glossary-term">**Anomalien**</a>
   - Erkennung von Inkonsistenzen und Lücken
   - Bewertung der Vollständigkeit

2. **Perspektivische Bewertung**
   - Einnehmen verschiedener Sichtweisen
   - Rollenspezifische Analyse
   - Berücksichtigung unterschiedlicher <a href="./Glossar.md#use-case" title="→ Glossar öffnen" class="glossary-term">**Use Cases**</a>
   - Stakeholder-orientierte Bewertung

3. **Spezialisierte Prüfung**
   - Fokussierung auf spezifische Aspekte
   - Standard-Konformitätsprüfung
   - Syntax- und Formatvalidierung
   - Technische Machbarkeitsbewertung

4. **Konstruktive Dokumentation**
   - Präzise Problembeschreibung
   - Nachvollziehbare Lokalisierung
   - Verbesserungsvorschläge entwickeln
   - Positive Aspekte hervorheben

**Effizienzsteigerung durch Spezialisierung:**
> Einzelne <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a> sollen sich um spezielle Aspekte kümmern, um die Effizienz zu erhöhen.

**Beispiel-Spezialisierung für Pixel Leap API-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>:**

| <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a> | Spezialisierung | Fokusbereich |
|----------|----------------|--------------|
| **Sicherheitsexperte** | Authentifizierung & Autorisierung | Sicherheitslücken, Datenschutz |
| **Performance-Spezialist** | Effizienz & Skalierung | Latenz, Durchsatz, Ressourcenverbrauch |
| **Entwickler** | Implementierbarkeit | Technische Machbarkeit, Architektur |
| **Tester** | <a href="./Glossar.md#testbarkeit" title="→ Glossar öffnen" class="glossary-term">**Testbarkeit**</a> | Messbarkeit, Validierbarkeit |
| **UX-Designer** | Benutzerfreundlichkeit | API-Usability, Entwicklererfahrung |

**Ausgewogene Bewertung:**
> <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a> haben darauf zu achten, dass auch die als gut befundenen Teile benannt werden.

*Beispiel:* Ein <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a> könnte dokumentieren: "Die Authentifizierungslogik in Abschnitt 3.2 ist vorbildlich implementiert und sollte als Referenz für andere Module dienen. Jedoch fehlt in Abschnitt 3.4 die Spezifikation für Session-Timeouts."

### Protokollant-Rolle

#### Dokumentation und Nachverfolgung

> Der <a href="./Glossar.md#protokollant" title="→ Glossar öffnen" class="glossary-term">**Protokollant**</a> dokumentiert alle diskutierten und gefundenen Unklarheiten verfälschungsfrei.

**Dokumentationsaufgaben:**

1. **Vollständige Erfassung**
   - Alle identifizierten Probleme und <a href="./Glossar.md#anomalie" title="→ Glossar öffnen" class="glossary-term">**Anomalien**</a>
   - Diskutierte Lösungsansätze
   - Getroffene Entscheidungen
   - Offene Fragestellungen

2. **Strukturierte Kategorisierung**
   - <a href="./Glossar.md#fehlerzustand" title="→ Glossar öffnen" class="glossary-term">**Fehlerzustände**</a> nach Schweregrad
   - Zuständigkeiten und Verantwortlichkeiten
   - Zeitrahmen für Korrekturen
   - <a href="./Glossar.md#status" title="→ Glossar öffnen" class="glossary-term">**Status**</a>-Informationen

3. **Präzise Formulierung**
   - Knapp und verständlich
   - Verfälschungsfreie Wiedergabe
   - Nachvollziehbare Beschreibungen
   - Eindeutige Lokalisierung

**Erforderliche Kompetenzen:**
* **Schnelle Auffassung**: Komplexe Diskussionen verstehen
* **Präzise Formulierung**: Kernaussagen extrahieren
* **Multitasking**: Zuhören und gleichzeitig dokumentieren
* **Fachverständnis**: Technische Inhalte korrekt wiedergeben

#### Technologische Entwicklung und Rollenwandel

> Durch die steigende Anzahl an Werkzeugen zur Unterstützung des <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>prozesses wird die Rolle des <a href="./Glossar.md#protokollant" title="→ Glossar öffnen" class="glossary-term">**Protokollanten**</a> zunehmend obsolet.

**Moderne Werkzeug-Unterstützung:**
* **Kollaborative Plattformen**: Gemeinsame Befund-Erfassung
* **Integrierte <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Tools**: Automatische Dokumentation
* **Digitale Whiteboards**: Visuelle Problemerfassung
* **KI-gestützte Protokollierung**: Automatische Transkription und Strukturierung

#### Pragmatische Lösung: <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> als <a href="./Glossar.md#protokollant" title="→ Glossar öffnen" class="glossary-term">**Protokollant**</a>

> Aus pragmatischen Gründen führt in der Praxis oft der <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> selbst das Protokoll.

**Vorteile der <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a>-Protokollierung:**
* **Detailverständnis**: Genau wissen, was für Korrekturen erforderlich ist
* **Präzision**: Ausreichende Information für spätere Änderungen
* **Effizienz**: Direkte Verbindung zwischen Befund und Umsetzung
* **Vollständigkeit**: Keine Informationsverluste durch Übertragung

**Potenzielle Nachteile:**
* **Doppelbelastung**: Gleichzeitige Teilnahme und Dokumentation
* **Subjektivität**: Mögliche Verzerrung der Protokollierung
* **Ablenkung**: Reduzierte Aufmerksamkeit für Diskussion
* **Vollständigkeitsrisiko**: Übersehen wichtiger Punkte

*Beispiel:* Bei einem Pixel Leap Datenmodell-<a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a> protokolliert der <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> selbst: "Tabelle 'PlayerStats' - Reviewer Schmidt: Index auf 'player_id' + 'game_session' fehlt für Performance-Optimierung. Priorität: Hoch. Umsetzung bis Freitag."

### Rolleninteraktion und Kommunikation

#### Effektive Zusammenarbeit

Die erfolgreiche <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Durchführung erfordert koordinierte Zusammenarbeit aller Rollen:

**Kommunikationsmatrix:**

| Von/An | Management | <a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">**Reviewleiter**</a> | <a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">**Moderator**</a> | <a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">**Autor**</a> | <a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">**Reviewer**</a> |
|--------|------------|-------------|-----------|-------|----------|
| **Management** | - | Ziele, Ressourcen | - | Erwartungen | - |
| **<a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">Reviewleiter</a>** | Status, Ergebnisse | - | Koordination | Anforderungen | Aufgaben |
| **<a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">Moderator</a>** | - | Feedback | - | Prozess | Struktur |
| **<a href="./Glossar.md#autor" title="→ Glossar öffnen" class="glossary-term">Autor</a>** | - | Bereitschaft | Kontext | - | Erläuterungen |
| **<a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">Reviewer</a>** | - | Befunde | Diskussion | Fragen | Abstimmung |

### Qualitätssicherung der Rollenausführung

#### Kompetenzanforderungen und Entwicklung

Jede Rolle erfordert spezifische Kompetenzen:

**<a href="./Glossar.md#reviewleiter" title="→ Glossar öffnen" class="glossary-term">Reviewleiter</a>-Kompetenzen:**
* Projektmanagement-Fähigkeiten
* Fachliche Autorität
* Kommunikationsstärke
* Qualitätsbewusstsein

**<a href="./Glossar.md#moderator" title="→ Glossar öffnen" class="glossary-term">Moderator</a>-Kompetenzen:**
* Sitzungsleitung
* Konfliktmanagement
* Neutralität
* Prozessverständnis

**<a href="./Glossar.md#reviewer" title="→ Glossar öffnen" class="glossary-term">Reviewer</a>-Kompetenzen:**
* Fachexpertise
* Analytische Fähigkeiten
* Konstruktive Kritikfähigkeit
* Teamarbeit

Die klare Definition und konsequente Umsetzung der Rollen und Verantwortlichkeiten ist entscheidend für den Erfolg des <a href="./Glossar.md#review" title="→ Glossar öffnen" class="glossary-term">**Review**</a>-Prozesses und trägt wesentlich zur <a href="./Glossar.md#qualitaetssicherung" title="→ Glossar öffnen" class="glossary-term">**Qualitätssicherung**</a> in der Softwareentwicklung bei.