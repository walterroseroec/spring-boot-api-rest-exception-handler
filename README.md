# Manejo de excepciones y validación de solicitudes en Spring Boot API REST Exception Hander y @Valid

Este proyecto tiene la configuración y desarrollo necesario para implemntar en tus APIs REST con Spring Boot el correcto uso de excepciones y validaciones aplicando buenas practicas para potenciar tus proyectos. 

## Explicación del proyecto

Puedes ver a detalle el proyecto directamente desde mi canal de YouTube [https://youtu.be/Ef2Y0YsQJCE](https://youtu.be/Ef2Y0YsQJCE)


## Script de la base de datos

```
create database db_springboot_dev;
CREATE TABLE `db_springboot_dev`.`clientes` (
  `id_cliente` INT ZEROFILL NOT NULL AUTO_INCREMENT,
  `nombre` VARCHAR(45) NOT NULL,
  `apellido` VARCHAR(45) NOT NULL,
  `correo` VARCHAR(45) NOT NULL,
  `fecha_registro` date  NOT NULL,
  PRIMARY KEY (`id_cliente`));
INSERT INTO clientes (nombre, apellido, correo, fecha_registro) VALUES('Joel', 'Jurado', 'juradoec@yahoo.com', '2023-08-01');
INSERT INTO clientes (nombre, apellido, correo, fecha_registro) VALUES('Carlos', 'Miranda', 'mirandaTr98@gmail.com', '2023-08-02');
INSERT INTO clientes (nombre, apellido, correo, fecha_registro) VALUES('Marcela', 'Sanchez', 'schMarce@itb.com', '2023-08-03');
INSERT INTO clientes (nombre, apellido, correo, fecha_registro) VALUES('Ben', 'Tennyson', 'ben10@cn.com', '2023-08-04');
```

