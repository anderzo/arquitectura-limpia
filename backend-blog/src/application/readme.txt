Aquí reside la lógica de aplicación, comúnmente estructurada en "Casos de Uso" (Use Cases) 
o servicios de orquestación. Su trabajo es coordinar las acciones del sistema: recibe las 
peticiones que vienen desde la API, aplica las reglas del negocio llamando a las entidades del dominio, 
y utiliza las interfaces de los repositorios para guardar o consultar datos. Al igual que el dominio, 
esta capa se mantiene aislada de los detalles técnicos de infraestructura, enfocándose únicamente en los 
flujos de trabajo de la aplicación.