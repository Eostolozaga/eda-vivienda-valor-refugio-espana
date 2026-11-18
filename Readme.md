# 🏠 EDA: Housing in Spain as a Safe Haven

The central aim of this analysis is to determine whether the **Spanish housing market** acts as a safe-haven asset in periods of economic uncertainty, by examining how resilient it is to inflation and how it compares with other traditional assets.

---

## 📋 Project description

To test this hypothesis, the study is organized around the following milestones:

*   **Hedging capacity:** How housing has appreciated relative to the **CPI (IPC)** and its historical correlation with **gold**.
*   **Financial decoupling:** Whether sale prices have held up as **Euribor** has risen.
*   **Rental yield:** How the rental market has evolved as a driver independent of the sales cycle.
*   **Affordability gap:** The **"critical effort ratio"** (wages versus prices).
*   **Historical analysis:** How the current cycle compares with the **2008** crisis, in order to identify patterns of solvency.

---

## 📊 Featured visualizations

<p align="center">
  <img src="EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/Gif_Readme.gif" width="100%" alt="Housing analysis">
</p>

![Infographic: housing versus gold](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/Infografia%20EDA%20Vivienda%20como%20valor%20refugio%20en%20España.png)

---

## 🛠️ Technology stack


| Tool | Main use |
| :--- | :--- |
| **Python** | Core language for the analysis |
| **Pandas / NumPy** | Data processing and cleaning |
| **Matplotlib / Seaborn** | Statistical visualization |
| **Scikit-Learn** | Linear regression modeling |
| **Functools** | Functional-style utilities |

> **Data sources:** INE (Instituto Nacional de Estadística, the Spanish National Statistics Institute), Idealista, and open-data portals.

---



## 📂 Repository layout

The whole project lives in the folder [`EDA Correlacion del precio de la vivienda respecto al oro/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/):

*   [`data/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/data/): original datasets (`raw/`) and processed datasets (`processed/`).
*   [`notebooks/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/notebooks/):
    *   [`main/EDA Main.ipynb`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/notebooks/main/EDA%20Main.ipynb): **main notebook**, with the full narrative and the conclusions.
    *   [`exploratory/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/notebooks/exploratory/): separate analyses by source (CPI, gold, Euribor, rent, home sales, and others).
*   [`reports/figures/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/reports/figures/): exported charts and visualizations.
*   [`documents/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/documents/): project write-up and presentation.
*   [`src/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/): graphics used in the README (GIF and infographic).
*   [`requirements.txt`](requirements.txt): dependencies needed to reproduce the environment.

---

## ▶️ How to reproduce it

```bash
git clone https://github.com/Eostolozaga/eda-vivienda-valor-refugio-espana.git
cd eda-vivienda-valor-refugio-espana
pip install -r requirements.txt
jupyter notebook "EDA Correlacion del precio de la vivienda respecto al oro/notebooks/main/EDA Main.ipynb"
```
