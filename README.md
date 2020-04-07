# reconocedor-emociones
Este repositorio utiliza una red neuronal convolucional de 4 capas para clasificar las emociones de un conjunto de imágenes de entrenamiento. 

## Dataset
Este ejemplo utiliza el dataset de emociones CK+ (tipo FACS) el cual debe descargar y ponerlo en la raíz. Desgargar el [CK.zip](https://drive.google.com/file/d/1LToyqX560nZwlLOLRWSe-lWYtF7Wzz2N/view?usp=sharing)

Debe extraer el zip de tal forma de que quede la siguiente estructura:

- CK
  - anger
  - contempt
  - fear
  - happy
  - sadness
  - surprise

cada folder contiene imagenes de 48x48 pixeles en blanco y negro.

## predecir-emociones.ipynb
Este archivo es un cuaderno de Jupyter (Jupyter Notebook) para ejecutar este cuaderno, por favor instale Anaconda y Python 3.6.

### reconocedor-facial.h5
Este archivo contiene los pesos de la red neuronal ya entrenada, asi que puede utilizar este archivo para cargar la red y realizar predicciones sin tener que volver a entrenar la red.



