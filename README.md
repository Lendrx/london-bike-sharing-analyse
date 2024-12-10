# London Bike-Sharing Analyse

## Überblick
Dieses Projekt analysiert die Nutzungsmuster des Londoner Bike-Sharing-Systems mittels Python und Tableau. Es zeigt die Zusammenhänge zwischen Wetterbedingungen, Tageszeiten und Fahrradnutzung.

## Funktionen
- Interaktives Tableau-Dashboard
- Wetter- und Nutzungsanalyse
- Stündliche und saisonale Muster
- Anpassbare Zeitreihenanalyse

## Projektstruktur
```
/
├── london-bikes.ipynb     # Datenaufbereitung und Analyse
├── bikes-london-project.twb   # Tableau Visualisierungen
└── data/
    ├── london_merged.csv      # Rohdaten
    └── london-bikes-final-data.xlsx  # Aufbereitete Daten
```

## Installation & Nutzung
1. Repository klonen
2. Python-Pakete installieren:
   ```bash
   pip install pandas kaggle openpyxl jupyter
   ```
3. Jupyter Notebook ausführen
4. Tableau-Workbook öffnen

## Datenaufbereitung (london-bikes.ipynb)
1. Datenimport von Kaggle
2. Bereinigung und Transformation
3. Feature Engineering (Wetter, Jahreszeiten)
4. Export für Tableau

## Dashboard-Funktionen
- Gesamtfahrten-Übersicht
- Temperatur/Wind-Heatmap
- Wettereinfluss-Analyse
- Stündliche Nutzungsmuster

## Technologien
- Python 3.12
- Tableau 2024.1
- Pandas
- Kaggle API

## Datenquelle
London Bike Sharing Dataset (Kaggle)

## Lizenz
MIT