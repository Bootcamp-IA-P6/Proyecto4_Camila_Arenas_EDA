# Análisis Exploratorio de Datos (EDA): COVID-19 en EE. UU.

Este repositorio contiene un análisis profundo sobre el impacto de la pandemia de COVID-19 en los Estados Unidos, utilizando datos históricos de **The COVID Tracking Project**. El enfoque principal fue identificar disparidades entre el volumen de contagios y la severidad de la mortalidad por estado.

## Tecnologías Utilizadas
* **Python 3.13**
* **uv**: Gestión de entornos y dependencias.
* **Pandas**: Manipulación y limpieza de datos.
* **Matplotlib & Seaborn**: Visualización avanzada de datos.
* **Jupyter Notebooks**: Entorno de desarrollo interactivo.

##  Hallazgos Principales

### 1. Diagnóstico de Datos y Limpieza
Se realizó una auditoría de valores nulos, detectando que variables como `positiveTestsPeopleAntigen` carecían del **97% de los datos** (20,147 valores faltantes). Por ello, el análisis se centró en métricas consolidadas de hospitalización y fallecimientos.

### 2. Volumen vs. Letalidad
A través del análisis, se desmintió la idea de que los estados con más casos fueron necesariamente los más letales proporcionalmente:
* **Líder en Volumen:** California (CA) con >3.5 millones de casos.
* **Líder en Letalidad (CFR):** Nueva Jersey (NJ) con una tasa de **2.9%**.

### 3. Tendencias Temporales
Se identificó un punto de inflexión crítico en **noviembre de 2020**, donde la curva de fallecimientos acumulados mostró un crecimiento acelerado, superando la barrera de los 500,000 hacia marzo de 2021.

##  Instalación y Uso

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/Factoria-F5-madrid/ai_project_EDA.git](https://github.com/Factoria-F5-madrid/ai_project_EDA.git)
