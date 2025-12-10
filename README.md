# 💘 Cupido - Predicción de Compatibilidad en Citas

## 📋 Descripción del Proyecto

Cupido es un proyecto de Machine Learning enfocado en predecir la compatibilidad entre personas en el contexto de citas. El proyecto implementa un flujo completo de análisis de datos, desde la exploración inicial hasta el desarrollo de modelos predictivos avanzados mediante técnicas de ensemble.

## 🗂️ Estructura del Proyecto

```
Cupido/
│
├── 📊 analisis, eda y graficos/
│   ├── Cupido MAIN (renombre columnas, tipo de datos y mediana_moda).ipynb
│   ├── Análisis univariante y multivariante (categóricas y cuantitativas).ipynb
│   ├── Valores nulos.ipynb
│   ├── Preprocesado avanzado + feature engineering.ipynb
│   ├── Relaciones no lineales sobre preprocesado avanzado.ipynb
│   ├── Clustering.ipynb
│   └── Graficos_IA PROJECT.ipynb
│
├── 📁 csv_s/
│   ├── csv limpio/
│   └── csv_s genericos/
│       ├── train.csv
│       ├── test.csv
│       └── sample_submission.csv
│
├── 🧪 Experimentos/
│   ├── Regresion_logistica.ipynb
│   ├── xgboost.ipynb
│   ├── Ensamble.ipynb
│   └── Ensamble2.ipynb
│
├── 🤖 modelos/
│   ├── 1. Iteraciones_modelados_Yannis.ipynb
│   ├── 2. Iteraciones_modelados_Yannis.ipynb
│   ├── 3. Iteraciones_modelados_yannis
│   ├── 4. Iteraciones_modelados_yannis
│   ├── Búsqueda de hiperparámetros
│   └── Ensamble.ipynb
│
├── 📑 presentación/
├── Cupido.ipynb
└── README.md
```

## 🔍 Metodología

### 1. Análisis Exploratorio de Datos (EDA)

El proyecto sigue un proceso sistemático de exploración de datos:

1. **Inspección General**: Análisis inicial con `describe()` y `head()`
2. **Tipos de Datos**: Identificación de variables cuantitativas y categóricas
3. **Valores Nulos**: Tratamiento mediante moda/media/mediana, KNN, MICE o MLE
4. **Duplicados**: Detección y eliminación
5. **Inspección Visual**: Análisis de distribuciones
6. **Balance de Clases**: Evaluación del equilibrio en los datos
7. **Outliers**: Detección de valores atípicos mediante boxplots
8. **Correlaciones**: Análisis de relaciones entre variables
9. **Transformaciones**: Aplicación de transformaciones logarítmicas cuando sea necesario
10. **Relaciones No Lineales**: Análisis mediante LOWESS y GAM
11. **Multicolinealidad**: Evaluación mediante VIF
12. **Análisis Multivariante**: Estudio de interacciones entre variables

### 2. Preprocesamiento

- **Feature Engineering**: Creación de nuevas variables derivadas
- **Normalización**: Estandarización mediante z-score
- **Balanceo**: Experimentación con y sin SMOTE

### 3. Modelado

El proyecto explora múltiples aproximaciones:

- **Regresión Logística**: Modelo base interpretable
- **XGBoost**: Algoritmo de gradient boosting
- **Ensemble Methods**: Combinación de múltiples modelos
- **Clustering**: Segmentación de datos para análisis adicional
- **Búsqueda de Hiperparámetros**: Optimización de modelos

## 🛠️ Tecnologías Utilizadas

- **Python**: Lenguaje principal
- **Pandas**: Manipulación de datos
- **NumPy**: Operaciones numéricas
- **Scikit-learn**: Modelado y preprocesamiento
- **XGBoost**: Algoritmos de gradient boosting
- **Matplotlib/Seaborn**: Visualización de datos
- **Jupyter Notebooks**: Desarrollo iterativo

## 🚀 Cómo Usar

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/Sescoruela/Cupido.git
   cd Cupido
   ```

2. **Instalar dependencias**:
   ```bash
   pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyter
   ```

3. **Ejecutar los notebooks**:
   - Comenzar con `Cupido MAIN` en la carpeta de análisis
   - Continuar con los notebooks de preprocesamiento
   - Explorar los modelos en la carpeta `modelos/`

## 📊 Flujo de Trabajo Recomendado

1. **Análisis**: `analisis, eda y graficos/Cupido MAIN.ipynb`
2. **Preprocesamiento**: `analisis, eda y graficos/Preprocesado avanzado + feature engineering.ipynb`
3. **Modelado**: `modelos/Iteraciones_modelados_Yannis.ipynb`
4. **Optimización**: `modelos/Búsqueda de hiperparámetros`
5. **Ensemble**: `modelos/Ensamble.ipynb`

## 📈 Resultados

Los resultados de los modelos y predicciones finales se encuentran en:
- `Experimentos/submission.csv`
- Múltiples notebooks de iteraciones en la carpeta `modelos/`

## 👥 Contribuciones

Proyecto desarrollado como parte de un análisis de Machine Learning aplicado a predicción de compatibilidad.

## 📝 Notas

- Los datos originales se encuentran en `csv_s/csv_s genericos/`
- Los datos procesados se almacenan en `csv_s/csv limpio/`
- Cada notebook está documentado con los pasos específicos del análisis

## 📧 Contacto

Para más información sobre el proyecto, consulta el repositorio o abre un issue.

---

⭐ Si este proyecto te ha sido útil, considera darle una estrella!