# GESTION
 
# Los códigos de respuesta:

> 1. 500 : Internal Server Error → Se ha producido un error interno
> 2. 422 : Unprocessable Entity → Entidad no procesable
> 3. 400 : Bad Request → La solicitud contiene sintaxis errónea y no debería repetirse
> 4. 204 : No Content → La petición se ha completado con éxito pero su respuesta no tiene ningún contenido

# Definimos las URL que emplearemos
No usar verbos

> GET /credencial → recuperara una lista de personas.
> GET /credencial/1 → recupera la información de una persona en especifico.

> GET / → /c → recuperara una lista de personas.

# Configurar peticiones con rutas del proyecto

> 1. obtener credencial : GET : http://localhost/gestion/credencial
