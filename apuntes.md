# T A L L E R   O C T A L

**Sábado 1 de abril, 2017.**

Octal es un proyecto financiado por la UE, por medio del programa [stars4all](http://stars4all.eu).

STAR4ALL. *La polución lumínica como “hermano pobre” de la contaminación, pero genera efectos importante del cual se buscar generar conciencia este programa.*

GITHUB. *Subir código y trabajar colaborativamente, es una plataforma de versionado.* 

SCRAPING. *Ir a una página y sacar la información que quiero de esa página.*

**EN LA TERMINAL**

	sudo -s
	bash-3.2# /Users/FACO/Desktop/taller-octal-gh-pahes/FAU/noticias 
	bash-3.2# cd /Users/FACO/Desktop/taller-octal-gh-pahes/FAU/noticias
	bash-3.2# ls
	.DS_Store	data		lat.js
	bash-3.2# chmod u+x lat.js
	bash-3.2# node lat
	bash-3.2# cd data
	bash-3.2# ls
	resultados-afp.csv		resultados-privacidad+datos.csv
	resultados-contaminación.csv	resultados-trump.csv
	

**EXPLICANDO LO QUE SE METE EN LA TERMINAL**

`sudo -s` - te da el acceso de superadministrador, después de ingresar la clave puedes continuar. Justo acá conviene saber que: "Using the sudo command in Terminal requires a non-blank administrator password" [detalles](https://support.apple.com/en-ph/HT202035).

`cd` - te mete al directorio. Después de un espacio debes indicar cuál es el directorio; puedes arrastrar la carpeta desde donde esté hacia el termina, automáticamente se generará la dirección que corresponde.

`cd ..` - te saca del directorio. No olvidar los espacios entre cd y puntos.

`ls` - te muestra los contenidos del directorio en donde te encuentres.

`chmod u+x` - te permite modificar los permisos a un documento, ejemplo: `chmod u+x lat.js`

`cat` - te muestra los contenidos de un documento, ejemplo: `cat semaforos.csv`

Ahora, con los resultados que me entreguen los js, después de ejecutados, podemos hacer una visualización descriptiva: *Visualización descriptiva es una visualización simple, que me ayuda a saber qué me están diciendo los datos.* 

[RAW](http://app.rawgraphs.io/) es una buena herramienta para ese tipo de visualización.

Otros vínculos de interés:

- [CKAN](https://ckan.org/) A powerful data management system that makes data accessible – by providing tools to streamline publishing, sharing, finding and using data.

- [Bounding Box Tool](http://boundingbox.klokantech.com/) Metadata Enrichment for Catalogue Records by Visually Selecting Geographic Coordinates (Latitude / Longitude) for Maps

- [Conjunto de datos en gob.datos.cl](http://datos.gob.cl/dataset) - Portal de Datos Abiertos - Gobierno de Chile (generado con CKAN 2.4.1)
