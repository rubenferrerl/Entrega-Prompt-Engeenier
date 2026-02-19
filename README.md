# Asistente Integral de Organización Adaptativa mediante Fast Prompting

## Introducción

El presente proyecto desarrolla una **Proof of Concept (POC)** que implementa técnicas de **Fast Prompting** para la creación de un asistente integral de organización personal utilizando modelos de Inteligencia Artificial de Google (Gemini API).

El problema abordado consiste en la dificultad de organizar de manera equilibrada el trabajo, los estudios y los hábitos personales, especialmente en contextos dinámicos donde existen cambios imprevistos durante la semana.

Muchas herramientas tradicionales de planificación son rígidas y no permiten adaptaciones eficientes, lo que genera frustración y desorganización. Este proyecto propone una solución basada en modelos generativos de lenguaje que permiten planificar y replanificar de manera optimizada, flexible y estructurada.

---

## Objetivos

- Implementar una POC utilizando técnicas de Fast Prompting.
- Diseñar prompts estructurados y eficientes.
- Minimizar el número de consultas a la API.
- Permitir replanificación dinámica ante cambios.
- Evaluar la mejora respecto a un enfoque tradicional fragmentado.
- Analizar eficiencia en consumo de tokens y rendimiento del modelo.

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
6. Evaluación de eficiencia y consistencia de resultados.

Se utilizó un enfoque modular con integración en una única llamada a la API para optimizar recursos y coherencia del resultado.

---

## Herramientas y Tecnologías

- Python  
- Jupyter Notebook  
- Google Generative AI (Gemini API)  
- Modelo utilizado: `gemini-1.5-flash`  
- Alternativa configurable: `gemini-1.5-pro`  

---

## Técnicas de Prompting Utilizadas

- Role Prompting  
- Structured Prompting  
- Instruction Compression  
- Context Reuse  
- Temperature Control  
- Modular Prompt Design  
- Output Formatting Control (Markdown / JSON estructurado)  

Estas técnicas permiten reducir ambigüedad, mejorar coherencia, controlar variabilidad del modelo y disminuir costos operativos.

---

## Implementación

La implementación se basa en:

1. Prompt estructurado único para planificación completa.
2. Función optimizada para replanificación adaptativa.
3. Control de temperatura bajo para mayor consistencia.
4. Minimización de consultas innecesarias a la API.
5. Configuración del modelo Gemini mediante Google Generative AI SDK.

El sistema permite:

- Generar planificación semanal equilibrada.
- Adaptar la planificación ante cambios imprevistos.
- Mantener prioridades sin sobrecargar la agenda.
- Devolver resultados estructurados (tabla Markdown o JSON).

---

## Análisis de Optimización

En lugar de realizar múltiples consultas separadas para trabajo, estudio y hábitos, se diseñó un único prompt estructurado que integra todas las variables en una sola generación.

Esto permitió:

- Reducir número de llamadas a la API.
- Mejorar coherencia global del plan.
- Disminuir consumo de tokens.
- Optimizar tiempos de respuesta.
- Aumentar la eficiencia del sistema.

El uso de Gemini permitió además evaluar desempeño en términos de velocidad y costo frente a modelos alternativos.

---

## Conclusión

La POC demuestra que la aplicación de técnicas de Fast Prompting, combinadas con el uso del modelo Gemini de Google, permite crear un sistema de organización adaptativa eficiente, coherente y económicamente viable.

El proyecto evidencia cómo una correcta ingeniería de prompts puede maximizar el rendimiento de modelos generativos sin necesidad de arquitecturas complejas, validando el enfoque propuesto como una solución práctica y escalable.
