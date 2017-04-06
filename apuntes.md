# APUNTES

#### Abril, 2017

**Workshop OCTAL** es financiado por la Union Europea, por medio del programa [stars4all](http://stars4all.eu). Este workshop está a cargo de [Cris Hernandez](http://crishernandez.co/), director del proyecto OCTAL.

Para participar del Workshop OCTAL necesitas [instalar Node.js](https://nodejs.org/es/download/) en tu computador. Node.js utiliza como interfaz la Terminal, donde se escribirá:

	sudo -s
	bash-3.2# cd /Users/FACO/Desktop/taller-octal-gh-pahes/FAU/noticias
	bash-3.2# ls
	.DS_Store	data		lat.js
	bash-3.2# chmod u+x lat.js
	bash-3.2# node lat
	bash-3.2# cd data
	bash-3.2# ls
	resultados-afp.csv		resultados-privacidad+datos.csv
	resultados-contaminación.csv	resultados-trump.csv


**¡MÁS LENTO CEREBRITO! ¿QUÉ ES LO QUE SE ESCRIBE?**

**En caso no sepas que es Node.js, puedes leer: [Node.JS - Primeros pasos y "Hola mundo"](https://geekytheory.com/node-js-primeros-pasos-y-hola-mundo). Después de esa lectura, será más sencillo comprender lo que sigue.**

`sudo -s` te permite ingresar como superuser/root. Conviene apuntar que: "Using the sudo command in Terminal requires a non-blank administrator password" [(Ver detalles)](https://support.apple.com/en-ph/HT202035).

`cd` te mete al directorio que indiques después de un espacio; puedes arrastrar la carpeta a la terminal, automáticamente se escribirá la dirección del directorio.

`cd ..` te saca del directorio donde te encuentres. No olvidar el espacio entre el `cd` y los `..`.

`ls` te muestra los contenidos del directorio en donde te encuentres.

`chmod u+x` te permite modificar los permisos a un documento, ejemplo: `chmod u+x lat.js`

`cat` te muestra los contenidos de un documento, ejemplo: `cat semaforos.csv`

Pueden encontrar más datos sobre la Terminal en este [Mac Terminal Cheat Sheet](https://gist.github.com/poopsplat/7195274)

Ahora, con los resultados que me entreguen los programas, podemos hacer una visualización descriptiva: *Visualización descriptiva es una visualización simple, que me ayuda a saber qué me están diciendo los datos.* [RAW](http://app.rawgraphs.io/), desarrollado por el Design Density, es una buena herramienta para ese tipo de visualización.

- - - - - - - - - - -

Otros vínculos de interés:

- [CKAN](https://ckan.org/) A powerful data management system that makes data accessible – by providing tools to streamline publishing, sharing, finding and using data.

- [Bounding Box Tool](http://boundingbox.klokantech.com/) Metadata Enrichment for Catalogue Records by Visually Selecting Geographic Coordinates (Latitude / Longitude) for Maps

- [Conjunto de datos en gob.datos.cl](http://datos.gob.cl/dataset) - Portal de Datos Abiertos - Gobierno de Chile (generado con CKAN 2.4.1)
