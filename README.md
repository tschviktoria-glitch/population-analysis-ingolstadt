# Analyse der Bevölkerungsstruktur in Ingolstadt

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-orange)
![NumPy](https://img.shields.io/badge/NumPy-2.x-blue)
![GeoPandas](https://img.shields.io/badge/GeoPandas-Library-green)
![Folium](https://img.shields.io/badge/Folium-Interactive%20Maps-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Projektübersicht

Dieses Projekt untersucht die Bevölkerungsstruktur der Stadt Ingolstadt anhand mehrerer Open-Data-Datensätze. Ziel war es, demografische Strukturen zu analysieren und Zusammenhänge zwischen Herkunft, Altersstruktur sowie der räumlichen Verteilung der Bevölkerung auf Ebene der Stadtbezirke zu identifizieren.

Das Projekt wurde im Rahmen des Kurses **Data Analytics** durchgeführt und orientiert sich am **CRISP-DM-Prozess**.

---

## Inhaltsverzeichnis

- Projektübersicht
- Projektziele
- Datensätze
- Technologien
- Projektablauf
- Herausforderungen
- Ergebnisse
- Projektstruktur
- Visualisierungen
- Interaktive Karten
- Kompetenzen
- Datenquelle

---

## Projektziele

Im Rahmen des Projekts wurden folgende Fragestellungen untersucht:

- Aus welchen Regionen stammen die Migranten in Ingolstadt?
- Wie unterscheidet sich die Altersstruktur zwischen den einzelnen Stadtbezirken?
- Wie verteilen sich Personen mit und ohne Migrationshintergrund innerhalb der Stadt?
- Besteht ein Zusammenhang zwischen dem Anteil von Personen mit Migrationshintergrund und einer jüngeren Altersstruktur?

---

## Verwendete Datensätze

Für die Analyse wurden fünf Open-Data-Datensätze der Stadt Ingolstadt kombiniert:

- Anteil der Ausländer nach Staatengruppen
- Einwohner nach Altersgruppen
- Ausländische Bevölkerung
- Deutsche mit Migrationshintergrund
- Deutsche ohne Migrationshintergrund

Durch die Zusammenführung mehrerer Datenquellen konnte ein umfassendes Bild der Bevölkerungsstruktur erstellt werden.

---

## Verwendete Technologien

- Python
- Pandas
- NumPy
- SciPy
- GeoPandas
- Folium
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Projektablauf (CRISP-DM)

### Business Understanding

- Definition der Projektziele
- Formulierung der Forschungsfragen

### Data Understanding

- Analyse der Datenstruktur
- Prüfung der Datentypen
- Identifikation fehlender Werte
- Prüfung auf Duplikate

### Data Preparation

- Datenbereinigung
- Vereinheitlichung der Bezirksnamen
- Transformation der Datumsangaben
- Umwandlung in ein einheitliches Long-Format
- Zusammenführung von fünf Datensätzen
- Validierung der Datenqualität

### Explorative Datenanalyse

- Analyse der Herkunftsregionen
- Analyse der Altersstruktur
- Analyse der räumlichen Verteilung
- Vergleich verschiedener Bevölkerungsgruppen

### Statistische Analyse

- Korrelationsanalyse zwischen Migrationsanteil und Altersstruktur
- Zeitliche Entwicklung von 2013 bis 2025

### Visualisierung

- Balkendiagramme
- Zeitreihen
- Korrelationsdiagramme
- Interaktive Karten mit Folium

---

## Herausforderungen

Während der Datenaufbereitung mussten mehrere praktische Herausforderungen gelöst werden:

- Zusammenführung von fünf unterschiedlichen Datensätzen
- Harmonisierung verschiedener Datenstrukturen
- Vereinheitlichung von Bezirksbezeichnungen
- Bereinigung inkonsistenter Einträge
- Behandlung fehlender Werte
- Transformation der Daten in ein analysierbares Format
- Validierung der Datenqualität

Diese Schritte ermöglichten eine konsistente und vergleichbare Datenbasis für die anschließende Analyse.

---

## Zentrale Ergebnisse

- Zusammenführung von fünf Open-Data-Datensätzen zu einem konsistenten Analysedatensatz
- Analyse von insgesamt 5.226 Beobachtungen
- Identifikation regionaler Unterschiede in Herkunft und Altersstruktur
- Erstellung mehrerer statistischer Visualisierungen
- Entwicklung interaktiver Karten zur räumlichen Analyse
- Nachweis eines stabilen statistischen Zusammenhangs zwischen Migrationsanteil und Altersstruktur (ohne kausale Interpretation)

---

## Projektstruktur

```
population-analysis-ingolstadt
│
├── images/
│   ├── *.png
│
├── maps/
│   ├── ingolstadt_demographics_2025.html
│   ├── ingolstadt_age_groups_2025.html
│   └── README.md
│
├── notebooks/
│   └── ingolstadt_population_analysis.ipynb
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt
```

---

## Beispielvisualisierungen

Im Repository befinden sich unter anderem:


### Herkunftsstruktur

![Herkunftsstruktur](images/Analysen%20zur%20Einwanderungsdynamik%20und%20Herkunftsstruktur%20in%20Ingolstadt.png)

---

### Altersstruktur

![Altersstruktur](images/Anteil%20der%20Altersgruppen%20nach%20Jahren.png)

---

### Demografische Entwicklung

![Demografie](images/Demografische%20Entwicklung_Gesamtstadt%20Ingolstadt.png)

---

## Interaktive Karten

Zusätzlich zu den statischen Visualisierungen wurden zwei interaktive Karten mit **Folium** entwickelt.

- 🗺️ Bevölkerungsstruktur nach Stadtbezirken
- 👥 Altersgruppen nach Stadtbezirken

Die Karten können direkt im Browser geöffnet werden:

➡️ **Bevölkerungsstruktur**

https://tschviktoria-glitch.github.io/population-analysis-ingolstadt/maps/ingolstadt_demographics_2025.html

➡️ **Altersgruppen**

https://tschviktoria-glitch.github.io/population-analysis-ingolstadt/maps/ingolstadt_age_groups_2025.html

---

## Projektergebnisse

✔ Daten aus fünf Quellen integriert

✔ Datensatz mit 5.226 Beobachtungen erstellt

✔ Zwei interaktive Karten entwickelt

✔ Mehrere statistische Visualisierungen erstellt

✔ Korrelationsanalyse durchgeführt

✔ Vollständiger Analyseprozess nach CRISP-DM umgesetzt

---

## Demonstrierte Kompetenzen

- Data Cleaning
- Data Preparation
- Data Wrangling
- Data Integration
- Explorative Datenanalyse (EDA)
- Statistische Analyse
- Datenvisualisierung
- Geodatenanalyse
- Data Storytelling
- Arbeiten nach dem CRISP-DM-Modell

---

## Datenquelle

Open Data Portal der Stadt Ingolstadt

https://ingolstadt.bydata.de/datasets

---

## Projekterfolg

Diese Projektarbeit wurde im Rahmen der Weiterbildung **Data Analytics** erstellt und mit der Bestnote bewertet.

🏆 **Bewertung: 100 von 100 Punkten**

---

## Autor

**Viktoria Tschuchmann**

Projekt im Rahmen der Weiterbildung **Data Analytics**
