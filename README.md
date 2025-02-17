# **Guía 2 - Análisis de datos con Pandas**

## Análisis de deserción de clientes en el sector de telecomunicaciones

Teniendo en cuenta que para las empresas de la industria de telecomunicaciones, la retención de clientes es un factor crítico donde adquirir nuevos clientes puede ser más costosos que mantener los actuales, el análisis se concentró en descubrir patrónes o factores que permitan identificar las causas posibles de deserción de clientes (*churn*).

El trabajo consistió, en primer lugar, en realizar un análisis explotarorio de la base de datos para entender la cantidad de información con la que se contaba, es decir, la dimensión del dataset, la cantidad y el tipo de variables que pueden ser relevantes para tratar el problema y la distribución de la variable objetivo *churn* y si el dataset contaba con información faltante o valores nulos.

Posteriormente, se utilizaron variables concernientes a servicios adicionales al plan de los clientes como plan internacional o servicio de correo de voz, con el din de identificar si eran factores que influyen en las tasas de deserción. En este casp, se encontró que la deserción es 30% mayor en planes que contaban con servicio internacional y de 8% más en planes que no cuentan con servicio de correo de voz.

Por otro lado, respecto a la duración de las cuentas de los clientes se encontró que la desersion de clientes es mayor en cuentas con mayor tiempo de antiguedad, sin embargo los promedios son muy similares similares.

Con relación a las variables asociadas al uso del servicio como los minutos usados en los diferentes momentos del día, se encontró que en general, decir tanto en minutos usados durante el día como en la noche, la cantidad de minutos promedio usados por los clientes dados de baja es mayor respecto a la media de clientes activos.

En lo que concierne a servicio al cliente, al agrupar los clientes que se comunican con la empresa más de 3 veces versus los que se comunican 3 veces o menos, se encontró que este primer grupo efectivamente tienen una mayor tasa de desercion, es decir, entre el cliente más se comunique con servicio al cliente, mayor es la probabilidad de que cancele su servicio.

Finalmente, se revisó si el costo total de las llamadas diurnas y nocturnas, así como el gasto realizado por los clientes en llamadas internacionales influían en la tasa de deserción. Se observa que el costo de las llamadas diuernas y nocturnas es mayor en los clientes dados de baja, así como el gasto en llamadas es mayor en estos usuarios respecto a los que aun siguen activos.

De esta manera, se puede concluir que los planes con servicio incluido de llamadas internacionales incluidos y de correo de voz; la cantidad de minutos usados; la cantidad de veces que el usuario se comunica con servicio al cliente y el costo de las llamadas son variables que influyen en la decisión de cancelar el servicio de telecomunicaciones en esta empresa y, por tanto, factores a mejorar para lograr una mayor tasa de retención de los clientes.



