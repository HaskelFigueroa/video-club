# Video Club

Sistema desarrollado como parte de una actividad académica para administrar un Video Club. Permite registrar películas, clientes y rentas, facilitando el control y seguimiento de la información mediante el uso de Git y múltiples repositorios remotos (GitHub, GitLab y Bitbucket).


## Getting Started

Estas instrucciones te permitirán obtener una copia del proyecto y ejecutarlo en tu máquina local para desarrollo y pruebas.

### Prerequisites

Necesitas tener instalado lo siguiente:

- Java JDK 17 o superior
- Apache NetBeans (o cualquier IDE compatible con Java)
- Git


### Installing

### Clonar el repositorio

```bash
git clone https://github.com/TU_USUARIO/video-club.git
```

### Entrar al directorio del proyecto

```bash
cd video-club
```

### Abrir el proyecto en el IDE

Abrir el proyecto en Apache NetBeans (o IDE preferido) y ejecutar la aplicación.

Al ejecutarlo podrás:

- Registrar clientes
- Registrar películas
- Realizar rentas
- Consultar información almacenada


## Running the tests

Las pruebas del sistema se realizan ejecutando la aplicación y validando el flujo completo de uso.

### Break down into end to end tests

Estas pruebas verifican el funcionamiento completo del sistema.

Ejemplo de flujo de prueba:

```text
Registrar cliente → Registrar película → Realizar renta → Verificar disponibilidad
```

Esto garantiza que todos los módulos funcionen correctamente de manera integrada.

## Deployment

El código sigue buenas prácticas de programación en Java:

- Uso de camelCase para variables y métodos
- Organización por clases
- Separación lógica del sistema
- Uso de patrones como Singleton (si aplica)

Ejemplo:

```java
public class Cliente {
    private String nombre;
    private String telefono;
}
```

## Built With

- Java – Lenguaje principal del sistema
- Apache NetBeans – Entorno de desarrollo
- Git – Control de versiones
- GitHub / GitLab / Bitbucket – Repositorios remotos utilizados

## Contributing

Este proyecto fue desarrollado con fines académicos. Las mejoras pueden realizarse mediante:

1. Crear un fork del repositorio
2. Crear una nueva rama
3. Realizar cambios
4. Enviar Pull Request

## Versioning

Se utiliza control de versiones con Git.

**v1.0.0** – Primera versión funcional del sistema.

## Authors

**Haskel Figueroa** – Desarrollo del sistema

## License

Proyecto de uso académico y educativo.

## Acknowledgments

Maestro: Oscar Daniel Pérez Piñón
