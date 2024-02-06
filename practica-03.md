Practica 3. Introducción a QGIS para Biogeografía, parte 1
================
<b>José-Ramón Martínez-Batlle</b> (<jmartinez19@uasd.edu.do>) <br>
Facultad de Ciencias, Universidad Autónoma de Santo Domingo (UASD) <br>
Santo Domingo, República Dominicana

<!-- README.md se genera a partir de README.Rmd. Por favor, edita ese archivo. -->

------------------------------------------------------------------------

# Generales

> Fecha de entrega: 17 de octubre, 23:59 horas.

> **Entregable:** Un documento donde se apliquen estilos adecuadamente
> (título, título 1, cuerpo de texto, pie de figura, y cualquier otro),
> se inserten figuras, pies de figuras, referencia cruzada a figuras,
> referencias bibliográficas. Entrega tu práctica en archivo(s) en
> formato nativo (editable) del programa que hayas usado y,
> opcionalmente, en formato PDF. Por ejemplo, si trabajaste tu documento
> en Microsoft Word, envía el correspondiente archivo .docx o .doc. Si
> lo hiciste en LibreOffice Writer, envía el archivo .odt o el que
> corresponda, pero que sea nativo y editable. Si trabajaste en LaTeX,
> envía el archivo .tex y los asociados a éste.

**Objetivo:** En esta práctica, te familiarizarás con el software QGIS y
algunos de sus complementos esenciales para trabajos en biogeografía.
Aprenderás a instalar QGIS, a agregar complementos como QuickMapServices
y GBIF Occurrences, y finalmente a visualizar datos biogeográficos
descargados desde GBIF.

------------------------------------------------------------------------

# Ejercicios

## Ejercicio 1. Instalación de QGIS

**Resumen:** En este primer paso, aprenderás a descargar e instalar QGIS
en tu computadora.

1.  Dirígete al sitio oficial de QGIS en <https://qgis.org/>.
2.  Elige la versión de tu sistema operativo y descarga el instalador.
3.  Ejecuta el instalador y sigue las instrucciones en pantalla hasta
    finalizar la instalación.
4.  Abre QGIS para comprobar que se ha instalado correctamente.

**Entrega:** Párrafo resumen del proceso realizado y captura de pantalla
del programa QGIS abierto en tu computadora.

*Figura 1: Captura de QGIS después de la instalación.* \[Insertar
captura de pantalla\]

## Ejercicio 2. Instalación del complemento QuickMapServices

**Resumen:** En este paso, aprenderás a instalar un complemento que te
permitirá cargar mapas base como Google Maps o OpenStreetMap.

1.  Abre QGIS.
2.  Dirígete a la barra de menú y selecciona “Complementos” \>
    “Administrar e instalar complementos…”.
3.  En la ventana emergente, escribe “QuickMapServices” en la barra de
    búsqueda.
4.  Selecciona el complemento “QuickMapServices” de la lista y haz clic
    en “Instalar complemento”.
5.  Activa los *contributed packs*, en “Web” \> “QuickMapServices” \>
    “Settings” \> Pestaña “More services” \> Botón “Get contributed
    packs”.
6.  Una vez instalado y activados los *contributed packs*, regresa a la
    ventana principal de QGIS y haz clic en el menú “Web” \>
    “QuickMapServices” y elige un mapa base, como Google Maps o
    OpenStreetMap; explora otras opciones, como las de CartoDB, Stamen,
    Bing y ESRI. Enfócaño en el área de República Dominicana, usando la
    herramienta de Zoom convenientemente.

**Entrega:** Párrafo resumen del proceso realizado y captura de pantalla
de QGIS con un mapa base cargado, por ejemplo, Google Maps.

*Figura 2: Uso de QuickMapServices para cargar un mapa base en QGIS.*
\[Insertar captura de pantalla\]

## Ejercicio 3. Instalación del complemento GBIF Occurrences

**Resumen:** Con este complemento, podrás acceder y cargar datos de
biodiversidad directamente desde GBIF.

1.  En QGIS, dirígete a “Complementos” \> “Administrar e instalar
    complementos…”.
2.  Busca “GBIF Occurrences” y haz clic en “Instalar complemento”.
3.  Una vez instalado, podrás acceder al complemento desde el menú
    “Vector” \> “GBIF Occurrences” \> “Load GBIF Occurrences”.
4.  Haz búsqueda de la familia que hayas elegido, restringiendo sólo
    para República Dominicana, porque si realizas una búsqueda global,
    el complemento podría devolver numerosos registros difíciles de
    manejar.

**Entrega:** Párrafo resumen del proceso realizado y captura de pantalla
mostrando el complemento “GBIF Occurrences” instalado y disponible en
QGIS.

*Figura: Complemento GBIF Occurrences instalado en QGIS.* \[Insertar
captura de pantalla\]

## Ejercicio 4. Representación en QGIS de un CSV descargado desde GBIF

**Resumen:** Aprenderás a visualizar datos biogeográficos de GBIF en
QGIS.

1.  Visita <https://www.gbif.org/> para acceder la interfaz web de GBIF.
    Esta interfaz antes proporcionaba descargas sin necesidad de
    registrarte en el servicio, pero ahora es prácticamene obligatorio
    crearte una cuenta, así que, tendrás que crearla.
2.  Busca una familia de organismos de tu elección (asegúrate de no
    elegir la misma familia que otro compañero o compañera),
    restringiendo sólo para República Dominicana, porque si realizas una
    búsqueda global, el complemento podría devolver numerosos registros
    difíciles de manejar.
3.  Descarga los registros en formato CSV.
4.  En QGIS, dirígete a “Capa” \> “Añadir capa” \> “Añadir capa de texto
    delimitado”.
5.  Busca y selecciona el CSV descargado.
6.  Asegúrate de que las coordenadas se interpreten correctamente y
    agrega la capa.
7.  Dirígete a las propiedades de la capa y en la sección “Símbolo”,
    elige una simbolización por color basada en el género de los
    organismos.
8.  Asegúrate de usar una base cartográfica de fondo, como
    OpenStreetMap, que sirva de referencia territorial.

**Entrega:** Párrafo resumen del proceso realizado y captura de pantalla
mostrando los registros de GBIF visualizados en QGIS con una
simbolización por color según el género.

*Figura 4: Representación en QGIS de datos de GBIF con simbolización por
género.* \[Insertar captura de pantalla\]

De forma general, no olvides usar referencias bibliográficas. Por
ejemplo, estas dos son obligatorias, pero puedes añadir otras, como el
dataset de GBIF específico (el cual tiene un DOI), referencias sobre tu
familia elegida, etc.

- [QGIS. (n.d.). QGIS Geographic Information System.](https://qgis.org/)
- [GBIF. (n.d.). GBIF: Global Biodiversity Information
  Facility.](https://www.gbif.org/)

## Criterios de evaluación y escala de valoración

| Criterio de Evaluación                               | Nivel 1 (En desarrollo)                                        | Nivel 2 (Aceptable)                                   | Nivel 3 (Bueno)                                        | Nivel 4 (Excelente)                                                      |
|------------------------------------------------------|----------------------------------------------------------------|-------------------------------------------------------|--------------------------------------------------------|--------------------------------------------------------------------------|
| **Instalación de QGIS**                              | No presenta evidencia de instalación.                          | Presenta intento de instalación con errores.          | Instalación correcta pero con omisión en detalles.     | Instalación exitosa con captura clara y descripción adecuada.            |
| **Instalación del complemento QuickMapServices**     | No presenta evidencia de instalación del complemento.          | Instalación parcial sin mapas base visibles.          | Instalación correcta pero sin los *contributed packs*. | Instalación exitosa con captura clara mostrando mapas base.              |
| **Instalación del complemento GBIF Occurrences**     | No presenta evidencia de instalación del complemento.          | Presenta intento de instalación con errores.          | Instalación correcta pero sin demostración visual.     | Instalación exitosa con captura clara del complemento en uso.            |
| **Visualización de datos de GBIF en QGIS**           | No presenta datos de GBIF en QGIS.                             | Datos presentados sin simbolización adecuada.         | Representación correcta con omisión en detalles.       | Representación impecable con simbolización por género.                   |
| **Aplicación de estilos en el documento**            | Falta de coherencia y uniformidad en estilos del documento.    | Aplicación básica de estilos sin refinamiento.        | Estilos bien aplicados con algunas omisiones menores.  | Uso experto y consistente de estilos en todo el documento.               |
| **Inclusión y calidad de figuras y pies de figuras** | Ausencia o irrelevancia de figuras. Pies de figuras faltantes. | Figuras de baja calidad o pies de figuras imprecisos. | Figuras claras con pies de figuras adecuados.          | Figuras de alta calidad con pies de figuras detallados y precisos.       |
| **Uso de referencias bibliográficas**                | Ausencia de referencias.                                       | Uso mínimo o inadecuado de referencias.               | Uso correcto de las referencias básicas.               | Uso extensivo y adecuado de referencias, incluyendo fuentes adicionales. |

**Nota:** La evaluación de cada criterio debe ser basada en el desempeño
del estudiante y la evidencia presentada en su entrega. Es vital
proporcionar retroalimentación constructiva para que el estudiante
comprenda las áreas de mejora.

## Referencias
