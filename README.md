# Challenge-Telecom-X-an-lisis-de-evasi-n-de-clientes---Parte-2

El objetivo del ejercicio era continuar con la base depurada del ejercicio anterior y generar dos diferentes modelos de predicción que ayudaran a identificar a los clientes con mayor posibilidad de cancelar el servicio.

Dado el desbalanceo de la información se propusieron dos metodologías, la primera de undersampling para igualar la cantidad de elementos en ambas clases reduciendo aquella que tenía más elementos y la segunda haciendo un oversampling generando data sintética hasta llegar al mismo número de elementos de clase con mayor número de elementos.

# Conclusiones Generales

* El modelo Undersample muestra un mejor performance ya que logra detectar más clientes con potencial a terminar el contrato.

* Las variables que más influye en la decisión de continuar o no con el servicio son remainder__tenure y onehotencoder__TechSupport_No
