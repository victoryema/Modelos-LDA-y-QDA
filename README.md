# Modelo Predictivo de Morosidad en Clientes Bancarios

## Descripción
Este proyecto implementa modelos de Machine Learning, específicamente Linear Discriminant Analysis (LDA) y Quadratic Discriminant Analysis (QDA), para predecir la morosidad de clientes bancarios basándose en atributos financieros.

## Instrucciones de Uso
- Clona este repositorio en tu máquina local.
- Asegúrate de tener las dependencias instaladas ejecutando pip install -r requirements.txt.
- Abre el notebook Jupyter Morosidad_Clientes.ipynb para explorar el análisis y ejecutar los modelos.

## Dependencias
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn (para el manejo de desbalance en las clases)
- jupyter (para ejecutar el notebook)

## Estructura del Proyecto
- Morosidad_Clientes.ipynb: Notebook principal con el código y análisis.
- default_credit.csv: Conjunto de datos utilizado.
- README.md: Documentación del proyecto.
- requirements.txt: Lista de dependencias y versiones.

## Conjunto de Datos
Se utiliza el archivo default_credit.csv, que contiene información sobre ingresos, saldo en cuentas de crédito, y el estado de morosidad de los clientes.

## Análisis Exploratorio de Datos (EDA)
Se realiza un análisis detallado, incluyendo visualizaciones sobre ingresos, saldos, distribución de clases, etc. Los hallazgos clave se encuentran documentados en el notebook.

## Modelos Utilizados
- Modelo LDA sin hiperparámetros.
- Modelo LDA con información exógena (priors modificados).
- Modelo LDA con SMOTE (oversampling).
- Modelo QDA con datos aumentados artificialmente.

## Resultados
Se proporcionan detalles sobre el rendimiento de cada modelo, destacando fortalezas y debilidades en la predicción de morosidad.

## Autor
Víctor Urra

## Agradecimientos
Agradezco a las bibliotecas de código abierto utilizadas.
