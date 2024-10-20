# Estudio de la Deserción en el TecMM Chapala
En este repositorio se desarrolla el trabajo intermedio de la asignatura Desarrollo de Proyecto 1, del 3er semestre de la Maestría en Ciencia de Datos.

# Descripción General de la Tesis
El Tecnológico Mario Molina Unidad Educativa Chapala, es una Universidad Pública miembro de los Institutos Descentralizados del Tecnológico Nacional de México. Su fundación fue en el año 2000. Actualmente Chapala cuenta con alrededor de 1000 estudiantes, distribuidos en las 5 Ingenierías y 1 Licenciatura que se imparten: Ingeniería en Sistemas Computacionales, Ingeniería Industrial, Ingeniería en Gestión Empresarial, Ingeniería Mecatrónica, Ingeniería en Animación Digital y Efectos Visuales y Licenciatura en Gastronomía.
Una de las problamáticas más importantes de las Instituciones Educativas de nivel superior es la deserción, que representa un porcentaje mayor del que las Instituciones quisieran. El presente trabajo trata de determinar los factores principales que generan la deserción escolar en la Unidad Académica Chapala del TecMM, mediante uso de modelos de aprendizaje automático aplicados la información de los alumnos en su trayecto académico en la Institución.

# Breve resumen de Resultados del análisis EDA
El archivo analizado cuenta con 116,00 registros, distribudos en 25 columnas, una vez analizada la información de las columnas, se establecen como de interés las relacionadas con el programa educativo, el código del alumno, la clave de la asignatura, la calificación obtenida en la asignatura y el año en que se aprobó. Ninguna de estas columnas presenta datos nulos. La información se genera a partir de 3690 alumnos que han cursado los 692 cursos ofertados por la institución.
En el anáisis se  pudo determinar los porcentajes de aprobación de asignaturas por carreras, y su comportamiento a través de los años.

# Estructura de repositorio

El objetivo de este repositorio es mostrar la organización de la información del proyecto, tomando en cuenta las buenas prácticas mencionadas en el paper ["Good Enough Practices in Scientific Computing"](https://arxiv.org/abs/1609.00037) de Greg Wilson, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, Tracy K. Teal.

La estructura del repositorio es la siguiente:

    ├── LICENSE           <- Licencia MIT.
    |  
    ├── README.md         <- README principal con la descripción general del proyecto. 
    |  
    ├── CONTRIBUTING.md   <- Pasos para contrinuir en el proyecto.  
    |  
    ├── CITATION.md       <- Forma de citar este trabajo.  
    |  
    ├── data              <- Datos utilizados en presente análisis.  
    |  
    ├── doc               <- Archivos de texto con la Descripción General del Proyecto.  
    |  
    ├── results           <- Resultados del Análisis Exploratorio de los datos. 
    |  
    └── src               <- Codigo utilizado para el Análisis Exploratorio.  
