# Asistente Integral de Organización Adaptativa mediante Fast Prompting

## Introducción

El presente proyecto desarrolla una Proof of Concept (POC) que implementa técnicas de Fast Prompting para la creación de un asistente integral de organización personal.  

El problema abordado consiste en la dificultad de organizar de manera equilibrada el trabajo, los estudios y los hábitos personales, especialmente en contextos dinámicos donde existen cambios imprevistos durante la semana.

Muchas herramientas tradicionales de planificación son rígidas y no permiten adaptaciones eficientes, lo que genera frustración y desorganización. Este proyecto propone una solución basada en Inteligencia Artificial que permita planificar y replanificar de manera optimizada y flexible.

---

## Objetivos

- Implementar una POC utilizando técnicas de Fast Prompting.
- Diseñar prompts estructurados y eficientes.
- Minimizar el número de consultas a la API.
- Permitir replanificación dinámica ante cambios.
- Evaluar la mejora respecto a un enfoque tradicional fragmentado.

---

## Metodología

El proyecto se desarrolló siguiendo los siguientes pasos:

1. Definición clara del problema.
2. Fraccionamiento en módulos:
   - Planificación inicial
   - Replanificación adaptativa
3. Diseño de prompt estructurado único.
4. Optimización para reducir consumo de tokens.
5. Implementación en Jupyter Notebook.
6. Evaluación de eficiencia y costos.

Se utilizó un enfoque modular pero con integración en una única llamada a la API para optimizar recursos.

---

## Herramientas y Tecnologías

- Python
- Jupyter Notebook
- OpenAI API
- Modelo: gpt-4o-mini

### Técnicas de Prompting utilizadas

- Role Prompting
- Structured Prompting
- Instruction Compression
- Context Reuse
- Temperature Control
- Modular Prompt Design

Estas técnicas permiten reducir ambigüedad, mejorar coherencia y disminuir costos.

---

## Implementación

La implementación se basa en:

1. Prompt estructurado único para planificación completa.
2. Función optimizada para replanificación.
3. Control de temperatura bajo para mayor consistencia.
4. Minimización de consultas innecesarias.

El sistema permite:

- Generar planificación semanal equilibrada.
- Adaptar la planificación ante cambios.
- Mantener prioridades sin sobrecargar la agenda.

---

## Análisis de Optimización

En lugar de realizar múltiples consultas separadas para trabajo, estudio y hábitos, se diseñó un único prompt estructurado que integra todas las variables.

Esto permitió:

- Reducir número de llamadas a la API.
- Mejorar coherencia del plan.
- Disminuir consumo de tokens.
- Aumentar rentabilidad del sistema.

---

## Conclusión

La POC demuestra que la aplicación de técnicas de Fast Prompting permite crear un sistema de organización adaptativa eficiente, coherente y económicamente viable, mejorando significativamente la propuesta inicial del proyecto.
