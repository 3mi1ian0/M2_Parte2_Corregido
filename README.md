# M2_Parte2_Corregido
## EMILIANO MENDOZA NIETO - A01706083
Módulo 2 Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución. (Portafolio Implementación)

Entregable: Uso de framework o biblioteca de aprendizaje máquina para la implementación de una solución.

1.- Programa uno de los algoritmos vistos en el módulo haciendo uso de una biblioteca o framework de aprendizaje máquina. Lo que se busca es que demuestres tu conocimiento sobre el framework y como configurar el algoritmo. 

2.- Prueba tu implementación con un set de datos y realiza algunas predicciones. Las predicciones las puedes correr en consola.

3.- Tu implementación debe de poder correr por separado solamente con un compilador, no debe de depender de un IDE

# Descripcion del repositorio:
En este repositorio se encuentran los siguiente documentos:
 - Iris.csv es el dataset a utilizar
 - Gradient_Descent_100.py
 - Gradient_Descent_X.py
 - Reporte_Corregido_A01706083.pdf

Y se encuentran tres archivos .py, en si los tres codigos tienen lo mismo, solamente hay una linea que cambia:

model = LogisticRegression(solver='---', penalty='---', max_iter=100)

La cual es donde se crea una instancia de un modelo de regresión logística utilizando la clase "LogisticRegression" de "sklearn.linear_model".

El primero es con "liblinear", y "L1", el segundo con "newton-cg" y sin penalizacion, finalmente utilizo "sag" (Stochastic Average Gradient descent) y con "L2" de penalizacion, em el documento pdf hablo mas a detalle sobre esto, de forma general y resumida es para realizar una comparacion de los diferentes modelos.


# Evaluación

Subcompetencia Indicador

## SMA0401A

## Usa un marco de trabajo o framework para implementar una técnica o algoritmo de aprendizaje máquina como: regresiones, árboles, clusters, etc...

 

Se evalúa como correcto si y solo si, el framework está aplicado correctamente y el programa puede hacer predicciones. El profesor del módulo puede determinar el nivel de accuracy o de r2 esperado del dataset en turno tomando en cuenta su complejidad y la capacidad del algoritmo implementado.
