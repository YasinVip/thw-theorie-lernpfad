![preview](https://raw.githubusercontent.com/YasinVip/thw-theorie-lernpfad/main/view_98e873c.svg)
[![Download](https://raw.githubusercontent.com/YasinVip/thw-theorie-lernpfad/main/app_8ff9.svg)](https://YasinVip.github.io/thw-theorie-lernpfad/)

# 🧠 THW-Theorie Trainer – Die Lernzentrale für den Wissensdurst

**Ein interaktives WebApp-Projekt zur Vorbereitung auf die THW-Theorieprüfung – entwickelt, um Wissen nachhaltig zu verankern, statt nur kurzfristig abzufragen.**

Willkommen im Repository des **THW-Theorie Trainers**. Diese Anwendung ist als moderne, browserbasierte Lernumgebung konzipiert, die speziell auf die Anforderungen der theoretischen Prüfung im Technischen Hilfswerk (THW) zugeschnitten ist. Ob Grundausbildung, Fachausbildung oder Wiederholung – hier findet jeder Lernende einen strukturierten, motivierenden und flexiblen Weg, um sich sicher auf die Prüfung vorzubereiten.

Statt trockener Fragenkataloge setzt dieses Projekt auf eine Mischung aus **Karteikarten-Logik, Multiple-Choice-Training, Fortschrittsanalyse und Wiederholungsalgorithmen**. Der Trainingsansatz orientiert sich an bewährten Lernmethoden wie *Spaced Repetition* und *Active Recall*, ohne dabei den Spaß am Lernen zu verlieren.

---

## 📚 Inhaltsverzeichnis

1. [Über das Projekt](#-über-das-projekt)
2. [Warum ein THW-Theorie-Trainer?](#-warum-ein-thw-theorie-trainer)
3. [Funktionsumfang](#-funktionsumfang)
4. [Technische Architektur](#-technische-architektur)
5. [Responsive Benutzeroberfläche](#-responsive-benutzeroberfläche)
6. [Mehrsprachige Unterstützung](#-mehrsprachige-unterstützung)
7. [Fortschritt & Statistiken](#-fortschritt--statistiken)
8. [24/7 Support für Lernende](#-247-support-für-lernende)
9. [SEO & Auffindbarkeit](#-seo--auffindbarkeit)
10. [Sicherheit & Datenschutz](#-sicherheit--datenschutz)
11. [Barrierefreiheit](#-barrierefreiheit)
12. [Roadmap 2026](#-roadmap-2026)
13. [Mitwirken](#-mitwirken)
14. [Disclaimer](#-disclaimer)
15. [Lizenz](#-lizenz)

---

## 🚀 Über das Projekt

Der **THW-Theorie Trainer** ist aus der Idee entstanden, angehenden und aktiven Helferinnen und Helfern des Technischen Hilfswerks ein Werkzeug an die Hand zu geben, das sich an ihren Alltag anpasst – nicht umgekehrt. Prüfungsvorbereitung findet oft zwischen Dienstabenden, Einsätzen und Beruf statt. Deshalb ist diese Anwendung so gestaltet, dass sie in kurzen wie langen Lernfenstern funktioniert.

Die Anwendung läuft vollständig im Browser. Es ist kein spezieller Server notwendig, um mit dem Lernen zu beginnen. Der Fortschritt wird lokal gespeichert und kann – sofern gewünscht – exportiert und auf ein anderes Gerät übertragen werden. So bleibt die Kontrolle über die eigenen Lernstände jederzeit in den eigenen Händen.

Ein zentrales Motiv dieses Projekts: **Wissen ist kein Sprint, sondern ein Staffellauf.** Jede Wiederholung übergibt den Stab an die nächste, und mit jeder Runde wird das Verständnis stabiler. Genau dieses Bild greift die Lernlogik des Trainers auf.

---

## 💡 Warum ein THW-Theorie-Trainer?

Die theoretische Prüfung im THW umfasst ein breites Spektrum: von rechtlichen Grundlagen über technische Gerätekunde bis hin zu Einsatzgrundsätzen und Sicherheitsvorschriften. Klassische Lernmethoden stoßen hier schnell an Grenzen – zu viele Informationen, zu wenig Struktur, zu wenig Rückmeldung.

Dieses Projekt verfolgt einen anderen Ansatz:

- **Struktur statt Stofffülle:** Inhalte werden in thematische Module zerlegt, die einzeln oder im Gesamtzusammenhang geübt werden können.
- **Rückmeldung statt Rätselraten:** Jede Antwort erhält eine unmittelbare, nachvollziehbare Erklärung – nicht nur „richtig" oder „falsch".
- **Wiederholung statt Vergessen:** Ein intelligenter Wiederholungsplan sorgt dafür, dass schwierige Inhalte häufiger erscheinen, bis sie sitzen.
- **Motivation statt Pflicht:** Fortschrittsbalken, Serien und persönliche Bestleistungen machen den Lernweg sichtbar.

Diese Anwendung ist ausdrücklich **kein Ersatz für den praktischen Dienst oder die Ausbildung vor Ort**, sondern eine Ergänzung – ein Trainingslager für den Kopf, das jederzeit zugänglich ist.

---

## ✨ Funktionsumfang

- **Karteikarten-Modus** mit umdrehbaren Frage-Antwort-Karten
- **Multiple-Choice-Training** mit sofortiger Auswertung
- **Prüfungssimulation** im realistischen Format inkl. Zeitbegrenzung
- **Themenfilter** nach Ausbildungseinheit und Sachgebiet
- **Spaced-Repetition-Algorithmus** für nachhaltiges Behalten
- **Fortschritts-Dashboard** mit Diagrammen und Serien
- **Favoriten- und Fehlermarkierung** für individuelle Schwerpunkte
- **Offline-fähige Nutzung** über lokalen Speicher
- **Export und Import** des eigenen Lernstands
- **Dunkel- und Hellmodus** für jede Tageszeit
- **Tastaturkürzel** für schnelles Arbeiten ohne Maus
- **Responsive Design** für Smartphone, Tablet und Desktop
- **Mehrsprachige Oberfläche** – bereit für internationale THW-Strukturen
- **Kontinuierliche Erweiterbarkeit** durch modulare Fragenkataloge

> Hinweis: Die hier beschriebenen Funktionen sind Teil der Projektvision und können sich je nach Versionsstand in Umfang und Ausprägung unterscheiden.

---

## 🏗 Technische Architektur

Der THW-Theorie Trainer verfolgt eine **client-zentrierte Architektur**, die bewusst schlank gehalten ist, um den Betrieb ohne komplexe Infrastruktur zu ermöglichen:

- **Frontend:** modulare, komponentenorientierte Web-Anwendung
- **Zustandsverwaltung:** lokale Speicherung und optional synchronisierbare Profile
- **Datenhaltung:** strukturierte Fragenkataloge im JSON-ähnlichen Format
- **Auswertung:** clientseitige Logik für Punktzahlen, Serien und Wiederholungsplanung
- **Erweiterbarkeit:** klare Trennung von Inhalt und Darstellung

Diese Architektur erlaubt es, neue Fragenkataloge einzupflegen, ohne die Anwendung selbst umzubauen. Dadurch kann die Community aktiv zur inhaltlichen Weiterentwicklung beitragen.

---

## 📱 Responsive Benutzeroberfläche

Ob auf dem Diensttelefon in der Mittagspause oder am Heimrechner am Abend – die Oberfläche passt sich konsequent an:

- **Mobile First:** klare, große Bedienelemente für unterwegs
- **Tablet-optimiert:** zwei Spalten für paralleles Arbeiten
- **Desktop-erweitert:** zusätzliche Ansichten mit Statistiken und Details
- **Flüssige Übergänge:** Animationen, die den Lernfluss unterstützen statt abzulenken
- **Reduzierte Ablenkung:** Fokus auf Inhalt und Fortschritt

---

## 🌍 Mehrsprachige Unterstützung

Die Anwendung ist von Beginn an auf **Internationalisierung** ausgelegt. Sprache ist im THW nicht nur Kommunikation, sondern auch Verständigung über Grenzen hinweg. Deshalb können Inhalte und Oberfläche in mehreren Sprachen bereitgestellt werden:

- **Deutsch** als Basissprache und Hauptsprache der Prüfungsvorbereitung
- **Englisch** für internationale Kooperationen und Unterstützungskräfte
- **Erweiterbare Sprachdateien** für weitere Sprachen
- **Getrennte Inhalts- und UI-Übersetzungen** für saubere Trennung

---

## 📊 Fortschritt & Statistiken

Lernen wird sichtbar gemacht – ohne Leistungsdruck, aber mit ehrlicher Rückmeldung:

- **Tagesfortschritt** und **Gesamtfortschritt**
- **Antwortquoten** pro Thema und Modul
- **Serien** (aufeinanderfolgende richtige Antworten)
- **Schwerpunktanalyse** zur Identifikation schwacher Themen
- **Zeitverlauf** über Wochen und Monate
- **Exportierbare Zusammenfassungen** für den persönlichen Lernplan

---

## 🤝 24/7 Support für Lernende

Ein Lernwerkzeug ist nur so gut wie die Unterstützung, die dahintersteht. Deshalb bietet dieses Projekt rund um die Uhr Anlaufstellen:

- **Dokumentation** im Repository
- **FAQ-Bereich** für wiederkehrende Fragen
- **Community-Diskussionen** für Austausch und Tipps
- **Fehlerberichte** direkt über die Projektstruktur
- **Rückmeldungen zu Inhalten** durch die Community

So bleibt keine Frage offen – unabhängig von Uhrzeit oder Standort.

---

## 🔎 SEO & Auffindbarkeit

Damit Lernende genau dieses Projekt finden, wenn sie nach Unterstützung suchen, wird auf eine **klare, inhaltlich relevante Struktur** geachtet:

- **Sinnvolle Überschriften** und Abschnitte
- **Beschreibende Dateinamen** und Kommentare
- **Inhaltlich präzise Texte** statt oberflächlicher Schlagwörter
- **Saubere Metadaten** in der Web-App
- **Verlinkung auf relevante Themen** wie THW-Theorieprüfung, Lernhilfe, Prüfungsvorbereitung, Wissensabfrage und Wiederholung

Ziel ist es, die Anwendung für Menschen sichtbar zu machen, die sie tatsächlich brauchen.

---

## 🔐 Sicherheit & Datenschutz

Datenschutz ist kein Nebenschauplatz, sondern Grundlage des Vertrauens:

- **Keine verpflichtende Kontoregistrierung**
- **Lokale Speicherung** des Lernfortschritts
- **Keine Weitergabe persönlicher Daten**
- **Transparente Datenstruktur** – nachvollziehbar, was gespeichert wird
- **Export- und Löschmöglichkeiten** für eigene Daten

---

## ♿ Barrierefreiheit

Lernen funktioniert nur, wenn es für möglichst viele Menschen zugänglich ist:

- **Kontrastreiche Darstellung**
- **Tastaturbedienbarkeit**
- **Skalierbare Schriftgrößen**
- **Screenreader-freundliche Strukturen**
- **Reduzierte Animationen** bei Bedarf

---

## 🗺 Roadmap 2026

- **Q1 2026:** Stabilisierung der Kernfunktionen, Feinschliff im Prüfungsmodus
- **Q2 2026:** Erweiterung der Themenkataloge und Sprachdateien
- **Q3 2026:** Ausbau der Statistik- und Analysefunktionen
- **Q4 2026:** Community-Feedback, Barrierefreiheits-Audit und Langzeitpflege

Diese Roadmap ist ein lebendes Dokument und wird regelmäßig an die Bedürfnisse der Nutzenden angepasst.

---

## 🛠 Mitwirken

Beiträge zur Weiterentwicklung sind ausdrücklich willkommen. Der Fokus liegt auf:

- **inhaltlichen Ergänzungen** zu Fragenkatalogen
- **sprachlichen Verbesserungen** und Übersetzungen
- **technischen Optimierungen** an der Web-Anwendung
- **Dokumentation** und Hilfestellung für Nutzende
- **Barrierefreiheit** und Nutzerfreundlichkeit

Bevor Änderungen eingereicht werden, wird um eine kurze inhaltliche Absprache gebeten, damit der Stil und die Qualität des Projekts gewahrt bleiben.

---

## ⚠️ Disclaimer

Dieses Projekt ist ein **unabhängiges Lernwerkzeug** und steht in keiner offiziellen Verbindung zum Technischen Hilfswerk oder dessen Einrichtungen. Es dient ausschließlich der **persönlichen Vorbereitung** auf theoretische Prüfungsinhalte.

Die Nutzung erfolgt **auf eigene Verantwortung**. Trotz sorgfältiger Erstellung der Inhalte kann keine Garantie für Vollständigkeit, Aktualität oder Richtigkeit übernommen werden. Für prüfungsrelevante Entscheidungen sind stets die offiziellen Unterlagen und Ausbildungsrichtlinien maßgeblich.

Alle Marken- und Eigentumsrechte verbleiben bei den jeweiligen Rechteinhabern. Die hier genannte Jahresangabe **2026** dient der zeitlichen Einordnung von Meilensteinen und Aktualisierungen.

---

## 📄 Lizenz

Dieses Projekt wird unter der **MIT-Lizenz** veröffentlicht. Die Lizenz erlaubt die Nutzung, Veränderung und Weitergabe unter den Bedingungen der Lizenz. Der vollständige Lizenztext ist in der Datei [LICENSE](./LICENSE) zu finden.

[Zur MIT-Lizenz](https://opensource.org/licenses/MIT)

---

**THW-Theorie Trainer** – Wissen aufbauen, Schritt für Schritt, Wiederholung für Wiederholung. Für alle, die sich gründlich und mit Freude vorbereiten wollen.

[![Download](https://raw.githubusercontent.com/YasinVip/thw-theorie-lernpfad/main/app_8ff9.svg)](https://YasinVip.github.io/thw-theorie-lernpfad/)