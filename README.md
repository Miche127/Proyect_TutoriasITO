# Proyect_TutoriasITO

# Descripción
El programa de tutorías en Java es una aplicación robusta diseñada para gestionar de manera eficiente la interacción entre administradores, tutores y alumnos en un entorno educativo. Utiliza una base de datos compuesta por cinco tablas: usuarios, alumnos, tutores, cursos y materias. Al iniciar el programa, los usuarios se autentican a través de un sistema de login que detecta su nivel de acceso, el cual puede ser administrador o tutor. Dependiendo del nivel de usuario, se despliega una versión específica de la interfaz. Los administradores tienen acceso a funciones avanzadas como la consulta y gestión de alumnos, tutores y materias. Pueden agregar, eliminar y actualizar los registros de alumnos, así como asignarles cursos. Asimismo, tienen la capacidad de gestionar tutores y asociar materias a cursos. Además, los administradores pueden crear nuevos usuarios con nivel de acceso de administrador.

En la versión para tutores, el programa presenta los cursos que han sido asignados a cada tutor. Los tutores pueden abrir archivos PDF relacionados con los cursos y consultar información detallada de los alumnos inscritos en sus cursos. La interfaz es intuitiva y permite una navegación fácil para realizar todas estas acciones. Este enfoque asegura que los administradores puedan mantener una supervisión y gestión detallada de todos los componentes educativos, mientras que los tutores pueden centrarse en sus cursos y los alumnos que enseñan. Con esta organización, el programa facilita una gestión educativa eficiente y estructurada, adaptándose a las necesidades específicas de administradores y tutores.

# Compatibilidad:
Version de Java
JDK 18
mySQL Workbench 8.0 CE
Librerias utilizadas
mysql-connector-j-9.0.0
jcalendar-1.4
TimeChooser
pdfbox-app-3.0.2
javax-inject
javax.activation-1.1.0v201105071233
javax-ejb
javax.faces-api-2.0
mail

# Como utilizar

Para utilizar el programa de tutorías en Java, siga las instrucciones detalladas a continuación. Al iniciar la aplicación, se le pedirá que ingrese su nombre de usuario y contraseña en la pantalla de inicio de sesión. Dependiendo de su nivel de acceso, será dirigido a la versión correspondiente del programa: administrador o tutor.

Video de funcionalidad : https://youtu.be/vJdvU05lM50

# Administradores:
Inicio de sesión:

Ingrese sus credenciales de administrador.
Si las credenciales son correctas, será dirigido a la interfaz principal de administrador.
Navegación en el menú lateral:

Alumnos:
Seleccione esta opción para consultar la lista de alumnos.
Desde aquí, puede agregar nuevos alumnos, eliminar registros existentes y actualizar información de los alumnos.
También puede asignar cursos a los alumnos.
Tutores:
Seleccione esta opción para gestionar los tutores.
Puede agregar, eliminar y actualizar la información de los tutores.
Materias:
Seleccione esta opción para consultar y gestionar las materias.
Puede asignar materias a cursos, agregar nuevas materias o eliminar las existentes.
Creación de nuevos usuarios:

Desde cualquiera de las opciones mencionadas, puede acceder a la funcionalidad para crear nuevos usuarios de nivel administrador.

# Tutores:
Inicio de sesión:

Ingrese sus credenciales de tutor.
Si las credenciales son correctas, será dirigido a la interfaz principal de tutor.
Navegación en el menú lateral:

Mis Clases:
Seleccione esta opción para ver los cursos que se le han asignado.
Recursos:
Desde aquí, puede abrir archivos PDF relacionados con sus cursos para acceder a materiales y recursos adicionales.
Mis Alumnos:
Seleccione esta opción para consultar la información de los alumnos inscritos en sus cursos.
Puede buscar alumnos específicos y ver detalles relevantes sobre su inscripción y progreso.
Estas instrucciones le permitirán aprovechar al máximo las funcionalidades del programa de tutorías, ya sea gestionando los diferentes componentes como administrador o accediendo a los recursos y datos necesarios para la enseñanza como tutor.
