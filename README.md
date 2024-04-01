# 🏫 Sistema Escolar Integral API RESTful

Bienvenido al repositorio del Sistema Escolar Integral, una API RESTful diseñada para facilitar la gestión completa de procesos educativos en instituciones escolares. Más Información acerca de los procesos educativos en la siguiente sección. </br> Este sistema está diseñado para ser robusto, escalable y fácil de integrar, ofreciendo una solución integral para administradores, profesores, estudiantes y padres de familia.
## Características ✅
- **Gestión de Estudiantes:** Registra, actualiza y elimina información de estudiantes. Seguimiento detallado de datos académicos y personales.
- **Gestión de Docentes:** Administra perfiles de docentes, asigna cursos y horarios, y realiza un seguimiento de su desempeño.
- **Cursos y Materias:** Crea y gestiona cursos, asignaturas y horarios de clases.
- **Organización de Horarios:** Planifica horarios de clases de manera eficiente, asignando materias a los diferentes períodos del día y días de la semana.
- **Calificaciones:** Registra y calcula calificaciones de estudiantes de manera automática o manual. Ofrece acceso rápido a los registros académicos.
- **Comunicación con Padres de Familia:** Facilita la comunicación entre la escuela y los padres, enviando notificaciones sobre el desempeño académico, eventos escolares y otros aspectos relevantes.
- **Pago de Inscripción:** Permite a los padres realizar el pago de la inscripción de manera segura y conveniente a través de la plataforma.
- **Seguridad y Privacidad:** Garantiza la seguridad de los datos y la privacidad de la información sensible mediante medidas de autenticación y autorización.
Con estas funcionalidades, el Sistema Escolar Integral proporciona una solución completa y centralizada para la administración y operación de instituciones educativas, mejorando la eficiencia y la comunicación entre todos los involucrados en el proceso educativo.

# 📋 Documentación de la Base de Datos
<!--
## Modelo de Datos

A continuación se presenta el modelo de datos utilizado en la base de datos del Sistema Escolar Integral:

- **Estudiantes:** 
  - `id` (int): Identificador único del estudiante.
  - `nombre` (string): Nombre completo del estudiante.
  - `grado` (int): Grado al que pertenece el estudiante.
  - `sección` (string): Sección a la que pertenece el estudiante.

- **Docentes:** 
  - `id` (int): Identificador único del docente.
  - `nombre` (string): Nombre completo del docente.
  - `especialidad` (string): Especialidad o materia que enseña el docente.
  
- **Cursos:** 
  - `id` (int): Identificador único del curso.
  - `nombre` (string): Nombre del curso.
  
- **Materias:** 
  - `id` (int): Identificador único de la materia.
  - `nombre` (string): Nombre de la materia.
  - `curso_id` (int): Identificador del curso al que pertenece la materia.
  
- **Horarios:** 
  - `id` (int): Identificador único del horario.
  - `hora_inicio` (time): Hora de inicio de la clase.
  - `hora_fin` (time): Hora de finalización de la clase.
  - `dia_semana` (string): Día de la semana en que se imparte la clase.
  - `materia_id` (int): Identificador de la materia a la que corresponde el horario.
  
- **Asistencias:** 
  - `id` (int): Identificador único de la asistencia.
  - `fecha` (date): Fecha de la clase.
  - `estado` (string): Estado de la asistencia (presente, ausente, tardanza, etc.).
  - `estudiante_id` (int): Identificador del estudiante.
  - `horario_id` (int): Identificador del horario correspondiente a la clase.-->
## Diagrama Entidad-Relación (ER) 📊
![school_management](https://github.com/GabyyHshss/School-Management-API/assets/135078706/ae097a32-083c-42f8-add8-292efd8374ed)
