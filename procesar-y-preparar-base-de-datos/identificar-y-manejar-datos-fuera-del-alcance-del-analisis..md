# Identificar y manejar datos fuera del alcance del análisis.

### OPRIME ESTE LINK <mark style="color:red;">Google Colaboratory</mark> Proyecto Profundización\_ML.

Encuentras todo el proceso realizado.

{% embed url="https://colab.research.google.com/drive/1dgnBe5gWuSLgAbOo5QkasRfzKS1fMQe4#scrollTo=Vlqq_pQy0Jvr&line=1&uniqifier=1" %}

### Conclusiones

1. Se realiza la eliminación de las variables "EmployeeCount" constante (1),  "Over18" constante(y) y "StandardHours" constante(8); porque son variables que contienen información continua en sus registros de datos.
2. Que entre estas variables **TotalWorkingYears y Age** que hay una multicolinealidad se elimina la variable **TotalWorkingYears;** ya que la variable **Age** es determinante para el estudio de los modelos.
3. Que entre estas variables **YearsAtCompany y YearsWithCurrManager y YearsSinceLastPromotion y YearsAtCompany** se elimina la variable **YearsAtCompany** porque conserva una multicolinealidad con dos variables**.** Y las otras variables  **YearsWithCurrManager y YearsSinceLastPromotion**  pueden ser determinantes para los modelos.
4. Se elimina las variables **EducationField y JobLevel** porque se considera que no es determinante para el estudio.
