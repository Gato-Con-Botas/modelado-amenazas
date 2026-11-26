# Modelado de Amenazas — Sitio Web de la Biblioteca Universitaria

Repositorio para la elaboración y almacenamiento del modelo de amenazas en formato JSON mediante **OWASP Threat Dragon**, correspondiente a la experiencia educativa **Programación Segura**.

## Datos de la actividad

- **Institución:** Universidad Veracruzana — Facultad de Estadística e Informática
- **Programa educativo:** Licenciatura en Ingeniería de Software
- **Experiencia educativa:** Programación Segura
- **Docente:** Mtro. Guillermo Humberto Vera Amaro
- **Estudiante:** Jorge Manuel Cobos Castro (`S23014045`)
- **Herramienta:** [OWASP Threat Dragon](https://www.threatdragon.com/#/)

## Descripción del sistema

El sitio web de la biblioteca universitaria es la primera implementación de una plataforma en línea para brindar servicios a bibliotecarios y usuarios de la biblioteca (estudiantes y personal universitario). Los roles contemplados son:

1. **Estudiantes:** inicio de sesión y búsqueda de libros.
2. **Personal universitario:** inicio de sesión, búsqueda de libros y solicitud de libros.
3. **Bibliotecarios:** inicio de sesión, búsqueda de libros, registro de libros y gestión de usuarios.

## Diagramas incluidos en el modelo

1. **Diagrama de flujo de datos — Sitio web de la biblioteca universitaria:** modela la interacción general entre usuarios, bibliotecarios, el servidor web, los archivos de configuración/páginas en disco y la base de datos MySQL bajo la metodología **STRIDE**.
2. **Diagrama de flujo de datos — Inicio de sesión del usuario:** detalla el flujo de autenticación entre el controlador web, el proceso de inicio de sesión, las vistas y la base de datos.

## Estructura del repositorio

- `README.md`: documentación general de la práctica.
- `Sitio web de la biblioteca universitaria.json`: archivo del modelo de amenazas generado y actualizado por OWASP Threat Dragon.
