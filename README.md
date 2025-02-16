# PracticaNLP

Proyecto NLP Análisis de Sentimiento reviews de productos de Amazon

# Análisis de Sentimientos en Reseñas de Música 🎵

Este proyecto tiene como objetivo analizar el sentimiento de reseñas de música utilizando técnicas de Procesamiento de Lenguaje Natural (NLP). Se implementan y comparan varios modelos de clasificación, incluyendo **Regresión Logística** y **BERT**, para predecir si una reseña es positiva o negativa.

## Descripción del Proyecto

### Español
El proyecto utiliza un conjunto de datos de reseñas de música de Amazon. El objetivo es clasificar las reseñas como positivas (4 o 5 estrellas) o negativas (1, 2 o 3 estrellas). Se implementan varios modelos de machine learning, incluyendo:
- **Regresión Logística**
- **BERT (Bidirectional Encoder Representations from Transformers)**

Se realiza un análisis exploratorio de los datos, preprocesamiento de texto, entrenamiento de modelos y evaluación de su rendimiento utilizando métricas como precisión, recall, F1-score, matriz de confusión y curva ROC.

### English
The project uses a dataset of music reviews from Amazon. The goal is to classify reviews as positive (4 or 5 stars) or negative (1, 2, or 3 stars). Several machine learning models are implemented, including:
- **Logistic Regression**
- **BERT (Bidirectional Encoder Representations from Transformers)**

An exploratory data analysis, text preprocessing, model training, and performance evaluation are conducted using metrics such as precision, recall, F1-score, confusion matrix, and ROC curve.

---

## Tecnologías Utilizadas

### Español
- **Lenguaje de Programación**: Python
- **Librerías Principales**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn` (análisis y visualización de datos)
  - `nltk`, `spacy` (procesamiento de texto)
  - `scikit-learn` (modelos de machine learning)
  - `transformers` (BERT)
  - `torch` (PyTorch para BERT)
- **Herramientas**:
  - Jupyter Notebook
  - Git y GitHub

### English
- **Programming Language**: Python
- **Main Libraries**:
  - `pandas`, `numpy`, `matplotlib`, `seaborn` (data analysis and visualization)
  - `nltk`, `spacy` (text processing)
  - `scikit-learn` (machine learning models)
  - `transformers` (BERT)
  - `torch` (PyTorch for BERT)
- **Tools**:
  - Jupyter Notebook
  - Git and GitHub

## Resultados

### Español
- **BERT** obtuvo un rendimiento superior con un **AUC de 0.99** y una **matriz de confusión casi perfecta**.
- **Regresión Logística** tuvo un rendimiento decente, con un **AUC de 0.94**, pero inferior a BERT.

### English
- **BERT** achieved superior performance with an **AUC of 0.99** and an **almost perfect confusion matrix**.
- **Logistic Regression** had decent performance, with an **AUC of 0.94**, but inferior to BERT.
---

## Conclusiones

### Español
- **BERT** es el modelo más efectivo para esta tarea, gracias a su capacidad para capturar el contexto semántico del texto.
- La **Regresión Logística** es una opción viable si los recursos computacionales son limitados, pero no igualan el rendimiento de BERT.
- Se recomienda el uso de BERT para tareas donde la precisión es crítica.

### English
- **BERT** is the most effective model for this task, thanks to its ability to capture the semantic context of the text.
- **Logistic Regression** is viable option if computational resources are limited, but they do not match BERT's performance.
- BERT is recommended for tasks where precision is critical.

---

Contribuciones
Español

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

    Haz un fork del repositorio.

    Crea una rama con tu nueva funcionalidad (git checkout -b nueva-funcionalidad).

    Realiza tus cambios y haz commit (git commit -m 'Añade nueva funcionalidad').

    Haz push a la rama (git push origin nueva-funcionalidad).

    Abre un Pull Request.

English

Contributions are welcome! If you want to improve this project, follow these steps:

    Fork the repository.

    Create a branch for your new feature (git checkout -b new-feature).

    Make your changes and commit them (git commit -m 'Add new feature').

    Push to the branch (git push origin new-feature).

    Open a Pull Request.

¡Gracias por visitar este repositorio! 🚀
