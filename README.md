# Motor de Inferencia de Lógica Difusa en Python

Implementación de un Sistema Experto basado en Lógica Difusa (motor Mamdani) utilizando Python. El sistema procesa múltiples variables de entrada mediante reglas lógicas para calcular una puntuación de salida unificada.

## Stack Tecnológico

* **Lenguaje:** Python 3.x
* **Librerías principales:** scikit-fuzzy, numpy, scipy, networkx
* **Entorno:** Jupyter Notebook

## Características Técnicas

* **Funciones de pertenencia:** Modelado de conjuntos difusos utilizando funciones triangulares (`trimf`) y trapezoidales (`trapmf`).
* **Base de conocimientos:** Motor de inferencia basado en 12 reglas escalonadas con operadores lógicos `AND`.
* **Manejo de excepciones:** Implementación de bloques `try...except` para capturar "puntos ciegos" (entradas no contempladas en las reglas) y evitar interrupciones de ejecución (`KeyError`).
* **Defuzzificación comparativa:** Ejecución simultánea de los métodos de Centroide (por defecto), Bisector y MOM (Mean of Maximum) para análisis de resultados.

## Arquitectura del Modelo

* **Antecedentes (Entradas):** 5 variables normalizadas en escalas de [0-10] y [0-100].
* **Consecuente (Salida):** 1 variable de evaluación en escala [0-10].
* **Validación:** Interfaz por línea de comandos (CLI) con filtrado y restricción de valores de entrada.

## Instalación y Ejecución

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/TU_USUARIO/NOMBRE_DEL_REPO.git](https://github.com/TU_USUARIO/NOMBRE_DEL_REPO.git)

 
