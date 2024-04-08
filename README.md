# Eightroom_wp
Wordpress Site Test creado para Eightroom 

#Descripción

Este proyecto fue desarrollado como una pagina de noticias deportivas ficticia. 
El desafió es usar WordPress, generar un sistema de entradas con custom_fields, utilizar taxonomia de categorías. 
Para esto cree 2 paginas y una entrada de post, en la pagina principal se ven los modulos centrales de la web uno de ellos es una seccion de noticias destacadas donde te muestra las ultimas 6 noticias, aparte de este tiene unas solapas para poder filtrarla por categorías.
Si vas a la sección noticias te muestra todas las noticias cargadas en formato de cards pudiendo acceder a ellas individualmente. 
Y por ultimo esta la seccion de la nota en si. Esta esta hecha con custom fields para poder cargar contenido facilmente desde el administrador de wordpress.
Todo el sitio esta hecho resposive tanto para tabletas como celulares. 


#Proceso de creación y archivos

Se genero un tema padre donde están el esqueleto del tema, acá genere los archivos principales con estructura basica y los vinculos bases entre las plantillas, templates-parts, y archivos scss, css y js.
El tema esta compuesto por 2 plantillas Home (home.php) usada como pagina principal y "Noticias"  (template-noticias.php). Estas plantillas tienen submodulos que estan alojados en /template-parts. Cada modulo esta vinculado a un css, se trabajo con scss pero se copilo, tiene instalado NPM y en el package.json está el script para ejecutar la copilación 
Los estilos los puse en una carpeta Styles en la raiz del tema, las fuentes y js en otra llamada Assets. Todo lo que son Imagenes estan por fuera del tema en la carpeta Uploads. 
En function.php instale la fuente (la misma que la pagina principal del tema), cree un tipo de entrada nueva que se llama "Noticias" e vincule un archivo ACF o custom Field (que se encuentra en la carpeta /inc/custom_fields) para poder cargar los datos de la entrada desde el administrador de wordpress. 

En el tema hijo desarrolle todas las paginas, genere todos los scss css y js necesarios. 


