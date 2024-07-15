# nodejs-first-project1.	

Filesystem (fs) en Node.js:
	•	Es un módulo incorporado en Node.js que permite interactuar con el sistema de archivos del servidor. Se utiliza para leer, escribir, actualizar, eliminar archivos y realizar operaciones de directorios.
	2.	Middleware en Express:
	•	Es una función que tiene acceso al objeto de solicitud (req), al objeto de respuesta (res) y a la siguiente función de middleware en el ciclo de solicitud/respuesta de una aplicación Express. Se utiliza para realizar tareas comunes como el análisis del cuerpo de las solicitudes, la gestión de sesiones, la autenticación, etc.
	3.	Endpoint en una API RESTful:
	•	Es una URL específica en una API donde los clientes pueden enviar solicitudes para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en los recursos.
	4.	Verbos HTTP:
	•	Son métodos que indican la acción a realizar en el servidor. Los más comunes son:
	•	GET: Obtener datos.
	•	POST: Enviar datos.
	•	PUT: Actualizar datos.
	•	DELETE: Eliminar datos.
	5.	JSON:
	•	JavaScript Object Notation es un formato de texto ligero para el intercambio de datos. Es utilizado en las API RESTful porque es fácil de leer y escribir tanto para humanos como para máquinas.
	6.	Body de una petición:
	•	Contiene los datos enviados por el cliente al servidor en una solicitud HTTP (generalmente con POST, PUT).
	7.	Body de una respuesta:
	•	Contiene los datos enviados por el servidor al cliente en una respuesta HTTP.
	8.	Query de una petición:
	•	Son parámetros que se envían en la URL de la solicitud, después del signo ?.
	9.	Params de una petición:
	•	Son parámetros de ruta que se especifican como parte de la URL, utilizados para identificar recursos específicos.
	10.	Verbo POST:
	•	Propósito: Enviar datos al servidor para crear un nuevo recurso.
	•	Uso: Cuando se necesita crear un nuevo recurso.
	•	Diferencias: POST crea un nuevo recurso, GET obtiene, PUT actualiza y DELETE elimina.
	•	Envío de datos: A través del cuerpo de la solicitud.
	11.	Verbo GET:
	•	Propósito: Obtener datos del servidor.
	•	Uso: Cuando se necesita recuperar datos.
	•	Diferencias: GET no modifica datos, POST crea, PUT actualiza y DELETE elimina.
	12.	Verbo PUT:
	•	Propósito: Actualizar un recurso existente.
	•	Uso: Cuando se necesita actualizar un recurso completo.
	•	Diferencias: PUT actualiza completamente, POST crea, GET obtiene y DELETE elimina.
	13.	Verbo DELETE:
	•	Propósito: Eliminar un recurso existente.
	•	Uso: Cuando se necesita eliminar un recurso.
	•	Diferencias: DELETE elimina, POST crea, GET obtiene y PUT actualiza.
	14.	Status code:
	•	Son códigos de respuesta HTTP que indican el estado de la solicitud.
	•	Más comunes:
	•	200: OK.
	•	201: Created.
	•	400: Bad Request.
	•	401: Unauthorized.
	•	404: Not Found.
	•	500: Internal Server Error.
	15.	Status code más comunes para el verbo POST:
	•	201: Created.
	•	400: Bad Request.
	16.	Status code más comunes para el verbo GET:
	•	200: OK.
	•	404: Not Found.
	17.	Status code más comunes para el verbo PUT:
	•	200: OK.
	•	204: No Content.
	•	400: Bad Request.
	•	404: Not Found.
	18.	Status code más comunes para el verbo DELETE:
	•	200: OK.
	•	204: No Content.
	•	404: Not Found.
