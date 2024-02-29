# Inflación de la Varianza (VIF)

### OPRIME ESTE LINK <mark style="color:red;">Google Colaboratory</mark> Proyecto Profundización\_ML.

Encuentras todo el proceso realizado.

{% embed url="https://colab.research.google.com/drive/1dgnBe5gWuSLgAbOo5QkasRfzKS1fMQe4#scrollTo=kgZhsqYNGBKu&line=1&uniqifier=1" %}

### Conclusiones

El resultado del Valor de la Inflación de la Varianza (VIF) para cada una de las variables predictoras:

1. **TotalWorkingYears (7.176271):**
   * Un VIF de 7.18 indica que hay cierta correlación entre esta variable y las demás predictoras. Es moderadamente alto y podría sugerir que la información de esta variable está relacionada con otras en el modelo.
2. **Age (5.191384):**
   * Un VIF de 5.19 indica una correlación moderada con las otras variables predictoras. Al igual que TotalWorkingYears, sugiere cierta relación con las demás.
3. **YearsAtCompany (8.489566):**
   * Este VIF es más alto (8.49), lo que sugiere una correlación más fuerte con las otras variables predictoras. Esto podría indicar multicolinealidad, lo cual debe ser considerado al interpretar el modelo.
4. **YearsWithCurrManager (5.659346):**
   * Con un VIF de 5.66, esta variable también muestra cierta correlación con las otras predictoras. Es moderadamente alto.
5. **YearsSinceLastPromotion (2.376760):**
   * Con un VIF de 2.38, esta variable tiene el valor más bajo de todos. Indica una correlación más débil con las demás variables predictoras.

Los valores de VIF más altos indican una mayor correlación con otras variables predictoras, lo que puede afectar la interpretación de los modelos.&#x20;

Se realiza diagrama de pares a visualizar la multicolinealidad entre las variables de estudio.

### Diagrama de Pares

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>
