Practica 4. Redacta “Metodología” y “Resultados” de ecología numérica
================
<b>José-Ramón Martínez-Batlle</b> (<jmartinez19@uasd.edu.do>) <br>
Facultad de Ciencias, Universidad Autónoma de Santo Domingo (UASD) <br>
Santo Domingo, República Dominicana

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

> Fecha de entrega: 14 de noviembre, 23:59 horas.

> Entrega tu práctica en archivo(s) en formato nativo (editable) del
> programa que hayas usado y, opcionalmente, en formato PDF. Por
> ejemplo, si trabajaste tu documento en Microsoft Word, envía el
> correspondiente archivo .docx o .doc. Si lo hiciste en LibreOffice
> Writer, envía el archivo .odt o el que corresponda, pero que sea
> nativo y editable. Si trabajaste en LaTeX, envía el archivo .tex y los
> asociados a éste.

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

## Entregable

- Documento, **redactado en tiempo pasado** que contenga las
  subsecciones “Metodología” y “Resultados” de **todas las técnicas de
  ecología numérica empleadas en tu informe personalizado**. Aunque el
  informe se basa en datos ficticios, los que obtendrás de tus colectas
  de hormigas en el campus de la UASD serán muy parecidos a estos. El
  tiempo pasado es el habitual en la redacción de la metodología y los
  resultados. También recuerda que debes ser consistente con la voz
  elegida (pasiva, activa).

## Localiza tu informe personalizado

Aquí tienes la lista de informes personalizados. Localiza el tuyo y
sigue las instrucciones de la siguiente sección.

| Estudiante                        | Ruta de informe                                                                                                      |
|:----------------------------------|:---------------------------------------------------------------------------------------------------------------------|
| Adrian-Rafael-Diplan-Montas       | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Adrian-Rafael-Diplan-Montas.html>       |
| Alan-Manuel-Contreras-Sanchez     | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Alan-Manuel-Contreras-Sanchez.html>     |
| Ana-Garcia                        | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Ana-Garcia.html>                        |
| Angel-Rolando-Gomez-Gonzalez      | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Angel-Rolando-Gomez-Gonzalez.html>      |
| Arisleydi-Mejia-De-La-Cruz        | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Arisleydi-Mejia-De-La-Cruz.html>        |
| Bryan-Josue-Funez-Ramos           | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Bryan-Josue-Funez-Ramos.html>           |
| Carmen-Munoz-Patricio             | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Carmen-Munoz-Patricio.html>             |
| Claribel-Reyes-Ramirez            | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Claribel-Reyes-Ramirez.html>            |
| Eddy-Bienvenido-Ulloa-Almonte     | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Eddy-Bienvenido-Ulloa-Almonte.html>     |
| Emely-Fabianny-Rodriguez-Martinez | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Emely-Fabianny-Rodriguez-Martinez.html> |
| Emely-Herrera-Arias               | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Emely-Herrera-Arias.html>               |
| Floranny-Lorenzo-Dominguez        | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Floranny-Lorenzo-Dominguez.html>        |
| Franchesca-Feliz-Linares          | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Franchesca-Feliz-Linares.html>          |
| Joel-Benjamin-Perez-Garcia        | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Joel-Benjamin-Perez-Garcia.html>        |
| Jose-Ramon-Martinez-Batlle        | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Jose-Ramon-Martinez-Batlle.html>        |
| Manuel-Enrique-Urena-Reyes        | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Manuel-Enrique-Urena-Reyes.html>        |
| Miguel-Landestoy-Tejeda           | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Miguel-Landestoy-Tejeda.html>           |
| Ramona-Geraldo-Munoz              | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Ramona-Geraldo-Munoz.html>              |
| Saderis-Carmona-Marte             | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Saderis-Carmona-Marte.html>             |
| Scarlin-Adames-Lantigua           | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Scarlin-Adames-Lantigua.html>           |
| Unifer-Tavarez-Ferreras           | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Unifer-Tavarez-Ferreras.html>           |
| Valeria-Novas-Perez               | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Valeria-Novas-Perez.html>               |
| Yenny-Mabel-Santana               | <https://biogeografia-202302.github.io/practicas/fuentes/practica-04/informe-Yenny-Mabel-Santana.html>               |

## Analiza tu informe personalizado, redacta “Metodología” y “Resultados”

Inspecciona tu informe personalizado concentrándote primero en el
documento propiamente, SIN OBSERVAR CÓDIGO INFORMÁTICO, al menos por
ahora. Puedes pedir ayuda al ChatGPT para que te describa lo que se
“obtuviste” en cada caso, pero dado que muchos resultados son sólo
gráficos, no podrás pedirle ayuda en todo. Para estos casos, apóyate de
los [vídeos
asociados](https://www.youtube.com/watch?v=2E5G3eC3E_Y&list=PLDcT2n8UzsCQKAO4T8N0xCxK89RpQ7jRz).

Cuando hayas obtenido una visión general, entonces profundiza
ligeramente en el código, especialmente en las líneas `library()`, que
son las que cargan paquetes. Luego, observa las funciones empleadas
(cualquier nombre acompañado de paréntesis es una función en `R`); en
los [vídeos
asociados](https://www.youtube.com/watch?v=2E5G3eC3E_Y&list=PLDcT2n8UzsCQKAO4T8N0xCxK89RpQ7jRz)
menciono las funciones clave en cada caso. Esto te ayudará a redactar la
parte de “Metodología”.

Verás que tu informe personalizado tiene cuatro secciones:

- Análisis exploratorio de datos (AED). Esta no cuenta como técnica de
  ecología numérica, sólo que se asume que debe realizarse de forma
  preceptiva en cualquier estudio.

- Análisis de agrupamiento.

- Técnicas de ordenación.

- Análisis de diversidad + análisis de agrupamiento abreviado.

Debes abarcar **todas estas técnicas de ecología numérica** en esta
práctica. De cada técnica que apliqué (agrupamiento, ordenación,
diversidad+agrupamiento; recuerda que el AED no cuenta como técnica de
ecología numérica, pero es imprescindible), redacta en un párrafo la
metodología empleada en tiempo pasado. Debes usar citas y explicar cómo
obtuviste tus resultados (sin adelantarlos) de la manera más breve
posible. Cuando redactes sobre las técnicas empleadas, no entres en
detalles que el autor o autora de la referida técnica ya haya descrito.
Normalmente, en la metodología mencionas, de manera inequívoca, el
nombre de el o los algoritmos usaste y para qué lo usaste, qué
parámetros del algoritmo definiste, qué criterios de selección empleaste
para elegir las técnicas y por qué. Es necesario mencionar el software
empleado (en este caso es `R`, que tiene una forma estándar de citarse).
También deberás mencionar algunos paquetes usados (quizá no todos), y
citarlos (busca cómo citar paquetes de `R`). Cuando hayas redactado la
metodología de cada técnica empleada, tendrás seguramente tres párrafos,
uno por cada técnica.

Asimismo, de cada técnica de ecología numérica (agrupamiento,
ordenación, diversidad+agrupamiento), describe en tiempo pasado los
resultados obtenidos tras examinar los productos que generé para ti. No
olvides los resultados generales, como riqueza total, sitio más rico,
sitio más pobre, especie más común, etc., que son típicamente elaborados
en la exploración de los datos. Abajo te transcribí algunas preguntas
que puedes usar para guiarte en la redacción de resultados. Los
resultados de cada técnica de ecología numérica no deberían exceder dos
párrafos (si lo haces en un párrafo es perfecto), por lo que,
juntándolos todos, tendrías entre **tres y seis párrafos de
resultados**, como mucho.

Al finalizar, construye tu documento entregable conteniendo dos
secciones:

- Metodología. Funde todas las metodologías que redactaste de forma
  parcial.

- Resultados. Funde los resultados que redactaste de forma parcial.

Te transcribo a continuación algunas preguntas que te podrían servir
para redactar la sección de resultados de cada técnica.

- Preguntas que te podrían guiar para extraer resultados del análisis de
  agrupamiento:

  - Las unidades muestrales, ¿se organizan en grupos diferenciados según
    la composición de especies?

  - Si existe algún patrón, ¿es consistente con alguna variable de la
    matriz ambiental?

  - ¿Hay especies indicadoras o con preferencia por determinadas
    variables?

- Preguntas que te podrían guiar para extraer resultados de las técnicas
  de ordenación:

  - En un espacio bidimensional, ¿existen tendencias apreciables de
    ordenación de las especies?

  - Si existen tendencias de ordenación, ¿se asocian éstas con
    determinadas variables?

- Preguntas que te podrían guiar para extraer resultados del análisis de
  diversidad + análisis de agrupamiento abreviado:

  - Según los análisis de estimación de riqueza, ¿está suficientemente
    representada la comunidad? Consideremos como buena representación un
    80% del total esperado.

  - ¿Es la riqueza esperada mayor o menor según en qué hábitats
    (caracterizados según variables) nos encontremos?

  - ¿Existe asociación de la diversidad alpha con las variables, es
    decir, es mayor o menor la diversidad alpha según en qué grupo de
    muestras nos encontremos?

  - ¿Existe contribución local o por alguna especie a la diversidad
    beta?

## Criterios de evaluación y escala de valoración

| Criterio de Evaluación                        | Nivel 1 (En desarrollo)                                      | Nivel 2 (Aceptable)                                            | Nivel 3 (Bueno)                                                | Nivel 4 (Excelente)                                              |
|-----------------------------------------------|--------------------------------------------------------------|----------------------------------------------------------------|----------------------------------------------------------------|------------------------------------------------------------------|
| **Formato y Entrega del Documento**           | Falta archivo nativo o no es editable.                       | Entrega archivo nativo, pero no sigue indicaciones precisas.   | Entrega archivo nativo siguiendo casi todas las indicaciones.  | Entrega archivo nativo siguiendo todas las indicaciones.         |
| **Uso del Tiempo Pasado en la Redacción**     | No utiliza tiempo pasado o lo usa inadecuadamente.           | Utiliza tiempo pasado, pero con inconsistencias notables.      | Utiliza tiempo pasado con pocas inconsistencias.               | Utiliza tiempo pasado de manera consistente y adecuada.          |
| **Redacción de la Sección “Metodología”**     | Falta la sección o es muy incompleta.                        | Menciona técnicas, pero falta citar o profundizar en detalles. | Menciona y cita técnicas, pero podría mejorar en claridad.     | Menciona y cita técnicas de manera clara y concisa.              |
| **Redacción de la Sección “Resultados”**      | Falta la sección o es muy incompleta.                        | Describe resultados, pero falta conexión con la metodología.   | Describe resultados de forma clara, con mínimas mejoras.       | Describe resultados de forma clara y conecta con la metodología. |
| **Coherencia entre Metodología y Resultados** | Las secciones no están conectadas o falta coherencia.        | Hay intento de conexión, pero con lagunas notables.            | Las secciones están conectadas, con pequeñas mejoras posibles. | Las secciones están perfectamente conectadas y coherentes.       |
| **Respuestas a las Preguntas de Guía**        | No responde o responde de manera inadecuada a las preguntas. | Responde a algunas preguntas, pero falta profundidad.          | Responde a la mayoría de las preguntas de forma adecuada.      | Responde a todas las preguntas de forma clara y completa.        |

## Referencias
