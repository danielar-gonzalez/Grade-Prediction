# Grade-Prediction

Este proyecto busca predecir la calificación final (G3) de los estudiantes utilizando un modelo de regresión lineal. Se toman en cuenta variables como edad, sexo, faltas, horas de estudio y acceso a internet. Además, se incluyen términos de interacción entre algunas variables para capturar relaciones complejas. 

La base de datos cuenta con la siguiente información: 
- “Escuela”. Indica si el estudiante en cuestión asistía a la escuela Gabriel Pereira (GP) o a la escuela Mousinho da Silveira (MS).
- “Sexo”. F para mujeres y H para hombres.
- “Edad”. Edad del estudiante, en años.
- “HorasDeEstudio”. Cantidad de horas de estudio: 1 indica menos de dos horas, 2 indica de dos a cinco horas, 3 indica de cinco a diez horas, 4 indica más de diez horas.
- “Reprobadas”. Indica la cantidad de materias reprobadas previamente.
- “Internet”. Si el estudiante tenía acceso (yes) o no (no) a internet en su casa.
- “Faltas”. Cantidad de veces que faltó a clases.
- “G1”. Calificación del primer periodo, escala del 0 al 20.
- “G2”. Calificación del segundo periodo, escala del 0 al 20.
- “G3”. Calificación final, escala del 0 al 20.

Documentos incluídos en el proyecto:
- [Reporte en formato ipynb](./Problemas.ipynb)
- [Reporte en formato html](./Problemas.html)
- [Base de datos](./Calificaciones.csv)
