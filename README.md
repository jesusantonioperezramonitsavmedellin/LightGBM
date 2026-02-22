# LightGBM
📈 Módulo de Inteligencia Financiera: LightGBM Predictor
Este repositorio contiene la implementación de un sistema de análisis y proyección financiera desarrollado para VINSUR. El proyecto utiliza algoritmos de Gradient Boosting para contrastar el desempeño histórico de 2025 frente a las métricas actuales de 2026.

🚀 Objetivos del Sistema
Síntesis de Datos: Consolidación de cuentas base y expansión de series de tiempo financieras.

Proyección Predictiva: Uso de LightGBM para estimar ingresos y gastos del cierre de ejercicio 2026.

Auditoría Inteligente: Identificación automática de desviaciones presupuestarias superiores al 10% mediante análisis interanual.

🛠️ Stack Tecnológico
Lenguaje: Python 3.10+

Modelado: lightgbm (LGBMRegressor).

Evaluación: sklearn.metrics (RMSE - Root Mean Squared Error).

Procesamiento: pandas para manipulación de DataFrames y numpy para operaciones vectoriales.

Visualización: seaborn y matplotlib para la generación de dashboards estadísticos.

📊 Metodología y Análisis de Datos
El sistema aplica técnicas avanzadas de ciencia de datos detalladas en el notebook:

Feature Engineering: Transformación de variables categóricas (Departamentos y Conceptos) para su procesamiento en el modelo.

Análisis YoY (Year-over-Year): Comparativa mensual directa para detectar picos atípicos en el gasto operativo.

Métricas de Error: El modelo se ajusta minimizando el RMSE, asegurando proyecciones alineadas con la realidad contable de la empresa.

📂 Estructura de Evidencias
Analisis_Financiero_LightGBM.ipynb: Pipeline completo desde la carga de datos hasta la inferencia del modelo.

Analisis_Financiero_LightGBM - Colab.pdf: Documento de Respaldo. Contiene las 8 gráficas clave y los resultados de ejecución "congelados" para auditoría inmediata.

📝 Instrucciones de Visualización
Para revisar las gráficas de dispersión (stripplot) y las tendencias de gasto, se recomienda abrir el PDF adjunto. Los desarrolladores interesados en la lógica del hiperparámetro y el entrenamiento pueden inspeccionar el notebook directamente en el entorno de GitHub Dev (presionando la tecla .).ub Dev**.
