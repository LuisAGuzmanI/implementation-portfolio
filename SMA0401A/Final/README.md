# SMA0401A - Final

Trabajo realizado para el entregable: Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

## Trabajo realizado

En este trabajo se emplea el [Student Marks Dataset](https://www.kaggle.com/datasets/yasserh/student-marks-dataset) disponible en Kaggle y publicado por el Ing. M Yasser H, que incluye registros del tiempo dedicado semanalmente al estudio por alumnos, la cantidad de cursos que cursan en el momento, y las calificaciones que los mismos optienen. Con esto se busca generar un modelo predictivo que pronostique las calificaciones de los alumnos basandose en el tiempo dedicado al estudio y su carga de cursos actual.

En el script se implementan 2 modelos de regresión (lineal y polinomial) utilizando la técnica de descenso de gradiente. Estas regresiones toman como variable de entrada el número de horas que dedicó al estudio el alumno en una semana, ya que fue la variable que se observó tenía una correlación más fuerte con la calificación final de los estudiantes. 

## Contenidos 

* Student_Marks_Regression.ipynb: Archivo de Jupyter Notebook que contiene la implementación de 2 técnicas de ML sin uso de frameworks para su evaluación.
* Student_Marks.csv: Archivo .csv que contiene el dataset necesario para correr el archivo previamente mencionado.

## Modificiaciones respecto a la última entrega

### Exploración estadistica de datos  

### Separación de datos de entrenamiento y pruebas

### Evaluación con metricas de desempeño