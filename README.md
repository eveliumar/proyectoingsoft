# PROYECTO FINAL DE INGENIERÍA DE SOFTWARE

Este programa realiza el ajuste de poligonales topográficas cerradas y abiertas

## LECTURA DE DATOS
La lectura de datos se realiza desde un archivo plano con un formato predefinido.

> El tipo de poligonal se ingresa por pantalla

> La ruta del archivo con las mediciones de la poligonal se digita en pantalla

## VALIDACIONES
El programa valida si el archivo con las mediciones cumple con el formato que el programa lee

## AJUSTES

### Poligonal cerrada
Si la poligonal es cerrada los posibles métodos de ajueste seran:

- Método de Brujula
- Método de transito

> Se solitara por pantalla al usuario las coodenadas de los puntos de la linea de referencia

### Poligonal abierta
Si la poligonal es abierta el metodo de ajuste sera **crandall**

> Se solitara por pantalla al usuario las coodenadas de los puntos de la linea de referencia de inicio y fin

## SALIDA
Los resultados de los calculos y los ajustes se guardan en un archivo plano en la misma ruta del archivo de entrada

## GRAFICAS
La poligonal se dibuja a través de uno de los siguientes métodos:

- Un archivo **Geojson** o **json**.
- En consola a través de una librería gráfica
- En un archivo CAD a traves de una librería externa

[Universidad Distrital](https://www.udistrital.edu.co)
**Evelio Madera**
