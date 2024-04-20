# Analizador y compilador básico en Python

Este proyecto consiste en un analizador y compilador básico implementado en Python. Puede leer un archivo de código fuente en C, quitar los comentarios y realizar algunas verificaciones semánticas simples, como la declaración de variables y la construcción de expresiones.

## Funcionalidades principales

### 1. `quita_comentarios(archivoEnt, archivoSal)`

Esta función toma un archivo de entrada que contiene código fuente en C y elimina todos los comentarios del mismo, escribiendo el código resultante en un archivo de salida.

### 2. `separa_tokens(archivo)`

Se encarga de separar el código en tokens, identificando palabras clave, operadores, identificadores y otros elementos del lenguaje.

### 3. `verifica_declara_var(tokens)`

Realiza la verificación semántica de las variables declaradas en el código, asegurando que no haya variables repetidas y que se declaren correctamente.

### 4. `posfija_a_intermedio(posfija)`

Convierte una expresión en notación posfija a código intermedio, facilitando su posterior procesamiento.

### 5. `evalua_posfija(posfija)`

Evalúa una expresión en notación posfija y devuelve su resultado.

## Uso

Para utilizar este programa, sigue estos pasos:

1. Asegúrate de tener instalado Python en tu sistema.
2. Descarga o clona este repositorio en tu máquina.
3. Ejecuta el archivo `main.py` y proporciona como entrada el nombre del archivo de código fuente en C que deseas compilar.

Por ejemplo:

```
python main.py archivo.c
```
