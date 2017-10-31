# SOLEMNE 2


----


Bruno Romero



----





## Parte 1



----





__1.__ Usted trabaja como asistente de investigacion en el centro de bioinformatica y biologia integrativa de la Universidad Andres Bello. Su jefe le asigna un proyecto de alta prioridad: se le indica que, en el refrigerador (a -20 °C), usted encontrara un tubo eppendorf que contiene ADN aislado desde una muestra fecal proveniente de un paciente, cuya identidad desconoce . el paciente presenta claros sintomas de una infeccion bacterian intestinal, pero no se ha podido identificar la identidad del patógeno responsable mediante el metodo tradicional de cultivo en placa de petri. Disponiendo usted de una muestra de ADN total aislado de una muestra de heces del paciente, describa de forma breve y precisa su plan de trabajo, paso a paso, para responder a la siguiente pregunta: ¿Que bacterias estan presentes en la muestra?






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






Primeramente busqué por isoprenyl sintethase (http://www.uniprot.org/uniprot/Q8KFR6), y en la página Pfam seleccioné al árbol de proteínas, de las cuales seleccioné 5:


1 http://pfam.xfam.org/protein/G2KWA7_LACSM



2 http://pfam.xfam.org/protein/B9DNS2_STACT



3 http://pfam.xfam.org/protein/K8E4Y2_CARML



4 http://pfam.xfam.org/protein/G2SNF3_LACRR



5 http://pfam.xfam.org/protein/I5B722_9DELT




La familia poliprenil sintetasa juega un rol en el procesamiento de los compuestos orgánicos en las células, añadiendo grupos funcionales a estos (código interpro de la familia: IPR000092, llegué a este código a partir de prosite PDOC00407).




Los códigos de las proteínas escogidas son:

1. Geranyltranstransferase, del gen ispA. Código uniprot: G2KWA7. EC:2.5.1.10.Lactobacillus sanfranciscensis. Según gene ontology, posee una función de dimetilalil transferasa.



Fasta 1. >tr|G2KWA7|G2KWA7_LACSM Geranyltranstransferase OS=Lactobacillus sanfranciscensis (strain TMW 1.1304) GN=ispA PE=3 SV=1
MLMKFNQKKLNRFQTEYIPKIDAVLSKEIKNSSNENLLVNSMQYSLMAGGKRLRPLLVLA
VLESYGVKITDELIKISCAVELLHTYSLIHDDLPEMDNSDYRRGKLANHKKFGDDIAVLA
GDGLLTLAFSWLSDNSLLASQRIKLVSLLSNAAGPKGMVEGQVIDVTSAEKTLDLVGLQT
LDRKKTGELFHYCILAGSVLAKVDEADQQSLSEFAWNFGIAFQIYDDILDAPTDETQEDI
DKNTYVNFLGMQGAKTKLSETVENCIKELEKLENAQSIDLLKSFLSYFQFGKG





2. Geranyltranstransferase, del gen Sca_1145.EC:2.5.1.10. Código uniprot: B9DNS2. Staphylococcus carnosus. Según gene ontology, posee una función de "dimethylallyltransferase activity", que es la misma en el caso 1.



Fasta 2. >tr|B9DNS2|B9DNS2_STACT Geranyltranstransferase OS=Staphylococcus carnosus (strain TM300) GN=Sca_1145 PE=3 SV=1
MNNLIIKQINELLLQSIPLSPLDTNLEESMRYSLEAGGKRIRPLLLIETLKMLSNNSDYS
KGLQTALALEMVHTYSLIHDDLPAMDNDDYRRGKLTNHKVYGEWKALLAGDALLTKAFHL
ISTDSLLDAEARIKLVEGLSDASGHLGMIGGQTLDMESENKQIPLETLQQIHKEKTGALL
TYAIMAAVTIVKPPNEISDILNNYSEHLGLIFQIKDDLLDVYGDEKNLGKPVGSDEKNHK
NTYVTLLGQVETENKLEYHVNQAETSLAQLKKSGYDTTQLEDLTKLFYKRDH




3. Farnesyl diphosphate synthase, del gen BN424_2190. EC:2.5.1.10.  Código uniprot: K8E4Y2. Carnobacterium maltaromaticum. Según gene ontology, posee la función de geranyltranstransferase activity y que en el primer paso de las reacciones enzimáticas, ocurre dimethylallyltransferase activity, que es la misma en caso 1. y 2.



Fasta 3. >tr|K8E4Y2|K8E4Y2_CARML Farnesyl diphosphate synthase OS=Carnobacterium maltaromaticum LMA28 GN=BN424_2190 PE=3 SV=2
MDLNEFKSIALPQLEDTLLEELEIGVPTKGSLFEAMTYSVKAGGKRIRPLLLLATIQSLG
GNIKSGLLAASALEYIHTYSLIHDDLPAMDDDALRRGQPTNHIIYGEALAILAGDGLLTL
GFELLAKSPLTEKQKVRLILALSKAAGANGMVVGQVSDMEGESQKLTLTDLQNIHKKKTG
ELLKFAAYAGAVIVDADQETETQLVKFASHLGLAFQIRDDILDVIGTTAELGKETGMDAV
HQKSTYPGLLTLAGAKKELAEELAKAQTSLANVDNKSVADTQLLEDFITLLEI




4. Geranylgeranyl pyrophosphate synthase, del gen LRC_08340. Código uniprot: G2SNF3. Lactobacillus ruminis. Según gene ontology, posee la función de "transferase activity".



Fasta 4. >tr|G2SNF3|G2SNF3_LACRR Geranylgeranyl pyrophosphate synthase OS=Lactobacillus ruminis (strain ATCC 27782 / RF3) GN=LRC_08340 PE=3 SV=1
MTMNNSELDNFQAEFLPLLNERMDVYLQQLNTRKTLHDSMSYSVDAGGKRIRPMIIMLVC
DSFKKKIDQDVLDVCASLEFVHTYSLIHDDLPAMDNDELRRGKATNHVVFGESMAILAGD
GLLTTAFECLGQTSISAKTKCTLMSRLAFAAGPQGMVNGQVGDIENEGVKLTLPQLRNVH
AQKTGALLRYAFESGGILAGVSDRALGELKELGNCFGLAFQIYDDIMDVVSTPEEMGKAT
HKDQSEHKNTYPGLLGLDGAYEELEKAKANAKAHLEVLAEEFGAKTMLLEELLNYFKAGK
N





5. Geranylgeranyl pyrophosphate synthase, del gen DespoDRAFT_03527. Código uniprot: I5B722. Desulfobacter postgatei. Según gene ontology, posee la función de "transferase activity".




Fasta 5. >tr|I5B722|I5B722_9DELT Geranylgeranyl pyrophosphate synthase OS=Desulfobacter postgatei 2ac9 GN=DespoDRAFT_03527 PE=3 SV=1
MKTFDLSGYLSRNRKLVDDALATVFDEFDRQRELVQAMTHSLMAGGKRVRPALALATADA
LGADPLIALPASCAIEMIHTYSLIHDDLPGMDDDDLRRGVPTCHKQFSEATAILAGDGLL
THAFHILAAPMTCFKVFPDAETRLILVEKISAAAGINGMVEGQMLDMQAEKNPENLPSDS
PGVLTHLKKIHRHKTGAMIEVSVASGAISAGADPDALNALGTYAQNIGLAFQVMDDILNV
IGDPKIMGKAAGTDALHDKMTFPAILGLEESKAFSRQLVADALEALDSYGEKEFKKNSEP
LRAIAAYIINRKR





Hay que destacar que, según Pfam todas las proteínas escogidas poseen el mismo dominio Polyprenyl synthetase (http://pfam.xfam.org/family/PF00348), y que además todas poseen la cualidad de ser transferasas, por lo que luego realicé un alineamiento en uniprot de las secuencias y comparé las diferentes características fisicoquímicas. (Es posible de que el trabajo siga en la base de datos al momento de que lo revise http://www.uniprot.org/align/A20171030AAFB7E4D2F1D05654627429E83DA5CCED81EC4Y).



Luego de hacer el alineamiento, me dieron valores muy altos de identidad (19%) y de similitud (68) (Imagen 1.).




![Valores](https://github.com/CapitanFlint/Solemne-2/blob/master/valoresuniprot.png)



__Imagen 1.__



Luego, seleccioné la opción similarity en el alineamiento, sugiriendo que existen regiones (dominios) altamente conservadas y que muy probablemente están relacionados con la función. Adicionalmente, se detalla en el alineamiento que estas regiones conservadas poseen los sitios activos y de unión de las enzimas. (Imagen 2).




![Similitud](https://github.com/CapitanFlint/Solemne-2/blob/master/similarity7.png)



__Imagen 2.__



Luego, para analizar los patrones fisicoquímicos seleccioné hidrofobicidad y polar al mismo tiempo, y se obtuvo que a pesar de que hay cambios en los aminoácidos de las secuencias, las cualidades polares e hidrofobicas son mantenidas en un nivel alto (Imagen 3.)




![foto3](https://github.com/CapitanFlint/Solemne-2/blob/master/polarhidrofoboo.png)




__Imagen 3.__



Finalmente, a partir de los resultados pienso que desarrollar una hipótesis de evolución divergente para estas proteínas es lo más adecuado, ya que las similitudes son altas y se encuentran en muchos parámetros diferentes: Poseen todas el mismo dominio según Pfam, el porcentaje de identidad es bastante alto, los dominios son muy conservados, y los patrones fisicoquímicos se mantienen a lo largo de las secuencias. Por lo que pienso que hay información suficiente como para sugerir que este es un caso de evolución divergente, ya que tal porcentaje de identidad y similitud no puede haberse producido solo por chance. Por otra parte, es altamente probable de que el plegamiento espacial de las proteínas sea también muy similar, debido a que mantiene las propiedades estéricas. Finalmente, realicé un árbol filogenético en clustalW (Imagen 4.) en el cual se aprecian altos valores de cercanía. Esta hipótesis se respalda además de que las funciones que realizan las proteínas son las mismas (transferir grupos), y que las variaciones nacen a partir de tener como objetivo distintos sustratos. Sin embargo, los pasos de las reacciones químicas son idénticos en todas las proteínas, respaldando la idea de que el sitio activo de estas proteínas posee un ancestro en común, y que las funcionalidades de éstas son causa de evolución divergente.




![arbol](https://github.com/CapitanFlint/Solemne-2/blob/master/arbol.png)



__Imagen 4.__




