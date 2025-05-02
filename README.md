## Integrantes
- Sofía García
- Joaquín Campos
- Gerardo Pineda
- Julio García Salas

# Simulación de Sistema y Tareas

Este proyecto contiene dos programas binarios diseñados para simular el funcionamiento de un **sistema** gestor de procesos y las **tareas** que éste programa:

- **casio_system**: ejecutable principal que lee un archivo de configuración del sistema, programa las tareas y las coordina mediante señales e interrupciones de temporizador.  
- **casio_task**: ejecutable que implementa el comportamiento de cada tarea individual, respondiendo a las señales enviadas por `casio_system` y simulando trabajo.

