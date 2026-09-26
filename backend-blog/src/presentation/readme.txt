presentacion o api (La Interfaz de Usuario / Entrada HTTP)
Esta es la capa encargada de exponer la aplicación al exterior para que los clientes 
(como la web o la app móvil) puedan consumirla. Contiene los controladores de NestJS 
(que reciben las peticiones HTTP), las rutas, los DTOs (Data Transfer Objects) para 
validar la estructura de los datos de entrada, y los filtros o guards de seguridad. 
Su única responsabilidad es traducir las solicitudes HTTP en llamadas a los casos de 
uso de la aplicación y devolver la respuesta formateada al cliente.