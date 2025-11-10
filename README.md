Backend Delivery
Instalación
📥 Descarga el repositorio.

 Ábrelo en tu IDE favorito.

 Crea la base de datos MariaDB/MySQL con nombre demon.

 Ajusta credenciales en src/main/resources/application.properties:

spring.datasource.url=jdbc:mariadb://localhost:3306/demon

spring.datasource.username=root

spring.datasource.password=12345678

 Instala dependencias y compila con ./mvnw clean install.

 Ejecuta DemonApplication.java.

👤 Usuario: admin   🔑 Contraseña: admin123


| Método | Endpoint | Descripción |
|--------|----------|-------------|
| `GET` | `/api/v1/products` |  Lista todos los productos |
| `POST` | `/api/v1/products` |  Crea un producto |
| `PUT` | `/api/v1/products/{id}` |  Actualiza por ID |
| `DELETE` | `/api/v1/products/{id}` |  Elimina por ID |
