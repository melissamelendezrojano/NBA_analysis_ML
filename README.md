# NBA_analysis_ML
Analysis and prediction about the winner of NBA.

🇬🇧

In the NBA, where every pass, shot and defense counts, machine learning becomes the invisible sixth man, accurately analyzing data to discover patterns that boost team performance, taking the game into a new strategic era. 

**Goal**: Create machine learning models to determine if the team will win the next game. 

**Method**: Web scraping technique for obtaining data from the web https://www.basketball-reference.com, exploratory data analysis (EDA) for the preparation and visualization of initial data, creation of variables from the initial ones for the enrichment of the database, a difference is made between a database of original variables and a database of original variables plus new variables. The time series databases are divided into training and test, Principal Component Analysis (PCA) technique is applied as a dimension reduction technique to each of the databases and the modeling techniques of Ridge Regression, Logistic Regression, XGBoost (Extreme Gradient Boosting), Random Forest and Support Vector Machines (SVM) are applied. 

**Results**: The SVM model demonstrated the highest accuracy and the highest AUC (60.02% and 0.6519, respectively) when considering the expansion of variables in the database. This study establishes a foundation for employing data as a key tool in improving the performance of NBA teams, offering the possibility of extrapolating these practices to other sports that also use collected data.

**Keywords**: Basketball, NBA, web scraping, requests, BeautifulSoup, PCA, Ridge Regression, Logistic Regression, XGBoost, Random Forest, SVM, accuracy, AUC. 

🇪🇸

En la NBA, donde cada pase, tiro y defensa cuenta, el aprendizaje automático se convierte en el sexto hombre invisible, analizando datos con precisión para descubrir patrones que potencian el rendimiento de rendimiento de los equipos, llevando el juego a una nueva era estratégica. 

**Objetivo**: Crear modelos de aprendizaje automático para determinar si el equipo ganará el siguiente partido. 

**Método**: Técnica de web scraping para la obtención de datos que provienen de la web https://www.basketball-reference.com, análisis exploratorio de datos (EDA) para la preparación y visualización de datos iniciales, creación de variables a partir de las iniciales para el enriquecimiento de la base de datos, se diferencia entre base de datos de variables originales y base de datos de variables originales más variables nuevas. Las bases de datos de series temporales son divididas en entrenamiento y prueba, se aplica la técnica de análisis de componentes principales como técnica de reducción de dimensiones a cada una de las bases de datos y se aplican las técnicas de modelado de regresión de crestas (Ridge Regression), Regresión Logística, XGBoost (Extreme Gradient Boosting), Random Forest y máquinas de vectores soporte (SVM). 

**Resultados**: El modelo SVM ha demostrado la máxima precisión y el AUC más elevado (60,02% y 0.6519 respectivamente) al considerar la ampliación de variables en la base de datos. Este estudio establece un fundamento para emplear datos como una herramienta clave en la mejora del rendimiento de los equipos de la NBA, ofreciendo la posibilidad de extrapolar estas prácticas a otros deportes que también utilicen datos recopilados.

**Palabras clave**: Baloncesto, NBA, web scraping, requests, BeautifulSoup, PCA, Ridge Regression, Regresión Logística, XGBoost, Random Forest, SVM, accuracy, AUC.
