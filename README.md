# Identificación del Problema

### OBJETIVO 

- Identificar un problema (el primer paso en todo proyecto de ciencia de datos).

### DESARROLLO

En este Postwork trabajaremos con estos 4 pasos.
### 1. Identificación de un problema
> - Mal manejo (intencional) de los recursos publicos del pais y una falta de mecanismos efectivos para tratar con esta problematica.
> - Rezago tecnologico/economico del pais en relacion con otros.

### 2. Investigación
- [México: Anatomía de la Corrupción - IMCO](https://imco.org.mx/wp-content/uploads/2016/10/2016-Anatomia_Corrupcion_2-Documento.pdf)
- [CORRUPTION PERCEPTIONS INDEX](https://www.transparency.org/en/cpi/2020/index/nzl)
- [¿Tiene solución
la corrupción?](https://imco.org.mx/indices/la-corrupcion-en-mexico/capitulos/analisis/tiene-solucion-la-corrupcion)
- [La corrupción y el control de la corrupción como impedimentos para la competitividad económica](http://www.scielo.org.mx/scielo.php?pid=S1405-10792010000200002&script=sci_arttext)
- [La relación entre corrupción y narcotráfico
un análisis general y algunas referencias a Colombia](https://dialnet.unirioja.es/servlet/articulo?codigo=7558575)
- [¿Podemos reducir la corrupción en México? Segunda Edición: Límites y posibilidades de los instrumentos a nuestro alcance](https://books.google.com.mx/books?hl=es&lr=&id=APFUDwAAQBAJ&oi=fnd&pg=PT149&dq=corrupci%C3%B3n+en+m%C3%A9xico&ots=zIKUtUmAXH&sig=7u5Ssh_-BtDua5EkOMrB8ReTTeE&redir_esc=y#v=onepage&q=corrupci%C3%B3n%20en%20m%C3%A9xico&f=false)
- [¿Podemos reducir la corrupción en México?
Límites y posibilidades de los instrumentos a nuestro alcance, CIDE,
México, 2018.](https://www.uv.mx/cedegs/files/2021/04/Revista-Letras-Juridicas-numero40.pdf#page=161)
- [Corruption Perceptions Index 2012
Statistical Assessment](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.872.1686&rep=rep1&type=pdf)

- [Time Lag Analysis of FDI Spillover Effect: Evidence from the Belt and Road Developing Countries Introducing China’s Direct Investment](https://www.researchgate.net/publication/335856559_Time_Lag_Analysis_of_FDI_Spillover_Effect_Evidence_from_the_Belt_and_Road_Developing_Countries_Introducing_China's_Direct_Investment)
- [Analysis: Europe in battle to overcome economic lag vs U.S., Asia](https://www.reuters.com/article/us-eurozone-economy-analysis-idUKKBN2A5155)


##### 3. Búsqueda de soluciones anteriores
- [Statistical analysis of corruption data and using the Internet to reduce corruption](https://www.sciencedirect.com/science/article/abs/pii/S1049007800000348)
- [A Statistical Analysis of Public Sector Corruption and Economic Growth](https://scholarship.claremont.edu/lux/vol2/iss1/6/)
- [Así se mide la corrupción en México
](https://www2.deloitte.com/mx/es/pages/dnoticias/articles/asi-se-mide-corrupcion-mexico.html)
- [Los Mexicanos Frente a la Corrupción y la Impunidad 2020.](https://contralacorrupcion.mx/los-mexicanos-frente-a-la-corrupcion-y-la-impunidad-2020/)

# Planteamiento de preguntas
### OBJETIVO 

- Realizar planteamiento de preguntas (el paso #2 en todo proyecto de ciencia de datos).

#### REQUISITOS 

- Haber identificado un problema
- Haber realizado algo de investigación sobre el problema y entenderlo bien
- Haber buscado soluciones o análisis que otras personas hayan realizado anteriormente para enriquecer nuestro proceso

#### DESARROLLO
1. Existe una relacion entre la cantidad de dinero perdido de un estado y su CPI?
2. La relacion entre en la corrupcion y el CPI es positiva o negativa?
3. Cuales son los estados con peor manejo de recursos
4. Cuanto dinero perdido tenemos alcualmente
5. Como varia el mal manejo de los recursos con respecto al tiempo
6. Cuales son las organizaciones gubernamentales con peor manejo de los recursos publicos
7. Cuales son los sectores peor administrados
8. Existe alguna relacion entre el sector y eficiencia de la resolucion de las auditorias?
9. Cual es el sector y la entidad federativa mas auditada

# Colección de Datos

### OBJETIVO 

- Identificar las diferentes maneras que hay de coleccionar datos y utilizar la más apropiada para responder a tus preguntas.

#### REQUISITOS 

- Haber elegido un problema que te parezca interesante.
- Haberte planteado una serie de preguntas que te parecen relevantes para tu problema.

#### DESARROLLO
- [Transparencia presupuestaria - Observatorio del gasto](https://www.transparenciapresupuestaria.gob.mx/es/PTP/Datos_Abiertos)
- [Portal de datos de la Auditoría Superior de la Federación](http://www.asfdatos.gob.mx/)
- [Encuesta Nacional de Calidad e Impacto Gubernamental (ENCIG)](https://datos.gob.mx/busca/dataset/encuesta-nacional-de-calidad-e-impacto-gubernamental-encig)
- [Encuesta Nacional de Victimización de Empresas (ENVE)
](https://datos.gob.mx/busca/dataset/encuesta-nacional-de-victimizacion-de-empresas-enve1)
- [Reporte del indicador general de percepción de corrupción](https://datos.gob.mx/busca/dataset/resultados-de-encuestas/resource/bd173fb7-e670-4ecf-93cb-d29782b4b3e5)
- [Encuesta Nacional de Calidad e Impacto Gubernamental (ENCIG) 2019](https://www.inegi.org.mx/app/saladeprensa/noticia.html?id=5724)
- [PERCEPCIÓN DE LA CORRUPCIÓN Y CALIDAD DE LA TRANSPARENCIA EN ENTIDADES FEDERATIVAS SELECCIONADAS](https://contralacorrupcion.mx/anatomiadigital/content/corrupcion-en-mexico.php)
- Algunos otros datasets de interes en [este sitio](https://politica.expansion.mx/mexico/2019/12/09/10-datos-que-revelan-que-tan-grave-es-la-corrupcion-en-mexico).

# 4.- Análisis Exploratorio de nuestro Dataset

### OBJETIVO 

- Leer nuestro dataset en un `DataFrame` de `pandas`.
- Realizar Análisis Exploratorio de Datos básico para conocer algunas de las características de nuestro conjunto de datos.

### DESARROLLO

En este Postwork vamos a empezar a analizar nuestro conjunto de datos usando `pandas`. Sé que hasta ahora sólo hemos revisado cómo leer archivos tipo JSON usando `pandas`. El módulo está diseñado para aprender los diferentes tipos de formatos y explorar nuevas fuentes de datos en el momento en el que sean más apropiadas. En caso de que tu dataset tenga algún formato distinto a JSON, pídele ayuda a tu experta para que te guíe rápidamente en el proceso de lectura de tus datos. La experta puede proveerte código para que rápidamente puedas convertir tu conjunto de datos a un `DataFrame`.

Algunas de las preguntas que estamos intentando responder en esta exploración son las siguientes:

1. ¿El conjunto de datos que tengo realmente me sirve para responder algunas de las preguntas que me planteé?
   > Si :)

2. ¿Qué tamaño tiene mi conjunto de datos? ¿Serán datos suficientes?
   > Contamos con datos del 100% de las entidades federativas de la nacion

3. ¿Qué columnas tengo y qué información tengo en cada una de esas columnas?
```
0   Año Cuenta Pública                21606 non-null  int64  
 1   Sector                            21606 non-null  object 
 2   Ente Fiscalizado                  21606 non-null  object 
 3   Entidad Federativa                21606 non-null  object 
 4   Tipo Auditoría                    21606 non-null  object 
 5   Título                            21606 non-null  object 
 6   Universo (miles pesos)            21606 non-null  object 
 7   Muestra (miles pesos)             21606 non-null  object 
 8   Ente a quien se dirige la Acción  21606 non-null  object 
 9   Tipo Acción                       21606 non-null  object 
 10  Texto Acción                      17841 non-null  object 
 11  terminado                         21606 non-null  bool   
 12  desaparecido                      5724 non-null   float64
```
4. Los nombres que tienen mis columnas, ¿son el nombre más apropiado?
   > Si

5. ¿Qué tipos de datos tengo en cada columna? ¿Parecen ser el tipo correcto de datos? ¿O es un tipo de datos "incorrecto"?
   > ...

6. Si selecciono algunas filas al azar y las observo, ¿estoy obteniendo los datos que debería? ¿O hay datos que parecen estar "sucios" o "incorrectos"?
   > Datos ok

Responde estas preguntas usando las técnicas que aprendiste en esta sesión y comparte tus hallazgos con tus compañeros y la experta.

##### (Para tu entrega final)

Escriban en su archivo de entrega final qué hallazgos preliminares encontraros en su exploración básica de datos. Asimismo, no se olviden de guardar bien su código para entregarlo en el Notebook final.