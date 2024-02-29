---
description: >-
  (Ingeniería de características)Esta etapa implica la creación de nuevas
  variables explicativas a partir de las características existentes en los
  datos.
---

# Feature Engineering

### OPRIME ESTE LINK <mark style="color:red;">Google Colaboratory</mark> Proyecto Profundización\_ML.

{% embed url="https://colab.research.google.com/drive/1dgnBe5gWuSLgAbOo5QkasRfzKS1fMQe4#scrollTo=-e6fwfUmalNi&line=1&uniqifier=1" %}

### Conclusiones

Se realizaron las siguientes categórias:

### Categórias

**Age (Edad): AgeCategory**

* Joven (<30) = 1
* Adulto joven (30-40) = 2
* Adulto (40-50) = 3
* Adulto mayor (50-60) = 4
* Mayor (>60) = 5

**DistanceFromHome (Distancia Desde Casa): DistanceCategory**

* Cerca (<5 km) = 1
* Moderada (5-10 km) = 2
* Lejana (>10 km) = 3

**MonthlyIncome (Ingreso Mensual): IncomeCategory**

* Bajo (<5000) = 1
* Medio (5000-10000) = 2
* Alto (10000-15000) = 3
* Muy Alto (15000-20000) = 4
* Excepcional (>20000) = 5

**NumCompaniesWorked (Número de Empresas Trabajadas): Companies Category**

* Poco (0-2 empresas) = 1
* Moderado (3-5 empresas) = 2
* Muchos (>5 empresas) = 3

**PercentSalaryHike (Aumento Porcentual del Salario): HikeCategory**

* Bajo (<15) = 1
* Moderado (15-20) = 2
* Alto (>20) = 3

&#x20;Se realizó tablas de copia:

df tabla original

**df\_1 tabla a la cual se le eliminaron las variables del proceso de categorias y se dejaron las variables nuevas y las cual es la tabla para realizar los modelos**

df\_2 se realizó en esta tabla las categórias en texto.

df\_3 se dejo copia de la tabla df\_1 sin eliminar variable.

