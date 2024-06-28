# ModelaIA
## Tp Integrador - Modelado de sistemas de IA
### Ejercicio Practico a Realizar
En este ejemplo contaras con un archivo .csv de entrada obtenido por webscraping que contiene diversas URLs a artículos sobre Machine Learning de algunos sitios muy importantes como Techcrunch o KDnuggets y como características de entrada -las columnas- tendremos:
Title: Titulo del Artículo
url: ruta al artículo
Word count: la cantidad de palabras del artículo,
#of Links: los enlaces externos que contiene,
#of comments: cantidad de comentarios,
#Images video: suma de imágenes (o videos),
Elapsed days: la cantidad de días transcurridos (al momento de crear el archivo)
#Shares: nuestra columna de salida que será la “cantidad de veces que se compartió el artículo”.
A partir de las características de un artículo de machine learning debera intentar predecir, cuantas veces será compartido en Redes Sociales.
Debera realizar una primer predicción de regresión lineal simple -con una sola variable predictora-  para poder graficar en 2 dimensiones (ejes X e Y) y luego un ejemplo de regresión Lineal Múltiple, en la que utilizara 3  dimensiones (X,Y,Z) y predicciones.
### Predecir cuántas veces será compartido un artículo de Machine Learning.
Regresión lineal simple en Python (con 1 variable)
TIPS o sugerencias:
- [ ] Importar el data set
- [ ] Explorar los datos
- [ ] Elegir la variable a analizar
- [ ] Utilizar la libreria SciKitLearn
- [ ] Se sugiere tomar como inputs la columna  Word Count y como "etiquetas" la columna #Shares
- [ ] Graficar la exploracion de datos
- [ ] Calcular la Prediccion
### Regresión Lineal Múltiple
Extender el ejercicio utilizando más de una variable de entrada para el modelo. Esto le da mayor poder al algoritmo de Machine Learning, pues de esta manera podremos obtener predicciones más complejas.
Nuestra “ecuación de la Recta”, ahora pasa a ser:
Y = b + m1 X1 + m2 X2 + … + m(n) X(n)
TIPS:
- [ ] Utiliar 2 “variables predictivas” para poder graficar en 3D
- [ ] Visualizar un plano en 3 Dimensiones en Python
- [ ] Predicción con el modelo de Mútiples Variables
- [ ] SUGERENCIA: # Para poder graficar en 3D, crear una variable nueva que será la suma de los enlaces, comentarios e imágenes
La primer variable seguirá siendo la Word Count y la segunda variable será la suma de 3 columnas de entrada: la cantidad de enlaces, comentarios y cantidad de imágenes
## Conclusión y Mejora de nuestro modelo
Explicar conclusiones y como se podria mejorar el modelo
