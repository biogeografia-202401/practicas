Práctica 5. Recojamos datos, formulemos preguntas
================
<b>José-Ramón Martínez-Batlle</b> (<jmartinez19@uasd.edu.do>) <br>
Facultad de Ciencias, Universidad Autónoma de Santo Domingo (UASD) <br>
Santo Domingo, República Dominicana

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

# Práctica 5. Recojamos datos, formulemos preguntas

------------------------------------------------------------------------

## Generales

> Fecha de entrega: en aula.

> Se trabajará por grupos de dos personas, **pero la entrega es
> individual**.

> **Entregar por correo electrónico, lo siguiente:**

- Cada estudiante entregará una hoja de cálculo o una lista en formato
  valores separados por delimitador (por ejemplo, un CSV), o incluso un
  correo electrónico, con las mediciones de ancho y largo, en sistema
  métrico (milímetros, centímetros), de 20 hojas de una misma especie de
  árbol (hojas simples, no compuestas), seleccionadas al azar de un
  mismo individuo, de las cuales 10 serán colectadas por ti, y otras 10
  serán colectadas por tu compañero/a.

- Cada miembro del grupo entregará una lista de tres preguntas que se
  podrían responder con los datos generados.

------------------------------------------------------------------------

## Ejercicio 1. Mide el largo y el ancho de 20 hojas

- En el campus, preferiblemente cerca del edificio FC, cada grupo de 2
  personas localizará un individuo de una especie de árbol o arbusto de
  hojas simples, que estén al alcance de la mano. Ponte de acuerdo con
  tu compañero/a para elegir el individuo, ya que ambas personas
  trabajarán sobre el mismo.

- Siempre que te sea posible determina, con tu compañero/a, la especie a
  la que pertenece; en caso contrario, por lo menos toma una foto de
  conjunto del individuo.

- Corta 10 hojas del árbol elegido; tu compañero/a debe hacer lo mismo,
  cortar 10, pero **no se deben mezclar**. Llévalas al aula.

- Si puedes (sólo si ves que tienes espacio para ello y recursos a
  mano), identifica cada hoja con un identificador único, o colócalas en
  orden del 1 al 10 (si lo haces colocándolas en orden, no las mezcles
  hasta finalizar la práctica, es decir, hasta que tu compañero/a
  también mida)

- Mide ancho y largo de las hojas que colectaste. Guíate de referencias
  para que identifiques con certeza el desde y hasta dónde medir (de
  base a ápice para el largo, y máximo valor de margen a margen para el
  ancho). **Especifica la unidad de medida**. Atento al instrumento de
  medir, para que no confundas pulgadas con centímetros.

- Mide ancho y largo de las hojas de tu compañero/a. Al finalizar,
  deberías tener 20 mediciones, organizadas en un tabla como esta:

<table>
<thead>
<tr>
<th style="text-align:right;">
ID de hoja
</th>
<th style="text-align:left;">
Nombre de estudiante
</th>
<th style="text-align:right;">
Ancho
</th>
<th style="text-align:right;">
Largo
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
5.06
</td>
<td style="text-align:right;">
8.55
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
5.14
</td>
<td style="text-align:right;">
8.38
</td>
</tr>
<tr>
<td style="text-align:right;">
3
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
5.03
</td>
<td style="text-align:right;">
7.97
</td>
</tr>
<tr>
<td style="text-align:right;">
4
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
5.13
</td>
<td style="text-align:right;">
7.83
</td>
</tr>
<tr>
<td style="text-align:right;">
5
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
4.89
</td>
<td style="text-align:right;">
8.11
</td>
</tr>
<tr>
<td style="text-align:right;">
6
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
5.04
</td>
<td style="text-align:right;">
8.28
</td>
</tr>
<tr>
<td style="text-align:right;">
7
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
4.74
</td>
<td style="text-align:right;">
8.34
</td>
</tr>
<tr>
<td style="text-align:right;">
8
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
5.15
</td>
<td style="text-align:right;">
7.73
</td>
</tr>
<tr>
<td style="text-align:right;">
9
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
4.89
</td>
<td style="text-align:right;">
7.32
</td>
</tr>
<tr>
<td style="text-align:right;">
10
</td>
<td style="text-align:left;">
Monesvol
</td>
<td style="text-align:right;">
4.61
</td>
<td style="text-align:right;">
8.70
</td>
</tr>
<tr>
<td style="text-align:right;">
1
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
4.78
</td>
<td style="text-align:right;">
8.69
</td>
</tr>
<tr>
<td style="text-align:right;">
2
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
5.28
</td>
<td style="text-align:right;">
8.22
</td>
</tr>
<tr>
<td style="text-align:right;">
3
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
5.22
</td>
<td style="text-align:right;">
7.93
</td>
</tr>
<tr>
<td style="text-align:right;">
4
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
4.25
</td>
<td style="text-align:right;">
8.06
</td>
</tr>
<tr>
<td style="text-align:right;">
5
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
4.09
</td>
<td style="text-align:right;">
6.85
</td>
</tr>
<tr>
<td style="text-align:right;">
6
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
5.00
</td>
<td style="text-align:right;">
7.32
</td>
</tr>
<tr>
<td style="text-align:right;">
7
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
4.88
</td>
<td style="text-align:right;">
7.90
</td>
</tr>
<tr>
<td style="text-align:right;">
8
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
4.48
</td>
<td style="text-align:right;">
8.03
</td>
</tr>
<tr>
<td style="text-align:right;">
9
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
5.15
</td>
<td style="text-align:right;">
8.04
</td>
</tr>
<tr>
<td style="text-align:right;">
10
</td>
<td style="text-align:left;">
Thor
</td>
<td style="text-align:right;">
5.08
</td>
<td style="text-align:right;">
8.16
</td>
</tr>
</tbody>
</table>

## Ejercicio 2. Formula tres preguntas

- Formula tres preguntas que entiendas se pueden responder con los datos
  colectados.

## Criterios de evaluación y escala de valoración

| Criterio                       | Nivel 1 (En Desarrollo)                                                                  | Nivel 2 (Aceptable)                                                                           | Nivel 3 (Bueno)                                                         | Nivel 4 (Excelente)                                                                                               |
|--------------------------------|------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|
| **Recolección de Datos**       |                                                                                          |                                                                                               |                                                                         |                                                                                                                   |
| Exactitud en las mediciones    | Mediciones imprecisas, con errores significativos o sin especificar la unidad de medida. | Mediciones con pequeños errores o inconsistencias leves en la unidad de medida.               | Mediciones mayormente precisas y consistentes en la unidad de medida.   | Mediciones completamente precisas y consistentemente en la unidad de medida adecuada.                             |
| Identificación de las hojas    | Identificación inexistente o incorrecta de las hojas.                                    | Identificación básica de las hojas con errores menores.                                       | Identificación correcta de la mayoría de las hojas.                     | Identificación precisa y detallada de todas las hojas.                                                            |
| Organización de la información | Datos desorganizados o mal presentados en la tabla.                                      | Datos presentados en la tabla con alguna desorganización o falta de claridad.                 | Datos bien organizados y presentados claramente en la tabla.            | Datos excepcionalmente bien organizados y presentados de manera clara y profesional en la tabla.                  |
| **Formulación de Preguntas**   |                                                                                          |                                                                                               |                                                                         |                                                                                                                   |
| Relevancia de las preguntas    | Preguntas no relacionadas con los datos recolectados o irrelevantes para el estudio.     | Preguntas algo relacionadas con los datos, pero con poca relevancia para el estudio.          | Preguntas bien relacionadas con los datos y relevantes para el estudio. | Preguntas altamente relevantes y profundamente conectadas con los datos recolectados y los objetivos del estudio. |
| Claridad y formulación         | Preguntas formuladas de manera confusa o incomprensible.                                 | Preguntas formuladas de manera aceptable, pero con algunos problemas de claridad o precisión. | Preguntas claras y bien formuladas, con una buena estructura.           | Preguntas excepcionalmente claras, precisas y bien estructuradas, mostrando un entendimiento profundo del tema.   |
| Potencial analítico            | Preguntas con poco o ningún potencial para análisis significativo.                       | Preguntas con potencial limitado para análisis significativo.                                 | Preguntas que invitan a un análisis detallado y significativo.          | Preguntas que promueven un análisis exhaustivo y profundo, evidenciando un entendimiento avanzado del tema.       |

## Preguntas guía

### Tali:

- ¿Cuánto mide, en promedio (media, mediana), el ancho de la hoja del
  individuo seleccionado?

- ¿Cuánto mide, en promedio (media, mediana), el largo de la hoja del
  individuo seleccionado?

- ¿La muestra de la persona 1 del grupo es representativa de la muestra
  completa del grupo?

- ¿Existen diferencias en la dispersión del ancho entre las mediciones
  realizadas por distintas personas?

- ¿Existen diferencias en la dispersión del largo entre las mediciones
  realizadas por distintas personas?

- ¿Existen diferencias en la dispersión del ancho entre las colectas
  realizadas por distintas personas?

- ¿Existen diferencias en la dispersión del largo entre las colectas
  realizadas por distintas personas?

- ¿Existe sesgo de medición entre distintas personas?

- ¿Existe sesgo de colecta entre distintas personas?

- ¿Existen diferencias significativas en las mediciones de ancho entre
  especies?

- ¿Existen diferencias significativas en las mediciones de largo entre
  especies?

- ¿Existen diferencias significativas entre las mediciones de largo y
  ancho?

- ¿Provienen las mediciones del ancho de una población normalmente
  distribuida?

- ¿Provienen las mediciones del largo de una población normalmente
  distribuida?

- Si se pierden datos u hojas, ¿podemos tomar medidas para rellenarlos?
  ¿Qué medidas?

- ¿Existen datos inconsistentes entre largo y ancho?

### Melany y María Fernanda

- ¿Cuál es la media aritmética del ancho de las hojas?

- ¿Cuál es la media aritmética del largo de las hojas?

- ¿El ancho de las hojas posee correlación con el largo de las hojas?

### Angélica

- ¿Qué probabilidad hay de que las hojas tengan el mismo largo?

- ¿ Qué tanto puede dificultar el enves al momento de tomar las medidas?

- ¿ Qué probabilidad hay e que las hojas posean el mismo ancho?

### Harly

- Sacar promedio de ancho?

- El color y el tamaño esta relacionado?

- Cuál es promedio relativo de la altura?

### Gabriel

- Habría alguna diferencia en la medida de la hoja si se mide por el
  envés?

- Por qué un individuo tiene hojas de diferentes colores y otro con
  hojas del mismo color?

- Las hojas de las plantas tienen alguna lógica matemática para su
  crecimiento, tienen un numero limite de cm de crecimiento?

### Luis

- ¿Qué probabibilidad hay que de la hoja esté torcida?

- ¿Cuál es la probabilidad de que las hojas tengan el mismo tamaño?

- ¿Cuál es la probabilidad de que las hojas pasen de 20 cm?

## Análisis

- Hasta 2 de abril, no se han realizado análisis, sólo consolidación de
  los archivos. Se realizarán análisis el 9 de abril.

``` r
library(readxl)
library(tidyverse)
library(kableExtra)
datos <- read_excel('data/mediciones-hojas.xlsx')

estadisticos_segun_quien_midio <- datos %>% 
  pivot_longer(
    cols = -(grupo:`colectas hechas por`),
    names_to = 'dimensión', values_to = 'valor') %>% 
  group_by(grupo, `mediciones hechas por`, dimensión) %>% 
  summarise(Media = mean(valor)) %>% 
  # pivot_longer(-(grupo:dimensión), names_to = 'estadísticos', values_to = 'valor')
  pivot_wider(names_from = 'dimensión', values_from = Media)
estadisticos_segun_quien_midio %>% kable()
```

<table>
<thead>
<tr>
<th style="text-align:left;">
grupo
</th>
<th style="text-align:left;">
mediciones hechas por
</th>
<th style="text-align:right;">
ancho (cm)
</th>
<th style="text-align:right;">
largo (cm)
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Angélica-Luis
</td>
<td style="text-align:left;">
Angélica
</td>
<td style="text-align:right;">
4.60
</td>
<td style="text-align:right;">
19.3
</td>
</tr>
<tr>
<td style="text-align:left;">
Angélica-Luis
</td>
<td style="text-align:left;">
Luis
</td>
<td style="text-align:right;">
4.49
</td>
<td style="text-align:right;">
19.2
</td>
</tr>
<tr>
<td style="text-align:left;">
Harly, Gabriel
</td>
<td style="text-align:left;">
Gabriel
</td>
<td style="text-align:right;">
9.74
</td>
<td style="text-align:right;">
26.0
</td>
</tr>
<tr>
<td style="text-align:left;">
Harly, Gabriel
</td>
<td style="text-align:left;">
Harly
</td>
<td style="text-align:right;">
9.38
</td>
<td style="text-align:right;">
25.5
</td>
</tr>
<tr>
<td style="text-align:left;">
Melany, María y Aironeli
</td>
<td style="text-align:left;">
Aironeli
</td>
<td style="text-align:right;">
7.67
</td>
<td style="text-align:right;">
15.8
</td>
</tr>
<tr>
<td style="text-align:left;">
Melany, María y Aironeli
</td>
<td style="text-align:left;">
Melany y María Fernanda
</td>
<td style="text-align:right;">
7.58
</td>
<td style="text-align:right;">
15.6
</td>
</tr>
</tbody>
</table>

## Referencias
