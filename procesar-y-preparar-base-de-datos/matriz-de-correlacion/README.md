# Matriz de Correlación



### OPRIME ESTE LINK <mark style="color:red;">Google Colaboratory</mark> Proyecto Profundización\_ML.

Encuentras todo el proceso realizado.

{% embed url="https://colab.research.google.com/drive/1dgnBe5gWuSLgAbOo5QkasRfzKS1fMQe4#scrollTo=ckg9T5CEgoZs&line=1&uniqifier=1" %}

### Conclusiones

El resultado de la matriz de correlación se observa las correlaciones más cercanas a 1 o -1. Aunque no hay correlaciones extremadamente cercanas a estos valores, podemos identificar algunas relaciones que podrían sugerir la posibilidad de multicolinealidad:

1. **TotalWorkingYears y Age:**
   * Correlación: 0.68 (cercana a 1)
   * Interpretación: La edad (`Age`) y el total de años trabajados (`TotalWorkingYears`) tienen una correlación positiva relativamente fuerte. Esto puede indicar que a medida que la edad de los empleados aumenta, también lo hace su total de años trabajados, lo cual es razonable. Sin embargo, la alta correlación podría sugerir cierta redundancia en la información.
2. **YearsAtCompany y YearsWithCurrManager:**
   * Correlación: 0.77 (cercana a 1)
   * Interpretación: Los años en la empresa (`YearsAtCompany`) y los años con el actual gerente (`YearsWithCurrManager`) muestran una correlación positiva fuerte. Esto sugiere que a medida que los empleados pasan más tiempo en la empresa, también pasan más tiempo con el mismo gerente. Esta alta correlación podría indicar cierta redundancia en la información y posiblemente multicolinealidad.
3. **YearsSinceLastPromotion y YearsAtCompany:**
   * Correlación: 0.62 (relativamente alta)
   * Interpretación: Existe una correlación positiva entre los años desde la última promoción (`YearsSinceLastPromotion`) y los años en la empresa (`YearsAtCompany`). Esto sugiere que los empleados que han pasado más tiempo en la empresa también han experimentado promociones con mayor frecuencia. La correlación relativamente alta podría sugerir una relación fuerte entre estas dos variables.

Es importante tener en cuenta que la multicolinealidad no está completamente determinada por correlaciones cercanas a 1 o -1, y se deben realizar más análisis para confirmar su presencia.&#x20;

Por este se realiza una técnica adicional, que es la variabilidad de inflación de la varianza (VIF), para evaluar la multicolinealidad de manera más cuantitativa.&#x20;

### Mapa de Calor - Matriz de Correlación

<figure><img src="../../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>
