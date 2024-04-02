Práctica 5. Recojamos datos, formulemos preguntas
================
<b>José-Ramón Martínez-Batlle</b> (<jmartinez19@uasd.edu.do>) <br>
Facultad de Ciencias, Universidad Autónoma de Santo Domingo (UASD) <br>
Santo Domingo, República Dominicana

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

------------------------------------------------------------------------

# Generales

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

# Ejercicio 1. Mide el largo y el ancho de 20 hojas

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
ID.de.hoja
</th>
<th style="text-align:left;">
Nombre.de.estudiante
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

# Ejercicio 2. Formula tres preguntas

Formula tres preguntas que entiendas se pueden responder con los datos
colectados.

## Criterios de evaluación y escala de valoración

## Referencias
