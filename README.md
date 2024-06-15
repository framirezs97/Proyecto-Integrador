
# Enfoques Modernos en la Predicción del Mercado de Acciones: XGBoost, Redes Neuronales y LSTM

Este documento proporciona toda la información necesaria para reproducir el proyecto de predicción de precios de acciones utilizando datos de compañías tecnológicas.

## Enlace al Repositorio de GitHub

[Repositorio del Proyecto en GitHub](https://github.com/framirezs97/Proyecto-Integrador)

## Fuentes de Datos

Los datos de las acciones de las siguientes compañías tecnológicas se obtuvieron de Yahoo Finance:
- Apple (AAPL)
- Google (GOOG)
- Microsoft (MSFT)
- Amazon (AMZN)

## Instrucciones para Reproducir el Proyecto

1. **Clonar el Repositorio:**
   ```bash
   git clone https://github.com/framirezs97/Proyecto-Integrador.git
   cd Proyecto-Integrador
   ```

2. **Instalar las Dependencias:**
   Asegúrate de tener `pip` instalado y luego ejecuta:
   ```bash
   pip install -r requirements.txt
   ```

3. **Ejecutar el Notebook:**
   Abre el archivo `Codigo_proyecto.ipynb` en Jupyter Notebook o Google Colab y ejecuta todas las celdas en orden.

4. **Descripción del Código:**
   - El notebook descarga los datos históricos de precios de las acciones mencionadas utilizando la librería `yfinance`.
   - Se combinan los datos de las diferentes compañías en un único DataFrame.
   - Se realizan análisis y visualizaciones de los datos.
   - Se implementan modelos de predicción para los precios de cierre de las acciones.

5. **Estructura del Proyecto:**
   - `Codigo_proyecto.ipynb`: El notebook principal con el código del proyecto.
   - `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto.

## Consideraciones Adicionales

- **Google Colab con GPU:** El proyecto se ha diseñado para ejecutarse en Google Colab con GPU para acelerar el procesamiento.

## Instrucciones Adicionales para Google Colab

1. **Subir el Notebook a Google Colab:**
   - Ve a [Google Colab](https://colab.research.google.com/).
   - Sube el archivo `Codigo_proyecto.ipynb`.

2. **Configurar el Entorno de Ejecución:**
   - En el menú superior, selecciona `Entorno de ejecución` > `Cambiar tipo de entorno de ejecución`.
   - Selecciona `GPU` como acelerador de hardware y haz clic en `Guardar`.

3. **Ejecutar todas las Celdas:**
   - Ejecuta todas las celdas del notebook en orden para reproducir el análisis y las predicciones de precios de las acciones.
