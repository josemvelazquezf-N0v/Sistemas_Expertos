# Investigación: Arquitectura de Sistemas Expertos (SE)

Este repositorio documenta la investigación técnica sobre el funcionamiento de los **Sistemas Expertos**, enfocándose en la transformación del conocimiento humano en lógica computacional.

---

## 1. Adquisición del Conocimiento

Representa la fase de entrada de inteligencia al sistema. Es el puente entre el mundo real y el software.

* **¿Qué?**: Es la extracción de la pericia técnica desde fuentes externas.
* **¿Para qué?**: Para "digitalizar" el saber especializado y convertirlo en un formato procesable por la máquina.
* **¿Cómo?**: Mediante el **Módulo de Adquisición de Conocimiento**. Aquí, el ingeniero de conocimiento (Cognimático) interactúa con expertos humanos, sensores o bases de datos para filtrar y codificar la información.

---

## 2. Representación del Conocimiento

Es la memoria estructurada donde reside la información organizada.

* **¿Qué?**: Son las estructuras de datos que contienen la lógica del dominio.
* **¿Para qué?**: Para que el sistema tenga un repositorio organizado donde consultar reglas y hechos actuales.
* **¿Cómo?**: Se organiza en dos secciones principales:
    * **Base de Conocimiento**: Almacena las reglas y leyes generales (Conocimiento a largo plazo).
    * **Base de Hechos**: Almacena la información específica del caso que se está resolviendo en el momento (Conocimiento a corto plazo).

---

## 3. Tratamiento del Conocimiento

Es el procesador lógico o "cerebro" que toma las decisiones.

* **¿Qué?**: Son los algoritmos de razonamiento lógico.
* **¿Para qué?**: Para procesar los hechos contra las reglas y así deducir nuevas conclusiones o diagnósticos.
* **¿Cómo?**:
    * **Motor de Inferencia**: Ejecuta el razonamiento lógico aplicando las reglas de la base de conocimiento.
    * **Módulo de Explicaciones**: Justifica al usuario el camino lógico seguido para llegar a una respuesta, aumentando la transparencia y confianza en el sistema.

---

## 4. Utilización del Conocimiento

Es la fase de interacción final con el usuario externo.

* **¿Qué?**: Es la Interfaz de Usuario.
* **¿Para qué?**: Para permitir que un usuario no experto pueda realizar consultas y recibir asesoramiento especializado de alto nivel.
* **¿Cómo?**: Mediante una interfaz de diálogo (GUI) que captura las variables del problema y devuelve la solución generada por el motor de inferencia.

---

## Resumen del Flujo Lógico

1.  **Entrada**: El conocimiento técnico se digitaliza y se guarda en la **Base de Conocimiento**.
2.  **Consulta**: El usuario ingresa un problema; estos datos se guardan en la **Base de Hechos**.
3.  **Procesamiento**: El **Motor de Inferencia** combina reglas y hechos para encontrar una solución.
4.  **Justificación**: El **Módulo de Explicaciones** detalla los pasos seguidos.
5.  **Salida**: El usuario recibe la respuesta final a través de la **Interfaz**.
mm