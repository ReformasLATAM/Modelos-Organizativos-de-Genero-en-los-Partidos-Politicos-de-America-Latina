# Modelos Organizativos de Género en los Partidos Políticos de América Latina

Bienvenidos/as al repositorio GitHub de la base de datos "Modelos Organizativos de Género en los Partidos Políticos de América Latina" mantenida por integrantes del Observatorio de Reformas Políticas en América Latina.

## Contenidos

-   [Resumen](#resumen)
-   [Descripción](#descripción)
-   [Citado](#citado)
-   [Referencias](#referencias)

## Resumen

El objetivo de la base de datos es contar con información para describir y conocer los modelos organizativos formales que se han desarrollado en los partidos políticos latinoamericanos; identificar cuáles son más amigables a las mujeres y evaluar en qué medida estas estructuras organizativas contribuyen a la representación descriptiva de las mujeres en los Poderes Legislativos. Si bien la política informal es clave para comprender cómo funcionan los partidos políticos (Bjarnegård y Kenny 2016; Kenny y Verge 2016; Piscopo 2016; Freidenberg y Levitsky 2006); en esta investigación la estrategia se centra en el análisis de las reglas formales, a partir de las cuales se configuran los escenarios de poder en los que las y los militantes se mueven, participan, se legitima la distribución de los incentivos y el modo en que se toman las decisiones.

Los modelos organizativos suponen criterios territoriales, funcionales y/o identitarios (como los que se encuentran basados explícitamente con el género) y fijan el modo en que se distribuyen tareas y acciones para alcanzar las metas, así como también establecen el modo en que se distribuyen los incentivos de participación (Panebianco 1982). Los modelos organizativos formales son las estructuras internas del partido, delineadas en las reglas estatutarias, que establecen el modo en que se dan las relaciones de poder, se toman las decisiones y se pauta el modo en que se distribuyen los incentivos de participación (selectivos y/o colectivos) (Panebianco 1982; Janda 1980). 

La base de datos sustenta el trabajo “Modelos organizativos, reglas formales y feminización de los partidos políticos en América Latina”, que es una investigación que forma parte del Observatorio de Reformas Políticas en América Latina (#ObservatorioReformas), del Instituto de Investigaciones Jurídicas de la Universidad Nacional Autónoma de México y la Secretaria para el Fortalecimiento de la Democracia de la Organización de los Estados Americanos. La investigación se encuentra en proceso de elaboración.

La selección de los partidos que son considerados como relevantes en 16 países de América Latina y que forman parte de las unidades de observación de este estudio, tiene como antecedente la empleada para la investigación de Alcántara Sáez y Freidenberg (2001), quienes crearon una matriz de selección basada en cuatro criterios. Los cuatro criterios son que un partido: a) hubiera obtenido representación en la Cámara baja en las tres últimas elecciones legislativas (fuerza numérica expresada en escaños o en votos obtenidos); b) que hubiera superado la barrera del 5% electoral en las tres últimas elecciones legislativas en la Cámara baja; c) que tuviera representación en todos los distritos electorales del país (fuerza territorial) o que su representación en determinados distritos fuera claramente significativa; y d) que contara sustantivamente en la dinámica partidaria del sistema político, es decir, que ejerciera capacidad de influencia en el sistema político (aun cuando no cumpliera las anteriores).

En una primera etapa, se aplicaron los cuatro criterios en 110 partidos en 16 países de la región. El resultado arrojó que 54 partidos cumplen los cuatro criterios de “partidos relevantes” y que son los que se analizaron en los dos últimos periodos legislativos de cada país. Con respecto a los dos primeros criterios no hubo dificultad en su operacionalización. El tercer criterio, que mide la fuerza territorial, se aplicó a partir del porcentaje de distritos electorales en los cuales los partidos presentaron candidaturas a la Cámara baja. Finalmente, el cuarto criterio, que mide la influencia en el sistema político, se consideró si habían logrado ganar elecciones presidenciales, si cuentan con un alto nivel de institucionalización (Freidenberg 2016) o tuvieran un papel relevante dentro del sistema partidista por su capacidad de chantaje, es decir, de alterar las decisiones de los otros partidos (Sartori 1992)

En una segunda etapa, se solicitó a expertos y expertas del Observatorio de Reformas Políticas en América Latina que revisaran la selección y la aplicación de los criterios al universo de partidos evaluados. El papel de las y los investigadores consistió en validar la propuesta de selección de partidos que le remitió el equipo responsable de la investigación. El ejercicio de evaluación externa fortaleció la propuesta de selección al enriquecer y esclarecer el papel que juegan los partidos en cada uno de los sistemas partidistas de la región.

Una vez que se identificaron las 54 unidades de observación relevantes, se identificó en cada uno de sus Estatutos, los artículos en donde se describe el modo en que se organizan los partidos en relación a la participación política de las mujeres. Los Estatutos se recopilaron de los sitios web oficiales de los partidos, de las consultas a las autoridades electorales de cada país, o en su defecto de las redes sociales en donde se tuviera acceso. Dichos Estatutos fueron publicados en el sitio web del Observatorio de Reformas Políticas en América Latina.

Integrantes del Observatorio de Reformas Políticas en América Latina recopilaron y codificaron la información. Las personas responsables de la recopilación de los datos son Carlos Guadarrama (Facultad Latinoamericana de Ciencias Sociales, sede México); Mauricio Morales (Facultad de Ciencias Políticas y Sociales, UNAM); Lucía Rosemblat (Universidad de Buenos Aires); Daniela Sosa (Facultad de Estudios Superiores Aragón, UNAM); Fernanda Nicoletti (Facultad de Estudios Superiores Acatlán, UNAM) y Eduardo Flores (Facultad de Estudios Superiores Acatlán, UNAM), mientras que las personas responsables de la codificación de los datos son Flavia Freidenberg (Instituto de Investigaciones Jurídicas, UNAM); Carlos Guadarrama (Facultad Latinoamericana de Ciencias Sociales, sede México) y Karolina Gilas (Facultad de Ciencias Políticas y Sociales, UNAM)

## Descripción

El directorio `./Data/` contiene el archivo `./Data/DD_ModelosOrganizativosGenero` en el cual se encuentra toda la información relevante respecto a la base de datos de los modelos organizativos de género en los partidos políticos de América Latina. En específico, la base de datos se compone de las siguientes variables:

-   `partido`: nombre de la organización partidista considerada en la muestra.

-   `país`: nombre del país en el cual se llevó a cabo la reforma al régimen electoral de la cámara baja en América Latina.

-   `siglas_pais`: siglas del país de acuerdo con el código de tres letras ISO (por ejemplo: ARG, MEX, SAL) disponible en: http://utils.mucattu.com/iso_3166-1.html 

-   `representación_descriptiva`: el porcentaje de mujeres legisladoras electas (por todos los principios de representación) en los partidos políticos en cada uno de los dos períodos legislativos.

-   `modelo_organizativo`: etiqueta de la estructura organizativa de acuerdo a lo que señalan los Estatutos partidistas. Sus valores van de 0 a 3, donde 0 es lo menos amigable y 3 es lo más amigable a las mujeres; 0 = no tiene; 1 = Estructura burocrática; 2 = Estructura autónoma 3 = Mixto (Estructuras burocrática y autónoma).

-   `ifreg`: Índice de Fortaleza del Régimen Electoral de Género de Caminotti y Freidenberg (2016).

-   `institucionalización`: años transcurridos entre el año de creación del partido y la fecha en que se realizó esta investigación (2022).

-   `ideología`: autoidentificación de las personas legisladoras a partir de las Encuestas a personas legisladoras realizadas para el Proyecto de Élites Parlamentarias de América Latina.

-   `genero_presidencia`: indica la presencia de mujeres en presidencias de partidos políticos en al menos un periodo observado, toma valores que van de 0 = no tiene y 1 = si tiene.

## Citado

``` r
Freidenberg, Flavia. Dir., 2022, “Modelos Organizativos de Género en los Partidos Políticos de América Latina”. Observatorio de Reformas Políticas en América Latina (1978-2022). Ciudad de México: Instituto de Investigaciones Jurídicas (IIJ-UNAM) y Washington, D.C.: Secretaría para el Fortalecimiento de la Democracia de la Organización de los Estados Americanos (SFD/OEA), V1. DOI: https://doi.org/10.6084/m9.figshare.20341359.v1.
```

## Referencias

Alcántara Sáez, Manuel y Freidenberg, Flavia. 2001. Eds. Los partidos políticos en América Latina. Salamanca: Ediciones Universidad de Salamanca.

Bjarnegård, Elin y Kenny, Meryl. 2016. Comparing candidate selection: A feminist institutionalist approach. Government and Opposition 51(3): 370–392.

Caminotti, Mariana y Freidenberg, Flavia. 2016. “Federalismo electoral, fortaleza de las cuotas de género y representación política de las mujeres en los ámbitos subnacionales en Argentina y México”. Revista Mexicana de Ciencias Políticas y Sociales 61 (228): 121-144.

Freidenberg, Flavia. Ed. 2016. Los sistemas de partidos en América Latina 1978-2015. 2 tomos. Ciudad de México: Instituto Nacional Electoral e Instituto de Investigaciones Jurídicas, UNAM.

Freidenberg, Flavia y Levitsky, Steve. 2006. “Informal Party Organizations in Latin America”, in Gretchen Helmke and Steven Levitsky, eds. Informal Institutions and Democracy: Lessons from Latin America. Washington, D.C.: John Hopkins University Press, 178-197.

Janda, Kenneth. 1980. Political Parties: A Cross-National Survey. New York: The Free Press.

Kenny, Meryl y Verge, Tània. 2016. “Opening Up the Black Box: Gender and Candidate Selection in a New Era.” Government and Opposition 51(3): 351–69.

Panebianco, Angelo. 1982. Modelos de partidos. Madrid: Alianza.

Piscopo, Jennifer M. 2016. “When informality advantages women: Quota networks, electoral rules and candidate selection in Mexico”. Government and Opposition 51(3): 487–512.

Sartori, Giovanni. 1992. Partidos y sistemas de partidos. Madrid: Alianza.