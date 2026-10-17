# Práctica 2: Preprocesamiento de Datos

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/xErnyx/Practica_2_Preprocesamiento_de_Datos/blob/main/Practica_2_Preprocesamiento_de_Datos.ipynb)

**Universidad Politécnica Salesiana - Sede Sur**
**Asignatura:** Inteligencia Artificial
**Carrera:** Computación
**Docente:** Ing. Rodrigo Tufiño
**Autor:** Juan D. Figueroa

## Descripción

Práctica de laboratorio sobre preprocesamiento de datos: identificación de instancias, atributos, features y labels, clasificación de variables y escalado de datos con Min-Max, Z-Score y Robust Scaler. El notebook incluye el fundamento teórico, el código paso a paso y la respuesta a cada pregunta de la guía.

## Objetivos

- Identificar instancias, atributos, features y labels en un dataset real.
- Clasificar variables según su tipo.
- Aplicar e interpretar las transformaciones Min-Max, Z-Score y Robust Scaler.
- Argumentar cuándo usar cada técnica de escalado según el contexto del dataset.
- Probar diferentes librerías (NumPy, pandas y scikit-learn) para transformar variables.

## Contenido

| Fase | Tema | Herramientas |
|------|------|--------------|
| 1 | Anatomía de un dataset (dataset de estudiantes) | pandas |
| 2 | Escalado desde cero (Min-Max y Z-Score) | NumPy, matplotlib |
| 3 | Dataset real: Palmer Penguins | pandas, scipy |
| 4 | Escalado con sklearn, división train/test y RobustScaler | scikit-learn |

## Requisitos

- Cuenta de Google para usar [Google Colab](https://colab.research.google.com/).
- Librerías: `numpy`, `pandas`, `scikit-learn`, `matplotlib` y `scipy` (ya vienen instaladas en Colab).

## Cómo ejecutarlo

1. Abre el notebook con el botón **Open in Colab**.
2. Ejecuta todas las celdas en orden (*Entorno de ejecución > Ejecutar todo*).
3. El dataset Palmer Penguins se descarga automáticamente desde Hugging Face, por lo que se necesita conexión a internet.

## Referencias

- Gorman, K. B., Williams, T. D., & Fraser, W. R. (2014). Ecological sexual dimorphism and environmental variability within a community of Antarctic penguins (Genus *Pygoscelis*). *PLOS ONE, 9*(3), e90081.
- Pedregosa, F., et al. (2011). Scikit-learn: Machine learning in Python. *Journal of Machine Learning Research, 12*, 2825–2830.
- SIH. (2024). *Palmer penguins* [Conjunto de datos]. Hugging Face. https://huggingface.co/datasets/SIH/palmer-penguins
- Tufiño, R. (2026). *Guía de práctica de laboratorio N.° 01: Preprocesamiento de datos*. Universidad Salesiana del Ecuador - Sede Sur.
