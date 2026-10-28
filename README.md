# StochasticAITechniquesClass

**Técnicas Estocásticas de Inteligencia Artificial**

  * **Profesor Magistral:** Juan Carlos Garcia Diaz
      * email: [jgarcia.d@javeriana.edu.co](mailto:jgarcia.d@javeriana.edu.co)
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

**Pendiente de confirmación para el periodo 2630:** el siguiente esquema proviene del README anterior. El cronograma del Word incluye un juego serio, pero no especifica porcentajes, quices ni infografía.

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

La distribución de temas y las fechas siguen el documento **TEIA_cronograma 2630**. Los notebooks del repositorio se asignan por tema; su numeración y sus casos prácticos pueden diferir de los materiales de la plataforma. La hackatón se ubica provisionalmente en la **semana 5**, con fechas y horarios por confirmar.

| Semana | Tema y encuentro sincrónico | Notebooks del repositorio | Actividades y fechas límite |
| :--- | :--- | :--- | :--- |
| **1** | Presentación y reducción de dimensiones<br>**28/10/2026** | [L1: Introducción a PCA](Notebooks/L1_IntroPCA-3.ipynb)<br>[L2: Pipeline con PCA](Notebooks/L2_pipelinePCA-2.ipynb)<br>[L3: Validación de ortogonalidad](Notebooks/L3_ValidationOrthogonal-2.ipynb) | Material fundamental: **27/10**.<br>Presentación de la asignatura, prácticas y foro: **30/10**.<br>Taller formativo de PCA: **01/11**. |
| **2** | Regresión lineal, selección de variables y regularización<br>**04/11/2026** | [L4: Regresión lineal y regularización](Notebooks/L4_LinearRegression.ipynb) — incluye validación cruzada y búsqueda de hiperparámetros para regresión | Material fundamental: **03/11**.<br>Prácticas de regresión lineal y regularización y foro: **06/11**. |
| **3** | Regresión logística y evaluación de modelos predictivos<br>**11/11/2026** | [L5: Regresión logística](Notebooks/L5_LogisticRegression.ipynb)<br>[L6: Validación cruzada y optimización de modelos](Notebooks/L6_CrossValidation.ipynb) — después de L5; ejemplos de clasificación, estrategias de partición, búsqueda de hiperparámetros y prevención de fuga de información | Material fundamental: **10/11**.<br>Prácticas de regresión logística y clasificación: **13/11**.<br>**Taller sumativo de modelos predictivos: 15/11**. |
| **4** | Clasificación con vecinos cercanos y medidas de distancia<br>**18/11/2026** | [L7: Medidas de distancia](Notebooks/L7_DistanceMeasures.ipynb)<br>[L8: KNN](Notebooks/L8_KNN.ipynb) | Material fundamental: **17/11**.<br>Práctica de KNN y foro: **20/11**. |
| **5** | Clasificación bayesiana y árboles de decisión<br>**25/11/2026** | [L9: Naive Bayes y CART](Notebooks/L9_NaiveBayes_CART.ipynb) — sección de ensambles como ampliación<br>[L11: Series de tiempo](Notebooks/L11_TimeSeries.ipynb)\*<br>[L12: Pronóstico a múltiples horizontes](Notebooks/L12_TimeSeries_MultiHorizont.ipynb)\*<br>[L13: Isolation Forest y reglas de negocio](Notebooks/L13_iforest_heristics.ipynb)\* | Material fundamental: **24/11**.<br>Prácticas de clasificación y foro: **27/11**.<br>**Taller sumativo de modelos de clasificación: 29/11**. |
| **5 — provisional** | Hackatón<br>Fechas y horarios por confirmar | Material del caso de la hackatón. | Preparación del caso; entendimiento del negocio; preparación de datos y modelado; evaluación y presentación de resultados. |
| **6** | Procesos estocásticos: cadenas de Markov y simulación de Monte Carlo<br>**02/12/2026** | [L10: Cadenas de Markov y simulación de Monte Carlo](Notebooks/L10_MarkovChains_MonteCarloSimulations.ipynb) | Material fundamental: **01/12**.<br>Práctica de Markov y foro: **04/12**.<br>Evaluación formativa de Monte Carlo y **juego serio: 06/12**. |

\* L11, L12 y L13 pueden utilizarse como material de apoyo para la hackatón, según las necesidades del caso.

Todas las fechas corresponden a **2026**. Las lecturas y actividades detalladas de la plataforma se consultan en el cronograma del curso; los enlaces anteriores organizan el material de apoyo del repositorio.

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
