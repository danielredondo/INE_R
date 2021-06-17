# Tutorial para descargar datos del Instituto Nacional de Estadística (INE) con R usando el servicio API JSON
### *Daniel Redondo Sánchez*

*Trabajo presentado en las XI Jornadas de Usuarios de R, celebradas en Madrid (2019)* 

En este trabajo se describe un método de descarga de información del **Instituto Nacional de Estadística** (INE) usando R. El código es totalmente reproducible.

Se utiliza el servicio **API** (Application Programming Interface) del INE. En primer lugar, se obtiene una URL válida para la descarga, en función del tipo de información a descargar (si es una tabla con número definido, o si es un fichero PCAxis).

Se procede a la descarga de información usando *httr::GET*. El contenido se descarga en formato **JSON** (JavaScript Object Notation), y es posteriormente procesado hasta obtener un data.frame.

Se muestran dos ejemplos de descarga basados en los datos de las estadísticas vitales de **defunciones perinatales según semanas de gestación**, y en **cifras de población por edad y provincia**. Se proporcionan representaciones visuales a partir de la información descargada.


[![DOI](https://zenodo.org/badge/196965728.svg)](https://zenodo.org/badge/latestdoi/196965728)


<img src="logos\logo_ibs.jpg" width="500"/>

<img src="logos\logo_easp.png" width="500"/>

<img src="logos\logo_ciber.png" width="500"/>