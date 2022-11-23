
IMPLEMENTACIÓN DE REGRESIÓN LINEAL AL PRECIO DEL ORO

La presente práctica de laboratorio se realiza con el fin de implementar el modelo de regresión lineal a un conjunto de datos seleccionado, 
el cual consiste en el precio del oro registrado desde el añpo 2011 hasta el año 2022, en el que se registran el voumen de ventas, el valor 
de cierre y apertura, el valor máximo y mínimo que ha tenido cada dia en el tiempo registrado. 

Esta implementación se hace en lenguaje Python y en lenguaje C++ haciendo uso de la libreria SkitLearn y Eigen respectivamente. Se implementa
la regresión lineal en dos casos, el primero es teniendo como variable objetivo el valor mínimo del valor del oro y la segunda es con el valor
alto del oro, se aplica la métrica de rendimiento R2 score y MSE, dando como resultado que apesar que el rendimiento en ambos lenguajes sea
bueno, la diferencia entre el valor real y el valor predicho es muy alta. Para lo cual se intenta ajustar mejor el modelo a los datos
implementando regresión de Ridge, ya que la regresión lineal implementada presenta un subajuste, es decir que el modelo es demasiado simple
para explicar el comportamiento de los datos. 

Teniendo en cuenta lo anterior este repositoorio contiene los programas realizados en C++ para la implementación de la regresión lineal.
