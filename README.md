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




Arquitectura del Proyecto
multimedia-project/ ├── main.py # Código fuente principal (Reproductor de video y generador de slideshows) ├── README.md # Documentación técnica del repositorio ├── Images/ # Carpeta de recursos gráficos (front.jpg, second.png) └── slide_show.mp4 # Archivo de video generado automáticamente por el sistema

Instrucciones de Ejecución
Clonar el repositorio:
<img width="821" height="191" alt="image" src="https://github.com/user-attachments/assets/35d4013a-5b5f-4f7d-94ce-3d29920d6ddd" />

<img width="565" height="272" alt="image" src="https://github.com/user-attachments/assets/fbd8c344-8de8-4466-b990-a389a243cb25" />

<img width="1006" height="1600" alt="image" src="https://github.com/user-attachments/assets/5fd109d1-c1cb-48c6-b164-7d4f88e8c0bc" />

Retrospectiva del Proyecto - Práctica 1
¿Qué funcionó bien?La división del código en dos módulos visuales claros (videoGUI y el generador de slideshows) facilitó la separación de responsabilidades y la integración de las librerías gráficas y multimedia.El uso de GitHub Projects nos ayudó a distribuir las tareas de manera transparente y organizada entre los integrantes del equipo.  La validación interactiva mediante ventanas emergentes (messagebox) permitió mejorar la retroalimentación visual hacia el usuario durante la carga de archivos.

¿Qué no funcionó o generó retrasos?La sincronización de los tiempos de los fotogramas y la gestión de rutas relativas para las imágenes iniciales generaron pequeñas inconsistencias iniciales.La resolución de conflictos menores de Git al momento de sincronizar los archivos generados automáticamente de video (slide_show.mp4).

¿Qué mejoras implementaremos para el siguiente proyecto?Configurar adecuadamente el archivo .gitignore desde la primera sesión para evitar subir archivos caché innecesarios o salidas de video temporales.Establecer convenciones de mensajes de commit más estandarizadas vinculadas directamente al número de Issue de GitHub Projects para mejorar el control de versiones colaborativo.




