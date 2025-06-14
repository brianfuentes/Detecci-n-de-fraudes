#  Detección de Fraude en Transacciones Financieras con Aprendizaje Automático

Facultad de Ciencias – UNAM  
Temas Selectos en Biomatemáticas  
Autor: Brian Eduardo Fuentes Hernández

---

## Resumen del Proyecto

Este proyecto aborda la detección de transacciones financieras fraudulentas mediante técnicas de aprendizaje automático, específicamente regresión logística. Se utilizaron dos bases de datos reales: una de Kaggle con transacciones con tarjeta de crédito y otra desde GitHub con información de pagos digitales.

Se realizaron análisis exploratorios, procesamiento de datos, normalización, codificación de variables y estrategias para mitigar el desbalance de clases. Los modelos se evaluaron utilizando métricas como precisión, recall, F1-score y matriz de confusión.

---

##  ¿Cómo Funciona?

El flujo del proyecto consiste en:

1. Carga y exploración de los datos (`Data/`)
2. Preprocesamiento: eliminación de valores faltantes, escalamiento, codificación.
3. Aplicación de regresión logística con `scikit-learn`.
4. Evaluación del modelo con métricas de clasificación binaria.
5. Visualización de resultados y comparación entre bases de datos.

---

##  Estructura de Archivos

 Data/           → Bases de datos (.csv)
 
 SRC/            → Código fuente (scripts, notebooks principales)
 
 notebooks/      → Notebook completo 
 
 imagenes/       → Capturas de pantalla, gráficas y visualizaciones
 
 doc/            → Documentación formal (PDF de la práctica)
 
 requirements.txt → Lista de librerías necesarias para correr el proyecto
 
 README.md        → Descripción general del proyecto


---

##  Requisitos

Para correr este proyecto se requiere Python 3.10+ y las siguientes librerías:

pandas==2.2.2  
numpy==1.26.4  
matplotlib==3.8.4  
seaborn==0.13.2  
scikit-learn==1.4.2  
jupyter==1.0.0


---

##  Instrucciones de Configuración
##  Instrucciones para replicar

1. Clona este repositorio:

```bash
[https://github.com/brianfuentes/Transtorno-de-sue-o-.git](https://github.com/brianfuentes/Detecci-n-de-fraudes.git)
```

2. Ejecuta los notebooks:

```bash
jupyter notebook
```

3. Explora el notebook principal: `Proyecto final.ipynb`


##  Referencias

1. IBM Corporation. “¿Qué es la detección de fraude?”
   Disponible en: [https://www.ibm.com/mx-es/topics/fraud-detection](https://www.ibm.com/mx-es/topics/fraud-detection)
   Consultado el 13 de junio de 2025.

2. Economipedia. “Modelo de regresión – qué es, definición y concepto.”
   Disponible en: [https://economipedia.com/definiciones/modelo-de-regresion.html](https://economipedia.com/definiciones/modelo-de-regresion.html)
   Consultado el 13 de junio de 2025.

3. IBM Corporation. “¿Qué es la regresión logística?”
   Disponible en: [https://www.ibm.com/mx-es/think/topics/logistic-regression](https://www.ibm.com/mx-es/think/topics/logistic-regression)
   Consultado el 13 de junio de 2025.

4. Kaggle. “Credit Card Fraud Detection Dataset.”
   Disponible en: [https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)
   Consultado el 13 de junio de 2025.

5. Kharwal, Aman. “Fraud Detection with Machine Learning.”
   Disponible en: [https://amanxai.com/2020/08/04/fraud-detection-with-machine-learning/](https://amanxai.com/2020/08/04/fraud-detection-with-machine-learning/)
   Consultado el 13 de junio de 2025.

---
  
