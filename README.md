📊 Telecom X – Parte 2: Predicción de Cancelación (Churn)
📣 Descripción del Proyecto

Después de realizar un análisis exploratorio exitoso en la Parte 1, este proyecto desarrolla modelos de Machine Learning para predecir la cancelación de clientes (Churn) en Telecom X.

El objetivo es anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios y proporcionar insights estratégicos que permitan implementar acciones de retención efectivas.

Este proyecto simula un entorno real de negocio donde el análisis técnico debe traducirse en decisiones estratégicas.

🎯 Objetivos

Preparar los datos para modelado predictivo.

Transformar variables categóricas a formato numérico.

Analizar correlaciones y relaciones clave con la cancelación.

Entrenar y comparar múltiples modelos de clasificación.

Evaluar desempeño con métricas relevantes.

Interpretar la importancia de variables.

Proponer estrategias de retención basadas en datos.

🧠 Tecnologías Utilizadas

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

Imbalanced-learn (SMOTE)

Entorno de desarrollo:

Google Colab

📂 Estructura del Proyecto
📁 telecom-x-churn
│
├── TelecomX_Parte2_Churn.ipynb
├── datos_tratados.csv
├── README.md
🔄 Pipeline del Proyecto
1️⃣ Preparación de Datos

Carga del dataset tratado en la Parte 1.

Eliminación de variables irrelevantes (ej. identificadores únicos).

One-Hot Encoding de variables categóricas.

Análisis de desbalanceo de clases.

Aplicación opcional de:

Undersampling

Oversampling

SMOTE

Normalización para modelos sensibles a escala.

2️⃣ Análisis Exploratorio Enfocado en Churn

Matriz de correlación.

Análisis de variables clave como:

Tiempo de contrato vs Cancelación.

Gasto total vs Cancelación.

Visualizaciones con boxplots y scatterplots.

3️⃣ Modelado Predictivo

Se entrenaron al menos dos modelos:

✔ Modelo basado en distancia:

Regresión Logística / KNN / SVM

✔ Modelo basado en árboles:

Decision Tree / Random Forest

Separación de datos:

70/30 o 80/20 (train/test)

4️⃣ Evaluación de Modelos

Se utilizaron las siguientes métricas:

Accuracy

Precision

Recall

F1-Score

Matriz de Confusión

También se analizó:

Overfitting

Underfitting

Capacidad de generalización

5️⃣ Interpretación de Variables

Dependiendo del modelo:

Regresión Logística → análisis de coeficientes.

Random Forest → importancia de variables.

KNN → influencia de proximidad.

SVM → impacto en la frontera de decisión.

📈 Principales Insights Estratégicos

El análisis permitió identificar:

Variables con mayor impacto en la cancelación.

Perfil de cliente con alto riesgo de churn.

Factores críticos relacionados con permanencia y gasto.

Oportunidades de intervención temprana.

💡 Estrategias Propuestas

Basado en los resultados del modelo:

Programas de fidelización para contratos cortos.

Incentivos para clientes con bajo tiempo de permanencia.

Segmentación de clientes de alto riesgo.

Ofertas personalizadas.

Mejora en servicio postventa.

🚀 Impacto del Proyecto

Este proyecto demuestra:

Capacidad para construir pipelines de Machine Learning.

Aplicación práctica de modelos de clasificación.

Interpretación de resultados con enfoque de negocio.

Comunicación técnica clara y estratégica.

👤 Rol en el Proyecto

Analista Junior de Machine Learning
Responsable de:

Preparación de datos

Construcción de modelos

Evaluación comparativa

Interpretación estratégica

📌 Próximos Pasos

Implementar validación cruzada.

Optimización de hiperparámetros (GridSearch / RandomSearch).

Evaluación con ROC-AUC.

Deployment del modelo como API.
