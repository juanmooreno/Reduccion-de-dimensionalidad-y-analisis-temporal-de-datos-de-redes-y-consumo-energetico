# Reducción de dimensionalidad y análisis temporal de datos de redes y consumo energético

Este proyecto aplica **métodos clásicos de predicción y reducción de dimensionalidad** para dos problemas distintos:

- **Protección de la ETSISI** ante ataques de red mediante el **análisis y clasificación de trazas**.
- **Mejora de la eficiencia energética en la UPM** a través del estudio de **series temporales de consumo eléctrico**.

El trabajo combina **técnicas de machine learning**, **visualización de datos** y **análisis estadístico** utilizando **Python**.

---

## 📋 Índice de la práctica

### 🧩 **PROBLEMA 1: Protegiendo la ETSISI de ataques de red**

- Estudio **cualitativo y cuantitativo** del dataset.
- Aplicación de **reducción de dimensionalidad**:
  - PCA
  - Truncated SVD
  - ISOMAP
  - t-SNE
- Evaluación de **modelos de predicción** sobre las trazas reducidas.
- **Visualización final comparativa** de los resultados.

### ⚡ **PROBLEMA 2: Mejorando la eficiencia energética en la UPM**

- **Análisis exploratorio** del consumo por **campus y bloques** (diario, semanal, mensual y anual).
- Creación de **modelos de predicción** para los **últimos 6 meses**.
- Análisis de **series temporales individuales** por bloque.

---

## 🧠 Resumen de resultados

### 🔒 **Problema de ataques de red**
- El modelo **`RandomForestClassifier`** alcanzó el **mejor rendimiento** con un **f1-score de 0.90**, seguido de MLP y KNN.
- Aunque la **reducción de dimensionalidad no mejoró significativamente la clasificación**, el método **`t-SNE`** fue el que **mejor separó visualmente las clases**.

### 🔋 **Problema energético**
- Se identificaron **patrones diarios y estacionales** en el consumo.
- El modelo **`Random Forest`** obtuvo el **menor error** (**MAE = 411.96**), seguido por:
  - SARIMAX (**MAE = 765.96**)
  - ARIMA

---

## 🧰 Tecnologías y librerías utilizadas

**Lenguaje:** `Python 3.10+`

**Librerías principales:**

- `numpy`, `pandas` — manipulación y análisis de datos
- `matplotlib`, `seaborn` — visualización
- `scikit-learn` — reducción de dimensionalidad y modelos de clasificación
- `statsmodels` — modelos ARIMA y SARIMAX para series temporales

> Trabajo académico realizado en el marco de estudios de **análisis de datos y machine learning** aplicados a **ciberseguridad** y **eficiencia energética**.

---

## ⚖️ Licencia

Este proyecto se distribuye bajo la licencia **Creative Commons Atribución-NoComercial 4.0 Internacional (CC BY-NC 4.0)**.  
Puedes **compartir** y **adaptar** el material, siempre que **cites la autoría** y **no lo uses con fines comerciales**.

Más información: [https://creativecommons.org/licenses/by-nc/4.0/deed.es](https://creativecommons.org/licenses/by-nc/4.0/deed.es)

---

## 👥 Realizado por:

- **Juan Moreno Segura**  
- **Alonso Ruiz Palomo**
