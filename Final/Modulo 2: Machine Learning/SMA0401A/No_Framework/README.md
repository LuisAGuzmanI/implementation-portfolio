# SMA0401A - Final

Trabajo realizado para el entregable: Momento de Retroalimentación: Módulo 2 Implementación de una técnica de aprendizaje máquina sin el uso de un framework.

## Trabajo realizado

En este trabajo se emplea el [Student Marks Dataset](https://www.kaggle.com/datasets/yasserh/student-marks-dataset) disponible en Kaggle y publicado por el Ing. M Yasser H, que incluye registros del tiempo dedicado semanalmente al estudio por alumnos, la cantidad de cursos que cursan en el momento, y las calificaciones que los mismos optienen. Con esto se busca generar un modelo predictivo que pronostique las calificaciones de los alumnos basandose en el tiempo dedicado al estudio y su carga de cursos actual.

En el script se implementan 2 modelos de regresión (lineal y polinomial) utilizando la técnica de descenso de gradiente. Estas regresiones toman como variable de entrada el número de horas que dedicó al estudio el alumno en una semana, ya que fue la variable que se observó tenía una correlación más fuerte con la calificación final de los estudiantes. 

## Contenidos 

* Student_Marks_Regression.ipynb: Archivo de Jupyter Notebook que contiene la implementación de 2 técnicas de ML sin uso de frameworks para la evaluación de la subcompetencia SMA0401A.
* Student_Marks.csv: Archivo .csv que contiene el dataset necesario para correr el archivo previamente mencionado.

## Modificiaciones respecto a la última entrega
* Se agregó una sección de exploración de datos haciendo uso de la función ```df.describe()``` de la librería *pandas*. 
* Se realizó una separación de los datos en 2 subconjuntos de entranamiento y prueba utilizando la función ```train_test_split(...)``` de la librería *sklearn*, con la finalidad de evaluar el desempeño de los modelos sobre datos que no ha visto anteriormente.
* Se agrega a la graficación del modelo las estadisticas de *MSE* para ambos subconjuntos de datos, agregando un indicador número que señala la diferencia en el rendimiento del modelo en diferentes conjuntos de datos.