# Prueba-de-concepto-con-Postman

Objetivos: Aprender a utilizar Postman para testear servicios REST.
Realizar una prueba de concepto.
Se pide: Instalar la herramienta Postman (link).
Utilizando la misma, crear una colección de pruebas para el siguiente servicio REST:
https://jsonplaceholder.typicode.com/posts

Operaciones:
GET - listar/buscar (utilizado como posts/45 obtiene el elemento con id=45)
PUT - actualizar (se deben enviar todos los valores salvo el ID, usando una ruta que incluya el ID del elemento, por ejemplo /posts/45)
POST - crear (se deben enviar todos los datos)
DELETE - borrar (se puede indicar cual ítem borrar por ID o cualquier otro atributo)
Nota: las modificaciones no se guardan en el servidor, solo se retornan en el momento de ejecución como tales.
Generar al menos 5 casos de prueba que validen los resultados.
Se debe incluir al menos 1 prueba inválida.
Se deben incluir al menos 2 pruebas cuyo resultado dependa de los datos enviados.

Elaborar un informe correspondiente a la tarea que incluya al menos los siguientes puntos:

Pruebas ejecutadas
Informar los resultados esperados, los resultados obtenidos, las validaciones (assertions) utilizadas y justificación.
Conclusiones y comentarios
