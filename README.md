# Analyse der Bevölkerungsstruktur in Ingolstadt mit Python

## Projektübersicht

Dieses Projekt untersucht die Bevölkerungsstruktur der Stadt Ingolstadt anhand mehrerer Open-Data-Datensätze. Ziel war es, demografische Strukturen zu analysieren und Zusammenhänge zwischen Herkunft, Altersstruktur sowie der räumlichen Verteilung der Bevölkerung auf Ebene der Stadtbezirke zu identifizieren.

Das Projekt wurde im Rahmen des Kurses **Data Analytics** durchgeführt und orientiert sich am **CRISP-DM-Prozess**.

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
Population-Analysis-Ingolstadt
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   └── Population_Analysis.ipynb
│
├── images
│
├── requirements.txt
│
└── README.md
```

---

## Beispielvisualisierungen

Im Repository befinden sich unter anderem:

- Analyse der Herkunftsregionen
- Altersstruktur der Bevölkerung
- Vergleich der Stadtbezirke
- Korrelationsanalysen
- Interaktive Karten auf Basis von Folium

---

## Erlernte und angewandte Kompetenzen

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

## Autor

**Viktoria Tschuchmann**

Projekt im Rahmen der Weiterbildung **Data Analytics**
