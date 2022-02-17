Datensatzdokumentation

# COVID-19-Impfungen in Deutschland

[Robert Koch-Institut](https://grid.ac/institutes/grid.13652.33) | RKI  
Nordufer 20  
13353 Berlin  

**FG 33 |  Impfprävention**  
[Anette Siedler](https://orcid.org/0000-0002-6359-1018) (Fachliche Leitung)  
[Thorsten Rieck](https://orcid.org/0000-0002-8799-8744) (Datenanalyse)  
[Annika Steffen](https://orcid.org/0000-0003-4072-9245) (Datenanalyse)  
Nita Perumal (Datenanalyse)  

**FG 31 | Infektionsepidemiologische Fach-IT und Anwendungsentwicklung**  
[Lei Mao](https://orcid.org/0000-0002-8356-755X) (Projektleitung)  
[Hermann Claus](https://orcid.org/0000-0002-0120-1846) (Technische Leitung)  
Constantin Fischer (Datenmanagement)  
Sven Schröder (Datenmanagement)  
Daniel Wesseler (Datenmanagement)  

**MF 4 | Forschungsdatenmanagement**  
[Hannes Wuensche](https://orcid.org/0000-0002-8837-0326) (Datenkuration)  

---

Robert Koch-Institut (2021): COVID-19-Impfungen in Deutschland, Berlin: Zenodo. DOI:[10.5281/zenodo.5126652](http://doi.org/10.5281/zenodo.5126652).  

Der Datensatz "COVID-19-Impfungen in Deutschland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License |](https://creativecommons.org/licenses/by/4.0/deed.de) <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/legalcode.de">CC-BY 4.0 International</a>

## Informationen zum Datensatz und Entstehungskontext  

Die COVID-19-Impfung kann einen Wendepunkt in der Kontrolle der COVID-19-Pandemie darstellen und erfährt daher hohes Maß an öffentlicher Aufmerksamkeit. Einführung und Umsetzung der COVID-19-Impfung gehen mit besonderen Herausforderungen einher, die bei der Impfdatenerfassung zu berücksichtigen sind. 

In diesem Kontext ist es Ziel des Projekts "Digitales Impfquoten-Monitoring" (DIM), tagesaktuell und bundesweit die Impfquote zu erfassen und folgend aufbereitet darzustellen, um zeitnah den Verlauf der COVID-19-Impfkampagne zu analysieren, bei Bedarf nachzusteuern und logistische bzw. organisatorische Konsequenzen zu ziehen.  

Ein Hauptbestandteil des DIM-Projekts ist die DIM-Anwendung, eine Web-basierte Softwarelösung zur Erfassung der Impfquote der Bevölkerung gegen SARS-CoV2 auf Grundlage der [Coronavirus-Impfverordnung (CoronaImpfV)](https://www.bundesgesundheitsministerium.de/service/gesetze-und-verordnungen.html).  

Die DIM-Anwendung besteht aus Eingabemasken/Dialogen (Frontend) und dahinter liegenden Datenbanksystem (Backend). Autorisiertes Personal der stationären Impfzentren und mobile Impfteams können über die Web-Anwendung die Impfdatensätze zur COVID-19-Impfung eingeben und über eine gesicherte Internetverbindung pseudonymisiert an die Bundesdruckerei übermitteln. Im Auftrag des RKI werden die Daten von der Bundesdruckerei zwischengespeichert und vom RKI mehrmals täglich abgerufen. Alternativ zur direkten Eingabe können Daten in einem vorgegebenen csv-Datenformat durch die DIM-Web-Anwendung übermittelt werden (csv-Upload Schnittstelle). Als dritte Möglichkeit können Datensätze über eine REST-API Schnittstelle aus einem Fremdsystem an in das Datenbanksystem übertragen werden. Die nachfolgende Darstellung zeigt schematisch den Datenfluss von Erfassung der Daten in den Impfzentren bis hin zur Weitergabe der aggregierten Daten durch das RKI.

![**Abbildung**: Überblick Datenfluss Digitales Impfquoten-Monitoring (DIM)](/.github/pictures/2021-08-27_DIM_Datenfluss_Uebersicht.jpg)


### Projektbeteiligte und Rollenbesetzung  

An dem Projekt "Digitales Impfquoten-Monitoring" sind verschiedene Stakeholder beteiligt. Projektauftraggeber ist das [Bundesministerium für Gesundheit (BMG)](https://www.bundesgesundheitsministerium.de/). Das [Robert Koch-Institut](https://rki.de) übernimmt die Projektleitung. Die [Bundesdruckerei (BDr)](https://www.bundesdruckerei.de/) ist zuständig für die technische Entwicklung und den Betrieb der Web-Anwendung. [Accenture GmbH (ACN)](https://www.accenture.com/) unterstützt das RKI bei der Konzeption, der Planung, Dokumentation und der Rolloutkoordination. Projektzeitraum ist vom 01.11.2020 bis 30.11.2022.  

**Projektleitung** 
- Anette Siedler | [Fachgebiet 33](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG33/FG33_node.html)  
- Lei Mao und Hermann Claus  | [Fachgebiet 31](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG31/FG31_node.html)  

Die zugrundeliegenden Daten werden über die Bundesdruckerei an das Robert Koch-Institut (RKI) übermittelt. Die Verarbeitung und Aufbereitung der vorliegenden Rohdaten erfolgt durch das [Fachgebiet 31 | Infektionsepidemiologische Fach-IT und Anwendungsentwicklung](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG31/FG31_node.html) des RKI. Die epidemiologische Datenanalyse erfolgt durch das [Fachgebiet 33 | Impfprävention](https://www.rki.de/DE/Content/Institut/OrgEinheiten/Abt3/FG33/FG33_node.html) des RKI. Inhaltliche Fragen zum Digitalen Impfquoten-Monitoring und dem Impf-Fortschritt können direkt an [info@rki.de](mailto:info@rki.de) gerichtet werden.   

Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-)Daten erfolgen durch das Fachgebiet [MF 4 | Forschungsdatenmanagement](https://www.rki.de/DE/Content/Institut/OrgEinheiten/MF/MF4/mf4_node.html). Fragen zum Datenmanagement und zur Publikationsinfrastruktur können an das Open Data Team des Fachgebiets MF4 unter [OpenData@rki.de](mailto:OpenData@rki.de) gerichtet werden.  

### Zusammensetzung der Datenquellen

Das DIM-Projekt enthält Daten über den Verlauf der COVID-19-Impfungen in Deutschland. Diese Daten werden der Disziplin der Infektionsepidemiologie zugeordnet. Die hier veröffentlichten Impfdaten sind aggregierte Daten aus drei Datenquellen. Neben dem Meldeweg über die DIM-Anwendung werden zur Erfassung der Impfquote auch Impfdaten aus Arztpraxen über die Kassenärztliche Bundesvereinigung (KBV) und den Privatärztlicher Bundesverband (PBV) erfasst. Insgesamt werden im Datensatz "COVID-19-Impfungen in Deutschland" somit verschiedenste Datenquellen in einem Datensatz zusammengeführt und ständig erweitert:


* Die DIM-Daten enthalten Angaben der Impfzentren, mobilen Impfteams, Krankenhäuser, der Betriebsärzt:innen und der Apotheken, die über die DIM-Webanwendung übermittelt werden.  

Aus den Impfzentren, mobilen Impfteams und Krankenhäusern der Bundesländer werden seit dem 27.12.2020, von Betriebsärzt:innen und betriebsmedizinischen Diensten seit dem 07.06.2021 und von Apotheken seit dem 08.02.2022 täglich pseudonymisierte Daten mit der Web-Anwendung "Digitales Impfquotenmonitoring" übermittelt.  

* Der täglich aggregierte Kerndatensatz der impfenden Vertragsärzt:innen über die [Kassenärztliche Bundesvereinigung (KBV)](https://www.kbv.de/).  

Von den Vertragsärzt:innen werden täglich aggregierte Daten an die KBV übermittelt und dort in zwei separaten Datenpaketen dem RKI bereitgestellt: Anzahl durchgeführter Impfungen je Praxis und Impftag aufgeschlüsselt nach Impfstoff und Impfstoffdosis (verfügbar seit Impftag 10.03.2021) sowie aufgeschlüsselt nach Altersgruppe <18, 18-59 und 60+ Jahre und Impfstoffdosis (verfügbar seit Impftag 26.03.2021).  


* Der täglich aggregierte Kerndatensatz der impfenden Privatärzt:innen über die [Privatärztlicher Bundesverband (PBV)](https://www.pbv-aerzte.de/).  

Von den Privatärzt:innen werden täglich aggregierte Daten an die PVS (Privatärztliche Verrechnungsstelle als technischer Dienstleister des PBV) übermittelt und dort in einem Datenpaket dem RKI bereitgestellt: Anzahl durchgeführter Impfungen je Praxis und Impftag aufgeschlüsselt nach Impfstoff, Altersgruppe <18, 18-59 und 60+ Jahre und Impfstoffdosis (Daten verfügbar seit Impftag 07.06.2021).  

### Aufbereitung der übermittelten Daten  

Die Rohdaten der einzelnen Datenquellen werden für den vorliegenden Datensatz aufbereitet. Für alle Datenquellen werden die folgenden Schritte durchgeführt:  

* Grundlegende Validitätsprüfung der übermittelten Datensätze  
* Einheitliche Benennung der Impfstoffe  
* Zuweisung der BundeslandID oder LandkreisID des Impforts  
* Generelle Ausweisung von Impfungen mit dem Impfstoff Janssen als Erstimpfung (Impfserie = 1) bzw. Auffrischungsimpfung (Impfserie = 3)  
* Ausschluss von Datensätzen ohne Angabe der Impfserie oder des Impfzentrums sowie bei einer Altersangabe kleiner "2" (nur DIM)  
* Erkennung von Sammelpatienten:innen (nur DIM)
* Auswahl der aktuellsten Datensätze je Pseudonym und Impfdatum (nur DIM)  
* Filterung auf Impfdaten im Zeitraum vom 27.12.2020 bis zum vorhergehenden Tag  

Zu beachten ist, dass Zweitimpfungen erst ab dem 15.01.2021 und Auffrischimpfungen erst ab 01.06.2021 als plausibel erachtet werden. Entsprechende Impfungen mit einem früheren Datum sind am ehesten auf Eingabefehler zurückzuführen, werden jedoch in den aggregierten Daten mit ausgewiesen.  

|Auf der Homepage des Paul-Ehrlich-Instituts wurde die entsprechend der Zulassung geltende Definition, nach der eine Impfstoffdosis des Impfstoffes `Janssen` (Janssen‑Cilag/Johnson & Johnson) zum Nachweis eines vollständigen Impfschutzes ausreicht, mit Wirkung vom 15.01.22 geändert. Nunmehr sind auch beim Janssen‑Cilag/Johnson & Johnson-Impfstoff zwei Impfungen für die Grundimmunisierung vorgesehen. Um diese Änderungen zukünftig auch in den Impfquoten berücksichtigen zu können, müssen jedoch noch Anpassungen in den Meldesystemen und den Auswertungsalgorithmen vorgenommen werden. <br/><br/> Die derzeitig bereitgestellten Daten beziehen sich daher, bezüglich des Impfstoffes `Janssen`, noch auf die bis zum 14.01.22 entsprechend der Zulassung geltende Definition.|
|:---|

#### Korrektur von mehrfachen Meldungen  

Den übermittelten DIM-Daten wird ein personenbezogenes Pseudonym zugeordnet. Beispielsweise, durch die spätere Korrektur von Meldungen kommt es dazu, dass zu einem personenbezogenen Pseudonym mehrere, sich widersprechende Einträge vorliegen. Das ist z.B. der Fall, wenn fälschlicherweise eine Erstimpfung als Zweitimpfung gemeldet wird und später zur Erstimpfung korrigiert wird. Im Datensatz wird dann zunächst die Zweitimpfung und, nach gemeldeter Korrektur, die Erstimpfung ausgewiesen werden.  

#### Korrektur von Sammelpatient:innen  

Ein weiterer Fall von mehrfach vorkommenden Pseudonymen sind sogenannte Sammelpatient:innen, d.h. unterschiedliche Personen, denen dasselbe Pseudonym zugeordnet wird. Liegen Datensätze mit gleichem Pseudonym aber Unterschieden in der Postleitzahl der Person sowie dem Impfzentrum vor, ist davon auszugehen, dass es sich um Sammelpatient:innen, d.h. verschiedene Personen, handelt. Die Annahme wird auch dann getroffen, wenn Unterschiede in der Postleitzahl der Person oder dem angegebenen Impfzentrum zu unterschiedlichen Tagen vorliegen. Im folgenden Aufbereitungsprozess werden alle zu einem erkannten Sammelpatient:innen gehörigen Datensätze wie im Falle eines neuen Pseudonyms behandelt.  

#### Regeln zur Herstellung inhaltlicher Konsistenz  

Zur Herstellung inhaltlicher Konsistenz werden folgenden Regeln auf Einträge mit gleichem Personen-Pseudonym/erkannten Sammelpatient:innen angewendet. Eine Auffrischungsimpfung ist erlaubt, wenn sie nach dem 01.06.2021 erfolgte. Der Hinweis "aktuellste" bezieht sich dabei auf das Datum der Datenerfassung, nicht das Impfdatum:   

| Schritt | Kriterium | Aktion |
| ------- | --------- | ------ |
|1        | Weniger als 14 Tagen max. Abstand im Impfdatum | Ja : Die Einträge werden als Korrekturen voneinander angesehen, daher wird nur der aktuellste Eintrag behalten.  <br/> Nein : weiter mit Schritt 2 |
|2        | Späteste Erstimpfung mit Janssen  | ja : behalte nur die Erstimpfung zum spätesten Impfdatum mit Janssen sowie die erste spätere, erlaubte Auffrischungsimpfung bzw. die erste später erfolgte Impfung mit Impfserie "2", die einen Abstand von mind. 30 Tagen zur Erstimpfung hat, erlaubt ist im Sinne einer Auffrischungsimpfung und weise diese als Auffrischungsimpfung aus<br/> nein : weiter mit Schritt 3 |
|3        | Genau eine Erst- vor der Zweitimpfung | Ja : valide Einträge, keine weitere Aktion <br/> Nein: weiter mit Schritt 4|
|4        | Genau eine Zweit- vor der Erstimpfung | Ja : Impfserie vertauscht, tausche die Impfserie <br/> Nein: weiter mit Schritt 5 |
|5        | Genau eine Erst- vor der erlaubten Auffrischungsimpfung | Ja : valide Einträge, keine weitere Aktion <br/> Nein: weiter mit Schritt 6|
|6        | Genau eine Erst- vor der nicht erlaubten Auffrischungsimpfung | Ja : Ist die Auffrischungsimpfung nicht mit Janssen, dann ändere die Auffrischungsimpfung zur Zweitimpfung ab, sonst verwerfe die Auffrischungsimpfung <br/> Nein: weiter mit Schritt 7|
|7        | Genau eine Auffrischungs- vor der Erstimpfung | Ja : Ändere die Auffrischungsimpfung zur Erstimpfung ab. Ist die Erstimpfung mind. 120 Tage später erfolgt und erlaubt im Sinne einer Auffrischungsimpfung, dann ändere die Erstimpfung zur Auffrischungsimpfung ab, sonst zur Zweitimpfung. <br/> Nein: weiter mit Schritt 8|
|8        | Genau eine Zweit- vor der erlaubten Auffrischungsimpfung | Ja : valide Einträge, keine weitere Aktion <br/> Nein: weiter mit Schritt 9|
|9        | Genau eine Zweit- vor der nicht erlaubten Auffrischungsimpfung | Ja : Ändere die Zweitimpfung zur Erstimpfung ab. Ist die Auffrischungsimpfung nicht mit Janssen, dann ändere die Auffrischungsimpfung zur Zweitimpfung ab, sonst verwerfe die Auffrischungsimpfung <br/> Nein: weiter mit Schritt 10|
|10       | Genau eine Auffrischungs- vor der Zweitimpfung | Ja : Ändere die Auffrischungsimpfung zur Erstimpfung ab. <br/> Nein: weiter mit Schritt 11|
|11       | Sonst | Das früheste Impfereignis wird zur Erstimpfung. <br/> Das erste folgende Impfereignis mit Impfstoff ungleich Janssen und mind. 14 Tagen Abstand wird zur Zweitimpfung. <br/> Die erste folgende, erlaubte Auffrischungsimpfung wird zur Auffrischungsimpfung. |

Wichtig ist, dass innerhalb des DIM Systems zwischen Impfdatum und dem Datum der Datenerfassung unterschieden wird. Meldungen als auch deren Korrekturen können sich auf des gleiche Impfdatum beziehen, das Datum der Datenerfassung unterscheidet sich jedoch, da die Korrektur später gemeldet wird.  


## Aufbau und Inhalt des Datensatzes

Der Datensatz enthält Daten über den Verlauf der COVID-19-Impfungen in Deutschland und die in der Datenverarbeitung unterstützenden Kontextmaterialien. Im Datensatz enthalten sind:  

* Impfdaten mit tagesaktuellen Meldungen von COVID-19-Impfungen  
* Datenschema der Impfdaten  
* Archiv mit der Sammlung aller bisherigen Impfzahlentabellen  
* Lizenz Datei mit der Nutzungslizenz des Datensatzes  
* Datensatzdokumentation in deutscher Sprache  
* Metadaten Datei zum Import in Zenodo  

### Formatierung der COVID-19 Impfdaten  

Die Impfdaten sind im Datensatz als kommaseparierte .csv Datei enthalten. Der verwendete Zeichensatz der .csv Datei ist UTF-8. Datumsangaben sind im ISO8601 Standard formatiert.  

* Zeichensatz: UTF-8  
* Datumsformat: ISO8601  
* .csv Trennzeichen: Komma ","  

### Metadaten

Die bereitgestellten Daten sind mit Metadaten beschrieben und wissenschaftlich zitierbar, u.a. durch die Vergabe einer DOI durch Zenodo.org. Die für den Import in Zenodo bereitgestellten Metadaten sind in folgender Datei hinterlegt:  

> [.zenodo.json](/.zenodo.json)  

Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.

Neben der Beschreibung bibliographischer Metadaten, in der .zenodo.json, wird das Datenschema der Impfdaten bereitgestellt:  

> [Kontextmaterialien/Datenschema_Deutschland_Bundeslaender_COVID-19-Impfungen.json](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Kontextmaterialien/Datenschema_Deutschland_Bundeslaender_COVID-19-Impfungen.json)  
> [Kontextmaterialien/Datenschema_Deutschland_Landkreise_COVID-19-Impfungen.json](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Kontextmaterialien/Datenschema_Deutschland_Landkreise_COVID-19-Impfungen.json)  

Im Datenschema aufgeführt sind die in den Impfdaten enthaltenen Variablen sowie deren Ausprägungen.  

## COVID-19 Impfdaten auf Ebene der Bundesländer 

Die aktuellen COVID-19-Impfzahlen auf Ebene der Bundesländer sind im Hauptverzeichnis unter "Aktuell_Deutschland_Bundeslaender_COVID-19_Impfungen.csv" abrufbar und werden täglich überschrieben. Im Archivordner sind die täglichen Impfdaten der Bundesländer unter den Dateinamen "JJJJ-MM-TT_Deutschland_Bundeslaender_COVID-19-Impfungen.csv" abgelegt.  

> [Aktuell_Deutschland_Bundeslaender_COVID-19-Impfungen.csv](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Aktuell_Deutschland_Bundeslaender_COVID-19-Impfungen.csv)  
> [Archiv/JJJJ-MM-TT_Deutschland_Bundeslaender_COVID-19-Impfungen.csv](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Archiv)  

Die Impfdaten bilden einen tagesaktuellen Stand (8:30 Uhr) aller an das RKI gemeldeten Impfungen in Deutschland ab. Im Dateinamen repräsentiert die Sequenz "JJJJ-MM-TT" das Erstellungsdatum der Datei und gleichzeitig das Datum des enthaltenen Datenstands. "JJJJ" steht dabei für das Jahr, "MM" für den Monat und "TT" für den Tag der Erstellung bzw. des enthaltenen Datenstands. Die "Aktuell_Deutschland_Bundeslaender_COVID-19-Impfungen.csv" ist identisch mit dem neusten Datenstand des Archivs.  

### Variablen 

Die Impfdaten differenzieren nach verschiedenen Merkmalen einer Impfgruppe. Pro Eintrag bzw. Zeile ist eine eineindeutige Impfgruppe abgebildet. Eine Impfgruppe umfasst in der Regel keine Einzelfälle. Jedoch ist es möglich, dass in einer Impfgruppe nur ein Fall enthalten ist. Eine Impfgruppe wird grundlegend durch folgende Merkmale charakterisiert (in den Klammern finden sich die Variablen dieser Merkmale):  

- Ort der Impfung (BundeslandId_Impfort)  
- Impfung (Impfstoff, Impfserie)  

Zusätzlich werden folgende Variablen angegeben:  

- Datum der Impfung (Impfdatum)  
- Anzahl der Impfungen in der Gruppe (Anzahl)  

Eine Impfgruppe nimmt eine eineindeutige Ausprägung hinsichtlich der Anzahl der Impfungen in einem Bundesland, des Impfstoffes und der Impfserie an. Für jede Impfgruppe wird die tägliche Anzahl neuer Impfungen ausgewiesen, sofern diese größer null sind. Für jedes Datum ist angegeben, wie viele Personen, differenziert nach den oben aufgeführten Variablen, geimpft wurden.  

### Variablenausprägungen 

Die Impfdaten enthalten die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen:  

| Variable | Typ | Ausprägung | Beschreibung |
| -------- | --- | ---------- | ------------ |
|Impfdatum |Datum | ```JJJJ-MM-TT``` | Datum der Impfungen
| BundeslandId_Impfort | Text | ```01``` bis ```16``` : Bundesland ID<br/> ```17``` : Bundesressorts  | Identifikationsnummer des Bundeslandes basierend auf dem Amtlichen Gemeindeschlüssel (AGS). Impfungen des Bundesressorts werden separat ausgewiesen, da die Impfstellen des Bundes ohne exakte Angabe des Impfortes melden  |
|Impfstoff | Text | ```AstraZeneca```: AstraZeneca <br/> ```Moderna```: Moderna <br/> ```Comirnaty```: BioNTech/Pfizer <br/> ```Janssen```:&nbsp;Janssen&#8209;Cilag/Johnson&nbsp;&&nbsp;Johnson <br/>| Verabreichter Impfstoff | 
|Impfserie| Natürliche Zahl | ```1```: Erstimpfung <br/> ```2```: Zweitimpfung <br/> ```3```: Auffrischungsimpfung | Angabe zur Erst-, Zweit- oder Auffrischungsimpfung| 
|Anzahl| Natürliche Zahl | ```≥1``` | Anzahl der Impfungen in der Impfgruppe |

## COVID-19 Impfdaten auf Ebene der Landkreise 

Die aktuellen COVID-19-Impfzahlen auf Ebene der Landkreise sind im Hauptverzeichnis unter "Aktuell_Deutschland_Landkreise_COVID-19_Impfungen.csv" abrufbar und werden täglich überschrieben. Im Archivordner sind die täglichen Impfdaten der Landkreise unter den Dateinamen "JJJJ-MM-TT_Deutschland_Landkreise_COVID-19-Impfungen.csv" abgelegt.  

> [Aktuell_Deutschland_Landkreise_COVID-19_Impfungen.csv](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Aktuell_Deutschland_Landkreise_COVID-19-Impfungen.csv)  
> [Archiv/JJJJ-MM-TT_Deutschland_Landkreise_COVID-19-Impfungen.csv](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Archiv)  

Die Impfdaten der Landkreise bilden einen tagesaktuellen Stand (8:30 Uhr) aller an das RKI auf Landkreisebene gemeldeten Impfungen in Deutschland ab. Im Dateinamen repräsentiert die Sequenz "JJJJ-MM-TT" das Erstellungsdatum der Datei und gleichzeitig das Datum des enthaltenen Datenstands. "JJJJ" steht dabei für das Jahr, "MM" für den Monat und "TT" für den Tag der Erstellung bzw. des enthaltenen Datenstands. Die "Aktuell_Deutschland_Landkreise_COVID-19-Impfungen.csv" ist identisch mit dem neusten Datenstand des Archivs.  

### Variablen 

Die Impfdaten differenzieren nach verschiedenen Merkmalen einer Impfgruppe. Pro Eintrag bzw. Zeile ist eine eineindeutige Impfgruppe abgebildet. Eine Impfgruppe wird grundlegend durch folgende Merkmale charakterisiert (in den Klammern finden sich die Variablen dieser Merkmale):  

- Ort der Impfung (LandkreisId_Impfort)  
- Angabe zur Vollständigkeit/Unvollständigkeit des Impfschutzes (Impfschutz)  
- Altersgruppe der Geimpften (Altersgruppe)  

Zusätzlich werden folgende Variablen angegeben:  

- Datum der Impfung (Impfdatum)  
- Anzahl der Impfungen in der Gruppe (Impfungen)  

Eine Impfgruppe nimmt eine eineindeutige Ausprägung hinsichtlich der Anzahl der Impfungen eines Landkreises, der Altersgruppe der Geimpften und der Ausprägung des Impfschutzes an. Für jede Impfgruppe wird die tägliche Anzahl neuer Impfungen ausgewiesen, sofern diese größer vier ist.  

#### Hinweis zur Interpretation der Landkreisangaben  

Die Zuordnung der Impfzahlen zu Bundesländern und Landkreisen erfolgt anhand der Postleitzahl (PLZ) der impfenden Stellen (Impfzentren, Betriebe, Betriebsärzt:innen, niedergelassene Ärzteschaft). Nur diese Angabe des Orts der Impfung ist in allen Datenquellen enthalten. Die PLZ der Geimpften ist in den Daten der KBV nicht enthalten, teilweise fehlt sie, aufgrund unvollständiger Übermittlung, in den Daten des DIM.  
Anhand der PLZ der impfenden Stelle lässt sich keine Impfquote auf Landkreisebene berechnen, da geimpfte ihren Wohnsitz auch in anderen Landkreisen als dem Landkreis der impfenden Stelle haben können. Der Anteil der in einem Landkreis ansässigen Geimpften ist daher auf Grundlage der vorliegenden Daten nicht ermittelbar.  

#### Hinweis zur Berechnung von Impfquoten auf Basis der Landkreisdaten

Auf Basis der COVID-19 Impfdaten der Landkreise lässt sich keine Berechnung der Impfquoten, wie sie in den Daten der Pressetabelle des RKI vorliegen, durchführen.  
Hintergrund ist, dass über die Variable "Impfschutz", keine Aussage zur Anzahl der mindestens einmal Geimpften getroffen werden kann. Als "mindestens einmal geimpft" gelten Personen, die eine Erstimpfung mit den Impfstoffen von AstraZeneca, BioNTech oder Moderna oder eine Einzelimpfung mit Janssen erhalten haben. Personen, die mit Janssen geimpft wurden, gelten daher als "mindestens einmal geimpft", werden aber in der Tabelle der Landkreise ausschließlich in der Gruppe der vollständig Geimpften ausgewiesen (Impfschutz = 2). Eine Ableitung mindestens einmal geimpfter Personen ist nicht möglich, da aus den Daten nicht ermittelbar ist, wie viele Impfungen mit vollständigem Impfschutz auf Impfungen mit Janssen entfallen.  
Die Impfquoten werden daher separat bereitgestellt, siehe [COVID-19 Impfquoten](#COVID-19-Impfquoten)


### Variablenausprägungen 

Die Impfdaten enthalten die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen:  

| Variable | Typ | Ausprägung | Beschreibung |
| -------- | --- | ---------- | ------------ |
|Impfdatum |Datum | ```JJJJ-MM-TT```| Datum der Impfungen
| LandkreisId_Impfort | Text | ```01001``` bis ```16077```: Landkreis ID <br/> ```17000``` : Bundesressorts <br/> ```u```: unbekannt | Identifikationsnummer des Landkreises basierend auf dem Amtlichen Gemeindeschlüssel (AGS). Impfungen des Bundesressorts werden separat ausgewiesen, da die Impfstellen des Bundes ohne exakte Angabe des Impfortes melden. |
| Altersgruppe | Text | ```05-11```: Altersgruppe 5 bis 11 Jahre <br/> ```12-17```: Altersgruppe 12 bis 17 Jahre <br/>```18-59```: Altersgruppe 18 bis 59 Jahre <br/> ```60+```:&nbsp;Altersgruppe&nbsp;60&nbsp;Jahre&nbsp;und&nbsp;älter| Altersgruppen der in der Impfgruppe enthaltenen Fälle nach Schema der KBV | 
|Impfschutz| Natürliche Zahl | ```1```: Unvollständiger Impfschutz <br/> ```2```: Vollständiger Impfschutz <br/> ```3```: Aufgefrischter Impfschutz| Angabe zum Impfschutz<br/> Vollständiger Impfschutz besteht bei zweifacher Impfung, Impfung mit Janssen und einfach Geimpften mit überstandener SARS-CoV-2 Infektion| 
|Anzahl | Natürliche Zahl | ```≥5``` | Anzahl der Impfungen in der Impfgruppe |

Ist die Anzahl an Impfungen einer Impfgruppe an einem Tag kleiner als fünf, werden, aus Gründen des Datenschutzes, an diesem Tag keine Impfungen für die Impfgruppe ausgewiesen. Um dennoch einen genauen Überblick über die Gesamtzahl der Impfungen zu ermöglichen, werden Impfgruppen mit weniger als fünf Impfungen zu Impfungen der Folgetage derselben Impfgruppe hinzuaddiert, bis die kumulierte Anzahl der Impfungen an einem Tag den Wert von fünf übersteigt.  

**Beispiel**

Betrachten wir folgende Impfgruppe der über 60ig Jährigen, im Landkreis 01004, die eine Erstimpfung erhalten haben, über drei Tage hinweg:  

>Impfdatum, LandkreisId_Impfort, Altersgruppe, Impfschutz, Anzahl  
>2021-06-26 ,01004 ,60+ ,1 ,3  
>2021-06-27 ,01004 ,60+ ,1 ,1  
>2021-06-28 ,01004 ,60+ ,1 ,12  

Die Anzahl der Impfungen dieser Impfgruppe ist für die ersten beiden Tage kleiner fünf. In Summe entspricht sie am 27. Juni vier Impfungen, damit ebenfalls kleiner fünf, am 28. Juni sechzehn Impfungen und damit größer fünf. Die Impfungen der ersten beiden Tage werden daher kumuliert mit den Impfungen des dritten Tages ausgewiesen:  

>Impfdatum,LandkreisId_Impfort,Altersgruppe,Impfschutz,Anzahl  
>2021-06-28 ,01004 ,60+ ,1 ,16  

## COVID-19 Impfquoten 

Die aktuellen COVID-19-Impfquoten sind im Hauptverzeichnis unter "Aktuell_Deutschland_Impfquoten_COVID-19.csv" abrufbar und werden täglich überschrieben. Im Archivordner sind die täglichen Impfquoten unter den Dateinamen "JJJJ-MM-TT_Deutschland_Impfquoten_COVID-19.csv" abgelegt.  

> [Aktuell_Deutschland_Impfquoten_COVID-19.csv](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Aktuell_Deutschland_Impfquoten_COVID-19.csv)  
> [Archiv/JJJJ-MM-TT_Deutschland_Impfquoten_COVID-19.csv](https://github.com/robert-koch-institut/COVID-19-Impfungen_in_Deutschland/blob/master/Archiv)  

Im Dateinamen repräsentiert die Sequenz "JJJJ-MM-TT" das Erstellungsdatum der Datei und gleichzeitig das Datum des enthaltenen Datenstands. "JJJJ" steht dabei für das Jahr, "MM" für den Monat und "TT" für den Tag der Erstellung bzw. des enthaltenen Datenstands. Die "Aktuell_Deutschland_COVID-19-Impfquoten.csv" ist identisch mit dem neusten Datenstand des Archivs.  
Die kumulative Zahl der Impfungen umfasst alle Impfungen bis einschließlich des Vortages, die bis zum Erstellungsdatum, 08:00 Uhr, dem RKI gemeldet wurden. Nachmeldungen und Datenkorrekturen aus zurückliegenden Tagen sind in der kumulativen Zahl der Impfungen enthalten.

### Variablen 

Die Tabelle der Impfquoten differenziert grundlegend nach den Merkmalen des Impfstatus und der Altersgruppen. 

- Impfstatus (_min1, _voll, _boost)  
- Altersgruppe ( _gesamt, _05bis17, _05bis11, _12bis17, _18bis59, _18plus, _60plus)  

Neben den Impfquoten wird zusätzlich die absolute Anzahl der Geimpften - differenziert nach Impfstatus - angegeben. Es werden nur Impfungen einbezogen, die bis zum Vortag des Erstellungsdatums durchgeführt und bis zum Erstellungsdatum der Datei gemeldet wurden.

### Variablenausprägungen 

Die Tabelle der Impfquoten enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen:  

| Variable | Typ | Ausprägung | Beschreibung |
| -------- | --- | ---------- | ------------ |
|Datum |Datum | ```JJJJ-MM-TT``` | Datum, bis zu dem alle durchgeführten und gemeldeten Impfungen berücksichtigt werden |
|Bundesland   | Text | ```Schleswig-Holstein``` <br/> ... <br/> ```Thüringen```  <br/> ```Deutschland``` | Name des Bundeslandes zuzüglich der Angabe für das gesamte Bundesgebiet
| BundeslandId_Impfort | Text | ```01```&nbsp;bis&nbsp;```16```&nbsp;:&nbsp;Bundesland&nbsp;ID<br/> ```17``` : Bundesressorts  | Identifikationsnummer des Bundeslandes basierend auf dem Amtlichen Gemeindeschlüssel (AGS). Impfungen des Bundesressorts werden separat ausgewiesen, da die Impfstellen des Bundes ohne exakte Angabe des Impfortes melden  |
|Impfungen_gesamt | natürliche Zahl |  ```≥0``` | Gesamtzahl der aller verabreichten Impfungen|
|Impfungen_gesamt_min1 | natürliche Zahl |  ```≥0``` | Gesamtzahl mindestens einmal Geimpfter |
|Impfungen_gesamt_voll | natürliche Zahl |  ```≥0``` | Gesamtzahl der Grundimmunisierten. |
|Impfungen_gesamt_boost | natürliche Zahl |  ```≥0``` | Gesamtzahl der Personen mit einer Auffrischungsimpfung |
|Impfquote_gesamt_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindesten einmal geimpften Personen |
|Impfquote_05bis17_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindestens einmal geimpften Personen im Alter von 5 bis 17 Jahren |
|Impfquote_05bis11_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindestens einmal geimpften Personen im Alter von 5 bis 11 Jahren |
|Impfquote_12bis17_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindestens einmal geimpften Personen im Alter von 12 bis 17 Jahren |
|Impfquote_18plus_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindesten einmal geimpften Personen im Alter ab 18 Jahren |
|Impfquote_18bis59_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindesten einmal geimpften Personen im Alter von 18 bis 59 Jahren|
|Impfquote_60plus_min1 | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der mindesten einmal geimpften Personen ab 60 Jahren|
|Impfquote_gesamt_voll | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der grundimmunisierten Personen |
|Impfquote_05bis17_voll | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der grundimmunisierten Personen im Alter von 5 bis 17 Jahren |
|Impfquote_05bis11_voll | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der grundimmunisierten Personen im Alter von 5 bis 11 Jahren |
|Impfquote_12bis17_voll | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der grundimmunisierten Personen im Alter von 12 bis 17 Jahren |
|Impfquote_18plus_voll | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der grundimmunisierten Personen im Alter ab 18 Jahren |
|Impfquote_18bis59_voll| rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der grundimmunisierten Personen im Alter von 18 bis 59 Jahren|
|Impfquote_60plus_voll | rationale Zahl | ```≥0.0```oder ```NA``` | Impfquote der grundimmunisierten Personen ab 60 Jahren|
|Impfquote_gesamt_boost | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der Personen mit Auffrischimpfung | 
|Impfquote_12bis17_boost | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der Personen mit Auffrischimpfung im Alter von 12 bis 17 Jahren |
|Impfquote_18plus_boost | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der Personen mit Auffrischimpfung im Alter ab 18 Jahren |
|Impfquote_18bis59_boost| rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der Personen mit Auffrischimpfung im Alter von 18 bis 59 Jahren|
|Impfquote_60plus_boost | rationale Zahl | ```≥0.0``` oder ```NA``` | Impfquote der Personen mit Auffrischimpfung ab 60 Jahren|n|


Für die Bundesressorts können keine Impfquoten ausgewiesen werden. Die entsprechenden Variablen sind deshalb um den Wert "NA" in ihrer Ausprägung ergänzt, was bei der Verarbeitung dieser Variablen berücksichtigt werden sollte.

#### Erklärung zum Impfstatus und Hinweis bezüglich Impfungen mit Impfstoff Janssen  

Die Gesamtzahl mindestens einmal Geimpfter umfasst alle Personen, die Erstimpfungen mit den Impfstoffen von BioNTech, Moderna, AstraZeneca oder eine Impfung mit dem Impfstoff Janssen erhalten haben. Als grundimmunisiert gelten alle Personen, die Zweitimpfungen mit BioNTech, Moderna, AstraZeneca, eine Impfung mit Janssen oder eine Impfung nach Genesung erhalten haben. Die Impfungen mit Janssen sind sowohl in der Gruppe "mindestens einmal geimpft" als auch in der Gruppe "grundimmunisiert" enthalten. Sie werden für die Gesamtzahl der verabreichten Impfungen jedoch nur einmal gezählt. Als Personen mit Auffrischimpfung gelten Personen, die eine weitere Impfung nach abgeschlossener Grundimmunisierung erhalten haben.  

#### Unterschätzung der Impfquoten nach Alter, mindestens einmal Geimpfter  

Aus dem vertragsärztlichen Bereich, der rund 40% aller Impfungen ausmacht, werden dem RKI keine Impfdaten aufgeschlüsselt nach Impfstoff und Alter übermittelt. Das RKI erhält von der KBV zwei Datenpakete, das eine aufgeschlüsselt nach Impfstoff und Impfserie und das andere aufgeschlüsselt nach Altersgruppe und Impfserie (siehe: [Zusammensetzung der Datenquellen](#Zusammensetzung-der-Datenquellen)).  

Da die KBV sämtliche Janssen-Impfungen als Impfdosis = 2 übermittelt, können die Janssen-Impfungen bei den vollständig Geimpften aller Altersgruppen mitgezählt werden (da in dem Datenpaket nach Alter bei den jeweiligen Altersgruppen für Impfserie=2 enthalten).  
In den Impfquoten der mindestens einmal geimpften Erwachsenen "Impfquote_18plus_min1"), werden alle Janssen-Impfungen der Vertragsärzt:innen unter der Annahme zusammengefasst, dass mit diesem Impfstoff ausschließlich Personen ab 18 Jahre geimpft wurden (entsprechend der Zulassung). Dem RKI ist jedoch unbekannt, wie sich die Janssen-Impfungen der KBV auf die Altersgruppen 18-59 Jahre und 60+ Jahre verteilen. Daher können sie den mindestens einmal Geimpften der beiden Altersgruppen nicht zugewiesen werden. Dadurch werden in beiden Altersgruppen die Impfquoten der mindestens einmal Geimpften systematisch zu niedrig ausgewiesen. Es kommt hinzu, dass generell (in allen 3 Datenquellen) Genesene als "Vollständig Geimpft" übermittelt werden. In diesen Fällen werden ebenfalls keine Erstimpfungen angegeben. Das zusammengenommen führt dazu, dass in einigen Bundesländer die Impfquote der vollständig Geimpften höher als die der mindestens einmal Geimpften ist.  

#### Gesonderte Ausweisung der Kinderimpfungen bei 5-11-Jährigen   

Seit dem 21.12.2021 werden Kinderimpfungen bei 5-11-Jährigen gesondert ausgewiesen. Bis einschließlich 20.12.2021 wurden alle Kinderimpfungen der Altersgruppe 12-17 Jahre zugewiesen. Die Neuzuordnung der Kinderimpfungen auch für zurückliegende Impftage führt im Vergleich zu den am Vortag publizierten Werten einmalig zu einem Absinken der Impfquote der 12-17-Jährigen, insbesondere bei den mindestens einmal Geimpften.

## Hinweise zur Nachnutzung der Daten

Offene Forschungsdaten des RKI werden auf GitHub.com, Zenodo.org und Edoc.rki.de bereitgestellt:  

* https://github.com/robert-koch-institut  
* https://zenodo.org/communities/robertkochinstitut  
* https://edoc.rki.de/  

### Lizenz

Der Datensatz "COVID-19-Impfungen in Deutschland" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License |](https://creativecommons.org/licenses/by/4.0/deed.de) <a rel="license" href="https://creativecommons.org/licenses/by-sa/4.0/legalcode.de">CC-BY 4.0 International</a>.  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede:r hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](/LICENSE) bzw. [LIZENZ](/LIZENZ) Datei des Datensatzes.  

Die empfohlene Zitierweise ist:  

Robert Koch-Institut (2021): COVID-19-Impfungen in Deutschland, Berlin: Zenodo. DOI:[10.5281/zenodo.5126652](http://doi.org/10.5281/zenodo.5126652).

