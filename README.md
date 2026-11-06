# Red Generativa Antagónica (GAN) aplicada a MNIST

## Descripción

En este proyecto se desarrolla una Red Generativa Antagónica (GAN) empleando Python, TensorFlow y Keras. Su finalidad es entrenar un modelo capaz de producir imágenes artificiales de dígitos escritos a mano, tomando como referencia el conjunto de datos MNIST.

## Objetivo

Explorar y poner en práctica los principios del aprendizaje adversarial mediante la implementación de dos redes neuronales que trabajan conjuntamente: un generador y un discriminador.

## Tecnologías y herramientas

- Python
- Google Colab
- TensorFlow / Keras
- NumPy
- Matplotlib
- Base de datos MNIST

## Implementación

Se desarrolló una arquitectura GAN integrada por dos componentes principales:

- **Generador:** encargado de producir imágenes de dígitos utilizando vectores de ruido aleatorio como entrada.
- **Discriminador:** encargado de evaluar las imágenes y determinar si corresponden a muestras originales del dataset o a imágenes creadas artificialmente.

El entrenamiento se realizó a lo largo de 50 épocas, permitiendo que ambos modelos mejoraran progresivamente su desempeño.

## Resultados obtenidos

Como resultado de la práctica, se consiguieron generar imágenes artificiales con características similares a los números manuscritos del conjunto MNIST. También se obtuvieron visualizaciones del proceso de entrenamiento, gráficas de pérdida y los modelos neuronales entrenados.
