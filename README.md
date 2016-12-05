
# Reddit

PRACTICA 1: Extracción de datos de una red social.

_Extracción de datos de una red social_

## Tareas a realizar

Definid al menos dos modos de extraer contenidos:

- [ ] Los últimos contenidos (extrayendo el máximo número que permite Reddit).
- [ ] Los contenidos más populares (acorde a las valoraciones de Reddit).

- [ ] El conjunto de entradas que obtengáis en el paso anterior, junto con sus comentarios
asociados, deben ser almacenadas en disco en un formato adecuado. Para ello, definid un
esquema XML que permita almacenar toda la información disponible (al menos, título,
contenido, fecha, tipo de entrada -post o comentario-) y guardad toda la colección obtenida
en un único archivo XML.

- [ ] Realizad un simple procesamiento del corpus anterior para vectorizar la colección y
mostrar los términos con mayor ponderación tf/idf.

- [ ] Instalad y familiarizaros con [scikit-learn](http://scikit-learn.org/stable/):
    - [ ] [Feature Extraction](http://scikit-learn.org/stable/modules/feature_extraction.html#feature-extraction)
    - [ ] [TfIdf Vectorizer](http://scikit-learn.org/stable/modules/generated/sklearn.feature_extraction.text.TfidfVectorizer.html).


- [ ] dado el corpus obtenido de Reddit, y considerando cada post o comentario como
un documento individual, utilizad el TfIdf Vectorizer (filtrando stopwords y todas
aquellas palabras que aparezcan en menos de 10 docs) para vectorizar la colección y
seguidamente mostrar los 10 términos más “centrales” en la colección. Entendiendo
como más centrales aquellos cuya suma acumulada de tf/idf sobre todos los
documentos es mayor.



## Valoración y Fecha de Entrega:

Esta práctica tiene una valoración de 3 puntos (sobre el total de 7 puntos de la parte práctica de la materia), que se dividen de la siguiente forma:
  * 2 puntos: programa python correcto y con las funcionalidades arriba indicadas.
  * 0.75 puntos: extracción de datos.
  * 0.5 puntos: creación XML.
  * 0.75 puntos: vectorización de la colección.
  * 1 punto: python notebook.
