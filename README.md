# api-design


Acceso a recursos 

WireMock UI
http://localhost:9000
http://139.144.239.109:9000

SwaggerEditor
http://localhost:9080
http://139.144.239.109:9080

REST representational state transfer
principios y reglas para el diseno de arquitecturas web que utilizan http para ña transferencia de datos rest se basa en el uso de recurso y en la representacionde los mismos mediante urls y metodos http
una api restful expone recursos a traves de urls y utiliza metodos http (GET, PUT, POST, DELETE)

principios de REST
- recursos, cualquier cosa que pueda ser identificada con una url, como un objeto, una imagen, un archivo
- Verbos HTTP get put post delete
- URIs
- representacion de recursos

ventajas de REST en apis
- escalabilidad
- flexibilidad
- bajo acoplamiento
- alta visibilidad
- seguridad

como se disena la estructura de una api

- define los recursos, identifica los recursos y asigna una uri unica a casa uno de ellos
- define los metodos HTTP
- define los formatos de respuesta, por ejmplo xml, json, html
- define los codigos de estado HTTP
- considera la escalabilidad, patrones como cache, paginacion, compresion
- considera la documentacion
