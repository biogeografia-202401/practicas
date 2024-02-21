Practica 3. Técnicas de ecología numérica, reproducibilidad, redacción,
estilos de formato, tablas, citas y referencias
================
<b>José-Ramón Martínez-Batlle</b> (<jmartinez19@uasd.edu.do>) <br>
Facultad de Ciencias, Universidad Autónoma de Santo Domingo (UASD) <br>
Santo Domingo, República Dominicana

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

# Practica 3. Técnicas de ecología numérica, reproducibilidad, redacción, estilos de formato, tablas, citas y referencias

> Entrega: 5 de marzo, 16:00 horas.

> Entrega tu archivo vía correo electrónico en formato nativo. Si como
> procesador de texto, usaste software de interfaz gráfica de usuario
> (GUI), como Microsoft Word o LibreOffice Writer, entrega tanto el
> archivo nativo .docx o .odt como el PDF. Si usaste procesadores de
> texto sin GUI, como LaTeX, Overleaf, RMmarkdown, entrega tanto el PDF
> como la carpeta (comprimida en ZIP) conteniendo los archivos
> necesarios para compilar el PDF.

“Calentemos motores”. Tanto el contenido propiamente (“el fondo”) como
la presentación (“la forma”) de tu redacción son importantes. El
objetivo de esta práctica es ayudarte a mejorar tales aspectos.

Esta práctica se basa en un informe personalizado que analiza, con
técnicas de ecología numérica, un sencillo conjunto de datos simulados.
Usarás tu propio conjunto de datos simulados, y los “analizarás” de
forma reproducible. Igualmente, y no menos importante, aplicarás estilos
de formato a tu texto, y harás uso apropiado de figuras, tablas, citas y
referencias.

Nota el “analizarás” entrecomillado, porque los análisis ya están hechos
realmente. Los datos simulados alimentan un informe de ecología
numérica, que te servirá de insumo en la redacción. La idea es que te
concentres en mejorar habilidades analíticas y presentar resultados con
nivel científico, antes de que comiences a colectar los datos de campo
para redactar formalmente tu manuscrito.

## ¿Cómo proceder?

> [Vídeos asociados, como apoyo para la realización de esta
> práctica](https://www.youtube.com/watch?v=2E5G3eC3E_Y&list=PLDcT2n8UzsCQKAO4T8N0xCxK89RpQ7jRz)

Elaboré informes personalizados usando datos ficticios y aplicando
técnicas de ecología numérica. Digamos que “te liberé” de la parte de
manipular datos y código informático. En esta práctica te pido que te
concentres en redactar cómo se hizo (metodología) y qué se obtuvo
(resultados) en tu informe personalizado, abarcando **todas las técnicas
de ecología numérica aplicadas en el mismo**. Si logras comprender esta
práctica, el análisis posterior de los datos de hormigas para tu
manuscrito será “un cachú”. Vamo’ al lío.

Localiza tu informe personalizado sobre “Datos y análisis para
resultados” en siguiente la tabla:

| Estudiante    | Ruta de informe                                                                                  |
|:--------------|:-------------------------------------------------------------------------------------------------|
| estudiante-01 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-01.html> |
| estudiante-02 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-02.html> |
| estudiante-03 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-03.html> |
| estudiante-04 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-04.html> |
| estudiante-05 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-05.html> |
| estudiante-06 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-06.html> |
| estudiante-07 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-07.html> |
| estudiante-08 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-08.html> |
| estudiante-09 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-09.html> |
| estudiante-10 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-10.html> |
| estudiante-11 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-11.html> |
| estudiante-12 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-12.html> |
| estudiante-13 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-13.html> |
| estudiante-14 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-14.html> |
| estudiante-15 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-15.html> |
| estudiante-16 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-16.html> |
| estudiante-17 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-17.html> |
| estudiante-18 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-18.html> |
| estudiante-19 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-19.html> |
| estudiante-20 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-20.html> |
| estudiante-21 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-21.html> |
| estudiante-22 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-22.html> |
| estudiante-23 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-23.html> |
| estudiante-24 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-24.html> |
| estudiante-25 | <https://biogeografia-202401.github.io/practicas/fuentes/practica-03/informe-estudiante-25.html> |

Distribuye tu texto en las siguientes cinco secciones:

- **Introducción** (tamaño recomendado: 3 párrafos). Desde lo amplio,
  comienza escribiendo sobre ecología numérica (qué es). A continuación,
  explica para qué sirven las técnicas que verás en tu informe
  personalizado, resume su importancia. Finalmente, plantea tu o tus
  objetivos, que en este caso tendrás que crearlos tú mismo/a. Cierra
  con la importancia de estos análisis para el conjunto de la ciencia.

Dentro de esta sección, debes incluir al menos tres citas. Los conceptos
y afirmaciones que no sean tuyas, deben citarse bibliográficamente, y
nunca deberás usar cita literal, pues se considera plagio. Las citas
bibliográficas que incluyas, deberán estar respaldadas por sus
correspondientes cuyas referencias, que deberán aparecer en la sección
final (Referencias). Las citas y la lista de referencias, deberán seguir
el estándar APA 7ma edición (APA7). Es casi imprescindible que uses un
gestor de citas y referencias, como Zotero.

- **Materiales y métodos** (tamaño recomendado: 2 párrafos). Explica
  cómo obtuviste los datos que usaste (en este caso, son simulados, y el
  código fuente se encuentra en el [archivo practica-03.Rmd de este
  repo](practica-03.Rmd) (nota que tiene extensión .Rmd, la “R” lo hace
  especial, pues es un cuaderno “tejible” que puede contener código), y
  describe brevemente las técnicas usadas. Dentro de la redacción, debes
  incluir al menos dos citas. También deberás incluir la matriz de
  comunidad en forma de tabla. Las técnicas empleadas deben sólo
  esbozarse, sin entrar en un detalle excesivo. Las técnicas que
  contiene tu informe fueron diseñadas por otras personas, así que cita
  manuales o artículos que las expliquen.

La tabla (matriz de comunidad) debes ponerle título (*caption*) y
referirla en el texto (“ver tabla X”), usando un sistema de referencia
cruzada asistido por el procesador de texto que uses (pregunta a tu
tutor de inteligencia artificial de preferencia cómo insertar títulos a
tablas, y cómo referirlos en el texto.

- **Resultados** (tamaño recomendado: 2 párrafos). Aquí debes escribir
  un extracto denso de lo que tu informe personalizado contiene. No se
  trata de copiar y pegar, sino de resumir los principales patrones. No
  hagas valoraciones en esta sección, simplemente sintetiza resultados
  en forma redacción de párrafo, no uses listas numeradas ni “viñetas”;
  tampoco se deben colocar números “a secas”, pues deben integrarse en
  la redacción. Si incluyes tablas o figuras, ponles título (*caption*)
  y refiérelas apropiadamente mediante referencia cruzada.

En detalle, más específicamente, una sección de “Resultados” de un
manuscrito científico en el campo de la ecología numérica es
fundamental, ya que presenta los hallazgos empíricos obtenidos a partir
del análisis de datos. En esta sección es donde detallas “los números” y
patrones observados en relación con las hipótesis o preguntas de
investigación planteadas. Esta sección debe ser clara y concisa,
exponiendo las cifras, tendencias y relaciones estadísticas pero,
reitero, sin incluir interpretaciones o explicaciones extensas, las
cuales reservarías para la discusión.

En esta sección manuscrito, es común encontrar tablas, figuras y
gráficos que ilustran los resultados de manera visual, facilitando la
comprensión de los datos complejos. Por ejemplo, podrías incluir
gráficos como el de mosaicos, los de violín, el panel de gráficos de
dispersión, que muestren las relaciones entre la matriz de comunidad y
los factores ambientales; o también podrías mostrar agrupamientos,
asociaciones o especies indicadoras, o modelos que expliquen patrones de
composición de especies. En general, lo que muestres dependerá mucho de
las preguntas/objetivos planteados, y de la técnica elegida. La
consistencia en la presentación de los resultados es crucial, asegurando
que los métodos estadísticos aplicados estén alineados con los objetivos
del estudio. **¡IMPORTANTE! Todo gráfico o tabla insertado debe
referirse mediante referencia cruzada. No insertes tablas ni gráficos si
no te vas a referir a ellos en el texto; y viceversa, no refieras un
gráfico o una tabla que no se encuentre debidamente insertada en el
documento.**

- **Discusión** (tamaño recomendado: 2 párrafos). Abre la discusión
  indicando si alcanzaste tus objetivos. Describe por qué era importante
  alcanzarlos. Comenta sobre las limitaciones, de cualquier tipo, ya sea
  las limitaciones de los datos, de la técnicas, de los objetivos de
  aprendizaje. Cierra indicando qué desafíos futuros quedan abiertos
  tras este trabajo.

- **Referencias**. Las referencias que hayas citado arriba, las deberás
  incluir aquí en formato APA 7ma edición.

## Instrucciones complementarias

1.  **Contenido y tiempo verbal:** Dado que estás redactando la sección
    “Resultados”, te centrarás sólo en el “**qué**”. Como te expliqué
    arriba, en los resultados muestras qué obtuviste tras aplicar
    técnicas analíticas a tus datos, sin valoraciones ni
    interpretaciones. Esto te obligará a usar el tiempo veral “pasado
    simple”, como por ejemplo: (con voz pasiva) “La riqueza alcanzó su
    valor máximo en…” o (con voz activa) “Realicé un análisis de …”.

2.  **Extensión:** No hay recetas fijas, pero es común que los
    resultados ocupen varias páginas, pero dependerá mucho de cuán
    profundo quieras llegar y del apoyo en tablas y figuras que uses. No
    obstante, no abuses de las figuras y tablas, pues un número excesivo
    de ellas hará imposible la lectura; normalmente, muchas revistas
    limitan a 3 figuras y 3 tablas dentro del cuerpo del artículo, y
    todo lo que no quepa allí, se debe transferir a información
    suplementaria. Asegúrate de ser claro/a y conciso/a en tu redacción.

3.  **Formato:** En cuanto a la forma, tal como te comenté arriba,
    redacta el texto entregable aplicando lo aprendido en la
    [“Practica 2. Métricas básicas de ecología numérica,
    reproducibilidad, redacción, estilos de formato, tablas, citas y
    referencias”](https://github.com/biogeografia-202302/practicas/blob/main/practica-02.md).
    Considera usar una plantilla de estilos, para lo cual, te dejo estas
    recomendaciones también:

    - Si usas Microsoft Word o LibreOffice Writer, puedes buscar
      plantillas de artículos (puedes usar las de algunas editoriales) o
      usar [esta plantilla](data/plantilla-manuscrito.dotx) si la
      consideras útil.
    - Independientemente de la plantilla o el software que elijas, lo
      importante es que apliques lo aprendido en la práctica 2.

Si vas a usar la plantilla facilitada por mí, te doy algunos consejos:

- Investiga sobre qué es una plantilla. Básicamente, es un archivo en el
  que te puedes basar para crear otros.

- Al ser una plantilla, si la abres con “doble-click”, se creará un
  documento basado en ella que posteriormente deberás guardar con un
  nombre asignado por ti.

- Puedes usarla en GoogleDocs y en LibreOffice Writer también, pero su
  compatibilidad máxima se consigue en Microsoft Word.

- La plantilla básicamente contiene definiciones de estilos para el
  título principal, títulos de nivel 1 a 3, texto de cuerpo (estilo
  “Normal”), texto de tablas, texto de pies de figuras y tablas,
  bibliografía, y estilo de párrafo para las figuras (suena raro, pero
  sí, las figuras “no flotantes”, que se comportan como texto, también
  tiene definición de estilos). Faltan estilos, como los de autor,
  viñetas, etc. Los puedes crear libremente.

- El texto y las figuras que he colocado de ejemplo son un mero relleno.
  Verás que puse una tabla, una figura, una ecuación, algunas citas y la
  lista de referencias. Debes borrar todo el contenido de ejemplo, pues
  es irrelevante para tu manuscrito.

- No es obligatorio usar esta plantilla, sólo úsala si la ves útil. Si
  ya dispones de un documento donde usas estilos apropiadamente, puedes
  seguir por esa vía. Si ya tienes un documento comenzado, y quieres
  basarte en los estilos de esta plantilla, puedes importar sus estilos
  (los de la plantilla) a tu documento (hay tutoriales sobre ello, como
  [éste](https://www.youtube.com/watch?v=YG7FhZvR2Do)).

- No me canso de repetirlo: consulta al tali. Es viable por correo, sólo
  que es necesario indicar qué problema obtuviste (error, fallo de
  funcionalidad, etc.) al intentar hacer qué cosa. Por ejemplo: “*me dio
  error A al intentar ejecutar B, aquí dejo una captura de pantalla*”.

Finalmente, transcribo abajo un “recuadro” sobre el tipo de voz a usar;
asegúrate de seguir estas recomendaciones.

> **RECUADRO: recomendaciones básicas de redacción**
>
> Usa una voz (activa o pasiva) de forma consistente, pero sólo ten
> presente que la redacción de manuscritos científicos a menudo se
> utilizan ambas voces, dependiendo del contexto y el mensaje que el/la
> autor/a quiera transmitir. Veamos algunos ejemplos:
>
> **Voz activa en manuscrito científicos:**
>
> - **Analicé** los datos utilizando el software R.
>
> - El experimento **mostró** que la temperatura afecta directamente la
>   tasa de reacción.
>
> - Los investigadores **encontraron** una correlación significativa
>   entre las dos variables.
>
> La voz activa puede hacer que la redacción parezca más directa y
> clara, y es especialmente útil cuando el/la autor/a quiere enfatizar
> quién llevó a cabo una acción o cuándo se desea hacer una afirmación
> fuerte.
>
> **Voz pasiva en artículos científicos:**
>
> - Los datos **fueron analizados** utilizando el software R.
>
> - **Se observó** que la temperatura afecta directamente la tasa de
>   reacción.
>
> - Una correlación significativa **fue encontrada** entre las dos
>   variables.
>
> La voz pasiva es común en la redacción científica porque a menudo se
> prefiere un tono más impersonal, enfocando la atención en los
> resultados y procedimientos en lugar de en quienes llevaron a cabo la
> investigación. También puede ser útil cuando no se quiere o no es
> relevante especificar quién realizó la acción.
>
> **En todas mis asignaciones, está completamente permitido usar IA
> (e.g. chatGPT), pero te recomiendo que la uses más como tutor que como
> redactor**. Tal como te sugerí arriba, no le pidas que te resuelva los
> problemas del mandato. Pídele que te dé ideas, y que luego tú las
> mejores o las descartes. No abuses tampoco del texto, pues mucha
> redacción no siempre es mejor; en redacción de ensayos “menos es más”.
> Cruza las redacciones que te ofrezca con tu conocimiento, y revisa si
> los términos o conceptos usados son descabellados (toda IA se inventa
> cosas, cuidate de no caer en esa trampa). Nunca le pidas referencias
> bibliográficas, porque se va equivocar.

## Criterios de evaluación y escala de valoración

## Referencias
