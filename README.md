IMAGENES SLIDESHOW

Sistema Multimedia: Reproductor y Generador de Slideshows

Este proyecto es una aplicación de escritorio desarrollada en Python que integra herramientas de procesamiento de video, manipulación de imágenes y una interfaz gráfica de usuario (GUI).

Descripción del proyecto
El proyecto consiste en una aplicación de escritorio desarrollada en Python utilizando la biblioteca Tkinter para la interfaz gráfica, junto con OpenCV y MoviePy para el procesamiento de video y multimedia. La herramienta se divide en dos módulos principales de flujo interactivo: un reproductor de video funcional con controles de reproducción, pausa y selección de archivos, y un sistema automatizado para generar y previsualizar slideshows (presentaciones) a partir de múltiples imágenes y duraciones personalizadas, compilando el resultado en un archivo de video en formato MP4.

Justificación de la necesidad
En muchos entornos académicos y profesionales, existe la necesidad de contar con utilidades multimedia ligeras, personalizadas y de código abierto que permitan manipular archivos de video e imágenes sin depender de software privativo pesado o interfaces complejas. Este sistema resuelve la necesidad de integrar en una sola plataforma la capacidad de reproducir contenidos multimedia locales de manera controlada y la automatización de la creación de videos tipo presentación (slideshow), facilitando la gestión de archivos visuales, la definición de tiempos de duración por fotograma y la previsualización directa de los resultados para fines didácticos o de desarrollo técnico

Selección de Metodología de DesarrolloEnfoque Seleccionado: 
Metodología Ágil (Kanban)Justificación:Duración y Flexibilidad: Dado el marco de tiempo de la práctica, un enfoque ágil nos permite trabajar con entregas incrementales y priorizar los módulos del sistema multimedia (reproductor de video y generador de slideshows) de forma independiente.  Estructura Modular: Al estar el proyecto dividido en componentes claros (interfaz gráfica en Tkinter, procesamiento con OpenCV y manipulación multimedia con MoviePy), Kanban facilita asignar cada funcionalidad a un integrante del equipo mediante Issues en GitHub Projects.  Adaptabilidad: Permite ajustar los requisitos de visualización de fotogramas y la integración de las librerías sin romper la planificación general de las fases del proceso. 

Historias de Usuario (User Stories)
HU-01: Reproducción de Video Local

Como usuario de la aplicación,

Quiero seleccionar y cargar un archivo de video local mediante un explorador de archivos,

Para reproducirlo de forma controlada en la interfaz gráfica.

HU-02: Control de Reproducción Multimedia

Como usuario del sistema,

Quiero utilizar botones de reproducción, pausa y reanudación,

Para gestionar la visualización de los fotogramas del video en tiempo real.

HU-03: Generación Automática de Slideshows

Como usuario,

Quiero seleccionar múltiples imágenes y definir sus tiempos de duración personalizados,

Para compilarlas automáticamente en un archivo de video en formato MP4.

HU-04: Previsualización de Resultados

Como usuario de la herramienta,

Quiero previsualizar el slideshow generado directamente mediante una ventana emergente,

Para verificar el resultado antes de finalizar el proceso.


Arquitectura del Proyecto
multimedia-project/ ├── main.py # Código fuente principal (Reproductor de video y generador de slideshows) ├── README.md # Documentación técnica del repositorio ├── Images/ # Carpeta de recursos gráficos (front.jpg, second.png) └── slide_show.mp4 # Archivo de video generado automáticamente por el sistema

Instrucciones de Ejecución
Clonar el repositorio:
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/ddf2a52d-ed0f-49cb-8068-3935cd8e0711" />

