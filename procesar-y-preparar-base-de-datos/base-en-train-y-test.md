---
description: Base Conjunto de Entrenamiento “train” y Conjunto de Rendimiento“test”
---

# Base en “train” y “test”

### OPRIME ESTE LINK <mark style="color:red;">Google Colaboratory</mark> Proyecto Profundización\_ML.

{% embed url="https://colab.research.google.com/drive/1dgnBe5gWuSLgAbOo5QkasRfzKS1fMQe4#scrollTo=GkbtCMhxOBT0&line=1&uniqifier=1" %}

### Conclusión

El resultado "Forma del conjunto de entrenamiento (X\_train, y\_train): (3528, 16) (3528,)" significa lo siguiente:

1. **Conjunto de entrenamiento (`X_train`, `y_train`):**
   * `X_train`: Este conjunto contiene 3528 filas y 16 columnas. Cada fila representa una observación (un empleado en tu caso), y cada columna es una característica o variable independiente utilizada para entrenar el modelo.
   * `y_train`: Este conjunto contiene 3528 filas, que corresponden a las 3528 observaciones en `X_train`. Es la variable respuesta (en tu caso, "Attrition") para las observaciones en `X_train`.
2. **Conjunto de prueba (`X_test`, `y_test`):**
   * `X_test`: Similar a `X_train`, este conjunto tiene 882 filas y 16 columnas. Son datos separados que no se utilizaron durante el entrenamiento y se utilizarán para evaluar el rendimiento del modelo.
   * `y_test`: Al igual que `y_train`, este conjunto tiene 882 filas, que se corresponden con las observaciones en `X_test`. Es la variable respuesta para las observaciones en `X_test`.

Estas dimensiones indican cuántos datos tienes para entrenar tu modelo (`X_train`, `y_train`) y cuántos datos tienes para probar su rendimiento (`X_test`, `y_test`). La proporción típica es 80% para entrenamiento y 20% para prueba, y en este caso, la división es aproximadamente así.
