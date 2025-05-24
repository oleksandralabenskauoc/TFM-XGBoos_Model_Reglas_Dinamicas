# 📊 Detección de Fraude Financiero con XGBoost y Reglas Dinámicas

Este repositorio contiene el notebook desarrollado en Python en la plataforma Kaggle para detectar transacciones fraudulentas combinando técnicas de machine learning (XGBoost) con reglas dinámicas.

---

## 🚀 Enlace al notebook:

📎https://github.com/oleksandralabenskauoc/TFM-XGBoos_Model_Reglas_Dinamicas/blob/main/tfm-xgboost-model-reglas-dinamicas-v3.ipynb

---

## 🧠 Modelo aplicado

Se ha utilizado:
- **XGBoost** como modelo base entrenado con el dataset de Kaggle "Creadit Card Fraud Detection" (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Regresión Logística** y **Random Forest** como modelos comparativos
- **Reglas dinámicas** para detectar patrones adicionales de fraude

---

## 📊 Resultados de la Comparación de los Modelos:

| Modelo                                      | Accuracy   | Precision  | Recall     | F1-score   | ROC AUC   |
|---------------------------------------------|------------|------------|------------|------------|-----------|
| XGBoost                                     | 0.999491   | 0.879121   | 0.816327   | 0.846561   | 0.986169  |
| Random Forest                               | 0.999491   | 0.952941   | 0.826531   | 0.885246   | 0.983225  |
| Logistic Regression                         | 0.999491   | 0.294118   | 0.867347   | 0.439276   | 0.966374  |
| XGBoost + Ajuste de los Hiperparámetros     | 0.999491   | 0.931818   | 0.836735   | 0.881720   | 0.984504  |

---

## 📈 Resultados Finales:

| Modelo                                    | Accuracy   | Precision  | Recall     | F1-score   | ROC AUC   |
|-------------------------------------------|------------|------------|------------|------------|-----------|
| XGBoost + Ajuste de los Hiperparámetros   | 0.999491   | 0.931818   | 0.836735   | 0.881720   | 0.984504  |
| XGBoost + Reglas Dinámicas                | 0.962010   | 0.036771   | 0.836735   | 0.070447   | NA        |


> ⚠️ Nota: Las reglas dinámicas reducen algunas métricas debido a su naturaleza "ad hoc", pero amplían la cobertura de detección.

---

## 📦 Cómo ejecutar:

1. Descargar el notebook que se puede encontrar en este repositorio.
2. Subir el notebook a la plataforma Kaggle.
3. Añadir el dataset "Creadit Card Fraud Detection" (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) al entorno.
4. Ejecutar con el botón "Run All".

---

## 📚 Créditos:

- Proyecto desarrollado como parte de un Trabajo de Fin de Master.
- Autor: Oleksandra Labenska
- Año: 2025
