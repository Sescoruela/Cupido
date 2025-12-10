# ❤️ Clasificación de Severidad Cardíaca (Multiclase)

> **Predicción de grados de enfermedad (0-4) priorizando la calidad del dato sobre la complejidad del modelo.**

## 📖 Acerca del Proyecto
Este repositorio el primer proyecto del máster de IA: no solo detectar la presencia de enfermedad cardíaca, sino clasificar su **severidad exacta** en 5 niveles.

A diferencia de la clasificación binaria, este enfoque se enfrenta a fronteras difusas entre los grados intermedios de la enfermedad, complicados por datos clínicos ruidosos y la ausencia de variables clave  en gran parte de la muestra.

## 🎯 Objetivo del Repositorio
El propósito principal de este código es demostrar el trabajo y diferentes estrategias implementadas para solucionar el problema

El flujo de trabajo documentado aquí explora:
* **El "Agujero Negro" de la Clase 2:** Análisis de por qué los modelos fallan en la severidad moderada.
* **Ingeniería de Datos:** Implementación de pipelines higiénicos (`RobustScaler`, Clipping, Imputación Híbrida) para mitigar el ruido.
* **Dilema Ingeniería vs. Complejidad:** Una comparativa técnica entre arquitecturas masivas (Stacking/Ensembles) y modelos individuales optimizados (SVM/Regresión logística).

## 💡 Filosofía: El principio de Ockham
Este proyecto defiende que, en entornos médicos con alta incertidumbre, el mejor modelo no es el que tiene más parámetros, sino el que logra generalizar mejor con la menor complejidad estructural posible, garantizando robustez ante nuevos pacientes.
