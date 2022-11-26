# Tidy Data

El propósito de este repositorio es ilustrar cómo se puede realizar en Python (con pandas) el proceso de limpieza de datos descrito en el artículo "Tidy Data" de Hadley Wickham. Este repositorio fue traducido al español del siguiente repositorio: https://github.com/webartifex/tidy-data

## Resumen


### Definición

**Tidy data** se definen como datos que vienen en forma de tabla que se adhieren a los siguientes requisitos:  
1. cada variable es una columna,
2. cada observación una fila, y
3. cada tipo de unidad de observación forma una tabla.

Esto es equivalente a [la tercera forma normal de Codd] (https://en.wikipedia.org/wiki/Third_normal_form), un concepto de la teoría sobre bases de datos relacionales. Un conjunto de datos que *no* satisface estas propiedades se llama **messy data**.


### Tidying Data

Los cinco problemas más comunes con los datos desordenados son:

1. Los encabezados de las columnas son valores, no nombres de variables.
2. Múltiples variables se almacenan en una columna
3. Las variables se almacenan tanto en filas como en columnas
4. Múltiples tipos de unidades de observación se almacenan en la misma tabla
5. Una sola unidad de observación se almacena en varias tablas


### Estudio de caso

Un estudio de caso muestra las ventajas de **tidy data** como un input estandarizado para funciones estadísticas y de visualización.

## Instalación

Obten una copia local de este repositorio con [git](https://git-scm.com/).

`https://github.com/vmlandae/tidy-data-mds-espanol.git`

En esta versión actualizada, este proyecto usa [conda](https://docs.conda.io/en/latest/) para manejar sus dependencias.
El archivo `environment.yml` tiene las dependencias 

```python

```
