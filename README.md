## Tarea 3: Sistema de calificación para un Colegio 

Actividad desarrollada con en lenguaje Javascript puro implementando: funciones, ciclos for, variables, condicionales, comparaciones, arrays y objetos. 

### Contenido

* index.html : archivo formato html para abrir en navegador (de preferencia Chrome) e inspeccionar la consola. 
* solución 
  * actividad_3.js : archivo formato javascript que contiene las declaraciones de las funciones y console.log() correspondientes. 
  * data.js : archivo formato javascript con el array que guarda toda la información del colegio.

### Funciones

1. function totalEstudiantes() : sin parametros. Se utiliza para contar la cantidad de estudiantes que hay en el colegio.

2. function totalEstudiantesPorNivel(datosColegio, nivel) : Primer parametro debe ser datosColegio, segundo parametro puede ser 'primaria' o 'secundaria'. Se
utiliza para contar la cantidad de estudiantes ya sea en primaria o secundaria.

3. function totalEstudiantesPorGenero(datosColegio, genero) : Primer parametro debe ser datosColegio, segundo parametro puede ser 'male' o 'female'. Se utiliza para saber
la cantidad total de niñas o niños en el colegio. 

4. function totalPrimariaPorGenero(datosColegio, nivel, genero) : Primer parametro debe ser datosColegio, segundo parametro puede ser 'primaria' o 'secundaria', tercer
parametro puede ser 'male' o 'female'. Se utiliza para saber la cantidad total de niñas o niños a nivel primaria o secundaria.

5. function notas(datosColegio1, nivel, grado, curso) : Primer parametro debe ser datosColegio1, segundo parametro puede ser 'primaria' o 'secundaria', tercer
parametro puede ser 'primero'-'once' según el nivel ingresado, cuarto parametro debe ser 'A' o 'B' según el curso deseado. Retorna array con el total de notas según parametro. 
Pueden haber 4 casos:
* Si desea solo colegio, defina primer parametro.
* Si desea primaria o bachillerato, defina primer y segundo parametro.
* Si desea por grado, defina primer, segundo y tercer parametro.
* Si desea por curso, defina primer, segundo, tercer y cuarto parametro. 

6. function mediaNotas(datosColegio1, nivel, grado, curso) : Primer parametro debe ser datosColegio1, segundo parametro puede ser 'primaria' o 'secundaria', tercer
parametro puede ser 'primero'-'once' según el nivel ingresado, cuarto parametro debe ser 'A' o 'B' según el curso deseado. Retorna la media de notas según parametro deseado. Pueden haber 4 casos:
* Si desea solo colegio, defina primer parametro.
* Si desea primaria o bachillerato, defina primer y segundo parametro.
* Si desea por grado, defina primer, segundo y tercer parametro.
* Si desea por curso, defina primer, segundo, tercer y cuarto parametro. 

7. function modaNotas(datosColegio1, nivel, grado, curso) : Primer parametro debe ser datosColegio1, segundo parametro puede ser 'primaria' o 'secundaria', tercer
parametro puede ser 'primero'-'once' según el nivel ingresado, cuarto parametro debe ser 'A' o 'B' según el curso deseado. Retorna la moda de notas según parametro deseado.
Pueden haber 4 casos:
* Si desea solo colegio, defina primer parametro.
* Si desea primaria o bachillerato, defina primer y segundo parametro.
* Si desea por grado, defina primer, segundo y tercer parametro.
* Si desea por curso, defina primer, segundo, tercer y cuarto parametro. 


8. function medianaNotas(datosColegio1, nivel, grado, curso) : Primer parametro debe ser datosColegio1, segundo parametro puede ser 'primaria' o 'secundaria', tercer
parametro puede ser 'primero'-'once' según el nivel ingresado, cuarto parametro debe ser 'A' o 'B' según el curso deseado. Retorna la mediana de las notas según parametro deseado. Pueden haber 4 casos:
* Si desea solo colegio, defina primer parametro.
* Si desea primaria o bachillerato, defina primer y segundo parametro.
* Si desea por grado, defina primer, segundo y tercer parametro.
* Si desea por curso, defina primer, segundo, tercer y cuarto parametro. 

9. function mejorPromAsignatura(asignaturaDeseada) : El parametro puede ser uno de los siguientes: 'historia','matematicas','filosofia','religion','artes','educacion_fisica',
'biologia','quimica','fisica'. Se utiliza para seleccionar el estudiante con mejor promedio según asignatura. 

10. function mejorPromParametro(datosColegio1, nivel, grado, curso) : Primer parametro debe ser datosColegio1, segundo parametro puede ser 'primaria' o 'secundaria', tercer
parametro puede ser 'primero'-'once' según el nivel ingresado, cuarto parametro debe ser 'A' o 'B' según el curso deseado. Retorna un template con el estudiante que tuvo
mejor promedio según parametro. Pueden haber 4 casos:
* Si desea solo colegio, defina primer parametro.
* Si desea primaria o bachillerato, defina primer y segundo parametro.
* Si desea por grado, defina primer, segundo y tercer parametro.
* Si desea por curso, defina primer, segundo, tercer y cuarto parametro. 

11. function mostrarEstudiante(datosColegio1, grado) : Primer parametro debe ser datosColegio1, segundo parametro puede ser un grado de 'primero'-'once', ambos parametros deben
ser definidos. Retorna objeto con los datos del estudiante escogido al azar del grado seleccionado. 


### Situación problema 

Las funciones definidas dan respuesta al planteamiento del siguiente problema:

Un colegio necesita una herramienta tecnológica que le permita automatizar el proceso de calificación de los profesores con respecto a sus estudiantes. El colegio tiene dos cursos por grado, es decir, 1A y 1B, este colegio tiene desde el grado 1 hasta el 11 y los grados de primaria constan del grado 1 al grado 5 con sus respectivos cursos mientras los grados de bachillerato constan del grado 6 al grado 11.

El colegio espera apoyarse en la herramienta tecnológica para conocer:

-	La cantidad total de estudiantes que hay en el colegio.
-	La cantidad total de estudiantes que hay en primaria.
-	La cantidad total de estudiantes que hay en bachillerato.
-	La cantidad de niños que hay en el colegio.
-	La cantidad de niñas que hay en el colegio.
-	La cantidad de niños que hay en primaria.
-	La cantidad de niñas que hay en primaria.
-	La cantidad de niños que hay en bachillerato.
-	La cantidad de niñas que hay en bachillerato.
-	La media de las notas en el colegio.
-	La media de las notas en el bachillerato.
-	La media de las notas en el primaria.
-	La media de las notas de un grado seleccionado por parametro.
-	La media de las notas de un curso seleccionado por parametro.
-	La moda de las notas en el colegio.
-	La moda de las notas en el bachillerato.
-	La moda de las notas en el primaria.
-	La moda de las notas de un grado seleccionado por parametro.
-	La moda de las notas de un curso seleccionado por parametro.
-	La mediana de las notas en el colegio.
-	La mediana de las notas en el bachillerato.
-	La mediana de las notas en el primaria.
-	La mediana de las notas de un grado seleccionado por parametro.
-	La mediana de las notas de un curso seleccionado por parametro.
-	Seleccionar el estudiante con mejor nota en promedio en cada materia.
-	Seleccionar el estudiante con mejor nota en promedio en el curso.
-	Seleccionar el estudiante con mejor nota en promedio en el grado.
-	Seleccionar el estudiante con mejor nota en promedio en primaria.
-	Seleccionar el estudiante con mejor nota en promedio en bachillerato.
-	Seleccionar el estudiante con mejor nota en promedio en el colegio.
-	Buscar un estudiante que pertenezca a un grado seleccionado por parametro.

Considere usar buenas practicas y codigo limpio. Asi mismo, documente su solucion.
La solucion a cada requerimiento que pide el colegio se debe realizar por medio de funciones, es decir, por cada uno de los 31 requerimientos funcionales, deberia contener en su solucion al menos 31 funciones. Recuerde que un grado consta de sus dos cursos, y un curso no puede existir sin grado. Por ultimo, documente cada uno de sus funciones en el README de su solucion, al documentar las funciones, tenga en cuenta, que debe ser clara la manera como debo invocar la funcion, si la funcion contiene parametro o parametos; el tipo de dato de cada parametro que considero necesario en la creacion del mismo, o cualquier otro dato que considere necesario para que cualquier persona pueda ejecutar su solucion y la responsabilidad de cada funcion.
