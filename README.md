Backend Delivery – Documentación principal
Instalación rápida
Clona o descarga el repo.

Abre en tu IDE (IntelliJ/VSCodium/NetBeans).

Crea la base de datos MariaDB/MySQL:

Nombre: demon

Ajusta credenciales en src/main/resources/application.properties:

spring.datasource.url=jdbc:mariadb://localhost:3306/demon

spring.datasource.username=root

spring.datasource.password=12345678

Instala dependencias y compila el proyecto:

./mvnw clean install o con el IDE.

Ejecuta DemonApplication.java.

Usuario demo: admin / Contraseña: admin123 (configurable)

Endpoints principales (productos)
GET /api/v1/products — Lista todos los productos

POST /api/v1/products — Crea un producto

PUT /api/v1/products/{id} — Actualiza por ID

DELETE /api/v1/products/{id} — Elimina por ID


