# ProyectAl

![bannerfinal](https://user-images.githubusercontent.com/73614233/156931688-00cb3cb6-185d-43cb-a583-589f7a3aae59.png)

#### Autores: Daniel Eduardo Ortiz Celis 2171469, Camilo Eduardo González Guerrero 2180065

### Objetivo:
Determinación del estadío de la enfermedad de Alzheimer a través de imagenología MRI: 
Herramienta para la detección de estadío de la enfermedad de Alzheimer a través de imagenología MRI. Se desarrolla con el fin de servir de guía o para correlación por parte del profesional de Neurología. Está enfocado para ser un problema Supervisado con fines de clasificación Multiclases(Estadíos de la Enfermedad)

### Dataset: 
El link del dataset que usamos es el siguiente: https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images

Hay que aclarar que el dataset que usamos fue creado a apartir de las imagenes de la carpeta train, cargamos las imagenes y las transformamos en escala de grises, volvimos un DataFrame las imagenes, le añadimos una columna extra llamada labels que representa alguna de la etapa del Alzheimer y por ultimo permutamos el DataFrame.
### Metodos:
* Gaussian Naive Bayes
* Decision Tree classifier
* Random Forest classifier
* Support vector machine (SVM) con 3 kernesl (RBF, poly y linear)
* Redes neuronales
* Redes convolucionales

### Librerias:
* Numpy, Pandas, Sklearn, Tensorflow, Keras, Matplotlib, Seaborn y Scipy

