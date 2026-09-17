# Simulación del Sistema de Atención Hospitalaria

Trabajo práctico de la materia **Simulación**, desarrollado en Python. El proyecto implementa una simulación de un sistema de atención hospitalaria con múltiples médicos, considerando llegadas de pacientes, tiempos de atención, formación de colas y abandono.

## Descripción

El modelo utiliza distribuciones de probabilidad obtenidas a partir del análisis estadístico de trabajos anteriores para simular:

* Llegadas de pacientes.
* Atención por múltiples médicos.
* Esperas en cola.
* Tiempo de permanencia en el sistema.
* Tiempo ocioso de los médicos.
* Abandono de pacientes.

Se pueden simular tres períodos:

* **Lunes**
* **Semana**
* **Fin de semana**

Cada período utiliza una distribución diferente para modelar los tiempos entre llegadas.

## Tecnologías

* Python 3
* NumPy
* Pandas
* SciPy
* Matplotlib
* Fitter

## Ejecución

Instalar las dependencias:

```bash
pip install numpy pandas scipy matplotlib fitter
```

Ejecutar:

```bash
python tp5_simulacion.py
```

El programa solicita la cantidad de médicos y el período que se desea simular.

## Resultados

La simulación calcula:

* Promedio de espera en cola.
* Promedio de permanencia en el sistema.
* Porcentaje de tiempo ocioso de los médicos.
* Porcentaje de pacientes arrepentidos.

## Contexto académico

Trabajo práctico de **Simulación** — Ingeniería en Sistemas de Información, **UTN**.

## Autor

**Elías Puddini**
