# Estudio de la replicación del granulovirus de *Spodoptera frugiperda* en cultivo celular 

\newpage

## Introducción

El desarrollo de sistemas *in vitro* ha sido fundamental para el estudio y la comprehensión del proceso infectivo de los baculovirus a nivel celular. En primer lugar, la posibilidad de reproducir el ciclo replicativo viral en condiciones controladas de laboratorio permite diseñar y probar distintas perturbaciones para conocer su funcionamiento a nivel molecular [@Beperet_2014; @Nguyen_2016]. Por otra parte, las herramientas de cultivo celular facilitan enormemente la aplicación de técnicas clásicas de ingeniería genética y virología para el estudio de baculovirus mutantes [@Kost_2016; @Summers_2006]. En particular, el estudio de mutantes que portan deleciones y los correspondientes virus reparados con una nueva copia del gen, la cual ha sido insertada en un locus distinto al original, representan el enfoque genético más empleado a la fecha para la caracterización de la función molecular de genes baculovirales no anotados [@Wang_2019; @Vanarsdall_2004; @Marek_2013; @Alfonso_2016]. A nivel biotecnológico, el cultivo celular también representa una alternativa atractiva debido a su compatibilidad natural con procesos de escalado y estandarización industriales [@van_Oers_2015; @L_pez_2018; @Thompson_2016; @Airenne_2013].

Para el caso de los granulovirus, se ha experimentado previamente con varias líneas celulares para la producción *in vitro* de diversos virus (AgseGV, CpGV, PhopGV, PrGV y TnGV). Para el caso de TnGV, se exploraron varias líneas celulares embrionarias que inicialmente soportaron la replicación de TnGV, pero luego de 20-25 pasajes perdieron su capacidad de soportar el ciclo infectivo del granulovirus [@Granados_1986; @L_ry_1997]. También se han empleado líneas celulares derivadas de *Cydia pomonella* y de *Phthorimaea operculella* para la amplificación de CpGV y PhopGV, respectivamente. Sin embargo, estas líneas corresponden a cultivos primarios no inmortalizados que han sido cultivados solo por 30 pasajes, lo que no garantiza que las infecciones sean sostenibles al aumentar el número de pasajes [@Naser_1984]. Existen casos menos prometedores también, como el de las líneas celulares embrionarias derivadas de los huevos de *Pieris rapae*, las cuales no son capaces de soportar la replicación de PrGV ni siquiera durante los pasajes iniciales del cultivos [@Dwyer_1988], o las línea celular derivada de *Agrotis ipsilon*, la cual es permisiva para varios nucleopoliedrovirus pero no soporta la replicación de AgseGV [@Alletti_2017]. Estos resultados demuestran que el desarrollo de líneas celulares que soporten la infección por granulovirus es un proceso dificultoso y representa un área vacante. Además, a esto se suma el hecho de que los títulos virales obtenidos para granulovirus son comparativamente más bajos (1 x 10⁵ TCID₅₀/ml) con respecto a los alcanzados por varios nucleopoliedrovirus (1 x 10⁷⁻⁸ TCID₅₀/ml) [@Winstanley_1993] y requiere cultivar las células a temperaturas más bajas (20°C) para asegurar que mantengan su susceptibilidad [@Winstanley_1993; @L_ry_1997].

En un reporte reciente, se confirmó la presencia de actividad transcripcional tardía y producción de BV para el granulovirus PrGV en tres lineas celulares diferentes, entre ellas Sf9 y High Five, dos líneas comerciales ampliamente utilizadas [@Hu_2013]. Para esto, los investigadores construyeron un bácmido de PrGV capaz de expresar los genes *ie-1*, *gp64* y *p35* correspondientes a AcMNPV. El razonamiento para la selección de estos genes se basó en su rol central en el proceso infectivo de los baculovirus. Dentro del grupo de los nucleopoliedrovirus, el gen inmediatamente temprano (*ie-1*) desempeña un papel central en la regulación de la expresión viral temprana y en el proceso de replicación genómica [@Berretta_2013], mientras que *p35* actúa como supresor del proceso apoptótico disparado por la infección viral [@Hershberger_1994] y *gp64* es la proteína de fusión involucrada en la entrada de los BVs a la célula, aunque en los granulovirus esta proteína es reemplazada por la proteína de fusión de la envoltura, *efp* [@Yin_2008], con la excepción de DisaGV, el cual codifica una copia del gen *gp64* [@Ardisson_Ara_jo_2015]. Es posible que las proteínas *ie-1*, *gp64* y *p35* codificados por AcMNPV sean más eficientes al momento de suprimir la respuesta antiviral por parte del hospedador y disparar la subsecuente cascada de expresión viral, en comparación con sus homólogos de granulovirus.

Nuestro laboratorio tiene experiencia previa en el estudio de la expresión geńica de granulovirus en cultivos celulares y en el desarrollo de herramientas de ingeniería genética para la generación de baculovirus recombinantes. Biedma et al [@Biedma_2009], analizó la actividad transcripcional de distintos promotores virales derivados de EpapGV en líneas celulares comerciales y en un contexto de infección por AgMNPV. Por otra parte, Haase *et al* [@Haase_2015_tesis] profundizó la caracterización de la actividad transcripcional de EpapGV y AgMNPV, y además desarrolló un sistema de recombinación novedoso para facilitar la modificación genética de AgMNPV. Teniendo en cuenta estos reportes previos y la experiencia de nuestro grupo en el estudio de baculovirus en sistemas *in vitro*, decidimos caracterizar el proceso replicativo de SfGV en cultivo celular. Para esto, tomamos provecho de la línea celular Sf9, la cual ha sido derivada de tejido ovárico de *S. frugiperda*. Se llevaron a cabo transfecciones con DNA genómico de SfGV y se comparó el efecto citopático frente a un control de AcMNPV marcado con la proteína fluorescente DsRed. Con el fin de estudiar el proceso replicativo en cultivo celular, se inició la puesta a punto de un protocolo de PCR cuantitativa a partir de cultivo celular para obtener medidas de los niveles de DNA genómico en distintos etapas del ciclo viral. Por último, se construyeron los vectores de expresión para las proteínas *ie-1*, *gp64* y *p35*, los cuales serán utilizados a futuro en ensayos celulares para sinergizar la replicación de SfGV en cultivo celular.

## Resultados

### Transfección de células de insecto con DNA genómico de baculovirus

Con el fin de evaluar la capacidad infectiva de SfGV en la línea celular Sf9, la cual ha sido derivada de su hospedador natural *Spodoptera frugiperda*, decidimos llevar a cabo una serie de transfecciones con DNA genómico viral. Como control positivo del proceso de transfección, empleamos el DNA genómico de un virus AcMNPV marcado con la proteína roja fluorescente DsRed, el cual es altamente infectivo frente a las células Sf9 y puede evaluarse fácilmente mediante microscopía de fluorescencia. La extracción de DNA se llevó a cabo de acuerdo al protocolo propuesto previamente [@Eberle_2012]. Brevemente, a partir de una muestra de OB purificados (Figura 2.1A) se realizó una lisis alcalina para disgregar su matriz proteica, seguida de una extracción con solventes orgánicos para purificar el DNA. Una vez resuspendido el DNA en ddH₂O, se confirmo su pureza a través de su perfil de absorbancia a 206 nm mediante mediciones en Nanodrop. Por otra parte, se evaluó la integridad física del DNA purificado mediante electroforesis en gel de agarosa, confirmando la presencia de bandas de elevado peso molecular tanto para la muestra de AcMNPV-DsRED como para SfGV (Figura 2.1B). Una vez obtenido el DNA genómico viral con una pureza y concentración adecuada, procedimos a ensayar dos condiciones de transfección diferentes para el DNA genómico de AcMNPV-DsRed, una empleando el reactivo comercial Cellfectin y la otra con el polímero catiónico polietilendimina (PEI). En ambos casos observamos la presencia de fluorescencia roja a partir del cuarto día post-transfección, sin embargo, la eficiencia de transfección resultó mayor cuando se utilizó Cellfectin, basados en el número de células fluorescentes observadas (Figura 2.2). Basados en estos datos, decidimos utilizar cellfectin en los ensayos subsecuentes de transfección.  

![Preparación de DNA genómico baculoviral para los ensayos de transfección en células Sf9. **A** Bandas opalescentes correspondiente a la fracción de OB purificados obtenidos mediante ultracentrifugación. **B** Electroforesis en gel de agarosa (0.6% p/v) del DNA genómico viral purificado de AcMNPV-DsRed y SfGV. El marcador de peso molecular corresponde a DNA Lambda digerido con la enzima *HindIII*.](assets/virus_adn_gel.png){width=80%}

![Células Sf9 transfectadas con DNA genómico correspondiente a AcMNPV-DsRed (Cellfectin a la izquierda y PEI a la derecha)](assets/ac-dsred_transfection.png){width=100%}

\newpage

### Efectos citopáticos y transcripcionales asociados a la entrada de DNA genómico viral

Una vez confirmada la capacidad del DNA genómico del virus control AcMNPV-DsRed para iniciar la infección en células Sf9, decidimos estudiar los efectos citopáticos inducidos por el ingreso de DNA genómico de SfGV, para lo cual empleamos el mismo procedimiento de transfección que se mencionó anteriormente. Sin embargo, las micrografías de células Sf9 a los siete días post-transfección muestran la ausencia de efectos citopáticos en las células tratadas con respecto al control (Figura 2.3). Aunque las células fueron incubadas por un período prolongado (hasta 14 días), en ningún caso observamos efectos diferenciales entre las células control y el tratamiento.   

![Transfección de células Sf9 con un control negativo de transfección (izquierda) y DNA genómico de SfGV (derecha) empleando Cellfectin.](assets/sfgv_transfection.png){width=100%}

Debido a que no pudo evidenciarse un efecto citopático apreciable a nivel celular en los ensayos previos, se decidió evaluar el progreso del ciclo infectivo de SfGV mediante la medición de los niveles de DNA genómico a través de un protocolo de PCR cuantitativa. Para esto, se diseñó un par de oligonucleótidos para amplificar un fragmento del gen *vp39* específico de AcMNPV y se evaluó la reproducibilidad de esta técnica para muestras de DNA total extraído a distintos tiempos post-tratamiento a partir de células transfectadas con DNA genómico de AcMNPV-DsRed (Tabla 2.1). Como puede observarse, los resultados por triplicado mostraron un elevado nivel de variabilidad entre las distintas réplicas biológicas y no reflejaron un incremento en los niveles de DNA viral a mayores tiempos post-transfección. En contraposición, la curva de calibración mostró un nivel de correlación aceptable (coeficiente de determinación R^2^ = 0.9635), lo que sugiere que los cebadores diseñados amplifican de forma eficiente la secuencia blanco (Figure 2.4).  

![Curva de calibración construida para cuantificar los niveles de DNA viral presentes en muestras de células Sf9 transfectadas con DNA viral de AcMNPV-DsRed.](assets/qpcr_acmnpv.png){width=80%}

\newpage

```table

---
caption: 'Cuantificación de los niveles de DNA virales para distintas muestras de células Sf9 transfectadas con DNA viral de AcMNPV-DsRed'
include: 'datasets/qpcr/qpcr_acmnpv.csv'
---

```

Por otra parte, decidimos explorar la presencia de mRNA virales por RT-PCR como una estrategia alternativa para estudiar el ciclo infectivo de SfGV en cultivo celular. En primer lugar, se diseñaron 4 pares de primers para amplificar un segmento de los mRNA de los genes *ie-1*, *helicase*, *vp39* y *granulin*. La especificidad de los oligos fue confirmada visualmente mediante el análisis de los productos de amplificación a través electroforesis en gel de agarosa (Figura 2.5A). Luego, el par de oligonucleótidos correspondientes a *ie-1* fue utilizado para confirmar la expresión de este gen en células transfectadas con DNA de SfGV (Figura 2.5B).  

![**A** Productos de amplificación específicos para los pares de oligos diseñados para los niveles de expresión de los genes *ie-1*, *hel*, *vp39* y *granulina*. **B** Expresión del gen *ie-1* en células Sf9 transfectadas con DNA de SfGV (siete días post-transfección).](assets/rt-pcr_sfgv_ie1.png){width=80%}

### Construcciones para facilitar la replicación de granulovirus en cultivo celular

Se construyeron vectores para expresar en células de insecto las proteínas de AcMNPV descriptas previamente como pro-virales, *ie-1*, *gp64* y *p35* [@Hu_2013]. A partir de DNA genómico de AcMNPV *wt* se amplificaron los ORF correspondientes a estos genes utilizando oligonucleótidos específicos con los cuales se incorporó un sitio de restricción *XbaI*. Se lograron obtener productos de amplificación específicos, los cuales fueron clonados en el vector comercial pIB/V5-His (Figura 2.5). La secuencia de cada gen clonado fue corroborada a través de secuenciación Sanger.  

![**A** Vector pIB/V5-His utilizado para la construcción de los vectores de expresión. **B** Construcciones empleadas para expresar los genes *ie-1*, *gp64* y *p35* en cultivos celulares de insecto.](assets/construcciones_cultivo.png){width=60%}

## Discusión y perspectivas

En este capítulo presentamos los resultados preliminares obtenidos con respecto a la caracterización del proceso replicativo de SfGV en cultivo celular. A partir de transfecciones con DNA de AcMNPV-DsRed confirmamos que esta metodología es aplicable para monitorear el ciclo infectivo de los baculovirus en cultivo celular. En el caso de SfGV, la introducción del DNA viral por sí sola no sería suficiente para desencadenar un proceso infectivo que lleve a una perturbación apreciable. Resultados similares han sido reportados en otros granulovirus, como el caso de AgseGV [@Alletti_2017], lo que indicaría que este fenómeno es común dentro del género Betabaculovirus. Sin embargo, si pudimos confirmar la presencia de actividad transcripcional inmediatamente temprana en células transfectadas con DNA de SfGV. Esto podría indicar que el bloqueo de la replicación en este granulovirus se localiza en etapas posteriores a la fase inmediatamente temprana del ciclo infectivo de baculovirus.

Como alternativa, decidimos poner a punto una metodología para cuantificar de forma sensible los niveles de DNA viral como una alternativa para estudiar el proceso infectivo de los granulovirus. En este sentido, la optimización en la preparación de muestras de DNA total a partir de cultivo celular resultará importante para aplicar una metodología de PCR cuantitativa para la medición de los niveles de DNA viral y su variación luego de la transfección. Una vez logrado esto, las construcciones ya preparadas podrán ser utilizadas para evaluar si durante una cotransfección del DNA genómico viral junto con los genes *ie-1*, *gp64* o *p35* se observa un incremento en los niveles de replicación viral.

## Materiales y Métodos

### Células y virus

Las células Sf9, (derivadas de *S. frugiperda*) fueron mantenidas a  27°C  en  medio Grace's  (Invitrogen) suplementado con 10%  de  suero  fetal  bovino (Internegocios).  

El stock viral de AcMNPV-DsRed fue propagado mediante infección en monocapa de células Sf9, mientras que SfGV fue amplificado y purificado a partir de larvas infectadas. Brevemente, larvas de *S.* *frugiperda* fueron enviadas desde la estación experimental del Instituto Nacional de Tecnología Agropecuaria (INTA) Tucumán y utilizadas para establecer una colonia dentro del Instituto de Biotecnología y Biología Molecular (IBBM). La colonia se mantuvo con un a dieta artificial y un período de luz controlada (16 horas de luz). 

### qPCR y RT-PCR

Para las reacciones de PCR cuantitativa se empleó una pre-mezcla de reacción 2X con SYBR Green (Roche) a la cual se le agregaron los oligonucleótidos y el molde previo al inicio de la reacción. Las curvas de calibración se construyeron a partir de diluciones seriadas de un stock de DNA genómico derivado de AcMNPV *wt* (concentración de 200 ng/μl).  

La extracción del RNA total presente en las células transfectadas se llevo a cabo mediante extracción en fase orgánica con el reactivo Transzol (Trans). La calidad y concentración del RNA purificado fue chequeado por absorbancia medida en Nanodrop. La reacción de retrotranscripción se llevo a cabo con una transcriptasa reversa derivada de M-MLV (Promega) de acuerdo a las indicaciones del fabricante. El cDNA resultante se empleó como molde para evaluar la presencia del transcripto correspondiente a *ie-1*.  

### Clonado molecular de los genes *ie-1*, *gp64* y *p35*

Los genes mencionados se obtuvieron a partir de una PCR utilizando como molde DNA genómico viral derivado de AcMNPV *wt*. El producto de amplificación fue purificado mediante columnas de sílica, digerido con *XbaI* (New England Labs), y ligado con el vector pIB (Thermo) previamente linealizado con *XbaI* y defosforilado con fosfatasa alcalina termosensible (Promega). Se chequeo la orientación del gen mediante PCR y se corroboró su secuencia mediante secuenciación Sanger.

### Extracción de DNA genómico viral a partir de cultivo celular

Se siguió la metodología propuesta por Eberle y colaboradores [@Eberle_2012]. En este protocolo, los OB son resuspendidos en ddH₂O e incubados con una solución de Na₂CO₃ 1M por 60 minutos a 37°C, con el fin de disgregar la matriz proteica de los mismos y liberar los viriones. Luego se lleva a pH neutro a través de la adición de HCl 1M. A esta suspensión de viriones se le agrega RNAsa A (45 ug/ml) y se incuba por 10 minutos a 37°C. Luego, se agregan 0.1 volúmenes de SDS 10%, 0.1 volúmenes de EDTA 0.5M y proteinasa K para alcanzar una concentración final de 2 mg/ml. Esta mezcla se incubo a 65°C por 1 hora. A partir de aquí se procede a realizar una extracción con solventes orgánicos, una precipitación final con etanol y el pellet de DNA se resuspende en ddH₂O o buffer TE.

### Transfección de células Sf9

Para las transfecciones con Cellfectin II, se realizaron de acuerdo al protocolo sugerido por el fabricante. Primero se mezcló el reactivo Cellfectin II antes de usarlo y luego se mezclaron 8 ul en 100 ul de medio Grace's sin complementado. En un tubo diferente, se mezclaron 1 ug de DNA viral con 100 ul de medio Grace's sin complementar. Luego se combinaron las soluciones conteniendo el medio con Cellfectin II y el medio con DNA viral, se mezcló con ayuda de un vortex y se incubo a temperatura ambiente por 15 minutos. La mezcla lípidos/DNA se agregó de a gotas a las células. Este momento se tomo como tiempo inicial de la transfección.  
Las transfecciones con PEI se llevaron a cabo como se ha descripto previamente [@Ogay_2006]. Primero se preparó una mezcla de DNA viral (1 ug) en 100 ul de solución NaCl 100 mM y se vortexeó para homogenizarla. Esta mezcla se esterilizó por calentamiento a 72°C durante 10 minutos y se dejo enfriar. Luego se le agregaron 3.3 ul de PEI, se mezcló con ayuda de vortex y se incubó por 10 minutos. Los 100 ul conteniendo los complejos DNA/PEI resultantes se agregaron lentamente y de forma uniforme a las células. Este momento se tomo como tiempo inicial de la transfección a partir del cual las células fueron monitoreadas diariamente.

### Oligonucleótidos

```table

---
caption: 'Oligonucleótidos utilizados para amplificar las regiones codificantes de los genes ie-1, g64 y p35.'
include: 'datasets/qpcr/oligos.csv'
---

```
