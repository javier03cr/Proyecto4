# Proyecto4

Estudiante: Javier Madrigal Oviedo

Carnet: B74368

Grupo: 1

Resultados de proyecto
Parte 1. Modulación y demodulación

Se tiene que para este proyecto, se debía crear una función la cual fuera capaz de modular y despues de desmodular la imagen con nombre arenal.jpg, se tiene que para se utilizó gran parte del código elaborado por el profesor Fabian Abarca, se procedió a realizar los respectivos cambios para implementar el método de modulación 16-QAM, uno de los principales cambios realizados, fue el de utilizar un SNR de 20, se podía utilizar un valor mayor para obtener mayor calidad de imagen, pero consideré más que suficiente el 20, a menor SNR, la calidad de la imagen era cada vez menor, con estos parámetros se obtuvo la siguiente imagen tanto transmitida como enviada como recibida con una cantidad de errores de 2556 lo cual es suficientemente bajo para el caso en particular:

![image](https://user-images.githubusercontent.com/85901651/125524034-7583e9ac-65e0-4b59-a9c4-e88527dea9ee.png)

Para las señales asociadas con la transmición y recepción de la imagen se tiene que se obtuvo lo siguiente: 

![image](https://user-images.githubusercontent.com/85901651/125528475-e3e32395-3c82-442c-9c76-33f5e9f70b99.png)

Parte 2. Estacionariedad y ergodicidad

Por otra parte, se tiene las siguientes gráficas: 

![image](https://user-images.githubusercontent.com/85901651/125532398-a82a684b-7c0b-4987-a05d-fe2daaf86875.png)

Dado que la media del proceso se mantiene estable con el paso del tiempo, se puede asegurar que el proceso es estacionario y es una de las condiciones para que el proceso sea estacionario, por otra parte, se tiene que la ergocidad no se cumple, ya que el promedio de realizaciones debe ser similar al valor teórico y esta condición se cumple en este caso, por lo cual se puede decir que el proceso es estacionario, pero no ergódico.

Parte 3. Densidad espectral de potencia
Se tiene por otra parte, la densidad espectral de potencia, se tiene que el pico se encuentra a una frecuencia de 5000 Hz, es totalmente lo esperado, ya que fue a esta la frecuencia a la cual se eligieron los parámetros, en este caso la frecuencia portadora, con lo cual se cumple con lo esperado: 

![image](https://user-images.githubusercontent.com/85901651/125530399-e52b20ba-bffb-4453-bc1d-eb415fa14a35.png)

