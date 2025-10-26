# Proyecto_Acc

Análisis de accidentes de tránsito en Chile utilizando **Python** y herramientas de **análisis de datos** y **machine learning**.

---

## Descripción

Este proyecto tiene como objetivo analizar los **siniestros viales reportados por Carabineros de Chile**, explorando si existen diferencias significativas y correlaciones entre:

* El **tipo de accidente** y el **perfil de las personas involucradas** (conductor, pasajero o peatón).
* Las **consecuencias** de los accidentes (muertos, graves, menos graves, leves o ilesos).
* La **conducta infractora** y su relación con las características del accidente.
* Las **fechas** y patrones temporales (por mes, día o temporada) en la ocurrencia de los siniestros.

A través de tres notebooks principales, se lleva a cabo la carga, limpieza, exploración y modelado de los datos, con el fin de **identificar patrones y factores de riesgo** asociados a la accidentalidad vial en Chile.

---

## Estructura del proyecto

* `ProyectoAcc1.ipynb`: Carga y limpieza de los datos.
* `ProyectoAcc2.ipynb`: Análisis exploratorio (EDA) y visualización de patrones.
* `ProyectoAcc3.ipynb`: Modelado estadístico y machine learning para detección de relaciones y predicciones.

---

## Requisitos

* **Python 3.8** o superior
* **Jupyter Notebook** o **JupyterLab**

Instalación de dependencias principales:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Uso

1. Clona este repositorio:

   ```bash
   git clone https://github.com/GrxmmLaw/Proyecto_Acc.git
   cd Proyecto_Acc
   ```

2. Abre los notebooks:

   ```bash
   jupyter notebook
   ```

3. Ejecuta los notebooks en orden:

   * `ProyectoAcc1.ipynb`
   * `ProyectoAcc2.ipynb`
   * `ProyectoAcc3.ipynb`

Esto te permitirá reproducir el flujo completo de análisis y generar las conclusiones del estudio.

---

## Tecnologías utilizadas

* **Python**
* **Pandas / NumPy** → Manipulación y procesamiento de datos
* **Matplotlib / Seaborn** → Visualización de resultados
* **Scikit-learn** → Modelado y evaluación estadística
* **Jupyter Notebook** → Entorno de desarrollo interactivo

---

## Objetivos del análisis

1. Identificar correlaciones entre el tipo de accidente y el perfil del infractor.
2. Evaluar el impacto de distintos tipos de conductas en las consecuencias del siniestro.
3. Explorar tendencias temporales y estacionales en la ocurrencia de accidentes.
4. Proponer visualizaciones y modelos predictivos que apoyen la prevención vial.

---

## Fuente de datos

Los datos provienen de los **reportes mensuales de siniestros viales de Carabineros de Chile**, que incluyen información sobre:

* Tipo de accidente
* Fecha y hora
* Tipo de participante (conductor, pasajero, peatón)
* Consecuencias (muertos, graves, menos graves, leves, ilesos)
* Variables complementarias para análisis de comportamiento e impacto.

---
