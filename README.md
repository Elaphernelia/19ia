[David Davó Laviña](https://ddavo.me) y Ela K. Shepherd Arévalo

# Prácticas de Inteligencia Artificial
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD)

Prácticas de la asignatura Inteligencia Artificial II del Grado en Ingeniería Informática (Rama de Ciencias de la Computación) de la Facultad de Informática de la Universidad Complutense de Madrid. Curso 2019/2020

## Práctica 1

Prácticas de aprendizaje automático, preparación, representación, análisis, representación y validación de datos. Se han usado árboles de decisión, algoritmos de clústering, redes neuronales...

También se realiza análisis de textos y consultas sobre redes semánticas del conocimiento como WikiData.

### Parte 1
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica1%2FP1P1_IA2.ipynb)

Agrupamiento (clústering) sobre el conjunto de datos de cifras de arrestos por cada 100.000 residentes en distintos estados de EEUU.

### Parte 2
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica1%2FP1P2_IA2.ipynb)

Análisis del tipo de tumor (benigno o maligno) basado en multitud de características. Se intentó usar un algoritmo de clusterización basado en 2 particiones (k-means con k=2). Para  seleccionar las variables más significativas se crearon y compararon varios árboles de decisión.

### Parte 3
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica1%2FP1P3_IA2.ipynb)

Regresión del PIB a diversos factores de la economía de un país usando una red neuronal.

## Práctica 2

### Parte 1
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica2%2FP2P1_IA.ipynb)

Análisis de sentimiento de opiniones positivas/negativas de Yelp. Transformación del texto en bolsa de palabras, vectorización con TF-IDF. Comparamos un clasificador naive bayes con un árbol de decisión.

### Parte 2
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica2%2FP2P2_IA.ipynb)

Se realiza un buscador de mensajes en un foro. Para ello se usa la similitud del coseno para calcular la relevancia de cada mensaje con respecto a la consulta.


## Práctica 3
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica3%2FP3IA.ipynb)

Se realizan consultas sobre wikidata en el lenguaje declarativo SPARQL. Las consultas las podemos realizar en ipynb tras registrar un `cell_magic` personalizado.

## Práctica 4
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gl/daviddavo%2F19ia/HEAD?filepath=Practica4%2FP4_IA.ipynb)

Práctica opcional en la que se implementan funciones para retornar las relaciones (caminos con entidades y propiedades comunes) entre dos entidades.