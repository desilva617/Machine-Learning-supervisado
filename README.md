# Entrenamiento de un modelo para el análisis del comportamiento de los clientes de Megaline
## introduccion
La compañía móvil Megaline quiere desarrollar un modelo que pueda analizar el comportamiento de los clientes y recomendar uno de los nuevos planes de Megaline: Smart o Ultra.
Se desarrollará un modelo con la mayor exactitud posible. En este proyecto, el umbral de exactitud es 0.75.
## Contenido
* [Introducción](#intro)
* [Carga de liberías y datos](#data_review)
* [Segmentación de datos](#seg)
* [Entrenamiento de modelos](#train)
    * [Árbol de decisión](#tree)
    * [Bosque aleatorio](#forest)
    * [Regresión logística](#reg)
* [Calidad del modelo](#cal)
* [Conclusión general](#conclusion)
## Conclusion
En conclusión, el mejor modelo para el conjunto de datos fue el árbol de decisión con profundidad máxima en 3. 
- Los hiperparámetros afectaron la calidad de predidcción.
- Se obtuvo una exactitud similar en los conjuntos de entremiento, validación y prueba, por lo tanto el modelo no estaba sobreajustado y predice correctamente en campo.
