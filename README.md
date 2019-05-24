# Proyecto_FInal_DavidJImenez


<img src="proyecto final/Word Art.png">

# Descripción y Motivación

El desarrollo regional ha sido un tema que siempre ha estado en la agenda de todos los gobiernos a nivel nacional, por eso se han diseñado estrategias en pro de promover las actividades que impulsen a los municipios y departamentos. sin embargo, producto del proceso de descentralización que viene desde la déada de los noventa, el desarrollo regional tambien viene desde las entidades territoriales.

En este sentido, resulta interesante revisar cuales son los temas que se encuentran dentro de la agenda de los gobiernos subnacionales y si estos son coherentes con las inversiones que se registran en el Formulario Único Territorial -FUT, así mismo a partir de estos datos también podemos observar con la información disponible si han tenido éxito o no estas iniciativas.



## Preguntas que surgieron antes del ejercicio

- la ley 715 del 2001 establece los topes de inversión mínimo para los sectores de Educación, Salud, agua potable y saneamiento básico, Cultura y Deporte con recursos del Sistema General de Participaciones que es la principal fuente de recursos para la mayoría de los municipios. ¿es posible que existan gobiernos que prioricen otros temas o encontraremos patrones que se repitan por todo el territorio nacional alrededor de estos sectores?

-Un porcentaje considerable del territorio nacional es rural, por lo tanto el tema agropecuario debería ser un tema central en la mayor parte de los municipios ¿es esto cierto, y esto se refleja presupuestalmente?

-Durante los últimos años, el presupuesto orientado a resultados ha sido una práctica que se ha promovido entendiendo todas las ventajas que este trae y por lo tanto, diversas instituciones han centrado sus esfuerzos en establecer cuáles son los objetivos de política y como estos se pueden traducir en indicadores de resultados, para medir el éxito de las mismas. A partir de la información actual disponibles ¿ es posible relacionar las prioridades del los PDT con resultados?


## Metodología Usada  

1. Scraping

           el DNP, cuenta con una plataforma en donde las entidades territoriales pueden socializar sus planes de desarrollo y la cual              usamos para descargar 806 PDT en formato pdf.
           
             https://portalterritorial.dnp.gov.co/pdt/
             
 2. Extracción de texto
            
            usando algunas herramientas del paquete TIKA, transformamos 756 PDT´s de los 806 a formato de texto (los demás no se                     pudieron porque la calidad del pdf no lo permitía), a partir de esta información separamos las palabras quitamos las que no             tenían valor en el análisis y estructuramos una base de datos por cada entidad territorial
              
 3. categorización de las palabras 
 
            como nuestro interés se centra en identificar los sectores que las entidades territoriales consideran estratégicos,                     realizamos una agrupación manual de las palabras por cada sector, posteriormente calculamos la frecuencia, para poder                   inferir cuales son los sectores más estratégicos 
            
  4. Cruces de información
  
            con los datos encontrados en los numerales anteriores se realizó un cruce de información con el FUT y los indicadores de                 resultados a fin de establecer si existe relación entre estas tres bases de datos.
            
            
      
## Hallazgos

como habíamos supuesto antes de hacer el ejercicio las palabras que mas se repiten en la mayoría de los planes de desarrollo están relacionadas con los sectores de Educación y Salud

a nivel presupuestal también se observa que la prioridad está en estos dos sectores. en educación tienen una importancia relativa del  10% de todas las palabras, mientras que en salud es del 7%

existe una mayor inclinación por los temas sociales sobre los de competitividad e innovación

a nivel departamental, las prioridades de Antioquia guardan coherencia con la de los municipios que estan dentro de la jurisdicción



          
  
