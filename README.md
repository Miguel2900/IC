# PROYECTO FINAL INTELIGENCIA COMPUTACIONAL

## Clasificador de entradas numéricas e imágenes

El proyecto consiste en crear 6 redes neuronales con diferentes características para así compararlas entre ellas y ver cuál es la que mejor predice. 
Las primeras 3 redes serán usadas para la primera página web, que consiste en que el usuario pueda dibujar en un recuadro un número del 0 al 9 y que el algoritmo haga una predicción sobre qué número es el que se dibujó. La primera red es una red neuronal normal, la segunda es una red neuronal convolucional y la tercera es una red convolucional con aumento de datos y dropout. Cada una de estas redes arroja una predicción, de esta manera el usuario puede darse cuenta cuál de las tres acertó con su predicción. 
Las otras tres redes son ocupadas en la segunda página web, la cual consiste en que el usuario pueda cargar una imagen desde su dispositivo y que el algoritmo predice a cuál de las 10 categorías pertenece. Estas 10 categorías son: avión, auto, pájaro, gato, venado, perro, rana, caballo, barco y camión. Esta página también contará con las 3 variantes de la red neuronal y también se podrán visualizar los 3 resultados. 

## ¿Cómo usarlo?

Puede descargarse los contenidos del repositorio para hacer uso del proyecto, ya viene incluido con los modelos entrenados necesarios, y con todo para que se pueda correr.

Lo único necesario será tener instalado [Python](https://www.python.org/downloads/) para poder correrlo dentro de un servidor HTTP. Al tenerlo instalado, deberá abrir una consola dentro de la carpeta donde se encuentra el proyecto, y escribir el siguiente comando.
```
python -m http.server 8000
```
Posterior a ello, solo es necesario escribir dentro de un navegador la siguiente dirección y haer uso de la herramienta.
```
localhost:8000
```


