<img src="img/UOC-logo.png" alt="Logo de la UOC" width="1000"/>

# Mantenimiento predictivo en la industria mediante *machine learning*

## Acerca del proyecto
Este trabajo constituye el Trabajo Final de Máster (TFM) del Máster Universitario de Ciencia de Datos de la Universitat Oberta de Catalunya (UOC). El proyecto se centra en la implementación de técnicas de machine learning para la predicción de fallos en maquinaria industrial, con el objetivo fundamental de optimizar los procesos de mantenimiento y reducir los costes operativos asociados mediante el análisis de datos provenientes de sensores industriales y los registros históricos de mantenimiento.

## Estructura del proyecto
El proyecto se organiza en dos notebooks principales que contienen todo el proceso de análisis y desarrollo del modelo predictivo:

### Notebooks
- `preprocesado.ipynb`: Este notebook contiene el análisis exploratorio de datos (EDA) y todo el proceso de preparación de datos. Incluye:
  - Carga y exploración inicial de datos
  - Limpieza y tratamiento de valores ausentes
  - Análisis de correlaciones entre variables
  - Transformación y normalización de variables
  - Generación de nuevas variables relevantes
  - Preparación final del dataset para el entrenamiento

- `modelo.ipynb`: Este notebook abarca el desarrollo completo del modelo predictivo:
  - Selección y evaluación de diferentes algoritmos de machine learning
  - Optimización de hiperparámetros
  - Entrenamiento del modelo final
  - Evaluación de resultados mediante métricas relevantes
  - Visualización de resultados

## Instrucciones de uso

### Requisitos previos
- Python 3.8 o superior
- Jupyter Notebook o JupyterLab

### Instalación y ejecución
1. Clonar el repositorio: `git clone https://github.com/i-roda/TFM_Master_Ciencia_Datos.git`
2. Instalar las dependencias: `pip install -r requirements.txt`
3. Ejecutar los notebooks en orden:
   - Primero `preprocesado.ipynb` para preparar y analizar los datos
   - Después `modelo.ipynb` para desarrollar y evaluar el modelo predictivo

### Nota importante
Los notebooks están diseñados para ejecutarse secuencialmente, ya que el segundo notebook (`modelo.ipynb`) depende de los datos procesados generados en el primero (`preprocesado.ipynb`).

## Licencia
Esta obra está sujeta a una licencia de Reconocimiento - NoComercial - SinObraDerivada 3.0 España de [CreativeCommons](https://creativecommons.org/licenses/by-nc-nd/3.0/es/).
![Licencia Creative Commons](img/license.png)
