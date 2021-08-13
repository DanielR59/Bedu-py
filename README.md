# Análisis de la corrupción en México
### ¿Por qué analizar la corrupción?
<p align="center">
Se considera a la corrupción como uno de los más relevantes obstáculos para el desarrollo del país, y como tal, es necesario entenderlo para saber afrontarlo de manera efectiva, y con esto, ayudar a construir una sociedad más justa y menos desigual.
</p>

## Equipo 14
<p align="center"><img src="img/giphy.gif" /></p>

- [Angelica Domínguez Cabello](https://github.com/AngelicaDC)
- [Erick Manuel Arroyo Gonzalez](https://github.com/Erick-INCS)
- [Ignacio Díaz Romero](https://github.com/Forever-D14)
- [José Daniel Rosas Avila](https://github.com/DanielR59)
- [José de Jesús Becerra Burguete](https://github.com/Burguete9)

# 1. Identificación del Problema

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

# 2. Planteamiento de preguntas
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

# 3. Colección de Datos

#### DESARROLLO
- [Transparencia presupuestaria - Observatorio del gasto](https://www.transparenciapresupuestaria.gob.mx/es/PTP/Datos_Abiertos)
- [Portal de datos de la Auditoría Superior de la Federación](http://www.asfdatos.gob.mx/)
- [Encuesta Nacional de Calidad e Impacto Gubernamental (ENCIG)](https://datos.gob.mx/busca/dataset/encuesta-nacional-de-calidad-e-impacto-gubernamental-encig)
- [Encuesta Nacional de Victimización de Empresas (ENVE)
](https://datos.gob.mx/busca/dataset/encuesta-nacional-de-victimizacion-de-empresas-enve1)
- [Reporte del indicador general de percepción de corrupción](https://datos.gob.mx/busca/dataset/resultados-de-encuestas/resource/bd173fb7-e670-4ecf-93cb-d29782b4b3e5)
- [Encuesta Nacional de Calidad e Impacto Gubernamental (ENCIG) 2019](https://www.inegi.org.mx/app/saladeprensa/noticia.html?id=5724)
- [PERCEPCIÓN DE LA CORRUPCIÓN Y CALIDAD DE LA TRANSPARENCIA EN ENTIDADES FEDERATIVAS SELECCIONADAS](https://contralacorrupcion.mx/anatomiadigital/content/corrupcion-en-mexico.php)
- Algunos otros datasets de interés en [este sitio](https://politica.expansion.mx/mexico/2019/12/09/10-datos-que-revelan-que-tan-grave-es-la-corrupcion-en-mexico).

# 4.- Análisis Exploratorio de nuestro Dataset

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
   > ( Ver respuesta a la pregunta 3 )

6. Si selecciono algunas filas al azar y las observo, ¿estoy obteniendo los datos que debería? ¿O hay datos que parecen estar "sucios" o "incorrectos"?
   > Datos limpiados correctamente

# 5.- Limpieza de datos y agregaciones
1. Explora tu dataset con el fin de encontrar los NaNs que contiene. Piensa en la distribución de NaNs por columna y por fila.
> Ok :heavy_check_mark:

Piensa cuáles son los procedimientos que puedes aplicar a tus NaNs. ¿Tenemos que eliminar las filas/columnas que tienen esos NaNs? ¿O podríamos rellenar esos NaNs con algún valor de manera que podamos retener esas filas/columnas?
> Para este proyecto es relevante mantener todos los datos, por lo que los NAs se omiten mediante filtros cuando es necesario.

Limpia tu dataset de manera que no quede ningún NaN.
> Ok :heavy_check_mark:

Reindexa tu dataset si lo consideras necesario.
> Ok :heavy_check_mark:

Renombra tus columnas si lo consideras necesario.
> Ok :heavy_check_mark:

Prueba aplicar agregaciones a tu DataFrame para ver si puedes empezar a responder algunas de las preguntas que te planteaste anteriormente
> Ok :heavy_check_mark:

# 7.- Transformación, filtración y ordenamiento de datos

1. Checa que todos tus datos tengan el tipo de dato correcto. Si no es así, usa casting para convertir tus datos al tipo de dato correcto (recuerda que tipos de dato como datetime64 se guardan como strings cuando están en archivos .csv, así que tendrás que convertirlos al tipo de dato apropiado cada vez que importes tu archivo.)
> Procedimiento realizado en el pipeline de preprocesamiento.

2. Si tienes columnas de texto, asegúrate de que todas tengan el formato correcto. Si no es así, utiliza las técnicas de manipulación de strings para darles el formato que necesitas.
> Procedimiento realizado en el pipeline de preprocesamiento.

3. Si consideras que alguna de tus columnas sería más clara si los datos tuvieran otro formato o representación usa map para transformar los datos de esa columna.
> Ok :heavy_check_mark:

4. Si crees que es posible generar nuevas columnas útiles a partir de las columnas que ya tienes, usa apply para generar nuevos datos a partir de los que tienes y añádelos a tu dataset.
> Ok :heavy_check_mark:

5. Con el fin de responder algunas de las preguntas que te planteaste acerca de tu dataset, usa filtros y sorting para crear nuevos subconjuntos y reordenamientos que sean más adecuados para responder tus preguntas. Primero comienza intentando responder las preguntas que te planteaste al principio, pero después puedes solamente explorar para ver si encuentras otras preguntas que no te habías planteado anteriormente.
> Ok :heavy_check_mark:

# 8.- Preparándose para las siguientes Fases

1.- La primera parte consiste en tomar todo lo que hemos hecho hasta ahora y colocarlo limpio y ordenado en un Jupyter Notebook. Una de las maravillas de los Jupyter Notebooks es que nos permiten intercalar texto con código, de manera que podamos ir "guiando" al lector a través de nuestro hilo de pensamiento. Bueno, imagina que quieres explicarle a alguien todo lo que has hecho usando solamente un Jupyter Notebook. No puedes hablar con esta persona ni aclararle cosas: todo debe de estar clarificado en el Notebook. Para embellecer un poco tus celdas de texto, puedes usar lenguaje Markdown. Asegúrate de empezar con una introducción donde hables acerca del tema que te llamó la atención. Explica por qué quisiste abordar este tema, cuáles fueron tus preguntas iniciales, y el problema que te gustaría resolver.
> Ok :heavy_check_mark:

2.- La segunda parte consiste en hacer planes para el futuro. El Procesamiento de Datos es sólo la fase "preparatoria". Después siguen las tres fases que le terminan de dar forma a todo proyecto de Ciencia de Datos: Análisis Estadístico, Visualización y Predicción/Inferencia. Esta última fase (Predicción) no siempre está presente y no siempre es necesaria. Pero el Análisis Estadístico y la Visualización son partes intrínsecas de la Ciencia de Datos. La segunda parte de este Postwork consiste en hacer planes a futuro. Piensa qué puedes hacer con los datos que tienes. ¿Qué te gustaría analizar? ¿Qué información está disponible en tus datos? ¿Cómo podrías ayudarte a entender mejor los datos usando gráficas y visualizaciones? Has una lista de tus planes a futuro. Seguramente esa lista irá cambiando conforme avances en el siguiente módulo, pero es un gran comienzo para tener una dirección clara.
> Ok :heavy_check_mark:

  1. ¿Qué te gustaría analizar?
  > Estamos interesados en analizar la distribución de los “incidentes” identificados en los recursos públicos y en buscar posibles factores o patrones en los datos que nos permitan obtener una mejor percepción numérica sobre estos fenómenos en la distribución de los presupuestos públicos del país, para asi, lograr desarrollar un sistema predictivo que nos permita tener un mejor control de los recursos públicos al identificar posibles casos de riesgo.

  2. ¿Qué información está disponible en tus datos?
  > Auditorias realizadas al presupuesto público con sus resultados, clasificadas por sector, estado, municipio, año y demas categorias.
  > También contamos con los datos de la totalidad del presupuesto publico en el portal de transparencia presupuestaria.

  3. ¿Cómo podrías ayudarte a entender mejor los datos usando gráficas y visualizaciones?
  > Utilizando histogramas que nos permitan identificar la naturaleza de los datos que manejamos.
  > Con gráficas de correlación para indentificar posibles variables predictoras.
  > Con un gráfico de caja podríamos observar la distribución de los datos y a partir de los outliers, identificar los estados que tienen una cantidad "anormal" de corrupción.
  > Mediante una representación cartográfica mostrar la correlación de entre la densidad de población y el nivel de corrupción.

# Jupyter Notebook
El Jupyter Notebook utilizado para este proyecto se encuentra disponible entre los archvos de este repositorio [(aquí)](Corrupt.ipynb).

Una version en Google Colaboratory se encuentra disponible en el siguiente enlace:
<p align="center">
  <div align="center"><a href="https://drive.google.com/file/d/11bZloNSfUc91HH-jQVN5-Jc7SdzQIw0U/view?usp=sharing" page="_blank"><img src="https://github.com/Erick-INCS/Bedu-py/blob/main/img/colab.png?raw=true">
  <br>
  Entra aquí</a>
</div>
</p>

# Video explicativo
<p align="center">

[![Alt text](https://github.com/Erick-INCS/Bedu-py/blob/main/img/slide.png?raw=true)](https://www.youtube.com/watch?v=6kOk_52CIOA)

</p>

## Presentación
<p align="center">
  <div align="center"><a href="https://docs.google.com/presentation/d/1zR2Sk9QEixoVjZQ0zXqgyQqsLSsFR9JUVnXxbekD3GA/edit?usp=sharing" page="_blank"><img src="https://github.com/Erick-INCS/Bedu-py/blob/main/img/slides.png?raw=true">
  <br>
  Entra aquí</a>
</div>
</p>


