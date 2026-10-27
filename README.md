# Umsatzprognose GreenGarten (Datenanalyse & Dashboard)

Dieses Repository enthält den Analyseteil unseres 3-köpfigen IHK-Projekts für die *GreenGarten Versandhandel GmbH* (Online-Händler für Gartenprodukte mit ca. 3,7 Mio. EUR Jahresumsatz).

## 🏢 Unternehmenskontext & Problemstellung
Bisher plant der Einkauf Bestellmengen und Lagerbestände manuell über Excel-Vorjahresvergleiche. Das führt zu Problemen wie Stockouts in der Hochsaison oder Kapitalbindung durch Überbestände. Das Ziel dieses Projekts ist die fundierte Analyse der historischen Verkaufs- und Marketingdaten mittels explorativer Datenanalyse (EDA), um die wesentlichen Umsatztreiber und Saisonnmuster aufzudecken.

## 👥 Meine Aufgaben & Arbeitsteilung

* **Team:** 3 Personen (IHK-Abschlussprojekt Data Analyst)

**Mein Verantwortungsbereich (dieses Repository):**
1. **Explorative Datenanalyse (EDA):** Untersuchung der Umsatzstrukturen nach Kategorien, Herstellern, Preisen und Saisonalität (`src/eda.ipynb`).
2. **Marketing-Analyse:** Überprüfung des Zusammenhangs zwischen Werbeausgaben und Umsatz.
3. **Dashboard:** Entwicklung des interaktiven Dashboards in Looker Studio für die Geschäftsführung und alle relevanten Abteilungen.

*(Die Datenbereinigung und der Bereich Machine Learning wurden von anderen Teammitgliedern bearbeitet).*

## 📈 Zentrale Ergebnisse der EDA
* **Umsatzstrukturen:** Werkzeuge, Pflanzen und Bewässerungssysteme machen über 82 % des Gesamtumsatzes aus. Das Premium-Segment (> 35 €) dominiert mit 56 %.
* **Saisonalität:** Stark ausgeprägter Peak im Frühsommer (Mai/Juni) und Jahrestief im Januar, getrieben durch die Hauptkategorien.
* **Marketingkorrelation:** Hoher Zusammenhang ($r = 0,96$) zwischen Werbeausgaben und Umsatz, wobei das Budget als Spiegelbild der Saisongestaltung dient.

## 📂 Repository-Struktur
* `raw/` – Ursprüngliche Rohdaten
* `interim/` – Bereinigte Daten (`verkaufe_clean.csv`)
* `src/` – Jupyter Notebooks (`data_cleaning.ipynb`, `eda.ipynb`)

## 🖥️ Dashboard
Das interaktive Dashboard zur Visualisierung der Ergebnisse wurde in **Looker Studio** erstellt:
👉 [Looker Studio Dashboard öffnen](https://datastudio.google.com/reporting/9622854a-b558-40ac-840c-e09c26d4eca7)
