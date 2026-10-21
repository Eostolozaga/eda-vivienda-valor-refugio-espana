# 🏠 Análisis EDA: La Vivienda en España como Valor Refugio

El objetivo central de este análisis es determinar si el **mercado inmobiliario español** actúa como un activo refugio frente a escenarios de incertidumbre económica, analizando su resiliencia frente a la inflación y otros activos tradicionales.

---

## 📋 Descripción del Proyecto

Para validar esta hipótesis, el estudio se desglosa en los siguientes hitos estratégicos:

*   **Capacidad de cobertura (Hedge):** Análisis de la revalorización de la vivienda frente al **IPC** y su correlación histórica con el **oro**.
*   **Desacople financiero:** Investigación de la resiliencia del precio de venta frente a la subida del **Euríbor**.
*   **Rentabilidad del alquiler:** Evolución del mercado de arrendamiento como motor independiente del ciclo de venta.
*   **Brecha de accesibilidad:** Determinación del **"Ratio de Esfuerzo Crítico"** (Salarios vs. Precios).
*   **Análisis Histórico:** Contraste del ciclo actual frente a la crisis de **2008** para identificar patrones de solvencia.

---

## 📊 Visualizaciones Destacadas

<p align="center">
  <img src="EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/Gif_Readme.gif" width="100%" alt="Análisis de Vivienda">
</p>

![Infografía Vivienda vs Oro](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/Infografia%20EDA%20Vivienda%20como%20valor%20refugio%20en%20España.png)

---

## 🛠️ Stack Tecnológico


| Herramienta | Uso Principal |
| :--- | :--- |
| **Python** | Lenguaje base del análisis |
| **Pandas / NumPy** | Procesamiento y limpieza de datos |
| **Matplotlib / Seaborn** | Visualización estadística avanzada |
| **Scikit-Learn** | Modelado de regresión lineal |
| **Functools** | Optimización de procesos funcionales |

> **Fuentes de datos:** INE (Instituto Nacional de Estadística), Idealista y portales de datos abiertos.

---



## 📂 Estructura del Repositorio

Todo el proyecto está dentro de la carpeta [`EDA Correlacion del precio de la vivienda respecto al oro/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/):

*   [`data/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/data/): datasets originales (`raw/`) y procesados (`processed/`).
*   [`notebooks/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/notebooks/):
    *   [`main/EDA Main.ipynb`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/notebooks/main/EDA%20Main.ipynb): **notebook principal** con la narrativa completa y las conclusiones.
    *   [`exploratory/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/notebooks/exploratory/): análisis individuales por fuente (IPC, oro, Euríbor, alquiler, compraventas...).
*   [`reports/figures/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/reports/figures/): gráficos y visualizaciones exportadas.
*   [`documents/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/documents/): memoria del proyecto y presentación.
*   [`src/`](EDA%20Correlacion%20del%20precio%20de%20la%20vivienda%20respecto%20al%20oro/src/): recursos gráficos del README (GIF e infografía).
*   [`requirements.txt`](requirements.txt): dependencias para replicar el entorno.

---

## ▶️ Cómo reproducirlo

```bash
git clone https://github.com/Eostolozaga/eda-vivienda-valor-refugio-espana.git
cd eda-vivienda-valor-refugio-espana
pip install -r requirements.txt
jupyter notebook "EDA Correlacion del precio de la vivienda respecto al oro/notebooks/main/EDA Main.ipynb"
```
