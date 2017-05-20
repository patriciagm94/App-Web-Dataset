# App Web Unidad 4: Premios Nobel.
----
# Contenido:

- Aplicación Propuesta
- Sector al que va orientado
- Miniguía "Consumiendo información de un dataset"
- Mockup de la aplicación
- Primer previo de página

----
# Aplicación Propuesta .
La aplicación web que se pretende realizar estará hecha para la promoción de la cultura e historia respecto a los *Premios Nobel*, sus ganadores, y una breve reseña con los datos más relevantes de éstos. Ya sea para quienes realicen investigaciones o tareas al respecto o al público en general que desee conocer esta información.
# Sector al que va orientado:

Se pretende que el alcance de ésta aplicación se vaya extendiendo, comenzando por estudiantes de cualquier nivel educativo que requieran información relativa al tema, hasta especialistas que se encuentren realizando investigaciones; sin olvidar al público en general, que puede requerir esta información con cualquier fin, ya sea didáctico o como cultura general.

----
# Miniguía: Consumiendo de una API:

Para poder trabajar con la API que seleccionamos se pueden utilizar diferentes herramientas o software de escritorio, haciendo que nuestro dataset esté como local en nuestra computadora. En el caso particuar de esta aplicación y para esta guía breve se optó por utilizar una herramienta on-line llamada **Hurl.it**.
Para utilizar esta herramienta solo basta con abrir el link de la página mencionada anteriormente y tener a mano el link de nuestra API.
- 1. Aparece una caja para introducir texto en la cual se pega el link de nuestra API
- 2. Se verifican ciertos captchas y se envía el requerimiento.
- 3. Lo que nos devolverá la página será nuestra API en formato JSON con sus distintos campos existentes.

>> {
    "prizes": [
    {"year": "2016","category": "physics","laureates": [
    {"id":       "928","firstname": "David J.","surname": "Thouless","motivation": "\"for theoretical discoveries of topological phase transitions and topological phases of matter\"","share": "2"}
    ]}
    ]}
    
Posteriormente hemos cambiado la herramienta utilizada a **Postman** [www.getpostman.com] en versión tanto de escritorio así como la extensión web disponible para el navegador Google Chrome.

---
# Mockup de la aplicación:
El programa utilizado para la realización del modelo de la aplicación web se llama **Proto IO**, es una herramienta de escritorio para prototipar aplicaciones web y/o móviles.
Preview de la aplicación web final
[mockup]: https://github.com/patriciagm94/App-Web-Dataset/blob/master/1.1-Screen%201.png


El Dataset a utilizar es el siguiente: https://github.com/jdorfman/awesome-json-datasets#nobel-prize

----
# Primer previo de página en HTML.
El archivo con extensión HTML se encuentra en este mismo repositorio, aquí sólo se muestra un previo de la página a la cual tendrá acceso el público al término del proyecto.

[Preview](https://gyazo.com/fe84e4af27cbe837fa3aef22e078a69c)
