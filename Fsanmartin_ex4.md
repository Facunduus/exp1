#Explica la diferència entre una petició *GET* i una petició *POST*
##Diferencies:
La diferencia entre los métodos *get* y *post* radica en la forma de enviar los datos a la página cuando se pulsa el botón “Enviar”. Mientras que el método *GET* envía los datos usando la URL, el método *POST* los envía de forma que no podemos verlos (en un segundo plano u "ocultos" al usuario).
##GET:
El concepto __GET__ es *obtener información* del servidor. Traer datos que están en el servidor, ya sea en un archivo o base de datos, al cliente. Independientemente de que para eso tengamos que enviar (request) algún dato que será procesado para luego devolver la respuesta (response) que esperamos, como por ejemplo un identificador para obtener una noticia de la base de datos. En el metodo *get* el **url** es visible para el usuario. [GitHub](http://github.com). ![Ejemplo](captura.png)
##POST:
**POST** sin embargo es *enviar información* desde el cliente para que sea procesada y actualice o agregue información en el servidor, como sería la carga o actualización en sí de una noticia. Cuando enviamos (request) datos a través de un formulario, estos son procesados y luego a través de una redirección por ejemplo devolvemos (response) alguna página con información. 
![Ejemplo](captura2.png)