# LightGBM
# 📈 Módulo de Predicción Financiera: LightGBM Predictor

Este repositorio contiene la implementación del modelo de Machine Learning basado en **Gradient Boosting** para la optimización de la cobranza y proyección de rentas en **VINSUR**.

## 🚀 Descripción del Proyecto
El objetivo de este módulo es transformar los datos históricos de facturación y rentas de maquinaria (extraídos previamente por el módulo de IA Multimodal) en información accionable. Utiliza el algoritmo **LightGBM** para predecir tendencias de pago y detectar posibles retrasos en la liquidación de servicios.

## 🛠️ Stack Tecnológico
* **Core:** Python 3.10+
* **ML Model:** LightGBM (Light Gradient Boosting Machine).
* **Data Handling:** Pandas & NumPy.
* **Visualization:** Matplotlib & Seaborn (Análisis de importancia de variables).
* **Excel Integration:** OpenPyXL para la sincronización con el Libro Maestro.

## 📊 Características del Modelo
* **Eficiencia:** Implementación diseñada para procesar grandes volúmenes de datos tabulares con bajo consumo de memoria.
* **Métricas de Éxito:** El modelo fue evaluado mediante MAE (Mean Absolute Error) y RMSE, logrando una precisión superior al 95% en proyecciones mensuales.
* **Interpretabilidad:** Se incluyen gráficas de *Feature Importance* para identificar qué factores (tipo de cliente, zona, equipo) afectan más la rapidez de los pagos.

## 📂 Contenido del Repositorio
* `LightGBM_Vinsur_Predictor.ipynb`: Notebook principal con el ciclo de vida del modelo (EDA, Entrenamiento, Validación).
* `LightGBM_Visual_Results.pdf`: Copia de respaldo con los resultados y gráficas renderizadas.
* `data/`: Estructura sugerida para los datasets (anonimizados).

## 📝 Instrucciones de Visualización
Para una auditoría rápida del código, se recomienda abrir el archivo `.pdf` incluido. Si desea explorar la lógica de entrenamiento, el notebook está optimizado para su visualización directa en GitHub o mediante el uso de la tecla `.` (punto) para activar el entorno **GitHub Dev**.
