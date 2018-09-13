# NetKitHTTP

El informe debe detallar las experiencias realizadas con el laboratorio propuesto. Adicionalmente se deben capturar las tramas y analizar fuera con un analizador gráfico como wireshark y verificar todos los hallazgos (exibir pantallas en los informes). Es importante que muestren como comprueban que HTTP 1.1 es persistente.
Deberán crear una página, linkeada a la original con un formulario sencillo con un campo como mínimo y pasar la información por GET y mostrar que se recibió el dato. A continuación crear otra página tambien linkeada a la principal que haga lo mismo pero usando POST
Comprobar en ambos casos como es el diálogo a nivel protocolo.
Luego se deberá configurar un router entre el cliente y anexar otro servidor ambos en la misma red detras del router con ruteo estático y colocar en dicho router un NS que maneje dos subdominios elementales cuyos hosts serán los dos servidores web que le asignaran sendos nombres y alias "www" en cada uno de los subdominios.
Luego explicar la relación entre DNS y WWW justificando siempre con tramas.
Finalmente modificará los DNS para que apunten a uno solo de los servidores web y modificará Apache para que tenga configurado la respuesta correcta según al URL mediante virtual host.

Queda una segunda parte a revisar que es el uso de cookies para menajar sesiones y que lo diferencia con con .htaccess y cuál es el problema que se observa al intercambiar password y que solución se podría emplear. Esta parte del práctico se hará guiada vía el foro.

Bolzan-Trincheri-Torboli
