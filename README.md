<div align="justify">
                 
# Sistema de cotizaciones  
He desarrollado un sistema web utilizando PHP y MySQL que permite la creación de clientes y generación automática de cotizaciones, incluyendo el cálculo del costo y tiempo estimado. Además, brinda la opción de imprimir las cotizaciones.

Una característica adicional es la sección de ajustes, donde se pueden personalizar diversos mensajes que se incluirán en las cotizaciones, como el remitente o un mensaje de agradecimiento.

# Instalación
Exporta el cóigo y editalo a tu gusto.
También puedes empezar a hacer uso del sistema como está. Para iniciarlo debes editar el archivo `env.php`, agrega las credenciales de la base de datos y actualiza el archivo.


# Características del software

Entre sus principales características encontramos las siguientes:

*   Realizar cotizaciones o presupuestos.
*   Estimar el costo requerido, el cual se configura por cada servicio.
*   Calcular tiempo requerido por cada servicio.
*   Describir características y/o condiciones del trabajo.
*   Agregar clientes para ligarlos a las cotizaciones.
*   Imprimir la cotización o guardarla como PDF (esto depende del navegador la mayoría de veces).
*   Multiusuario: cualquier usuario puede registrarse y usarlo, así de simple. Eso sí, las cotizaciones, servicios y características son separadas por usuario.
*   Totalmente open source.
*   Escrito con PHP, utiliza PDO para interactuar con la base de datos.
*   Base de datos MySQL.
*   Lado del cliente con Vue.JS y Bootstrap.
*   Mensaje de agradecimiento, presentación y footer totalmente configurables.

# Datos técnicos

-Este sistema está creado con PHP utilizando PDO para conectar con MySQL.

-En el lado del cliente utiliza a Bootstrap 4 y Vue.Js en su versión 2.

-La sesión de PHP es manejada por un Handler propio.

-No se utiliza ningún framework para PHP.

-Las contraseñas están cifradas con _bcrypt_.

-Se usa un token CSRF para evitar ataques CSRF.

-El sistema usa  _PHP_, el framework _Bootstrap 4_ para los estilos y sólo un poco de _JavaScript_ con _Vue.js_ para mejorar la experiencia de usuario y renderizar algunas cosas.

# Demostración y pruebas del software

Puedes probar el sistema aquí: https://demos-github-jl.000webhostapp.com/Cotizaciones-Web-Con-PHP/

Regístrate con tu correo electrónico y luego inicia sesión. El software es web, y por lo tanto multiplataforma. 

Puedes acceder a él desde una tableta, teléfono o computadora desde cualquier parte del mundo. Aparte de eso, gracias al diseño responsivo se adapta a cualquier pantalla. 
  
# Requisitos del sistema   

Necesita un servidor con *PHP y Apache*. La versión mínima de PHP es la *5.6*, esto debido a que se usa la notación corta del arreglo `[]`.

## Extensiones  
* PDO  
## Base de datos  
Base de datos de MySQL o MariaDB. El esquema está en _esquema.sql_  
  
## Credenciales  
Configurar las credenciales en el archivo _env.php_.  
  
# Licencia  
Código fuente disponible bajo la licencia MIT.

</div> 

# Capturas del proyecto
##Iniciar Sesión
