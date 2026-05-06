# StochasticAITechniquesClass

**Técnicas Estocásticas de Inteligencia Artificial**

  * **Profesor Magistral:** Jorge Andrés Alvarado Valencia
  * **Profesor de Seguimiento:** Sergio A. Mora Pardo
      * email: [sergioa.mora@javeriana.edu.co](mailto:sergioa.mora@javeriana.edu.co)
      * github: [sergiomorapardo](http://github.com/sergiomorapardo)

En esta asignatura se van a presentar los conceptos básicos para la aplicación de **modelos estadísticos** y **procesos estocásticos** como herramientas de solución a los problemas de **predicción**, **clasificación** y **optimización** en el campo del aprendizaje de máquina y la inteligencia artificial.

El curso se enfoca en la solución de problemas reales, resaltando ventajas, limitaciones y errores frecuentes en la aplicación de las técnicas.

-----

## Contenidos Principales

Las técnicas para discutir en el curso son:

  * Análisis de Componentes Principales (PCA).
  * Modelos de Predicción (Regresión Lineal y Regresión Logística).
  * Modelos de Clasificación (incluyendo Modelos Bayesianos).
  * Procesos Estocásticos (Cadenas de Markov y Simulación de Montecarlo).

-----

## Resultados de Aprendizaje

Al finalizar con éxito el curso usted estará en capacidad de:

  * Emplear técnicas de reducción de dimensiones para mejorar la calidad de los modelos predictivos.
  * Resolver problemas de predicción mediante regresión lineal y logística.
  * Resolver problemas de clasificación mediante modelos bayesianos.
  * Reconocer algunas aplicaciones de las cadenas de Markov en procesos de aprendizaje en inteligencia artificial.

-----

## Requisitos

  * [Python](http://www.python.org) version >= 3.7;
  * [Numpy](http://www.numpy.org), para álgebra lineal y arrays multidimensionales;
  * [Pandas](http://pandas.pydata.org/), para manipulación y análisis de datos;
  * [Scikit-learn](http://scikit-learn.org), librería de Machine Learning;
  * [Matplotlib](http://matplotlib.sf.net), para visualización;
  * [Seaborn](stanford.edu/~mwaskom/software/seaborn/), para visualización estadística.
  * [IPython](http://ipython.org), con las librerías requeridas para la interfaz de notebooks.

Una opción fácil de instalar que incluye todos estos paquetes (y más) es [Anaconda](https://www.anaconda.com/products/distribution).

-----

## Evaluación

Las estrategias de evaluación se centran en la valoración de los resultados de aprendizaje mediante dos enfoques:

### Evaluación Formativa
Compuesta por ejercicios a realizar mediante **Notebooks** en cada módulo. Su objetivo es revisar conceptos, mejorar competencias de programación y realizar análisis de resultados para la toma de decisiones.

### Evaluación Sumativa (100%)
Corrobora el logro de aprendizajes y competencias mediante las siguientes actividades:

* **(24%) Evaluación sumativa - Taller Técnicas Predictivas y Reducción de Dimensiones.**
* **(24%) Evaluación sumativa - Taller Técnicas de Clasificación.**
    * *Nota sobre Talleres:* Cada taller cuenta con tres momentos de retroalimentación: 
        1. Retroalimentación automática inicial.
        2. Guía para revisión y rediseño del modelo.
        3. Retroalimentación final del profesor y asignación de nota.
* **(12%) Evaluaciones de contenido:** Incluye tres quices (previos a las sesiones 2, 3 y 4) y una infografía (previa a la última sesión).
* **(40%) Evaluación de la actividad sincrónica intensiva - Hackatón.**

-----

## Cronograma

| Fecha | Sesión | Notebooks/Presentaciones | Ejercicios / Entregables |
| :---- | :--- | :--- | :--- |
| **Semana 1** | PCA y reducción de dimensiones | [L1: Intro PCA](Notebooks/L1_IntroPCA-3.ipynb)<br>[L2: Pipeline PCA](Notebooks/L2_pipelinePCA-2.ipynb)<br>[L3: Validación Ortogonal](Notebooks/L3_ValidationOrthogonal-2.ipynb) | Ejercicios en Notebooks |
| **Semana 2** | Regresión Lineal, Logística y Feature Selection | [L4: Regresión Lineal](Notebooks/L4_LinearRegression.ipynb) <br>[L5: Regresión Logistica](Notebooks/L5_LogisticRegression.ipynb) <br>[L6: Cross Validation & Grid Search](Notebooks/L6_CrossValidation.ipynb)| **Quiz 1** (Antes de sesión) |
| **Semana 3** | Modelos de Clasificación | [L7: Distance Measures](Notebooks/L7_DistanceMeasures.ipynb) <br> [L8: KNN](Notebooks/L8_KNN.ipynb) <br> [L9: Intro Bayesianos & CART](Notebooks/L9_NaiveBayes_CART.ipynb) | **Quiz 2** (Antes de sesión) |
| **Semana 4** | Procesos Estocásticos | [L10: Markov Chains & Monte Carlo Simulations](Notebooks/L10_MarkovChains_MonteCarloSimulations.ipynb) <br> [L11: Time Series](Notebooks/L11_TimeSeries.ipynb) <br> [L12: Multi-horizonts Forecasting](Notebooks/L12_TimeSeries_MultiHorizont.ipynb) | **Quiz 3** (Antes de sesión) |
| **Semana 5** | Hackatón | Presentación Hackatón | Hackatón |
| **Semana 6** | Cierre del Curso | - | **Infografía** (Antes de sesión) |

-----

## Recursos Bibliográficos

### Fundamentos (Reducción de dimensionalidad, Regresión y Clasificación)

  * Hastie et al. The elements of statistical learning. Springer, 2017.
  * Yan, X., Su, X. Linear Regression Analysis: Theory and Computing, World Scientific, 2009.

### Aplicaciones Computacionales (ML)

  * Kane, F. Hands-On Data Science and Python Machine Learning. Packt Publishing, 2017.
  * Hearty, J. Advanced Machine Learning with Python. Packt Publishing, 2016.
  * Hackeling, G., Mastering Machine Learning with Scikit-learn. Packt Publishing, 2017.
  * Murphy, K.P. Probabilistic Machine Learning: An Introduction. MIT Press, 2021.

### Fundamentos (Procesos de Markov y Simulación)

  * Cappé, O., Moulines, E., Rydén, T. Inference in Hidden Markov Models. Springer, 2005.
  * Li, S. Markov Random Field Modeling in Image Analysis. Springer, 2009.
  * Ibe, Oliver. Markov Processes for Stochastic Modeling, Elsevier, 2013.
  * Prescott, J., Monte Carlo Simulations: Advanced Techniques, BVR, 2016.

### Complementario (Probabilidad y Estadística)

  * Walpole, R. Probabilidad y estadística para ingeniería y ciencias. Pearson Educación 9a edición, México, 2012.
