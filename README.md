# Proyecto SOA - Servicio de Orientación para Adolescentes

El Proyecto SOA es un conjunto de 8 microservicios diseñados para ofrecer funcionalidades específicas relacionadas con la gestión de una correccional para adolescentes (SOA - Servicio de Orientación para Adolescentes). Cada microservicio se enfoca en aspectos clave del sistema, permitiendo un funcionamiento modular y escalable.

## Microservicios

1. **Adolescente:** Microservicio encargado de gestionar la información de los adolescentes ingresados en la correccional.
2. **Funcionario:** Gestiona los datos relacionados con el personal que trabaja en la correccional.
3. **Apoderado:** Se encarga de la gestión de los tutores legales o apoderados de los adolescentes.
4. **Ubigeo:** Proporciona datos geográficos relevantes para el manejo de ubicaciones dentro del sistema.
5. **Transferencia de Adolescentes:** Controla la transferencia de adolescentes entre diferentes instancias del sistema.
6. **Asignaciones:** Administra las asignaciones específicas de actividades o tareas a los adolescentes.
7. **Manejo de Archivos:** Encargado del almacenamiento y gestión de archivos relevantes para el sistema.
8. **Unidades Operativas:** Gestiona las unidades operativas dentro de la correccional.

## Tecnologías Utilizadas

- **Base de Datos:** PostgreSQL se utiliza como el sistema de gestión de bases de datos para almacenar la información del sistema.
- **Backend:** Se emplea Spring Boot para el desarrollo del backend de los microservicios, facilitando la creación de API RESTful y su integración.
- **Generación de Reportes:** JasperReports se utiliza para la generación de informes y reportes dentro del sistema.
- **Frontend:** Angular es el framework utilizado para desarrollar la interfaz de usuario, permitiendo una experiencia interactiva y amigable.
- **Node Modules:** Utilizados para la gestión de paquetes en el entorno de desarrollo de Node.js.

## Configuración y Ejecución

Para configurar y ejecutar el proyecto, sigue los siguientes pasos:

1. **Clonar Repositorio:** Clona este repositorio desde GitLab.
2. **Configuración de la Base de Datos:** Configura la conexión a PostgreSQL y asegúrate de tener la estructura adecuada de la base de datos ejecutando los scripts de creación proporcionados.
3. **Configuración de Microservicios:** Configura las variables de entorno y la conexión entre los microservicios si es necesario.
4. **Instalación de Dependencias:** En los microservicios que lo requieran, ejecuta `npm install` para instalar los paquetes necesarios en el entorno de Node.js.
5. **Ejecución:** Inicia cada microservicio por separado según sus respectivas instrucciones de inicio.

## Contribución

Si deseas contribuir al desarrollo de este proyecto, por favor sigue las pautas de contribución y envía tus pull requests.

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
