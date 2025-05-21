# Taller-4-Mapa-Citaciones
Sistema de Administración de Mapas de Citaciones Académicas
Este proyecto en C++ implementa un sistema para gestionar y analizar mapas de citaciones entre artículos académicos. El sistema permite modelar la relación de citación dirigida entre artículos, y provee funciones clave para estudiar la estructura y dinámica de dichas citaciones.

Descripción
En la investigación académica, los artículos suelen citar otros trabajos para apoyar sus resultados y construir el estado del arte. Este sistema representa esos vínculos como un grafo dirigido donde cada nodo es un artículo y cada arista representa una citación desde un artículo origen a uno destino.

El programa permite realizar las siguientes operaciones:

Encontrar el artículo más citado: Identificar el artículo que recibe la mayor cantidad de citaciones directas.

Contar grupos tras remover un artículo: Al eliminar un artículo, se cuentan los grupos de artículos interconectados en el grafo resultante.

Calcular el índice de referenciación: Métrica que relaciona la cantidad de citaciones recibidas con la mitad de las citaciones realizadas por un artículo.

Contar citaciones indirectas: Determina cuántos artículos son citados indirectamente (a través de citaciones de artículos citados) desde un artículo dado.

Implementación
El proyecto define un tipo IdArticulo para identificar artículos y una clase MapaCitaciones que administra las relaciones de citación mediante estructuras de datos eficientes. Se implementan algoritmos basados en búsquedas en amplitud (BFS) para analizar componentes del grafo.

Cómo usar
Compila el código con un compilador compatible con C++11 o superior:


g++ -std=c++11 main.cpp -o mapa_citaciones
Ejecuta el programa:



./mapa_citaciones
Modifica el archivo main.cpp para agregar artículos y relaciones, o adapta el código para leer datos desde archivos externos.

Autor
Diego Fernando Zabala

