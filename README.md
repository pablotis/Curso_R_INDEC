
# Programa y materiales de cursada

***


> Docentes: 

__Pablo TISCORNIA.__
Licenciado en Sociología, Universidad de Buenos Aires. En curso, Maestría en Generación y Análisis de la Información Estadística, Universidad Nacional Tres de Febrero (UNTREF). Actualmente se desempeña como Técnico Analista en la Dirección de Encuesta Permanente de Hogares (EPH) del Instituto Nacional de Estadísticas y Censos (INDEC) y como docente a cargo del curso de posgrado “Introducción a R para Ciencias Sociales. Aplicación práctica en la Encuesta Permanente de Hogares” junto a Guido Weksler, en el marco del programa CEIA – Centro de Estadística Aplicada e Informática Aplicada - Facultad Latinoamericana de Ciencias Sociales (FLACSO).

__Carla BARRECA.__
Licenciada en Economía (UNMdP) y Magíster en Economía Aplicada (UTDT). Se desempeña como analista de datos en la Dirección Nacional de Estadísticas de Condiciones de Vida del Instituto Nacional de Estadística y Censos (INDEC), realizando análisis estadístico/econométrico de la información vinculada a las encuestas a hogares. Actualmente se encuentra trabajando en la Encuesta de Nacional de Gastos de los Hogares, principalmente con el cálculo de estructuras de gastos y consumo de los hogares, imputaciones de datos faltantes mediante modelos de machine learning y cálculo de errores por muestra.

<br>

***

<br>

## Fundamentación

La actividad se inscribe en la política de formación del Instituto Nacional de Estadística y Censos (INDEC) orientada a Desarrollar programas de formación y actualización del personal profesional, técnico y operativo del Instituto acordes a los cambios tecnológicos y en los procesos de trabajo.
  
R es un programa para procesamiento de datos y análisis estadístico. Sus principales virtudes son las de ser gratuito (no es necesario comprar una licencia), de código abierto, y con una capacidad de expansión hasta ahora ilimitada. Es también un programa multiplataforma (permite trabajar en diferentes sistemas operativos –Windows, Mac, Linux, Unix- y, a la vez, se integra completamente con otros programas de código abierto como Python, SQL). En este sentido, R se encuentra completamente alineado con los principios de transparencia y los fundamentos de gobierno abierto.
  
Dada la forma en la que se ejecuta, R se destaca por su capacidad para trabajar de forma sistemática y ordenada, permitiendo reproducir procesamientos y, con el tiempo, optimizar procedimientos a través de funciones propias que eviten tener que escribir una y otra vez esas instrucciones repetitivas, imposibles de eludir en otros programas. Sus gráficos son una de las principales características, con calidad de publicación y posibilidad ilimitada para definir cualquier aspecto del mismo. 
  
El mundo de R y su plataforma de trabajo más conocida, RStudio, han crecido de tal manera que en el mismo programa es posible procesar, analizar y elaborar informes o reportes en una gran variedad de formatos (.html, .pdf, .doc, presentaciones en diapositivas, entre otros). 
  
Por último, pero no menos importante, debido al crecimiento global de su comunidad de usuarios y usuarias que, tanto a nivel individual como institucional, ponen a disposición sus sintaxis y comparten sus problemas, R ha incrementado su capacidad de consulta y respuesta, como así también potenciado la innovación de funciones para resolver los más diversos problemas sin tener que tropezar dos veces con la misma piedra. 
  
En este sentido, se ha organizado la presente actividad con la finalidad de formar a los técnicos del Instituto en las posibilidades y ventajas que ofrece en Software Estadístico R para el análisis y procesamiento de la información estadística que producen las distintas áreas del INDEC.

## Contribución esperada

Con la presente actividad se espera contribuir al análisis y procesamiento de la información estadística producida por el INDEC con la finalidad de lograr informes y publicaciones de datos de calidad, mediante la utilización de los comandos del Software Estadístico R. 

## Perfil del participante

Personal del INDEC que necesita incorporar al programa R como herramienta de trabajo.


## Objetivos

  * Objetivo principal
El presente Taller tiene como objetivo principal introducirse en el aprendizaje del lenguaje de programación R.

  * Objetivos secundarios
•	Se espera que los participantes logren:
•	Incorporar herramientas prácticas para el procesamiento de datos, haciendo énfasis en la producción y el análisis de la información como así también en la visualización y presentación de los resultados.
•	Incorporar la identificación de los diferentes tipos de datos con los participantes se pueden cruzar, y así, trabajar en función de ello de la forma más óptima.
•	Lograr un análisis estadístico descriptivo de datos de corte transversal en general, aunque se utilizarán, en la práctica, bases de datos de encuestas a hogares.


## Estrategias metodológicas y Recursos didácticos

Las clases del curso serán teórico-prácticas. Habrá una primera presentación conceptual para inmediatamente pasar a utilizar el programa. Se prioriza la utilización del mismo durante la clase y trabajar sobre los desafíos que se van planteando. A lo largo del curso se brindarán sintaxis al estilo “notas de clase”, en las cuales se plasman conjuntamente las líneas de código que se exponen durante la cursada y su correspondiente explicación respecto a los procedimientos realizados. A su vez, los participantes dispondrán de un script o sintaxis con el código de cada clase para ir corriendo secuencialmente los ejercicios en paralelo al docente. Finalmente, se propondrán ejercicios para resolver fuera de la clase con el objetivo de reforzar los conocimientos vistos en las mismas.


*** 

### Clases y contenido


__Módulo 1 - Introduciendo a R:__
  
+ Temas de clase: 
  + Descripción del programa “R”. Lógica sintáctica del lenguaje y comandos básicos
  + Presentación de la plataforma RStudio para trabajar en “R”
  + Caracteres especiales en “R”
  + Operadores lógicos y aritméticos
  + Definición de Objetos: Valores, Vectores y DataFrames
  + Tipos de variable (numérica, de caracteres, lógicas)
  + Lectura y Escritura de Archivos

  * [Introducción a R](Clase%201/Clase%201%20-%20Introduccion%20a%20R.nb.html)
  * [Práctica guiada](Clase%201/Clase%201%20-%20Practica%20guiada.nb.html)
  * [Práctica independiente](Clase%201/Clase%201%20-%20Practica%20independiente.nb.html)

__Módulo 2 – Trabajando con bases de datos__
 
+ Temas de clase:
  + Limpieza de Base de datos: Renombrar y recodificar variables, tratamiento de valores faltantes (missing values/ NA´s)
  + Seleccionar variables, ordenar y agrupar la base de datos para realizar cálculos
  + Creación de nuevas variables
  + Aplicar filtros sobre la base de datos
  + Construir medidas de resumen de la información
  + Tratamiento de variables numéricas (edad, ingresos, gastos, horas de trabajo, cantidad de hijos / componentes del hogar, entre otras).
  + Ejercicios prácticos para aplicar lo expuesto:
 

__Módulo 3: Gráficos y visualización de la información__  
  
+ Temas de clase:
  + Gráficos básicos de R (función “plot”): Comandos para la visualización ágil de la información
  + Gráficos elaborados en R (función “ggplot”): 
    + Gráficos de línea, barras, Boxplots y distribuciones de densidad
    + Parámetros de los gráficos: Leyendas, ejes, títulos, notas, colores
    + Gráficos con múltiples cruces de variables.


__Módulo 4: Documentación en R. Generación de reportes/informes__
  
+ Temas de clase:
  + Manejo de las extensiones del software “Rmarkdown” y “RNotebook” para elaborar documentos de trabajo, presentaciones interactivas e informes:
    + Opciones para mostrar u ocultar código en los reportes
    + Definición de tamaño, títulos y formato con el cual se despliegan los gráficos y tablas en el informe
    + Caracteres especiales para incluir múltiples recursos en el texto del informe: Links a páginas web, notas al pie, enumeraciones, cambios en el formato de letra (tamaño, negrita, cursiva)
    + Código embebido en el texto para automatización de reportes


__Módulo 5: Presentación de R Intermedio:__

+ Temas de clase: 
  + Acercamiento a técnicas más sofisticadas en R, útiles para automatizar el procesamiento periódico de la información:
    + Estructuras de código condicionales
    + Loops
    + Creación de funciones a medida del usuario
  + Herramientas para continuar el aprendizaje en R: Foros reconocidos de usuarios de R. Comunidades donde se comparten conocimientos, experiencias, consultas. Comandos para acceder a los documentos de ayuda.


## Trabajos prácticos: R en concreto / examen

+ Se presentará a los/as alumnos/as problemas concretos vinculados a la EPH y en relación a las experiencias que se fueron volcando a lo largo de la cursada. Se deberán abordar mediante el uso de R, aplicando lo aprendido en los módulos anteriores. En conjunto se expondrán los desafíos que emergen en el momento y la evaluación de las herramientas adecuadas para su abordaje y resolución. Entre los temas giran aquellos vinculados a la distribución personal del ingreso/Construcción de percentiles de ingreso; el mercado laboral a través de la herramienta Panel de datos; la documentación en R (Estilo de Notas de Clase).
+	Espacio para consultas puntuales sobre los temas vistos durante el curso y presentación del trabajo final a entregar.


#### Librerias a instalar

```
install.packages(c("tidyverse","openxlsx",'ggplot2','ggthemes', 'ggrepel','ggalt','kableExtra','GGally','ggridges','fs','purrr','rmarkdown'))
```

## Evaluación de los aprendizajes

Evaluación del proceso: mediante la supervisión de la realización de los ejercicios realizados en clase; puesta en común de las ejercitaciones no presenciales propuestos por los docentes.

Evaluación de producto: a través de la incorporación e integración de los conceptos y herramientas vistas en el curso, y de la aprobación de la ejercitación no presencial y del trabajo práctico final individual.

Los criterios de evaluación tendrán en cuenta la capacidad de incorporar, integrar y aplicar los conceptos y herramientas abordados durante el desarrollo del curso.

## Antecedentes

- __2018. _Curso de R para procesamiento de datos de la Encuesta Permanente de Hogares_, dictado por [Guido Weksler](https://independent.academia.edu/guidoweksler), [Diego Kozlowski](https://sites.google.com/view/diego-kozlowski/home) y [Natsumi Shokida](https://rpubs.com/natsumi_shokida/) para el INDEC + CEPED.

## Bibliografía

-	Wickham, H., & Grolemund, G. (2016). R for data science: import, tidy, transform, visualize, and model data. “O’Reilly Media, Inc.”. https://es.r4ds.hadley.nz/
-	Antonio Vazquez Brust (2019). Ciencia de Datos para Gente Sociable. https://bitsandbricks.github.io/ciencia_de_datos_gente_sociable/
-	Wickham, H. ggplot2: elegant graphics for data analysis. Springer, 2016. https://ggplot2-book.org/

