# Aplicación Inteligente de Gestión de Inventarios FullStack - DevSenior
Aquí se encuentra la construcción de una aplicación inteligente de gestión de inventarios empresarial Full-Stack con Spring Boot, Angular &amp; AI. Contando con 3 principales partes de su desarrollo:

## Parte1: El Backend y la Arquitectura Empresarial
**Objetivo Alcanzado**: Sentar las bases del desarrollo backend con Spring Boot y mostrar cómo la IA puede agilizar la creación de APIs.
**Contenido**:
- **Spring Boot**:
  - Uso Spring Boot para el desarrollo rápido de aplicaciones.
  - Configuración inicial de un proyecto con Spring Initializr.
- **Arquitectura Empresarial**:
  - Conceptos clave: capas de la aplicación (presentación, negocio, datos).
  - El patrón MVC (Modelo-Vista-Controlador) y su relación con una API REST.
  - Diseño de APIs RESTful: principios y mejores prácticas (verbos HTTP, códigos de estado, etc.).
- **Creación de una API RESTful con PostgreSQL usando IA**:
  - **Práctica**: Generación de código para una entidad (por ejemplo, `Producto` o `Estudiante`) con la ayuda de una herramienta de IA (como un generador de código).
  - **Configuración de la conexión a la base de datos**: Uso de `application.properties` para PostgreSQL.
  - **Creación de las capas**:
    - **Entidad (`Entity`)**: Definición del modelo de datos.
    - **Repositorio (`Repository`)**: Uso de JPA para la persistencia de datos.
    - **Servicio (`Service`)**: Lógica de negocio.
    - **Controlador (`Controller`)**: Exposición de los endpoints RESTful (GET, POST, PUT, DELETE).
  - **Demo**: Realizar una prueba de los endpoints con una herramienta como Postman.

## Parte2: Desarrollo Frontend con Angular
**ObjetivoAlcanzado**: Conceptos esenciales de Angular y mostrar cómo la IA puede acelerar la creación de componentes de la interfaz de usuario.
**Contenido**:
- **Desarrollo Web**:
  - Fundamentos: HTML (estructura), CSS (estilo) y JavaScript (interactividad).
  - Frameworks como Angular
- **SPA, Angular y TypeScript**:
  - **SPA (Single Page Application)**: Concepto y ventajas.
  - **Angular**: Características principales y elección popular para SPAs.
  - **TypeScript**: Tipado estático y cómo mejora el desarrollo.
- **Estructura y Tipos de Elementos**:
  - **Módulos**: Organización de la aplicación.
  - **Componentes**: El bloque fundamental de construcción de Angular (HTML, CSS y lógica).
  - **Modelos**: Definición de estructuras de datos.
  - **Servicios**: Lógica compartida e inyección de dependencias.
- **Creación de Componentes con IA**:
  - **Creación de una pantalla de listado**: Generación de un componente que consume y muestra datos de una API.
  - **Práctica**: Uso de la IA para generar el HTML (*ngFor) y el CSS para mostrar una tabla o una lista de elementos.
  - **Creación de un formulario de captura**: Generación de un componente para agregar o editar información.
  - **Práctica**: Uso de la IA para generar un formulario reactivo con validaciones básicas.

## Parte3: Integración, Seguridad y Mejores Prácticas
**Objetivo**: Conexión el frontend y el backend, asegurar la aplicación y finalizar con recomendaciones clave para un desarrollo profesional.
**Contenido**:
- **Integración entre Backend y Frontend**:
  - **CORS (Cross-Origin Resource Sharing)**: Uso como medida de seguridad
  - Configuración en Spring Boot para permitir peticiones desde el frontend de Angular.
  - **Consumo de APIs HTTP en Angular**: Uso del HttpClient para realizar peticiones (GET, POST, PUT, DELETE).

- **Mejores Prácticas**:
  - **Manejo de errores**: Capturar y mostrar errores de manera amigable al usuario.
  - **Código limpio**: Estructura del código, nombres de variables, comentarios.
  - **Mantenimiento y escalabilidad**: Consideraciones para el crecimiento de la aplicación.
  - **Futuro de la IA en el desarrollo de software**: Discusión sobre cómo la IA continuará transformando el sector.
- **Pendiente: Asegurando APIs**:
  - **Backend (Spring Security)**:
    - Spring Security y su importancia.
    - Conceptos clave: autenticación y autorización.
    - Configuración básica para proteger los endpoints.
  - **Frontend (Angular)**:
    - Estrategias de seguridad: manejo de tokens (JWT).
    - Uso de `interceptors` para añadir tokens a las peticiones HTTP.
    - Proteger las rutas de la aplicación con `guards`.
