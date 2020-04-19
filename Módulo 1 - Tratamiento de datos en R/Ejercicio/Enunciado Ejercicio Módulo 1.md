# Ejercicio Módulo 1: Tratamiento de datos en R

Desde 2008, los huéspedes y anfitriones han utilizado Airbnb para ampliar las posibilidades de viaje y presentar una forma única y personalizada de experimentar el mundo. El conjunto de datos airbnb_NYC_2019.csv describe la actividad de listado y las métricas en Nueva York para 2019.
Este dataset proviene con la siguiente descripción de columnas:



*	`id`: listing ID  
*	`name`: name of the listing  
*	`host_id`: host ID
*	`host_name`: name of the host
*	`neighbourhood_group`: location
*	`neighbourhood`: area
*	`latitude`: latitude coordinates
*	`longitude`: longitude coordinates
*	`room_type`: listing space type
*	`price`: price in dollars
*	`minimum_nights`: amount of nights minimum
*	`number_of_reviews`: number of reviews
*	`last_review`: latest review
*	`reviews_per_month`: number of reviews per month
*	`calculated_host_listings_count`: amount of listing per host
*	`availability_365`: number of days when listing is available for booking

## Se pide
Realiza un análisis descriptivo del conjunto de datos y trata de extraer conclusiones interesantes de estos.
Aqui tienes algunas ideas como ejemplos:

*	Puedes comenzar realizando un análisis de los valores faltantes ó valores extremos sin sentido, y tomar las decisiones de imputación que veas convenientes.
*	Puedes realizar un resumen estadístico básico de las variables numéricas y no numéricas.
*	Calcular una tabla con el precio máximo, medio y mínimo según el neighbourhood y neighbourhood_group.
*	Comprobar la columna calculated_host_listings_count contando el número de apariciones de cada anfitrión y enfrentándolo contra esta columna.
*	Realizar un ranking con el top 10 anfitriones más populares de Airbnb (con más apariciones en el conjunto de datos).
*	Realizar un ranking con el top 10 neighbourhood con más anuncios. Construye el ranking para poder ver también el neighbourhood_group al que pertenece cada uno.
*	Puedes dibujar las distribuciones de cada variable.
*	Puedes dibujar gráficas de dispersión entre parejas de variables que a priori puedan aportar algún resultado interesante.
*	Puedes dibujar en un gráfico de barras la cantidad de anuncios según el grupo de barrio al que pertenece.
*	Analizar el mínimo número de noches que las personas se quedan según el tipo de habitación, con una gráfica para cada tipo.
*	Analizar la distribución de precios según el grupo de barrios.
*	Analizar correlaciones entre variables

## ARCHIVOS A ENTREGAR
Código en archivo .R y pequeño documento explicativo en formato pdf o word.