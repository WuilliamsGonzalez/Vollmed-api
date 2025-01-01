# Proyecto: Vollmed Api SpringBoot 3

Este repositorio contiene el código del proyecto desarrollado como parte del curso de **Spring Boot 3** ofrecido por **Alura Latam**. El proyecto incluye la implementación de una aplicación backend que utiliza Spring Boot 3 en Java y bases de datos relacionales como **MySQL** y **PostgreSQL**. Además, se realizaron pruebas de API con **Insomnia**.

## Tecnologías utilizadas

- **Java**
- **Spring Boot 3**
  - Spring Data JPA
  - Spring Web
  - Spring Security
- **MySQL**
- **PostgreSQL**
- **Insomnia** (para pruebas de endpoints)
- **Maven** (gestión de dependencias)

## Funcionalidades del proyecto

- Gestión de entidades principales con operaciones CRUD.
- Conexión a bases de datos relacionales mediante JPA.
- Configuración de perfiles para soportar MySQL y PostgreSQL.
- Pruebas de endpoints utilizando Insomnia.


## Requisitos previos

- **Java 17 o superior**
- **Maven 3.8+**
- **MySQL y/o PostgreSQL instalados**
- **Insomnia** (opcional, para pruebas)

## Configuración del proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/WuilliamsGonzalez/Vollmed-api.git
   ```

2. Configura las propiedades de conexión en `application-dev.properties` o `application-prod.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/nombre_de_tu_bd
   spring.datasource.username=usuario
   spring.datasource.password=contraseña
   ```

3. Ejecuta la aplicación:
   ```bash
   mvn spring-boot:run
   ```

## Pruebas de API

Puedes importar el archivo de configuración de Insomnia (si existe) para realizar pruebas. Asegúrate de que la base de datos esté correctamente configurada antes de ejecutar las pruebas.

## Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

**CÓDIGO CREADO POR ALURA LATAM**
