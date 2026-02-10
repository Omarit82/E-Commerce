### E-Commerce

Ejemplo de un E-commerce realizado para el curso de Backend en Coderhouse

# Tecnologias Utilizadas
- Desarrollado en Node.JS
- Express - Express Session - Express Handlebars
- JWT para autenticacion
- Passport con conexion Github y local
- Mongo DB
- Sweet Alert para el frontend con Handlebars

# Caracteristicas
- CRUD completo
- Gestion de inventarios y stock
- Manejo de excepciones
- Validacion de datos

## Configuracion e Instalacion

git clone https://github.com/Omarit82/E-Commerce

Navega al directorio del proyecto y ejecuta:

npm install

finalmente:

npm run start

El proyecto estará disponible en: http://localhost:8080

*** Usuarios para ver funcionalidades: ***

user: omar@omar.com
pass: 123456

Rol de usuario, puede loguearse y ver los productos, no puede acceder a la ruta localhost:8080/new-product o cualquier ruta exclusiva del administrador (carga de stock, vista de tickets)

user: admin@admin
pass: admin

Rol de administrador, puede loguearse y ver los productos como un usuario normal. Sobre el header aparece un boton de Admin, para administrar el stock, la carga de un nuevo producto y la vista de los tickets de compras.
