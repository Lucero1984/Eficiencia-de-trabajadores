# 🗂️ Analisis de eficiencia de trabajadores
Se identificaron los trabajadores con mayor y menor eficiencia de un callcenter

## Herramientas
Python | Pandas | numpy | matplotlib | scipy | seaborn | math

## Metodologia

Preprocesamiento de datos: Se limpiaron los datos, eliminando inconsistencias y verificando la ausencia de duplicados y valores faltantes.
Procesamiento de datos: Se analizo para cada operador la cantidad de llamadas perdidas, el tiempo de espera, la cantidad de llamadas realizadas por dia, semana o mes.

## Conclusiones y recomendaciones

-Los operadores con baja eficiencia en llamadas entrantes por tiempo de espera prolongado fueron aprox 180

-Los operadores con baja eficiencia en llamadas entrantes por llamadas perdidas fueron aprox 180

-Los operadores con baja eficiencia por baja cantidad de llamadas realizadas (salientes) fueron aprox 230

-Los operadores que presentaron baja eficiencia en los 3 parametros fueron pocos (4)

-Los datos de llamadas salientes se analizaron por dia, semana y mes, se encontro que los datos por semana contenian menos valores atipicos, por lo que se usaron estos datos para determinar la baja eficiencia.
