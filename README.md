Mi Primera Red Neuronal

Autor: Álvaro

Este proyecto es una implementación simple de una red neuronal artificial utilizando TensorFlow para predecir la conversión de temperaturas de Celsius a Fahrenheit.

Descripción

La red neuronal tiene:

Capa de entrada oculta 1: 3 neuronas

Capa oculta 2: 3 neuronas

Capa de salida: 1 neurona

Se entrena con un conjunto de datos de temperaturas conocidas y puede predecir Fahrenheit a partir de cualquier valor Celsius ingresado.

Cómo usarlo

Asegúrate de tener Python y TensorFlow instalados.

Ejecuta el script mi_primera_red_neuronal.py.

Observa el gráfico de pérdida por épocas y realiza predicciones con tu modelo entrenado.

Ejemplo de predicción
resultado = modelo.predict(np.array([100.0]))
print("El resultado es " + str(resultado) +  " fahrenheit!")

Dependencias

TensorFlow

NumPy

Matplotlib
