# Proyecto de Visualización de Datos 

En este docuemnto se presenta una descripción de las tablas de la base de datos de la Plataforma de Matemáticas de la Universidad del Caribe. En la primera parte se describe la jerarquía de la información contenida en los cursos, en la segunda el registro de las actividades de los usuarios.

## Jerarquía de la información

### Cursos

Lista de los cursos para los cuales se ha generado material didáctico

### Unidades

Cada unidad está asociada a algún curso.

### Temas

Una unidad está compuesta temas

### Secciones

Una sección es la unidad de aprendizaje más básica, con las cuales se compone un tema.

### Actividades

En cada sección se lista una serie de actividades que los estudiantes deben desarrollar, las cuales pueden ser de los siguientes tipos: 

1. Notas.
2. Videos.
3. Ejercicios.

## Actividades de usuarios


### ResumenActTema

Lista las actividades (ejercicios) que un usuarios ha resuelto correctamente en cada tema. Presenta también una columna con el procentaje de avance del usuario en el tema.

### HistorialEvaluación

Para cada tema, el usuario debe presentar una evaluación. La tabla lista los ejercicios resueltos correctamente.

### 
