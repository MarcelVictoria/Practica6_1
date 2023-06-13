# PRACTICA 6
## EJERCICIO 1: Lectura/escritura memoria SD
Consiste en conectar la ESP32 con un lector de tarjetas MicroSD. En esta tarjeta hemos añadido un archivo. Para realizar el montaje hemos seguido la siguiente asignación de pines:
```cpp
#define CS_PIN 15
// MOSI 23
// MISO 19
// CLK 18
```
En el puerto MISO hemos conectado una resistencia en serie, y el VCC a 5V.

En el setup debe inicializarse el lector y después abrir el archivo que hay dentro de SD y leerlo con la siguiente instrucción: ```myFile.read()```

Nos ha funcionado correctamente y el montaje es el siguiente:

[Imagen montaje](https://drive.google.com/file/d/1PRdirnKIYyA6SJ73pjihNdsQnBCB6y9t/view?usp=sharing)


## EJERCICIO 2
El código de este ejercicio y su correspondiente informe lo podemos encontrar en el repositorio "Practica6_ex2".