¿Que es CRUD de PHP?
CRUD en PHP se refiere a las operaciones básicas que se realizan en bases de datos: Crear (Create), Leer (Read), Actualizar (Update) y Borrar (Delete). Estas operaciones son fundamentales en el desarrollo de aplicaciones web y se utilizan para interactuar con los datos almacenados en una base de datos.

En el contexto de PHP, CRUD se implementa utilizando SQL para interactuar con la base de datos y PHP para manejar las solicitudes del cliente y generar las consultas SQL necesarias. Por ejemplo, para crear un registro en una base de datos, se utilizaría una consulta de inserción SQL dentro de un script PHP que se ejecutaría cuando el usuario enviara un formulario.

# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario.

## Tecnologías Utilizadas

- **PHP:** Lenguaje de script del lado del servidor utilizado para el desarrollo web.
- **MySQL:** Sistema de gestión de base de datos utilizado para almacenar datos de usuario.
- **HTML & CSS:** Utilizados para estructurar y dar estilo a las páginas web.
- **Tailwind CSS:** Un framework de CSS utilitario para el desarrollo rápido de interfaces de usuario.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- **Funcionalidad:** Muestra todos los usuarios de la base de datos en un formato de tabla.
- **Características:** 
  - Ver todos los usuarios.
  - Enlaces de navegación para agregar, editar o eliminar información de usuario.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

- **Funcionalidad:** Permite agregar un nuevo usuario a la base de datos.
- **Características:** 
  - Formulario para ingresar detalles del usuario (nombre, correo electrónico, teléfono móvil, contraseña).
  - Validación de datos y envío a la base de datos.

### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

- **Funcionalidad:** Permite editar detalles de usuarios existentes.
- **Características:** 
  - Formulario prellenado con la información actual del usuario.
  - Actualización de detalles del usuario en la base de datos.

### 4. Eliminar Usuario (`delete.php`)

- **Funcionalidad:** Facilita la eliminación de un usuario de la base de datos.
- **Características:** 
  - Eliminación de información de usuario basada en el ID de usuario.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

1. Clona el repositorio en tu máquina local.
2. Configura un entorno PHP y MySQL (como XAMPP).
3. Crea la base de datos usando phpmyadmin.
4. Ejecuta la aplicación en un servidor local.

## Nota de Seguridad
Esta aplicación representa una demostración básica y no cuenta con medidas de seguridad avanzadas implementadas. Se aconseja el uso de declaraciones preparadas (prepared statements) o ORM para las interacciones con la base de datos, con el fin de prevenir posibles ataques de inyección SQL.

-En resumen, la aplicación CRUD de PHP proporciona una demostración básica de cómo realizar operaciones de creación, lectura, actualización y eliminación en una base de datos MySQL utilizando PHP. A través de diferentes páginas y funcionalidades, los usuarios pueden agregar, ver, editar y eliminar información de usuario.

Sin embargo, es importante destacar que la seguridad de la aplicación es limitada. Se recomienda encarecidamente implementar medidas de seguridad adicionales, como el uso de declaraciones preparadas o el uso de un ORM, para proteger la aplicación contra posibles ataques de inyección SQL. Estas precauciones son cruciales para garantizar la integridad y seguridad de los datos de la aplicación en entornos de producción.
Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

