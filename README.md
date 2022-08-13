# Tidy Data

El propósito de este repositorio es ilustrar cómo se puede realizar en Python (con pandas) el proceso de limpieza de datos descrito en el artículo "Tidy Data" de Hadley Wickham. Este repositorio fue traducido al español del siguiente repositorio: https://github.com/webartifex/tidy-data

Después de instalar las dependencias para este proyecto (consulte las notas de instalación a continuación), se recomienda leer primero el documento para tener una idea general y luego trabajar con los seis cuadernos Jupyter que se enumeran a continuación.


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
2. múltiples variables se almacenan en una columna
3. las variables se almacenan tanto en filas como en columnas
4. múltiples tipos de unidades de observación se almacenan en la misma tabla
5. una sola unidad de observación se almacena en varias tablas


### Estudio de caso

Un estudio de caso muestra las ventajas de tidy data como un input estandarizado para funciones estadísticas y de visualización.


## Instalación

Obten una copia local de este repositorio con [git](https://git-scm.com/).

`git clone https://github.com/webartifex/tidy-data.git`

Si no tienes familiaridad con [git](https://git-scm.com/), sencillamente descarga la última versión en un archivo zip [aquí](https://github.com/webartifex/tidy-data/archive/master.zip).

Este proyecto usa [poetry](https://python-poetry.org/docs/) para manejar sus dependencias, instalando todos los paquetes externos en un [virtual environment](https://docs.python.org/3/library/venv.html).

`poetry install`

De manera alternativa, usando [Anaconda Distribution](https://www.anaconda.com/products/individual) no debería haber problema para correr estos notebooks.
