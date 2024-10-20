## DESCRIPCIÓN DE LOS DATOS.
Los datos obtenidos contienen poco más de 116,000 registros:
 
![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-13%20143733.png)

Con el siguiente encabezado:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20200803.png)

Distribuidos en 25 columnas

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-13%20143915.png)

De las cuáles solo resultan de interés las siguientes:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20190755.png)

Nombre del programa educativo, Número de control del alumno, Clave de la Asignatura, Calificación obtenida, Aprueba y Año en que la cursó.
Ninguna de las cuales tiene datos nulos:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20191332.png)

Los Programas Académicos que ha tenido la Institución son los siguientes:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20192251.png)

Con la columna del número de control, podemos determinar el total de alumnos que fueron parte de la Institución en el periodo de estudio:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20192846.png)

A partir de las claves de asignatura, se encuentra que el número de asignaturas distintas cursadas en la Institución es de:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20193246.png)

La columna de calificaciones incluye la calificación obtenida por asignatura cursada por alumno. Podemos ver el comportamiento de la variable en el siguiente diagrama de caja:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20194413.png)

Se puede observar que la mediana de la calificación de todas las asignaturas es de alrededor de 85 puntos. El 50% de los datos se concentran entre 80 y 95 , el resto de los valores de la caja oscilan entre 70 y 100, lo cual se debe verse influenciado por el hecho que la calificación mínima aprobatoria en este sistema es de 70. Las calificaciones reprobatorias se consideran atípicas, se encuentran muy lejos del comportamiento del conjunto de datos.
Mediante una tabulación cruzada, se utiliza la columna “Aprueba” para obtener la siguiente información:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20204237.png)

En la que se muestran las asignaturas aprobadas y reprobadas por programa académico, misma información del siguiente gráfico, pero ahora normalizado.

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Screenshot%202024-05-14%20211234.png)

Gráficamente la misma información se muestra de la siguiente manera:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Porc%20Aprob%20y%20Repr.png)

Se puede apreciar que las carreras con mayores índices de reprobación son Animación Digital y Efectos Visuales, y la Licenciatura en Gastronomía, ambas con índices de reprobación de dos dígitos.
La última columna contiene el año en que el alumno cursó la asignatura, que al contrastarla con la columna “Aprueba” mediante una tabla de tabulación cruzada, se obtiene el siguiente gráfico:

![](https://github.com/OctavioMendoza/Estudio-de-la-Desercion-en-el-TecMM-Chapala/blob/main/results/assets/Aprb%20y%20Reprob%20hist.png)

El paso de los años muestra un incremento en los índices de reprobación, lo que puede generarse por distintas razones, el crecimiento en la población de estudiantes puede generar que sean más los que presenten bajos niveles académicos, o sean más los que deserten, que los esquemas de evaluación se hayan hecho más estrictos…
