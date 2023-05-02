


# Presentación Proyecto

## Primera parte: presentación y contexto

1. Presentación de equipo (0-2) Lidya

-Somos No Secrets Data, agencia de tratamiento de datos. Nuestro equipo está conformado por cuatro emprendedoras, dispuestas a desentrañar todos los secretos de los datos.
-Cristina
-Lidya
-Esti
-Iris

2. Qué pidio el cliente, qué material entregó y los objetivos del proyecto. Explicar qué necesidades cubre el trabajo realizado. (3) Lidya

    - Adalab solicita conocer si está formando a las alumnas con las herramientas adecuadas para el objetivo principal del bootcamp: formación en análisis de datos. Además, saber si hay recursos que pueda ser aconsejable incorporar en el futuro en base a las tendencias actuales del mercado.
    - Para llevar a cabo este cometido se nos han facilitado cuatro archivos en formatos diversos: la encuesta en pdf, las respuestas a la misma en xml, txt, y dos csv. Como parte previa a este análisis se realiza una limpieza y fusión de archivos para futuros usos del cliente.
    - Tras la realización del trabajo, desde No Secrets Data planteamos a Adalab nuestras conclusiones y sugerencias de mejora. 

3. Explicar metodología y herramientas. Como hemos ido avanzando hasta quedarnos con el conjunto de datos seleccionado para el análisis. (4-5) Lidya

    - Para realizar las labores anteriormente descritas hemos utilizado librerías especializadas de Python para visualización, como Matplotlib o Seaborn, VSCode y Jupyter Notebooks como editores de código.

    -El desarrollo del trabajo parte de: 
        - Análisis de la encuesta (Número de encuestados: 25973)
        - Procesamiento de los archivos en sus diferentes formatos
        - Eliminación de las columnas consideradas de poco interés para este análisis concreto.
        - Unión de archivos
        - Archivo final para análisis (imagen del archivo final) a disposición de cliente en el repositorio del proyecto, sobre el cual realizamos una exploración inicial de cara a la toma de decisiones sobre las variables a investigar en detalle y decidir si nos quedábamos con el total de datos o seleccionábamos una muestra dentro de los mismos.
    
4. Análisis:  (6-8) Iris

    - Perfiles socio-demográficos. Agrupados para mayor comodidad en el manejo posterior de los datos. (6)
        -Países: la agrupación de paises europeos junto a EEUU suponen una proporción similar a la de la India. Utilizamos la encuesta sin cribar, por paises porque si conservamos sólo el cribado por España la muestra se reduce considerablemente. Además en nuetsro análisis no percibimos diferencias significativas en las respuestas para las variables de nuestro interés.

        -Género: en la encuesta, la proporción de hombres es superior a la de mujeres, viendo cierta estabilidad en las diferentes segmentaciones de la muestra. Podemos destacar como diferencia notable la presencia de las muejeres europeas en la encuesta no supera el 16%, por debajo de países como India o EEUU. SIn embargo, cuando observamos los datos referidos sólo respecto al perfil Data Analyst en Europa este porcentaje incrementa a un 22%.

        -Edad: relacionada íntimamente con la ocupación, los rangos de edad de los encuestados sube notablemente cuando en la variable de la ocupación omitimos o filtramos por Data Analyst. En su mayoría, la encuesta se compone por Estudiantes. Una vez que filtramos por Data Analyst la media de los encuestados se acrecenta. En España, como dato reseñable, el rango hasta 45-49, aunque este dato no es muy sólido apuntando que el tamaño muestral en nuestro país es bastante reducida.

        -Ocupación: como hemos mencionado, una cuarta parte de los encuestados de la muestra son estudiantes (26,2%). Les siguen en proporción los Data Scientist (13,9) y Software Engineer. Para nuestro estudio decidimos quedarnos únicamente con los datos resultantes del filtrado por Data Analyst, ya que lo consideramos más relevante para el análisis que nos ocupa. En adelante, nuestras conclusiones y datos se referirán sólamente al perfil Analista de Datos.

        -Empresas y equipos: (7-8) Iris
        Es interesante ver los perfiles profesionales y laborales dada la orientación del bootcamp a favor de la empleabilidad. El mercado tiene mucha diversidad en cuanto a los roles tanto de empresa como de equipos. lo aplicado aquí se extiende tanto a la encuesta completa como a la filtrada por Analista de Datos.

5.  Detalle de columnas analizadas por ser las de mayor interés para valorar los contenidos del bootcamp(decidir qué gráficas mostrar): (9-13) Cris
        . Lenguajes de programación: herramienta primaria para el tratamiento de datos
        . Visualización: herramienta para el traslado de datos a imágenes y hacerlos más comprensibles
        . IDEs: entornos de desarrollo integrado, facilita al programador el desarrollo de software 
        . Notebooks: herramientas de ejecución, editores de código

6. Finalización: (14-16) Esti

    - Conclusiones obtenidas por el quipo de No Secrets Data: 

        -En primer lugar, hemos evaluado los lenguajes de programación enseñados en el Bootcamp y podemos decir que son adecuados para la industria. Los conocimientos adquiridos en Python, y SQL son muy demandados por las empresas en la actualidad y son fundamentales para el desarrollo de proyectos tecnológicos.
        
        - En cuanto a la visualización de datos, según las investigaciones que hemos llevado a cabo podemos inferir que es adecuada debido a la presencia en los primeros puestos de Matplotlib y Seaborn.

        - De igual manera, consideramos que los entornos de desarrollo integrado son adecuados, ya que las herramientas más utilizadas son Jupyter Notebooks y VSCode.

        - Respecto a las plataformas de desarrollo integrado haremos una serie de consideraciones en la siguiente diapositiva.

        - Por último, queremos destacar que este Bootcamp es una gran oportunidad de desarrollo para las mujeres. El programa se enfoca en formar al género femenino en tecnología y les brinda la oportunidad de adquirir habilidades en un sector que tradicionalmente ha estado dominado por hombres.

    - Como sugerencias de mejora, proponemos:

        - Incluir una master class sobre plataformas de computación en la nube como Kaggle Notebooks o Colab Notebooks con el objetivo de profundizar en estas herramientas.

        - También sugerimos incluir lecciones de fundamentos de "R", dado su presencia notable en la encuesta realizada. Este lenguaje de programación es muy utilizado en el ámbito de la estadística y el análisis de datos, por lo que es importante que las alumnas tengan conocimientos sólidos en este campo.

        - Por último, la encuesta cuenta con información suficiente para elaborar un análisis individualizado de la materia de Machine Learning en el futuro si es de interés para Adalab. 

