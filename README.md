# 🤖 Telecom X – Predicción de Churn con Machine Learning

## 📌 Descripción del proyecto

Telecom X enfrenta una alta tasa de cancelación de clientes (*churn*).
Después de realizar un análisis exploratorio de datos en el desafío anterior, en este proyecto se desarrollan **modelos de Machine Learning** para predecir qué clientes tienen mayor probabilidad de cancelar el servicio.

El objetivo es identificar **patrones de comportamiento, variables relevantes y perfiles de clientes con mayor riesgo de evasión**, con el fin de apoyar estrategias de retención basadas en datos.

---

# 🎯 Objetivos

* Construir modelos de **Machine Learning** para predecir churn.
* Evaluar el desempeño de los modelos mediante **métricas de clasificación**.
* Identificar **las variables más influyentes** en la cancelación de clientes.
* Determinar **el perfil de cliente con mayor riesgo de churn**.
* Proporcionar **recomendaciones estratégicas** para la empresa.

---

# 📂 Estructura del proyecto

```
TelecomX-Churn-Prediction
│
├── telecomx_dataset_limpio.csv
├── telecomx_churn_prediction.ipynb
└── README.md
```

**Archivos principales**

* **telecomx_dataset_limpio.csv**
  Dataset limpio generado en el desafío anterior.

* **telecomx_churn_prediction.ipynb**
  Notebook con el proceso completo de modelado y análisis.

---

# 🧠 Modelos de Machine Learning utilizados

Se entrenaron dos modelos de clasificación:

### 1️⃣ Regresión Logística

Modelo base utilizado para establecer un punto de referencia en la predicción de churn.

### 2️⃣ Random Forest

Modelo de ensemble basado en árboles de decisión que permite capturar relaciones más complejas entre variables.

---

# 📊 Métricas de evaluación

Para evaluar el desempeño de los modelos se utilizaron las siguientes métricas:

* **Accuracy**
  Proporción de predicciones correctas.

* **Precision**
  Proporción de clientes identificados como churn que realmente cancelaron.

* **Recall**
  Capacidad del modelo para detectar clientes que cancelarán.

* **F1 Score**
  Balance entre precision y recall.

También se utilizaron **matrices de confusión** para visualizar el desempeño de los modelos.

---

# 📈 Variables más importantes

El modelo **Random Forest** permitió identificar las variables con mayor influencia en la cancelación de clientes, entre ellas:

* Tipo de contrato
* Antigüedad del cliente (*tenure*)
* Cargos mensuales
* Cargos totales
* Método de pago

Estas variables resultan clave para entender el comportamiento de los clientes.

---

# 👥 Perfil de cliente con mayor riesgo de churn

A partir del análisis del modelo se identificó que los clientes con mayor probabilidad de cancelar el servicio suelen presentar las siguientes características:

* Contratos **mensuales**
* **Poca antigüedad** como clientes
* **Cargos mensuales elevados**
* Menor número de servicios contratados

---

# 💡 Recomendaciones estratégicas

Con base en los resultados obtenidos, se proponen las siguientes acciones:

* Incentivar la migración hacia **contratos de mayor duración**.
* Implementar **estrategias de retención durante los primeros meses del cliente**.
* Diseñar **promociones personalizadas para clientes con alto riesgo de churn**.
* Utilizar modelos predictivos para **identificar clientes en riesgo antes de que cancelen**.

---

# 🚀 Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# 📌 Próximos pasos

El modelo desarrollado puede utilizarse para:

* Integrarse en sistemas de **gestión de clientes (CRM)**.
* Generar **alertas tempranas de riesgo de churn**.
* Diseñar **estrategias de marketing y retención basadas en datos**.

---

# 👩‍💻 Autor

Proyecto desarrollado como parte de un **challenge de Data Science enfocado en predicción de churn y análisis de comportamiento de clientes**.
