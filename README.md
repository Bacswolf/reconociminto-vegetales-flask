# Nombre del Proyecto

## Reconocimiento de vegetales

## Descripción

Reconocimiento de vegetales mediante la implementación de una red neuronal con uso de un modelo pre-entrenado (VGG16) y una base de datos de 15 clases de vegetales. 


## Dataset

El dataset utilizado es el [Vegetable Image Dataset](https://www.kaggle.com/datasets/misrakahmed/vegetable-image-dataset) de la plataforma Kaggle. Este dataset contiene 15 clases de vegetales con 1000 imágenes por clase. El dataset puede ser cambiado por otro dataset que necesite solo debera colocar las imagenes en la carpeta `dataset/train`  

## Características

- modelo pre-entrenado (VGG16)
- base de datos de 15 clases de vegetales
- uso de la librería tensorflow y keras
- despliegue de la red neuronal en una aplicación web con Flask
- 15000 imágenes de entrenamiento
- aumento de datos (image data generator)

## Instalación

- Clonar el repositorio
- crear un entorno virtual
- instalar las dependencias con el comando `pip install -r requirements.txt`
- ejutar el cuaderno de jupyter `gener_modelo.ipynb` para entrenar el modelo y guardarlo
- ejecutar el archivo `app.py` para desplegar la aplicación web
- abrir localhost:5000 en el navegador

## Uso

- La aplicación web permite subir una imagen de un vegetal y se muestra el resultado de la predicción de la red neuronal.



