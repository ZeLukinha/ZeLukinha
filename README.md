ESTRUCTURA DE DATOS Y ALGORITMOS - TAREA 2

Esta tarea consiste en el desarrollo de un sistema llamado “DISCORDIA GAME BOT: Guess the Picture”, donde el jugador debe adivinar una palabra a partir de una imagen que se va revelando parcialmente en base a sus intentos.

Se utilizan estructuras de datos para representar los píxeles de una imagen encriptada (formato .dis), los cuales deben ser ordenados por su ID para reconstruir correctamente la imagen original (.ppm). Además, se emplean distintos algoritmos de ordenamiento para observar sus diferencias de complejidad al desencriptar parcialmente las imágenes.

El objetivo del programa es leer un archivo de imagen encriptado, ordenar los datos utilizando distintos algoritmos, generar versiones parciales de la imagen revelada, y medir empíricamente el rendimiento de los algoritmos.

• Condiciones de compilación y ejecución:
  El programa debe ser compilado en el entorno Aragorn, usando gcc versión 4.8.5 y el estándar C99.

• Instrucción de compilación:
  make

• Instrucción de ejecución:
  ./programa <numero_archivo.dis>

  Ejemplo:
  ./programa 3.dis

• Archivos generados:
  imagen_25.ppm
  imagen_50.ppm
  imagen_75.ppm
  imagen_100.ppm
  analisis.txt

• Información del creador:
  Lucas Ignacio Andrade González - Paralelo 201
  RUT: 202230517-7


<!---
ZeLukinha/ZeLukinha is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
