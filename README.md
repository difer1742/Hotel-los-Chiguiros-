# Hotel-los-Chiguiros-
 Sistema web de gestión hotelera orientado a la administración de reservas, huéspedes, habitaciones y personal del Hotel Los Chigüiros, ubicado en la Vereda Pompeya, Villavicencio, Meta. El proyecto busca mejorar los procesos administrativos internos del hotel y ofrecer una plataforma digital moderna para sus clientes.


🚀 Tecnologías Utilizadas

- Java JDK 21
- Jakarta EE 10
- JSP (Java Server Pages)
- Servlets
- Apache NetBeans 25
- Eclipse GlassFish 7.1.1
- MySQL 8
- Maven
- HTML5
- CSS3
- JavaScript


📋 Requisitos del Sistema

- Java JDK 21 o superior
- Apache NetBeans 25
- GlassFish Server 7
- MySQL Server 8
- MySQL Workbench
- Maven


⚙️ Instalación del Proyecto
1. Clonar el repositorio
git clone https://github.com/usuario/hotel-los-chiguiros.git
2. Abrir en NetBeans

- Abrir Apache NetBeans.
- Seleccionar:
File → Open Project

- Buscar la carpeta:
hotel_los_chiguiros


3. Configurar GlassFish
Agregar servidor:
Services
└── Servers
    └── Add Server
Seleccionar:
GlassFish Server 7


4. Crear Base de Datos
CREATE DATABASE hotel_chiguiros;
Seleccionar:
USE hotel_chiguiros;


🗄️ Modelo de Datos
Actualmente el sistema cuenta con las siguientes entidades:
Roles
roles
Permite definir:

- Administrador
- Recepcionista
- Empleado
Usuarios
usuarios
Controla el acceso al sistema.
Campos:

- id_usuario
- usuario
- password
- id_rol
- id_empleado
- estado
Empleados
empleados
Información del personal del hotel.
Clientes
clientes
Información de huéspedes y visitantes.
Habitaciones
habitaciones
Control de disponibilidad y características.
Reservas
reservas
Registro de hospedajes.


🎯 Funcionalidades Implementadas
✅ Login Visual
Formulario desarrollado con:

- HTML5
- CSS3
Características:

- Validación HTML
- Campos requeridos
- Diseño responsive


✅ Conexión a MySQL
Conexión mediante:
DriverManager.getConnection()
Características:

- JDBC
- Manejo de excepciones
- Validación de conexión


✅ Arquitectura MVC
Estructura actual:
com.hotel_los_chiguiros

├── config
├── controller
├── dao
└── model


✅ Modelo Usuario
Clase:
Usuario.java
Encargada de representar los usuarios del sistema.


✅ DAO Usuario
Clase:
UsuarioDAO.java
Implementación de acceso a datos para:

- Consultar usuarios
- Validar credenciales


✅ Servlet de Login
Clase:
LoginServlet.java
Permite:

- Recibir credenciales
- Consultar la base de datos
- Validar acceso
- Redireccionar al Dashboard


✅ Dashboard Administrativo
Acceso exitoso después del login.
Página actual:
dashboard.html


📁 Estructura Actual del Proyecto
hotel_los_chiguiros

├── src
│
├── main
│   │
│   ├── java
│   │
│   │   └── com.hotel_los_chiguiros
│   │       │
│   │       ├── config
│   │       ├── controller
│   │       ├── dao
│   │       └── model
│   │
│   └── webapp
│       │
│       ├── admin
│       ├── cliente
│       ├── css
│       ├── empleados
│       ├── habitaciones
│       ├── img
│       ├── js
│       ├── layouts
│       ├── login
│       ├── reservas
│       │
│       ├── dashboard.html
│       └── index.html
│
└── pom.xml


🔒 Seguridad Implementada

- Validación de formularios HTML
- Prepared Statements
- Prevención básica de SQL Injection
- Manejo de excepciones
- Separación por capas (MVC)


🚧 Roadmap del Proyecto
Módulo 1
✅ Login
✅ Dashboard


Módulo 2
🔲 Gestión de Habitaciones

- Registrar habitaciones
- Editar habitaciones
- Eliminar habitaciones
- Consultar habitaciones


Módulo 3
🔲 Gestión de Clientes

- Registro de clientes
- Consulta de clientes
- Historial de reservas


Módulo 4
🔲 Gestión de Reservas

- Crear reserva
- Modificar reserva
- Cancelar reserva


Módulo 5
🔲 Gestión de Empleados

- Registro de empleados
- Actualización de información
- Gestión de usuarios


Módulo 6
🔲 Gestión de Turnos

- Asignación de horarios
- Calendario laboral


Módulo 7
🔲 Nómina

- Liquidación de salarios
- Horas extras
- Reportes


👨‍💻 Autor
Diego Fernando Cardozo Polania 
GitHub: https://github.com/difer1742/Hotel-los-Chiguiros
Proyecto: Hotel Los Chigüiros - Villavicencio, Meta, Colombia.

