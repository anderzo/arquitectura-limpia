Esta carpeta contiene las reglas de negocio puras y las entidades fundamentales 
de tu aplicación. Define qué es un objeto de negocio (por ejemplo, un usuario o una noticia) 
y establece los contratos o interfaces de lo que el sistema necesita hacer (como los métodos de un repositorio). 
Lo más importante es que esta capa no conoce nada del exterior: no sabe de bases de datos, frameworks como NestJS, 
ni librerías externas. Es código totalmente agnóstico que puede sobrevivir aunque cambies de tecnología por completo.