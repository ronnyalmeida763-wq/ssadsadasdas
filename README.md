Este proyecto implementa un sistema para almacenar, registrar y consultar información relacionada con contenido audiovisual, incluyendo películas, series, documentales, actores, temporadas e investigadores, permitiendo organizar datos dentro de archivos locales y gestionarlos mediante programación orientada a objetos

Objetivo del Proyecto

Crear un sistema funcional que permita ingresar información, guardarla, leerla y mostrarla desde archivos, aplicando principios de código limpio, POO, SOLID y separación por clases para mejorar la mantenibilidad del software

Descripción General

El programa está compuesto por clases independientes que representan los elementos del contenido audiovisual, una clase principal administra la creación de archivos, ingreso de información, lectura y visualización del contenido, el usuario puede almacenar datos y recuperarlos posteriormente sin perder información, logrando una base de datos elemental en formato de archivos

Funcionalidades

Creación y almacenamiento de información en archivos .txt

Lectura y visualización del contenido almacenado

Estructura modular de clases para cada tipo de dato

Control de entrada y salida de datos en consola

Base para expansión a menús, filtros o interfaz gráfica

Estructura del Proyecto

Carpeta src
CreadorDeArchivo.java maneja el guardado de información
LectorContenido.java permite leer y mostrar los datos almacenados
GestorAudiovisual.java administra la lógica general del sistema
PruebaContenido.java ejecuta el sistema y prueba sus funciones
