#Clon pagina Dev.to - Equipo 1

## Hecho con 🧡 por:

- [@Paoxx](https://github.com/Paoox)
- [@Alejandrojunio29](https://github.com/Alejandrojunio29)
- [@kherzo99](https://github.com/kherzo99)
- [@arqsam](https://github.com/arqsam)
- [@fiddly-digits](https://www.github.com/fiddly-digits)

##PROCESO DE DESARROLLO DE MAQUETADO PAGINA DEV.to.



1. Organización de Equipo. 
2. Inspección de la página DEV.to
3. Análisis y elaboración de wareframes general.
4. Análisis por sección y elaboraboración de wareframes.
5. Asignación de secciones para realización de tareas individuales. 
6. Boceto de la esctructura general, por medio de Boostrap.
	{.row, .col-2, .col-7, .col-3} -----> Dimensiones asignadas a las columnas de cada sección. 


Sección HEADER (Karla Herzo):
 1. Se ectructuró, iniciamlmente en un elemento <nav>. 
 2. Dentro de elementco <nav> se alojan dos elementos: 
	2.1 <div> ---> Contiene un elemento img (logo), e imput (search bar).
	2.2 <div> ---> Contiene botones de interacción para el usuario (<a>, <i>), los cuales presentan la pseudoclase ::hover.
		-Dentro del contenedor del elemento <i> "campana", se agregó un <div> con posición absolut, por medio del 
             pseudoelemento ::after.

Sección MAIN_SECTION (Body):
 En esta sección se encuentra la distribucion de las tres columnas del sitio utilizando la herramienta boostrap. 	
	{.row, .col-2 (Menú), .col-7 (Main), .col-3 (Listing)} -----> Dimensiones asignadas a las columnas de cada sección.
 
Sección MENÚ (Rob Cruz):
 1. Menú  se eligió con la propiedad flex en boostrap.
 2. El elemento principal del menú, es un <aside> con la propiedad grid.
	2.1 <aside> contiene al elemento <nav>, con la propiedad flex. 
	2.2 <nav> contiene un elemento <ul>
	2.3 <ul> en sus elementos <li> contienen elementos <a>.
	2.4 <a> contienen elementos <img>.
 3. Se integró un contenedor <nav> en el cual se hace uso de un elemento <ul> en donde se replica el mismo comportamiento del contenedor anterior. 
 4. Los tags están dentro de un elemento <div> que contiene elementos <a>, todos con una pseudoclase ::before.
 5. Se integra un <div> con prodiedad flex, 
	5.1 El <div> contiene un <h2>, <a>, <i> y pseudoelemento ::before.
	5.2 Se agregó otro <div> con propiedad <h3> que contiene una <img>.
 5. Contiene elementos <p>, con la propiedad <Strong>.
 6. Todos los elementos cuentan con la pseudoclase ::hover.

Sección MAIN (Pao Arreola):

 1. El elemento principal es un <div> con propiedad flex, que contiene tres <div>, que a la vez contienen: un elemento <button> y una <ul>. Todos comparten la propiedad flex y ::hover. 
 2. Le sigue un elemento <nav> que tiene <a> y ::hover con propiedad flex. 
 3. Se integra un <article> con 7 <div>, el primero contiene únicamente una <img> random, los 6 posteriores con propiedad flex y ::hover.
 4. El comportamiento anterior (sin la primera <img>), se repite por cada uno de los post de los integrantes del equipo. 
 5. Se creó el enlace para el segundo documento index-post.html.

Sección LISTING (Max Alejandro):

 1. Listing se eligió con la propiedad flex en boostrap.
 2. El elemento principal de listing, es un <aside> con la propiedad flex.
 3. El primer elemento dentro de <aside> es un <div>
	3.2 Contiene un <div> con un <a> y <h2> con propiedad flex y ::hover.
 4. Le sigue un <div> con elementos <p> con propiedades flex y ::hover. 
 5. El comportamiento anterior (4) se replica 6 veces, y el 3.2 completo se repite 3 veces. 

Sección FOOTER (Sam Castillo): 

 1. El contedor principal está dentro de la sección footer. 
 2. Dentro de el <div> principal se encuentra un elemento <div> y <a> con propiedades flex y ::hover. 
 3. Le sigue un elemento <ul> que contiene elementos <a> y <span> con propiedades flex y ::hover.
 4. Se repite el comportamiento anterior.
 5. Finalmente se agrega un <div> que contiene elementos <p> y elementos <a>, con propiedades flex y ::hover. 

-------------------------------------------------------------------------------------------------------------------------------------------------

Sección HEADER (Karla Herzo):
 1. Se mantiene el mismo procedimiento de la página 1. 

Sección MAIN_SECTION (Body):
 En esta sección se mantiene el ordenamiento de la pagina 1 con boostrap. 

Sección MENÚ--Post (Rob Cruz):
 1. Contiene un <aside>
	1.1 Contiene un elemento <div> que contiene un elemento <i> y un elemento <p> con propiedad flex y ::hover. 
 2. Se replica el comportamiento anterior tres veces. 

Sección MAIN (Pao Arreola):

 1. Contene un <article>
	1.1 El primer elemento entro de <article> en un <div> con una <img> random.
	1.2 Le sigue un <div>, que dentro tiene los elementos <img>, <div>, <a>, que comparten la propiedad flex y ::hover.
	1.3 El siguiente elemento es un <div>, que dentro tiene el elemento <a> y comparte la propiedad ::hover.
	1.4 El siguiente elemento es un <div> que colo contiene elementos <p>.
	1.5 Le sigue un <div> que contiene los elementos <div>, <h2>, <a>, <img>, <textarea>, <p>, y comparten las propiedades flex y ::hover.
	1.6 El siguiente elemento es un <div> con propiedad grid, que contiene los elementos <div>, <h3>, <i>, <img>, <p> y comparten las propiedades flex 	    y ::hover.

Sección LISTING (Max Alejandro):

 1. Listing se eligió con la propiedad flex en boostrap.
 2. El elemento principal de listing, es un <aside> con la propiedad flex.
 3. El primer elemento dentro de <aside> es un <div>
	3.1 <aside> contiene los elementos <img>, <h2>, <a>, <p>, <h3> con propiedades flex y ::hover. 
 4. El siguiente elemento es un <div> que contiene los elementos <div>, <h2> y <p> con propiedades flex y ::hover. 

Sección FOOTER (Sam Castillo): 

 1.  Se mantiene el mismo procedimiento de la página 1.