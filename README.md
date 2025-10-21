# EDA
Exploratory Data Analysis (EDA)

Este proyecto tiene como objetivo realizar un análisis exploratorio de datos (EDA) utilizando Python.
El propósito del EDA es examinar los datos para descubrir patrones, identificar valores atípicos, analizar relaciones entre variables y detectar posibles problemas de calidad, como datos faltantes o errores, antes de aplicar técnicas analíticas o modelos predictivos.

El análisis se desarrolla sobre un conjunto de datos que contiene información salarial de empleados públicos.
A lo largo del proceso se implementan diversas técnicas estadísticas y visuales para comprender la estructura y distribución de las variables, así como para evaluar la calidad de la información disponible.

## Objetivos específicos

Explorar la estructura del conjunto de datos e identificar los tipos de variables.

Detectar valores faltantes, inconsistencias o datos no numéricos.

Analizar la distribución de los salarios y sus componentes principales.

Identificar valores atípicos y su posible impacto en los resultados.

Estudiar las variaciones del salario promedio a lo largo de los años.

Determinar los cargos con mayores niveles de remuneración.

### Herramientas utilizadas

El proyecto fue desarrollado en Visual Studio Code con el uso de las siguientes librerías de Python:

Pandas: para la manipulación y limpieza de datos.

NumPy: para operaciones numéricas y manejo de valores nulos.

Matplotlib: para la generación de gráficos y visualizaciones.

Seaborn: para el análisis visual y la presentación de tendencias.

### Metodología

Importación de librerías y carga de datos:
Se cargó el archivo Salaries.csv y se realizó una inspección inicial del contenido, las columnas y los tipos de datos.

### Análisis preliminar:
Se revisó la estructura del conjunto de datos mediante las funciones head(), info() y describe(), con el fin de identificar las características generales de las variables.

### Visualización inicial:
Se graficó la distribución porcentual de los salarios totales y se calculó el salario promedio por año para observar su evolución temporal.

### Identificación de cargos mejor remunerados:
Se elaboró un ranking de los diez cargos con mayores salarios promedio, evidenciando la concentración de ingresos en los niveles directivos.

### Limpieza de datos:
Se convirtieron a valores numéricos las columnas con datos inconsistentes, reemplazando errores por valores nulos (NaN).
Además, se eliminaron valores negativos y se verificó nuevamente la integridad de las variables salariales.

### Análisis de componentes del salario:
Se calcularon los promedios de los principales componentes (BasePay, OvertimePay, OtherPay y Benefits) y se visualizaron mediante gráficos de barras.

### Detección de valores atípicos:
Se identificaron observaciones con salarios totales superiores al percentil 99, asociados a posiciones de alta dirección.

# Resultados principales

La mayoría de los salarios se concentran en el rango de 50 000 a 100 000 USD.

Los pagos por horas extra representan en promedio un 15 % del total.

Se identificaron valores atípicos con salarios superiores a 300 000 USD, posiblemente pertenecientes a cargos directivos.

Los salarios promedio mostraron un leve crecimiento entre 2011 y 2014, sin variaciones significativas.

Los ingresos más altos corresponden a posiciones de liderazgo dentro de instituciones públicas, como el General Manager – Metropolitan Transit Authority y el Chief Investment Officer.

# Conclusiones

El análisis exploratorio permitió evidenciar que los salarios en la ciudad de San Francisco presentan una marcada concentración en los niveles jerárquicos más altos, mientras que la mayoría de los trabajadores se ubica en un rango salarial medio.
Asimismo, se constató la necesidad de limpiar y estandarizar los datos antes de aplicar métodos analíticos más complejos, debido a la presencia de valores inconsistentes y no numéricos en las variables de pago
