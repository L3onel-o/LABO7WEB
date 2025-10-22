# LABO7WEB

Por error llame a mi proyecto labo 6, pero todo lo demas esta bien

Pregunta 1: ¿Cuál es la diferencia entre autenticación y autorizacion?

Autenticacion: Es el proceso de verificar la identidad del usuario cuando intenta 
acceder a un sitio o aplicación web.

Ejemplo: Cuando un usuario entra a una pagina web y llena un formulario con email 
y contraseña, el servidor comprueba si existen en la base de datos.

Autorizacion: Es el proceso de determinar qué puede hacer o ver el usuario ya autenticado.

Ejemplos: 
Un usuario normal puede ver su perfil, pero no puede acceder al panel de administración.

Un usuario con rol admin sí puede crear, editar o eliminar usuarios.

Pregunta 2: ¿Cuál es la función del token JWT en la guía?

El JWT cumple el papel central en el proceso de autenticación y 
autorización entre el cliente (React) y el servidor (Express).

1- Identificar al usuario autenticado
2- Mantener la sesión sin necesidad de almacenarla en el servidor
3- Autorizar el acceso a recursos protegidos
4- Proteger el sistema contra accesos no autorizados
