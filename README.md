# Repaso arrays de objetos

## Ejercicios básicos

1. Mostrar en consola el primer elemento del array estudiantes. 

2. Mostrar en consola la propiedad `edad` del primer elemento del array estudiantes. 

3. Mostrar en consola la propiedad `nombre` del primer elemento del array estudiantes (Nota: es un objeto adentro de otro). 

4. Modificar la edad del primer elemento por `18`. Mostrarlo en consola. 

5. Mostrar en consola la propiedad `materias` del primer elemento. 

6. Recorrer el array `materias` del primer elemento y mostrar en consola solo el `nombre` de cada materia, no la nota. 

7. Usando el metodo `filter`, mostrar en consola solo las `materias` desaprobadas (5 o menos) del primer elemento del array. 

8. Usando el metodo `map`, mostrar en consola los hechizos favoritos de la propiedad `amigues` del primer elemento. 

9. Usando el metodo `some`, devolver `true` si alguno de los `amigues` tiene como `hechizoFavorito` el mismo que el primer elemento. Devolver `false` en caso contrario. 

10. Mostrar en consola el siguiente mensaje para el primer elemento del array: `El alumno Ellis Reeves tiene 18 años y su hechizo preferido es "Expecto Patronum",`. No "hardcodear" los datos, sacarlos del objeto. 

## Ejercicios avanzados

Nos piden que hagamos las siguientes funciones. Todas ellas utilizan algun metodo de array: forEach, map, filter, reduce, some, every. 

(Nota: Deben ser **funciones**, es decir, estar declaradas como tales, recibir parámetros y retornar el dato pedido. No debe ser código suelto.)

1. `estudiantesPorHechizo`, que tome por parámetro el nombre de un hechizo y un array de estudiantes y devuelva un array con todos les estudiantes que tengan ese hechizo como hechizoPreferido

2. `estudiantesConMasAmiguesQue`, que tome por parametro un numero y un array de estudiantes y devuelva un array con todos les estudiantes que tengan un número de amigues mayor o igual a el número pasado por parámetro

3. `estudiantesConFamiliares`, que tome por parámetro un array con nombres de familiares (p.ej, ["Sapo", "Lechuza"]) y un array de estudiantes y devuelva un array con les estudiantes que tengan cuyo familiar sea alguno de los incluidos en el parámetro

4. `obtenerPromedioDeEstudiante`, que tome por parámetro une estudiante (que se saca del array estudiantes) y devuelva el promedio total de todas las materias

5. `estudiantesConPromedioMayorA`, que tome por parámetro un número y un array de estudiantes y devuelva un array con les estudiantes que tengan un promedio total mayor a dicho número (usar la función anterior)

6. `mejoresEstudiantesPorCasa`, que tome por parámetro el nombre de una casa y un array de estudiantes y devuelva les estudiantes de dicha casa cuyo promedio total es mayor a 6

7. `casaConMejoresEstudiantes`, que tome por parámetro un array de estudiantes y devuelva el nombre de la casa que tiene más cantidad de estudiantes con promedio total mayor a 6 (usar la función anterior)

8. `estudiantesPorMateriaAprobada`, que tome por parámetro el nombre de una materia y un array de estudiantes y devuelva una array con les estudiantes que tienen en dicha materia un promedio superior a 6

9. `obtenerInfoResumida`, que tome por parámetro un array de estudiantes y devuelva un array con objetos, habiendo un objeto por estudiante, donde cada objeto tiene las siguientes propiedades: `nombre`, `casa`, `promedio`, `amigues` (cantidad)

10. `cantidadDeEstudiantesPorCasa`, que tome por parámetro un array de estudiantes y devuelva un objeto con los nombres de las casas como propiedades y la cantidad de estudiantes por casa (no debe contar amigues)

11. `cantidadDeEstudiantesPorMateriaAprobada`, que tome por parámetro un array de estudiantes y devuelva un objeto con los nombres de las materias como propiedades y la cantidad de estudiantes que aprobaron dicha materia (promedio superior a 6)

12. `promedioPorMateria`, que tome por parámetro un array de estudiantes y devuelva un objeto con los nombres de las materias como propiedades y el promedio total de dicha materia entre todes les estudiantes (suma de todos los promedios divido la cantidad de estudiantes)

13. `familiarPreferido`, que tome por parámetro un array de estudiantes y devuelva el familiar que más estudiantes tienen
