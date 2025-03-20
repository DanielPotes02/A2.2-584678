# A2.2 LDA y Árboles de Decisión

En este trabajo, se analizará una base de datos histórica que contiene información sobre los pasajeros del Titanic, con el objetivo de predecir la probabilidad de supervivencia de cada uno de ellos utilizando un modelo de regresión logística. Esta técnica es adecuada, ya que la variable a predecir ("Survived") es binaria: 1 significa que el pasajero sobrevivió, y 0 que no lo hizo.

Variables utilizadas:

* Survived: Variable objetivo (0 = No sobrevivió, 1 = Sobrevivió).
* Pclass: Clase del pasajero (1 = Primera clase, 2 = Segunda clase, 3 = Tercera clase).
* Age: Edad del pasajero.
* SibSp: Número de hermanos o cónyuges a bordo.
* Parch: Número de padres o hijos a bordo.
* Fare: Tarifa pagada por el pasajero.
* Cabin_known: Indica si se conoce el número de camarote (1 = Sí, 0 = No).
* Sex_male: Género del pasajero (1 = Hombre, 0 = Mujer).
* Embarked_Q: Indica si el pasajero embarcó en el puerto Queenstown (1 = Sí, 0 = No).
* Embarked_S: Indica si el pasajero embarcó en el puerto Southampton (1 = Sí, 0 = No).
* Con estas variables, el modelo buscará patrones que permitan identificar qué tipo de pasajeros tuvieron mayor probabilidad de sobrevivir al hundimiento.

Este proyecto incluye los siguientes documentos:

[Reporte en formato ipynb](A2.2%20584678.ipynb)

[Reporte en formato html](A2.2%20584678.html)

[Base de datos](DataTitanic_Processed.csv)
