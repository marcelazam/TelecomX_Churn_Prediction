# 📊 Telecom X – Churn Prediction Analysis

## 📌 Descripción del proyecto
Este proyecto desarrolla un análisis completo de evasión (churn) de clientes para la empresa Telecom X.  
El objetivo es identificar los factores que influyen en la cancelación del servicio y construir modelos de Machine Learning capaces de predecir qué clientes tienen mayor riesgo de abandono.

Se trabajó todo el flujo de ciencia de datos: limpieza, análisis exploratorio, preparación, modelado y conclusiones de negocio.

---

## 🎯 Objetivos
- Limpiar y transformar los datos originales
- Analizar patrones de cancelación
- Detectar variables más influyentes
- Crear modelos predictivos de churn
- Evaluar rendimiento de los modelos
- Proponer estrategias de retención

---

## 📂 Dataset
El dataset contiene información de clientes de Telecom X:
- datos demográficos
- tipo de contrato
- servicios contratados
- cargos mensuales y totales
- variable objetivo: **Churn (cancelación)**

---

## ⚙️ Proceso del proyecto

### 1️⃣ Extracción y limpieza
- Carga de archivo JSON
- Normalización de estructuras anidadas
- Eliminación de columnas irrelevantes (customerID)
- Conversión de tipos de datos
- Tratamiento de valores nulos
- Estandarización de categorías
- Exportación a CSV tratado

### 2️⃣ Análisis Exploratorio (EDA)
- Proporción de churn
- Distribución de variables
- Boxplots y scatterplots
- Análisis dirigido:
  - Tiempo de contrato vs churn
  - Gasto total vs churn
- Matriz de correlación

### 3️⃣ Preparación de datos
- Encoding (One-Hot Encoding)
- Separación train/test
- Normalización para modelos sensibles a escala

### 4️⃣ Modelado
Se implementaron múltiples modelos:

- Regresión Logística
- KNN
- Random Forest

### 5️⃣ Evaluación
Métricas utilizadas:
- Accuracy
- Precision
- Recall
- F1-score
- Matriz de confusión

### 6️⃣ Importancia de variables
- coeficientes (Logística)
- feature importance (Random Forest)

---

## 📈 Principales hallazgos
- Clientes con contratos mensuales presentan mayor churn
- Menor antigüedad → mayor probabilidad de cancelación
- Cargos mensuales altos influyen en abandono
- Servicios adicionales aumentan retención

---

## 💡 Recomendaciones de negocio
- Incentivar contratos largos
- Ofrecer descuentos a clientes nuevos
- Programas de fidelización
- Paquetes de servicios combinados

---

## 🛠️ Tecnologías utilizadas
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## ▶️ Cómo ejecutar
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

Abrir el notebook:
```
analisis_TelecomX_completo.ipynb
```

Ejecutar todas las celdas.

---

## 👩‍💻 Autora
Marcela Zamora  
Proyecto desarrollado como parte del desafío de Data Science.
