# 📊 Detección de Fraude Financiero con XGBoost y Reglas Dinámicas

Este repositorio contiene el notebook desarrollado en Kaggle para detectar transacciones fraudulentas combinando técnicas de machine learning (XGBoost) con reglas dinámicas.

---

## 🚀 Enlace al notebook:

📎 https://github.com/oleksandralabenskauoc/TFM-XGBoos_Model_Reglas_Dinamicas/blob/main/tfm-xgboos-model-reglas-dinamicas.ipynb

---

## 🧠 Modelo aplicado

Se ha utilizado:
- **XGBoost** como modelo base entrenado con el dataset de Kaggle "Creadit Card Fraud Detection" (https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Reglas dinámicas** para detectar patrones adicionales de fraude

---

## 📈 Resultados:

| Modelo                        | Accuracy | Precision | Recall  | F1-Score |
|------------------------------|----------|-----------|---------|----------|
| XGBoost                      | 0.9995   | 0.866     | 0.857   | 0.861    |
| XGBoost + Reglas Dinámicas   | 0.9816   | 0.075     | 0.857   | 0.138    |

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
