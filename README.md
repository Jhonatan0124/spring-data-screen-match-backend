# Screen Match Application

Este proyecto es una aplicación de Screen Match desarrollada con Java Spring Data JPA. La aplicación permite buscar y guardar series y episodios en una base de datos relacional, realizar diferentes tipos de consultas, y mostrar información detallada sobre las series y episodios.

## Características

- **Bases de Datos Relacionales**: Utiliza una base de datos relacional para almacenar series y episodios.
- **Modelado de Clases**: Modela las clases de Series y Episodios con relaciones adecuadas.
- **Tipos de Consultas**: Soporta Derived Queries, Native Queries y JPQL.
- **Buscar y Guardar Series**: Permite buscar cualquier serie y guardarla en la base de datos.
- **Buscar y Guardar Episodios**: Permite buscar episodios y guardarlos en la base de datos.
- **Mostrar Información**: Muestra todas las series y episodios buscados.
- **Buscar Series por Título**: Permite buscar series por su título.
- **Top 5 Mejores Series**: Muestra las top 5 mejores series.
- **Buscar Series por Categoría**: Permite buscar series por categoría.
- **Filtrar Series**: Filtra series por el número de temporadas y su evaluación.
- **Buscar Episodios por Nombre**: Permite buscar episodios por su nombre.
- **Top 5 Episodios por Serie**: Muestra los top 5 episodios por serie.
- **Relaciones entre Tablas**: Soporta relaciones OneToMany y ManyToOne.
- **Relaciones Bidireccionales**: Implementa relaciones bidireccionales entre las entidades.
- **Guardar Episodios de Series**: Permite guardar episodios de las series.
- **Llave Foránea**: Relaciona correctamente la llave foránea entre las tablas.
- **Queries Derivadas**: Soporta queries derivadas para búsquedas complejas.
- **Búsqueda Personalizada**: Permite la búsqueda de datos personalizada.
- **Búsqueda por Categorías con Enums**: Utiliza enums para buscar por categorías.

## Requisitos

- Java 8 o superior
- Spring Boot
- Spring Data JPA
- Maven
- Base de datos relacional (ej. MySQL, PostgreSQL)

## Instalación

1. Clona este repositorio:
   ```sh
   git clone https://github.com/tu-usuario/screen-match-application.git
