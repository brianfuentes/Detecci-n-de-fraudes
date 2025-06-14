

Este proyecto explora la detección de transacciones fraudulentas utilizando algoritmos de aprendizaje automático, con énfasis en la **regresión logística**. Se analizaron dos conjuntos de datos reales (Kaggle y GitHub), y se aplicaron técnicas de preprocesamiento, balanceo de clases y evaluación de modelos para obtener un sistema eficaz de clasificación binaria.

---

Objetivo

Implementar una solución basada en **regresión logística** que permita detectar patrones de fraude en transacciones financieras mediante:

- Análisis exploratorio de datos (EDA)
- Preprocesamiento y normalización
- Modelado supervisado (scikit-learn)
- Evaluación mediante métricas como **accuracy, recall y F1-score**

## 
 Tecnologías usadas

- Python 3.11
- Scikit-learn
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

## Conjuntos de datos

1. **Kaggle - Credit Card Fraud Detection**  
   [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

2. **GitHub - Payment Fraud Dataset**  
   [https://github.com/amankharwal/Website-data/blob/main/payment_fraud.csv](https://github.com/amankharwal/Website-data/blob/main/payment_fraud.csv)

---

##  Principales resultados

- El modelo logró un **F1-score > 0.74** en la base de Kaggle al aplicar técnicas de balanceo.
- En el segundo conjunto, el modelo mejoró drásticamente al usar `class_weight='balanced'` y submuestreo.
- Se observó la importancia de **tratar el desbalance de clases** para evitar resultados engañosos.

---

##  Anexo: Recursos de apoyo

- [Kaggle – Credit Card Fraud Detection by Khwaish Saxena](https://www.kaggle.com/code/khwaishsaxena/credit-card-fraud-detection#Model-Evaluation)
- [Blog de Aman Kharwal – Fraud Detection](https://amanxai.com/2020/08/04/fraud-detection-with-machine-learning/)

---

##  Autor

**Brian Eduardo Fuentes Hernández**  
Facultad de Ciencias – UNAM  
Correo: [brianfuentes106@ciencias.unam.mx](mailto:brianfuentes106@ciencias.unam.mx)  
Fecha: 13 de junio de 2025
