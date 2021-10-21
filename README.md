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
