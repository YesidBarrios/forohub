# ForoHub

ForoHub es una aplicación de foro desarrollada con Spring Boot. Permite a los usuarios crear, leer, actualizar y eliminar tópicos en diferentes cursos.

## Tecnologías Utilizadas

- **Java**
- **Spring Boot**
- **Maven**
- **JPA/Hibernate**
- **PostgreSQL**

## Estructura del Proyecto

El proyecto está organizado en los siguientes paquetes:

- `model`: Contiene las entidades `Usuario`, `Curso` y `Topico`.
- `repository`: Contiene los repositorios `UsuarioRepository`, `CursoRepository` y `TopicoRepository`.
- `service`: Contiene la lógica de negocio en `TopicoService`.
- `controller`: Contiene los controladores REST en `TopicoController`.

## Endpoints

### TopicoController

- **GET /topicos**: Obtiene todos los tópicos.
- **GET /topicos/{id}**: Obtiene un tópico por ID.
- **POST /topicos**: Crea un nuevo tópico.
- **PUT /topicos/{id}**: Actualiza un tópico existente.
- **DELETE /topicos/{id}**: Elimina un tópico por ID.

## Cómo Ejecutar la Aplicación

1. Clona el repositorio:
   ```sh
   git clone https://github.com/YesidBarrios/forohub.git
