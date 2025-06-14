#  Detección de Fraude en Transacciones Financieras con Aprendizaje Automático

Facultad de Ciencias – UNAM  
Temas Selectos en Biomatemáticas  
Autor: Brian Eduardo Fuentes Hernández

---

## Resumen del Proyecto

Este proyecto aborda la detección de transacciones financieras fraudulentas mediante técnicas de aprendizaje automático, específicamente regresión logística. Se utilizaron dos bases de datos reales: una de Kaggle con transacciones con tarjeta de crédito y otra desde GitHub con información de pagos digitales.

Se realizaron análisis exploratorios, procesamiento de datos, normalización, codificación de variables y estrategias para mitigar el desbalance de clases. Los modelos se evaluaron utilizando métricas como precisión, recall, F1-score y matriz de confusión.

---

## ⚙️ ¿Cómo Funciona?

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
