# CC3102 Teoría de la Computación (2020 Primavera)
_(Actualizado el 2020-09-22-20:00)_

**Propósito:**
Conocer qué problemas 
  puede resolver un computador a través 
  de diversos modelos de computación.
Conocer diferencias en cuanto a la eficiencia de computación de
  distintos problemas.

**Profesor:** [Alejandro Hevia](http://www.dcc.uchile.cl/~ahevia/)
- Cátedras: Martes y Jueves 12:15pm-1:15pm
- Clases auxiliares: Miércoles 4:15pm-5:45pm. 
	- Auxiliares: Ilana Mergudich, y Rodrigo Fuentes.
	- Ayudantes: Antonia Labarca, Diego León, Pablo Paredes Haz, Vicente Rojas
- Sitio web oficial del curso: este y [ucursos](https://www.u-cursos.cl/ingenieria/2020/2/CC3102/1)
- [Programa del curso](https://users.dcc.uchile.cl/~ahevia/cursos/2019/cc3102/programa.pdf)

## Objetivo del curso 

Al finalizar el curso el alumno será capaz de 
conocer qué problemas puede resolver un computador a través de
diversos modelos simples de computación. Algunos de estos modelos son 
usados en diversas áreas como la construcción de compiladores 
(análisis léxico y sintáctico), sistemas de entrada y 
salida de datos discretos, editores de texto, búsqueda de patrones, etc.
Además, el alumno será capaz de conocer y clasificar problemas
  en términos de límites conjeturados en eficiencia 
  teórica en su computación.


## Metodología del Curso

El curso consiste en clases de cátedra más clases auxiliares ambas síncronas (vía zoom). El material docente, el cual incluye presentaciones de clases (anotadas) y pautas de auxiliares, y libros de material de lectura del curso, será publicado en ucursos. Para consultas al equipo docente y discusión de la materia pueden usar el foro de ucursos o escribirle directamente a los auxiliares.

El libro de referencia del curso es el libro de Michael Sipser, 
  _Introduction to the Theory of Computation, 
	Third Edition_. 
También se usará el apunte del profesor Navarro para ciertos capitulos, lo cual se indicará explícitamente.
Se espera que el estudiante lea y estudie en forma independiente el o los capítulos correspondientes
  a la materia vista en clases.

El curso está fuertemente basado en trabajo personal. Se espera que los estudiantes: 
- asistan a las clases de cátedra y auxiliares, (y de ser posible pregunten vía audio o chat),
- lean los capítulos de los libros clase a clase,
- interactúen (hagan preguntas) en el foro de estudiantes y chats (por ej. zoom en cátedras y auxiliares),
- resuelvan los problemas propuestos (dejados en clase), y
- resuelvan los problemas de las guías de problemas propuestos.

Para algunas de las actividades evaluativas, lxs estudiantes deberán estar familiarizados con el software [JFLAP](http://www.jflap.org/).

## Evaluaciones

El curso será completamente evaluado con 3 controles obligatorios y uno recuperativo, cada uno tipo "tarea" (para la casa).
Para resolver cada control tendrán 2 semanas, y su solución tendrá dos partes:
- la solución escrita (un PDF en latex o escrita a mano siempre que tenga letra legible y ordenada), y
- un video de a lo más 3 min explicando lo fundamental de su solución (esto NO es re-describir su solución, sino explicar brevemente la idea principal de cada solución, o con qué se inspiraron, o en base a qué problema o lo hicieron, o si no la entendieron completamente, qué si entendieron). 

Se espera que cada estudiante **entienda bien su solución**. El equipo docente se reserva el derecho a *citar a entrevista personal (vía zoom)* a algunos estudiantes para que expliquen su solución del control. Cuáles estudiantes serán citados será decidido arbitrariamente por el profesor. Note que, el que Ud. sea llamadx _no significa que esté acusado de copia o nada_, simplemente es una manera de confirmar que cada estudiante entiende su solución. Si es llamado a entrevista, la nota final de la solución dependerá tanto de la explicación escrita como de la entrevista.

Tendremos una evaluación extra opcional (del tipo control para la casa) para recuperar la nota al final. El examen (eximidos con 5.0) tendrá parte evaluativa no síncrona (como los controles, sin video) pero tendrá obligatoriamente una parte síncrona, en la forma de una entrevista.

**Escala de notas:** _(Actualizado 2020-09-03-22:30)_ Las evaluaciones serán calificadas con notas 1,3,5 y 7, sin valores intermedios. Dado que las políticas de colaboración (ver siguiente sección) permiten colaborar, esto busca motivarlos a hacer un buen trabajo y no sólo buscar el 4.0. El equipo docente buscará que su tarea tenga "valor agregado", esto es, que el documento muestre que Ud. se esforzó en entender mejor la pregunta y dar una solución más completa o mejor razonada. Sólo contestar lo mínimo probablemente no sea suficiente para aprobar.

## Politica de Colaboración

Para resolver las actividades evaluativas, pueden colaborar entre dos o más personas siempre que usen la política de _Whiteboard_ (o "pizarrón en blanco"), esto es
- Al juntarse, pueden compartir un pizarrón o editor donde ambxs escriban y discutan cómo resolver el problema, pero **nadie puede grabar ni tomar fotografías**.  
- Al terminar, se "borra" (se cierra), y luego de 30min, cada unx escribe/redacta su solución en forma individual.

Se prohibe buscar soluciones por Internet, o usar las soluciones de otra persona.
(En serio, no use soluciones encontradas en Internet, no sólo por un tema ético sino porque hay muchas equivocadas o que usan ideas o conceptos que vemos distinto en este curso).

Para más detalles o en caso de duda, preguntar a los auxiliares o al profe.

Actualización 2020-09-22: Existe un servidor de [Discord](https://discord.gg/V6G9c4Y) para el curso. Está disponible para contactar a los auxiliares, ayudantes y el profesor; además puede usarlo para colaborar si lo desea. Si no sabe usarlo, preguntar en el foro.

## Calendario

Semana | Clase  | Tema                 | Contenidos        | Lecturas                       | Comentarios    
:----  | :----: | :--------------:     | :--------------   | :--------------                |  :---------
1      | 0      | Introducción         | Motivación        | Navarro Cap. 1, Sipser Cap. 0  |  
1      | 1      |                      | Conceptos Básicos | idem   |  
2      | 2      | Lenguajes Regulares (LR)  | Autómatas finitos (AF) determinísticos, operaciones y clausura  | Navarro Cap. 2.2, Sipser Cap. 1.1 |  
2      | 3      |                      | AF no deterministas, equivalencia | Navarro Cap. 2.3,2.5, Sipser Cap. 1.2, HMU: Cap. 4.4 (pag.155-165)  | 
3      | 4      |                      | Continuación clase pasada  |  | 
3      | 5      | Expresiones Regulares  | Clausura usando no-determinismo, Expresiones Regulares  | Navarro Cap. 2.1; Sipser Cap. 1.2, 1.3 | 
4      | 6      |                      | ER Parte II (Equivalencia AF y ER), Props. Algorítmicas de LR.   | Navarro Cap. 2.3,2.4,2.6,2.9; Sipser Cap. 1.2, 1.3 | 
4      | 7      | Lema del Bombeo  | Enunciado y Ejemplo | Navarro Cap. 2.8; Sipser Cap. 1.4 | 
5      | 8      | Lenguajes Libres de Contexto (LLC)| Gramáticas Libres de Contexto (GLC)   | Navarro Cap. 3.1,3.2; Sipser Cap. 2.1  |
5      | 9      |                      | Autómatas de Pila (AP)  | Navarro Cap. 3.3; Sipser Cap. 2.1  | 
6      | 10     |                      | Equivalencia GLC y AP  | Navarro Cap. 3.4,3.5; Sipser Cap. 2.2  | 
6      | 11     |                      | Teorema de Bombeo, Props. Algorítmicas y Clausura LLC  | Navarro Cap. 3.6,3.7,3.8; Sipser Cap. 2.3  | 


## Bibliografia
- **[Sipser]** Michael Sipser, **Introduction to the Theory of Computation, 
	Third Edition*, 2013. Cengage Learning Press.
	(Ver ucursos.)
- **[Navarro]** Gonzalo Navarro, **Teoría de la Computación (Lenguajes Formales, Computabilidad y Complejidad), Apuntes y Ejercicios**, Universidad de Chile, Dic. 2018.  
  Disponible desde [la página del prof. Navarro](http://www.dcc.uchile.cl/~gnavarro/apunte.html). 
- **[HMU]** J. Hopcroft, R. Motwani, y J. Ullman. *Introduction to Automata Theory, Languages and Computation*. 3er edition, Addison-Wesley, 2007.
- **[LP]** H. Lewis y C. Papadimitrou. Elements of the Theory of Computation. Prentice-Hall, 1981.
