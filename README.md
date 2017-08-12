# laboratorio-01-bioinformatica

## Nombre: _Benjamin Flores Oviedo_ 

## Parte 1: enfermedades geneticas y genes


### Busca una enfermedad genetica humana en alguna base de datos de literatura, i.e., Pubmed,Google Scholar, o en bases de datos de enfermedades genéticas, e.g., OMIM

_R_: Enfermedad de niemann-pick. 


### Describe en no mas de 4 lineas la causa y lo que lo provoca la enfermedad que escogiste

_R_: La enfermedad de niemann-pick es causada en una mutacion del gen NPC1 que genera un déficit en la enzima esfingomielinasa, que participa en la ruta de degradación de los esfingolipidos, esto provoca una acumulación desconrtrolada de lipidos en distintos organos como el cerebro. 

### ¿cuál(es) gene(s) han sido relacionados con esta enfermedad?

_R_: NPC1.

### ¿Tiene nombre alternativo el gen?

_R_: Otro nombre alternativo del gen es el NPC.

### ¿En que cromosoma esta? ¿Cuantos exones tiene? ¿Cuántas isoformas de transcritos?

_R_: Se encuentra en el cromosoma 18, posee 29 exones y 9 isoformas del transcrito.

### ¿Que tipo de proteina es codificada por este gen? ¿Cual es su numero EC?

_R_: EL gen codifica para una proteinas trasportadora intracelular de colesterol. Al no ser una enzima no posee numero EC.

### ¿Que gen están inmediatamente rio arriba/abajo? 

_R_: Rio arriba se encuentra el gen ANKNRD29 y rio abajo se encuentra C18ORF8.

### ¿Cual es la longitud de tu gen?

_R_: Posee una longitud de 80,434 K.

### ¿Cuántas variantes de tu gen hay descritas y en qué posiciones?

_R_: El gen posee 281 variantes y algunas posiciones son: Chr18:21111666, Chr18:21111681, Chr18:21111817.

### ¿Las sustituciones corresponden a cambios sinónimos o no sinónimos?

_R_: Las variantes seleccionadas, en la pregunta anterior, presentan su mutacion en los extremos 3'UTR, por ende, serian sinónimas. 

### ¿Existen ortólogos de tu gen en otras especies? ¿Cuántos?

_R_: Existen 217 organismos que tienen el ortologia con el gen humano NPC1.

### ¿Y paralógos? ¿Hay pseudogenes? ¿Cuántos?

_R_: En la base de datos de NCBI no se encuentran paralógos ni pseudogenes reportados.


## Parte 2: Rutas y procesos metabólicos

### Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles?

_R_: Los nombres del reportado por Kegg son los mismo que reporta NCBI, que son NPC1 y NPC.

### ¿En qué rutas metabólicas participa la proteina codificada por tu gen?

_R_: participa en la ruta metabolica de los lisosomas.

### ¿Cuál es el número de identificación de tu gen (entry number)?

_R_: 04142

### En general, cada unidad dentro de una base de datos tiene un número o código de identificación único. De esta forma, uno puede obtener exactamente lo que quiere dentro de un oceano de otras cosas ¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso?

_R_: El gen esta presente en la base de datos de REACTOME, BioCyc y UniProt con numeros de accesos 5216153 , 06833 y O15118 respectivamente.

### La figura más cásica que se puede obtener es el diagrama con una ruta metabólica. Probablemente tu gen está involucrado en más de una. Escoge una y toma un pantallazo para que lo incluyas en tu informe.

[Ruta metabolica](https://drive.google.com/file/d/0B0rzqm380_roMlVXR2VONW5lNTQ/view?usp=sharinghttps://drive.google.com/file/d/0B0rzqm380_roMlVXR2VONW5lNTQ/view?usp=sharing)

### ¿En qué otras rutas metabólicas está involucrado tu gen?

_R_: El gen NPC1 solo esta involucrado en la ruta de los lisosomas, debido a que es una proteina de transporte de colesterol tipo 2 que solo esta presente en estos organelos.

### ¿Qué significan los cuadros verdes en el diagrama?

_R_: Los cuadros verdes representas proteinas involucradas en la ruta metabolica.

### ¿Con qué rutas se cruza la ruta metabólica?

_R_: La proteina codificada por el gen NPC1, al encontrarse en la membrana de los lisosomas, participa en las distintas rutas de degradación como la regulacion de la autofagia y degradación de los fagosomas.  

### ¿Cuántos "dominios" forman la anotación GO? Ve a "Tools" --> "AmiGO 2" y escribe en la casilla de búsqueda GO:0006096

_R_: 

### ¿A qué corresponde este término y qué información te entrega la página?Haz clic en "Graph Views" y examina el gráfico. Anota 10 sub-categorías GO a la cual GO:0006096 pertenece.

_R_: Fosforilacion de nucleotidos, procesos metabolicos del nucleosido difosfato, procesos metabolicos de ribonucleotidos, procesos metabolicos de ATP, procesos metabolicos del piruvato, procesos metabolicos del ADP, procesos metabolicos de acidos organicos, procesos catabolicos de carbohidratos, procesos metabolicos de acidos monocarboxilicos, procesos metabolicos deribados de carbohidratos, entre varios otros.     

## Parte 3: Descargando secuencias, convirtiendo formatos.

### ¿Cuántos items fueron encontrados? ¿cuántos en animales?Probablemente tus resultados fueron una mezcla de fragmentos de genes, regiones codificantes parciales, genes completos, etc. Filtra tus datos por mRNA, animales, RefSeq. Haz clic en la entrada para la secuencia de GAPDH de gallina (_Gallus gallus_).

_R_: En NCBI se encontraron 35 bases de datos cada uno con una gran cantidad de items. Filtrando los datos por mRNA, animales y RefSeq. se obtuvo 439 item mRNA, 684 items de animales y un total de 25702 de item pertenecientes a RefSeq. 

### ¿Cuál es la longitud del gen?

_R_: 1288 bp

### ¿Cuál es la referencia bibliográfica más reciente?

_R_: La referencia bibliografica proviene del articulo "Binding chicken Anx2 is beneficial for infection with infectious bursal disease virus" publicado el 09-JUL-2017.

### ¿Cuál es el número de acceso?

_R_: 26221766

### __Descarga la secuencia en formato fasta y agrégala a tu informe__

[Secuencia FASTA](https://drive.google.com/file/d/0B0rzqm380_roX2luZFZwVVdMdlE/view?usp=sharing)

[Secuencia NEXUS](https://drive.google.com/file/d/0B0rzqm380_roUU1KRHNkTG9XS00/view?usp=sharing)

## Parte 4: Buscando artículos científicos en linea

[Alerta de busqueda NCBI PubMed](https://drive.google.com/file/d/0B0rzqm380_roelpwcms3ekpuVms/view?usp=sharing)

[conﬁrmación a la suscripción Nature](https://drive.google.com/file/d/0B0rzqm380_roemlNUHJHNHB4bEk/view?usp=sharing) 

### ¿Son los resultados idénticos o no?

_R_: Para el caso de "Human Microbiome" los resultados fueron los mismos lo que cambio es la palabra remarcada de cada articulo, en el caso del uso de comillas, en el pequeño resumen que tienen, solo destacan "Human Microbiome". Mientras que en caso donde no se utilizo las comillas las palabras remarcadas son "Human Microbiome" tanto juntas como separada. En resumen los articulos buscados utilizando comillas solo daran resultados donde aparezcan el(los) caracter(s) juntos, entretanto al no usar comillas los resultados seran donde estos caracteres esten juntos o separdos.

### ¿En qué cambiaron los resultados de la búsqueda?

_R_: En este caso los resultados fueron los mismos.  

### ¿Qué encuentras en los resultados? Prueba sin el rango también

_R_: los resultados son distintos entre si.

### Describe tus resultados

_R_: Al buscar el articulo restringido al tipo de archivo solo cambio algunas paginas encontradas.

### ¿En qué cambian los resultados de la búsqueda?
 
 _R_: En este caso los resultados entregados en cada caso fueron totalmente distintos. En el caso donde se busco con "+ temperatura" los articulos encontrados relacionan la investigacion con la temperatura, pero no es asi en el caso de "-temperatura".
 
 ### De nuevo, ¿en qué cambian los resultados de la búsqueda?
 
 _R_: Los resultados son distintos, ya que uno busca articulos que contengan el caracter "soil" o "Human pathogens", mientras el otro busca paginas que relaciones estos dos caracteres.



