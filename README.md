# 📊 Modelo Predictivo de Churn - Telecom

Este repositorio contiene exclusivamente el **notebook completo** del proceso de desarrollo del modelo de machine learning para predecir la deserción de clientes (**Churn**) en empresas de telecomunicaciones. Está basado en el **famoso conjunto de datos de Telecom**, utilizado ampliamente para estudios de retención de clientes.

El modelo desarrollado en este notebook es el núcleo que **alimenta tanto la API como la aplicación web** creadas para facilitar su uso desde diferentes plataformas.

---

## 🧠 Objetivo del Proyecto

Predecir con alta precisión qué clientes tienen mayor probabilidad de abandonar el servicio, permitiendo así a la empresa tomar acciones proactivas para retenerlos.

---

## 📁 Contenido del repositorio

- `churn_model_notebook.ipynb`: contiene el proceso completo, desde la carga y análisis de datos hasta la serialización del modelo (`joblib`).
- No se incluyen interfaces gráficas ni endpoints en este repositorio. **Este notebook es la base del modelo utilizado por la API y la WebApp.**

---

## ⚙️ Tecnologías y Herramientas

- Python
- Pandas, NumPy
- Scikit-learn
- Gradient Boosting
- RandomizedSearchCV
- Matplotlib / Seaborn
- Joblib

---

## ✅ Rendimiento del Modelo

Tras el procesamiento y la optimización con técnicas como ingeniería de características y búsqueda de hiperparámetros, el modelo final (basado en **Gradient Boosting**) logró los siguientes resultados:

- **AUC-ROC: 0.934**
- Excelente capacidad de generalización y discriminación entre clases.
- Adecuado para conjuntos de datos desbalanceados gracias al enfoque en métricas robustas y curvas ROC.

---

## 🔗 Enlaces Relacionados

- 🔌 **API del modelo**: [Repositorio de la API](https://github.com/cesaredcruz/api-telecom-churn)
- 🌐 **Web App**: [Aplicación Web de Predicción de Churn](https://churn-app-telecom.onrender.com)

---

## 👤 Autor

**César Eduardo Cruz Cabrera**  
[LinkedIn](https://www.linkedin.com/in/cesar-eduardo-cruz-cabrera)

