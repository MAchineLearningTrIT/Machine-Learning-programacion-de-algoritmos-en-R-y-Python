# Ejercicio Módulo 0: Implementación de un sistema de recomendación de contenidos 

Imagina que tu empresa dispone de una plataforma con servicios de reproducción de vídeos en streaming (similar a Netflix), y empiezas a recopilar datos de los usuarios. Por una parte, te interesa conocer a tus usuarios: su perfil, qué visualizan, cómo lo hacen, etc. Por otro lado, decides implementar un sistema recomendador, que sugiere contenidos personalizados, acordes a los gustos y experiencias previas del usuario en la plataforma. Para llevar a cabo este caso práctico se facilitará un conjunto de datos y se enunciarán una serie de cuestiones a resolver, relacionadas con el contenido del módulo. 

Para este ejercicio se proporciona una plantilla de Excel, la cual habrá que completar en tres fases, detalladas a continuación:


## Fase 1
La primera hoja del archivo Excel proporcionado, contiene información acerca de las películas de las que dispones en tu plataforma.

Utilizando los conocimientos adquiridos acerca de álgebra lineal, se pide:
1.	Completar la hoja llamada “Representación vectorial”, de forma que cada película se represente con vectores numéricos. Utiliza las columnas ya definidas para ello. Para automatizar el proceso, se recomienda hacer uso de la siguiente fórmula en Excel: =N(ESNUMERO(HALLAR(Celda1;Celda2)))
2.	Completar la hoja llamada “Normalización de vectores”, en la que los vectores calculados anteriormente se normalizarán, de forma que su módulo sea unitario. Para automatizar el proceso, se recomienda hacer uso de la función SUMA en Excel. Calcula la norma de cada vector para asegurarte de que es igual a 1.
3.	En la hoja llamada “Matriz de Similitudes (coseno)” se han calculado la mayoría de similitudes entre las películas, utilizando la métrica del coseno. Se pide completar las similitudes que faltan, marcadas en amarillo (6 en total). Puedes utilizar la función SUMAPRODUCTO para realizar el producto escalar entre vectores en Excel.
4.	En la hoja llamada “Recomendaciones” se pide calcular los scores de recomendación para el usuario con userId=4, y seleccionar el top 10 de películas, con su título correspondiente.

## Fase 2
Utilizando conceptos de estadística descriptiva, se utilizarán los datos de la Hoja “Usuarios”, que contiene información acerca de los usuarios de la plataforma. En esta fase se calcularán estadísticos y se generarán gráficas a partir de estos datos.
1.	Calcular el rating medio por cada usuario. Para automatizar el proceso, se recomienda utilizar la función en excel PROMEDIO.SI.CONJUNTO. Además, también se deberá calcular el rating máximo y mínimo para cada usuario, y el rango, marcando con una “X” aquellos usuarios cuyo rango sea el máximo de todos (pueden existir varios usuarios).
2.	Calcular la varianza y desviación típica de los ratings medios calculados en el paso anterior.
3.	Realizar un gráfico de cajas con el rating medio, y de la edad de los usuarios, identificando posibles outliers.
4.	Calcular el histograma de la variable edad, la frecuencia absoluta de géneros y representarlo con gráfico de barras.
5.	Realizar un gráfico de dispersión entre el rating medio y la edad y calcular la correlación entre los pares de variables rating medio - edad y rango de rating- edad.
6.	Completar la hoja “Matriz de similitudes (correlaciones”), en la que se utiliza la correlación entre pares de vídeos utilizando su representación vectorial.

# Fase 3
Utilizando los conceptos de estadística inferencial, se pide completar los campos de la fase 3 dentro de la hoja “Usuarios” en el fichero Excel. En concreto, se pide:
1.	Calcular la probabilidad de que un usuario escogido al azar sea hombre
2.	Aproximar la distribución de probabilidad de la edad de los usuarios a una normal (ejemplo de respuesta: la edad de los usuarios sigue una distribución normal N(20,4)
3.	Utilizando la aproximación de la distribución normal en el paso anterior, calcular la probabilidad de que la edad de los usuarios esté comprendida entre 35 y 40 años.
4.	Realizar un test estadístico para comprobar si la correlación entre la edad y el rating medio es significativa
5.	Obtener la recta de regresión que relaciona el rating medio y la edad.
6.	Predecir qué rating medio tendría un usuario con 60 años de edad.

## ARCHIVOS A ENTREGAR: Fichero Excel completado. Puede utilizarse cualquier procesador de hojas de cálculo