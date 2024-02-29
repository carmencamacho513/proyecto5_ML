# Imputación de Datos

### OPRIME ESTE LINK <mark style="color:red;">Google Colaboratory</mark> Proyecto Profundización\_ML.

{% embed url="https://colab.research.google.com/drive/1dgnBe5gWuSLgAbOo5QkasRfzKS1fMQe4#scrollTo=MZYIu-SYnsC3" %}

### Conclusiones

#### Nulos

1. Se especifican las variables 'NumCompaniesWorked'  a la que se le imputarán valores nulos.
2. Se calcula la media y la décima parte de la desviación estándar de la variable para generar valores aleatorios cercanos a la media.
3. Se reemplazan los valores nulos en la variable con los valores aleatorios generados.

#### Outliers

**Iteración sobre cada variable:** Para cada variable 'Age', 'DistanceFromHome', 'EmployeeID', 'MonthlyIncome', 'StockOptionLevel' NumCompaniesWorked', 'PercentSalaryHike', 'TrainingTimesLastYear', 'YearsSinceLastPromotion', 'YearsWithCurrManager' a imputar, se realiza el siguiente proceso:

a. **Identificación de valores atípicos (outliers):** Se calculan los cuartiles Q1 (25%) y Q3 (75%), así como el rango intercuartílico (IQR). Se definen límites inferior y superior para identificar outliers.

b. **Identificación de outliers:** Se crea una máscara booleana que indica cuáles son los valores que se consideran outliers según los límites definidos.

c. **Imputación con la mediana:** Se imputan los valores atípicos con la mediana de la variable correspondiente.

