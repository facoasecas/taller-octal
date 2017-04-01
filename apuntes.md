# T A L L E R   O C T A L

**Sábado 1 de abril, 2017.**

Octal es un proyecto financiado por la UE, por medio del programa [stars4all](http://stars4all.eu).

STAR4ALL. *La polución lumínica como “hermano pobre” de la contaminación, pero genera efectos importante del cual se buscar generar conciencia este programa.*

GITHUB. *Subir código y trabajar colaborativamente, es una plataforma de versionado.* 

“scraping”: ir a una página y sacar la información que quiero de esa página. 

**EN LA TERMINAL**

	sudo -s
	bash-3.2# /Users/FACO/Desktop/taller-octal-gh-pahes/FAU/noticias 
	bash-3.2# cd /Users/FACO/Desktop/taller-octal-gh-pahes/FAU/noticias
	bash-3.2# ls
	.DS_Store	data		lat.js
	bash-3.2# chmod u+x lat.js
	bash-3.2# node lat
	
	*me entrega los resutados*
	
	bash-3.2# cd data
	bash-3.2# ls
	resultados-afp.csv		resultados-privacidad+datos.csv
	resultados-contaminación.csv	resultados-trump.csv
	

**EXPLICANDO LO QUE SE METE EN LA TERMINAL**

`sudo -s` te da el acceso de superadministrador, después de ingresar la clave. 

`cd` te lleva al directorio, después de un espacio indica cuál es el directorio, puedes arrastrar la carpeta de

`cd ..` te saca del directorio, no olvidar los espacios entre cd y puntos.

`ls` te muestra los contenidos del directorio 

`cat` te muestra los datos de un documento, ejemplo: `cat semaforos.csv`

`chmod u+x` le entrega abre todos los permisos a un documento, ejemplo: `chmod u+x lat.js`

Ahora, con los resultados que me entreguen los js, después de ejecutados, podemos hacer una visualización descriptiva: *Visualización descriptiva es una visualización simple, que me ayuda a saber qué me están diciendo los datos.* 

Esta es buena herramienta para la visualización descriptiva: [RAW](http://app.rawgraphs.io/)

Otros vínculos de interés:

- [CKAN](https://ckan.org/) A powerful data management system that makes data accessible – by providing tools to streamline publishing, sharing, finding and using data.

- [Bounding Box Tool](http://boundingbox.klokantech.com/) Metadata Enrichment for Catalogue Records by Visually Selecting Geographic Coordinates (Latitude / Longitude) for Maps

- [Conjunto de datos en gob.datos.cl](http://datos.gob.cl/dataset) - Portal de Datos Abiertos - Gobierno de Chile (generado con CKAN 2.4.1)

*Esta tarea es para mi: Generar un p5 que me permita hacer consultas a las bases de datos del gobierno sobre un tema específico.
