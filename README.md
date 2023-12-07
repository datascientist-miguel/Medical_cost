# ----------------------------- English ---------------------------
# Medical Costs Analysis and Prediction

This project focuses on exploratory analysis and prediction of medical costs using data science techniques and regression models.

## Project Description

The main objective of this project is to understand the relationships between demographic variables, lifestyle habits, and medical costs. It explores data containing information about age, gender, body mass index (BMI), number of children, smoking habit, region, and medical costs.

## Project Structure

- **Importing Necessary Libraries and Loading Data**: Necessary libraries are imported, and the data is loaded from a CSV file.
- **Analysis of Numeric Variables**: Statistical and graphical analysis of numeric variables to understand their distribution and relationship with medical costs.
- **Analysis of Categorical Variables**: Conducts an analysis of categorical variables using bar charts.
- **Correlation Analysis**: Explores correlation between variables and identifies those with the most influence on medical costs.
- **Data Preparation**: Prepares data for modeling, including categorical variable transformation and splitting into training and testing sets.
- **Model Training**: Employs regression models (Linear Regression, RandomForestRegressor, and GradientBoostingRegressor) to predict medical costs.
- **Hyperparameter Optimization**: Conducts grid searches to find the best hyperparameters for the selected models.
- **Evaluation of Selected Model**: Evaluates and visualizes the performance of the selected best-performing model (GradientBoostingRegressor).
- **Conclusions**: Summarizes the conclusions obtained from the analysis and prediction of medical costs.

## Usage

To use this project:

1. Clone the repository to your local machine.
2. Ensure you have the required libraries. You can install them using `pip install -r requirements.txt`.
3. Run the code step-by-step as described in the Jupyter Notebook or provided script.

## Technologies Used

- Python
- Pandas, NumPy, Matplotlib, Seaborn for data analysis and visualization
- Scikit-learn for modeling and evaluating regression models
- Jupyter Notebook for development and presentation of the analysis

## Results

The GradientBoostingRegressor model showed the best performance with an MSE of approximately 19,841,789.80 and an R2 Score of around 0.872. The analysis highlighted the importance of BMI, smoking habit, and age in predicting medical costs.

## Contributions

Feel free to contribute to the project by opening issues, suggesting new features or improvements, and submitting pull requests.

## License

This project is licensed under the MIT License. For more details, check the LICENSE file.


# ----------------------------- Español ---------------------------
# Análisis y Predicción de Costos Médicos

Este proyecto se centra en el análisis exploratorio y la predicción de costos médicos utilizando técnicas de ciencia de datos y modelos de regresión.

## Descripción del Proyecto

El objetivo principal de este proyecto es comprender las relaciones entre variables demográficas y hábitos de vida con los costos médicos. Se exploran datos de un conjunto que contiene información sobre edad, género, índice de masa corporal (BMI), número de hijos, hábito de fumar, región y costos médicos.

## Estructura del Proyecto

- **Importación de librerías y carga de datos**: Se cargan las bibliotecas necesarias y se importan los datos de un archivo CSV.
- **Análisis de Variables Numéricas**: Se realiza un análisis estadístico y gráfico de las variables numéricas para entender su distribución y relación con los costos médicos.
- **Análisis de Variables Categóricas**: Se lleva a cabo un análisis de variables categóricas mediante gráficos de barras.
- **Análisis de Correlación**: Se explora la correlación entre las variables y se identifican las que tienen mayor influencia en los costos médicos.
- **Preparación de los Datos**: Se preparan los datos para el modelado, incluyendo la transformación de variables categóricas y la división en conjuntos de entrenamiento y prueba.
- **Entrenamiento de Modelos**: Se emplean modelos de regresión (Linear Regression, RandomForestRegressor y GradientBoostingRegressor) para predecir los costos médicos.
- **Optimización de Hiperparámetros**: Se realizan búsquedas en cuadrícula para encontrar los mejores hiperparámetros de los modelos seleccionados.
- **Evaluación del Modelo Seleccionado**: Se evalúa y visualiza el rendimiento del mejor modelo seleccionado (GradientBoostingRegressor).
- **Conclusiones**: Se resumen las conclusiones obtenidas del análisis y la predicción de costos médicos.

## Uso del Proyecto

Para utilizar este proyecto:

1. Clona el repositorio en tu máquina local.
2. Asegúrate de tener las bibliotecas requeridas. Puedes instalarlas usando `pip install -r requirements.txt`.
3. Ejecuta el código paso a paso según se describe en el Jupyter Notebook o script proporcionado.

## Tecnologías Utilizadas

- Python
- Pandas, NumPy, Matplotlib, Seaborn para análisis y visualización de datos
- Scikit-learn para el modelado y evaluación de modelos de regresión
- Jupyter Notebook para el desarrollo y presentación del análisis

## Resultados

El modelo GradientBoostingRegressor mostró el mejor rendimiento con un MSE de aproximadamente 19,841,789.80 y un R2 Score de alrededor de 0.872. El análisis destacó la importancia del BMI, el hábito de fumar y la edad en la predicción de los costos médicos.

## Contribuciones

Siéntete libre de contribuir al proyecto abriendo issues, proponiendo nuevas funcionalidades o mejoras, y presentando pull requests.

## Licencia

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.
