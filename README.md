# SOLEMNE 2


----


Bruno Romero



----





## Parte 1



----





__1.__ Usted trabaja como asistente de investigacion en el centro de bioinformatica y biologia integrativa de la Universidad Andres Bello. Su jefe le asigna un proyecto de alta prioridad: se le indica que, en el refrigerador (a -20 °C), usted encontrara un tubo eppendorf que contiene ADN aislado desde una muestra fecal proveniente de un paciente, cuya identidad desconoce . el paciente presenta claros sintomas de una infeccion bacterian intestinal, pero no se ha podido identificar la identidad del patógeno responsable mediante el metodo tradicional de cultivo en placa de petri. Disponiendo usted de una muestra de ADN total aislado de una muestra de heces del paciente, describa de forma breve y precisa su plan de trabajo, paso a paso, para responder a la siguiente pregunta: ¿Que bacterias estan presentes en la muestra?



__R:__



Primeramente, en la muestra es probable de que tengamos cientos de DNA provenientes de distintos organismos, por lo que el primer paso es encontrar algún gen en las secuencias de los organismos que esté bien conservado (y que esté en todas las moléculas) como para poder establecer:



1. Un punto comparativo (análisis mediante mutaciones)




2. Diseñar primers ubicuos que puedan permitir secuenciar esa zona específica en todas las moléculas de DNA en la muestra compleja.

 
 
Tanto el paso 1 como 2, nos servirán para caracterizar a las moléculas en perfiles taxonómicos a partir de la filogenia. Los primers (oligonucleótidos) los emplearía en un amplicon sequencing, ya que se ha demostrado que es útil en la caracterización de perfiles taxonómicos en función del análisis a partir del secuenciamiento del gen de 16s rRNA. Además, el acceso a las bases de datos que publican información taxonómica sobre el gen de 16s rRNA es bastante fácil y en abundancia, ya que es un gen muy estudiado.
Por otra parte, suele ser un gen multicopia, por lo que nos puede entregar una plétora de datos más robustos.



Posteriormente, al terminar el amplicon sequencing, debería tener la información alojada en un computador. Con ésta información, haría los análisis filogenéticos y taxonómicos correspondientes al utilizar herramientas de alineamiento entre las secuencias obtenidas del gen de rRNA 16s.



Como control negativo, utilizaría una secuencia de rRNA 16s conocido y realizaría el ensayo de amplicon sequencing con el mismo primer diseñado anteriormente. 



__2.__ Siguiendo con la situacion planteada en el enunciado anterior. Usted ya tiene los resultados de su trabajo, es decir, usted sabe qué bacterias estan presentes en la muestra. De acuerdo a sus hallazgos, ¿bajo que criterio usted indicaria a una de las bacterias como el patogeno y por qué?



Primeramente, mediante el análisis taxonómico identificaría bacterias patógenas previemente descritas y detalladas en bases de datos que se encuentren en la muestra de DNA complejo. De esta forma, podría descartar las bacterias no patógenas de las potencialmente patógenas. Sin embargo, existe la posibilidad de que:

1. Alguna de las bacterias que se hayan secuenciado a partir del amplicon sequencing no estén tan descritas o que no hayan sido reportadas en literatura.

2. Que la enfermedad se deba a una suma de factores de riesgo y que no pueda establecerse una realción causa-efecto a partir de solo un organismo. Incluso, existe la posibilidad de que la/s bacteria/s causante de la enfermedad sea una no esencialmente patógena sino que por causa del contexto del individuo (pj. baja en la defensa inmunológica) sea una bacteria descrita como parte de la microbiota normal del individuo.


En el caso de que yo conozca todas las bacterias presentes y que estén además, descritas en las bases de datos, bastaría con realizar un secuenciamiento _de novo_ de la bacteria que estimo potencialmente patógena y compararía los genes que secuencian para las proteínas de la maquinaria de patogenicidad de la bacteria en la muestra compleja con las descritas en literatura. Así podría afirmar con un mayor grado de certeza, cuál es la bacteria causante de la enfermedad ya que estaría definiendo la relación causa/efecto de la enfermedad a partir de la bacteria. El secuenciamiento lo realizaría a partir de un shotgun sequencing, ya que así no solo podría obtener el genoma de la bacteria patógena, sino que además su abundancia en el medio complejo. Estimar la abundancia puede ser un respaldo clave en la sintomatología de la enfermedad, ya que si el DNA de la bacteria patógeno es muy abundante, es otra prueba de que esa bacteria es la responsable de la enfermedad. Por otra parte, también nos entregaría información valiosa sobre el estado de la microbiota del individuo, y podría servir para incluir o descartar la participación de las bacterias de la flora normal en el desarrollo de la enfermedad.




## Parte 2



----





__1.__ Segun lo visto en el laboratorio, en este caso requerira caracterizar evolutivamente proteinas de la familia de isoprenyl synthetase (5 proteinas) determinando si ¿existe una relacion convergente o divergente entre ellas? ¿porque?, para lo cual debera utilizar las distintas herramientas como las bases de datos uniprot, prosite, pfam, entre otras.


Proteínas escogidas:

1 http://pfam.xfam.org/protein/G2KWA7_LACSM
2 http://pfam.xfam.org/protein/B9DNS2_STACT
3 http://pfam.xfam.org/protein/K8E4Y2_CARML
4 http://pfam.xfam.org/protein/G2SNF3_LACRR
5 http://pfam.xfam.org/protein/I5B722_9DELT
 



















