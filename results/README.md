## DESCRIPCIÓN DE LOS DATOS.
Los datos obtenidos contienen poco más de 116,000 registros:
 
![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-13%20143733.png)

Con el siguiente encabezado:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-13%20200803.png)

Distribuidos en 25 columnas

De las cuáles solo resultan de interés las siguientes:

Nombre del programa educativo, Número de control del alumno, Clave de la Asignatura, Calificación obtenida, Aprueba y Año en que la cursó.
Ninguna de las cuales tiene datos nulos:


Los Programas Académicos que ha tenido la Institución son los siguientes:

Con la columna del número de control, podemos determinar el total de alumnos que fueron parte de la Institución en el periodo de estudio:

A partir de las claves de asignatura, se encuentra que el número de asignaturas distintas cursadas en la Institución es de:

La columna de calificaciones incluye la calificación obtenida por asignatura cursada por alumno. Podemos ver el comportamiento de la variable en el siguiente diagrama de caja:

Se puede observar que la mediana de la calificación de todas las asignaturas es de alrededor de 85 puntos. El 50% de los datos se concentran entre 80 y 95 , el resto de los valores de la caja oscilan entre 70 y 100, lo cual se debe verse influenciado por el hecho que la calificación mínima aprobatoria en este sistema es de 70. Las calificaciones reprobatorias se consideran atípicas, se encuentran muy lejos del comportamiento del conjunto de datos.
Mediante una tabulación cruzada, se utiliza la columna “Aprueba” para obtener la siguiente información:

En la que se muestran las asignaturas aprobadas y reprobadas por programa académico, misma información del siguiente gráfico, pero ahora normalizado.

Gráficamente la misma información se muestra de la siguiente manera:

Se puede apreciar que las carreras con mayores índices de reprobación son Animación Digital y Efectos Visuales, y la Licenciatura en Gastronomía, ambas con índices de reprobación de dos dígitos.
La última columna contiene el año en que el alumno cursó la asignatura, que al contrastarla con la columna “Aprueba” mediante una tabla de tabulación cruzada, se obtiene el siguiente gráfico:

El paso de los años muestra un incremento en los índices de reprobación, lo que puede generarse por distintas razones, el crecimiento en la población de estudiantes puede generar que sean más los que presenten bajos niveles académicos, o sean más los que deserten, que los esquemas de evaluación se hayan hecho más estrictos…
