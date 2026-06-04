# Data Science & ML Job Salaries – Exploratory Data Analysis

**Fragestellung:** Was bestimmt das Gehalt als Data Scientist oder Machine Learning Engineer?

Dieses Projekt analysiert globale Gehaltsdaten aus dem Data-Science- und ML-Bereich (2020–2024) mit dem Ziel, die wichtigsten Einflussfaktoren auf das Jahresgehalt zu identifizieren.

---

## Datensatz

- **Quelle:** [Data Science Salaries 2024 – Kaggle](https://www.kaggle.com/datasets/sazidthe1/data-science-salaries)
- **Ursprung:** ai-jobs.net (selbst gemeldete Gehaltsdaten)
- **Umfang:** ~14.000 Einträge, Zeitraum 2020–2024
- **Wichtige Spalten:** `work_year`, `experience_level`, `employment_type`, `job_title`, `salary_in_usd`, `remote_ratio`, `company_location`, `company_size`

---

## Analyseschwerpunkte

1. Wie entwickeln sich Gehälter über die Jahre (2020–2024)?
2. Welchen Einfluss hat das Erfahrungslevel (Junior → Senior → Executive)?
3. Welche Job-Titel zahlen am meisten – und welche am wenigsten?
4. Remote-Arbeit: zahlen Remote-Jobs mehr oder weniger?
5. Geografische Unterschiede: USA vs. Europa vs. Rest der Welt
6. Unternehmensgröße als Faktor

---

## Methoden & Tools

- Python 3.x
- pandas – Datenverarbeitung & Analyse
- matplotlib / seaborn – Visualisierung
- Jupyter Notebook

---

## Key Findings

*(werden nach Abschluss der Analyse ergänzt)*

---

## Projekt starten

```bash
# Repository klonen
git clone https://github.com/DEIN-USERNAME/ds-salaries-eda.git
cd ds-salaries-eda

# Abhängigkeiten installieren
pip install -r requirements.txt

# Datensatz herunterladen
# → https://www.kaggle.com/datasets/sazidthe1/data-science-salaries
# → CSV-Datei in data/raw/ ablegen

# Notebook öffnen
jupyter notebook notebooks/analysis.ipynb
```

---

## Projektstruktur

```
ds-salaries-eda/
├── data/
│   └── raw/              ← Rohdaten (nicht in Git versioniert)
├── notebooks/
│   └── analysis.ipynb    ← Hauptanalyse
├── README.md
├── requirements.txt
└── .gitignore
```

---

*Erstellt im Rahmen eines Data-Science-Portfolios. Weitere Projekte: [github.com/DEIN-USERNAME](https://github.com/soribge)*
