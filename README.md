# Proyecto curso machine learning - Base de datos Obesidad
Presentado por: Laura Cuestas y Carlos Piñeros
Profesor: Isaac Zainea

En el presente trabajo se busca aplicar distintos modelos de aprendizaje supervisado y no supervisado sobre la base "Estimation of obseity level based on eating habits and physical condition" obtenida del repositorio UCI Machine Learning, teniendo como objetivo la variable de niveles de obesidad en personas de Colombia, México y Perú, de acuerdo con los hábitos alimenticios y condiciones físicas. 

Este trabajo se desarrolló de la siguiente manera:
- exploración de los datos: En el cuaderno **1.exploracion.ipynb** se desarrolla un análisis descriptivo inicial sobre los datos, haciendo hincapié en la revisión de las variables cuantitativas del dataset. Una vez realizado esto, mediante aprendizaje no supervisado se busca ver patrones de agrupación en la información.
- Modelos supervisados: En el cuaderno **2. Modelos_supervisados.ipynb** se realiza la tranformación de toda la base de datos mediante pipelines para aplicar modelos de clasificación para la variable niveles de obesidad del dataset. Para este punto se aplican modelos: Logístico, Naive Bayes, Árbol de decisión, Random forest y redes neuronales, con el fin de escoger el mejor modelo mediante el accuracy.

- Modelos supervisado (opcional): En el cuaderno **3. Modelos_supervisados_opcional.ipynb** se realiza el mismo proceso del punto anterior con la particularidad de tomar la variable objetivo de forma binaria, es decir: 0 si el individuo no presenta ningún nivel de obesidad, 1 si el individuo presenta algún nivel de obesidad. Para este punto se aplican modelos: Logístico, Naive Bayes, Árbol de decisión, Random forest y redes neuronales, con el fin de escoger el mejor modelo mediante el accuracy.

- Conclusiones: Se presentan las conclusiones finales sobre los resultados obtenidos de los distintos modelos.
