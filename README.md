# Asistente Integral de Organización Adaptativa mediante Fast Prompting

## Resumen

Este proyecto desarrolla una Proof of Concept (POC) que implementa técnicas de Fast Prompting para la creación de un asistente de organización personal utilizando modelos de Inteligencia Artificial generativa.

El sistema permite generar una planificación semanal equilibrada considerando horarios fijos, tareas flexibles, hábitos personales y niveles de energía. A partir de esta planificación, se genera además una representación visual del calendario mediante un prompt de generación de imagen.

La solución utiliza dos tipos de modelos de IA:  
- **Modelo texto-texto** para generar el plan semanal estructurado.  
- **Modelo texto-imagen** para crear una visualización del calendario.

La implementación se desarrolla en un **Jupyter Notebook**, utilizando la API de **Google Gemini**, demostrando cómo las técnicas de ingeniería de prompts pueden optimizar la generación de resultados consistentes, eficientes y adaptables.

---


## Presentación del problema

La organización del tiempo es uno de los principales desafíos en contextos donde deben combinarse múltiples responsabilidades como estudio, trabajo y hábitos personales.

Muchas herramientas tradicionales de planificación requieren que el usuario estructure manualmente su agenda, lo que puede resultar complejo cuando existen cambios imprevistos o múltiples variables a considerar, como niveles de energía o prioridades.

Esto genera problemas como:

- Sobrecarga de tareas en ciertos días.
- Falta de equilibrio entre trabajo y descanso.
- Dificultad para mantener hábitos saludables.
- Baja adaptabilidad ante cambios inesperados.

En este contexto, los modelos de inteligencia artificial generativa ofrecen la posibilidad de automatizar la planificación, generando estructuras equilibradas y adaptativas a partir de información básica proporcionada por el usuario.

---

## Desarrollo de la propuesta de solución

La solución propuesta consiste en un asistente de planificación personal basado en modelos generativos de IA que permite:

1. Generar automáticamente una **planificación semanal equilibrada**.
2. Adaptar dicha planificación ante cambios imprevistos.
3. Visualizar el resultado mediante una **representación gráfica tipo calendario**.

El sistema utiliza dos tipos de modelos:

### Modelo texto-texto

Se utiliza el modelo **Gemini 1.5 Flash** para generar la planificación semanal estructurada a partir de un prompt que incluye:

- horarios fijos
- tareas flexibles
- hábitos personales
- niveles de energía

El modelo devuelve un **plan semanal estructurado en formato tabla**.

### Modelo texto-imagen

A partir de la planificación generada, se crea un **prompt de generación de imagen** que permite representar el calendario semanal mediante herramientas externas de generación de imágenes.

Esto permite transformar la información textual en una **visualización clara del plan semanal**, facilitando su interpretación.

---

## Justificación de la viabilidad del proyecto

El proyecto es técnicamente viable debido a:

- La disponibilidad de APIs de modelos generativos accesibles como **Google Gemini**.
- La facilidad de integración con **Python y Jupyter Notebook**.
- La posibilidad de generar resultados mediante **ingeniería de prompts**, sin necesidad de entrenar modelos propios.

Además, el proyecto se mantiene dentro de un alcance manejable al tratarse de una **Proof of Concept**, enfocada en demostrar la viabilidad de la solución mediante prompts optimizados.

El uso de **Fast Prompting** permite reducir costos computacionales y simplificar la arquitectura del sistema.

---

# Objetivos

## Objetivo general

Desarrollar una Proof of Concept que utilice técnicas de Fast Prompting para generar un sistema de organización personal adaptativa mediante modelos de inteligencia artificial.

## Objetivos específicos

- Implementar un sistema de planificación semanal utilizando modelos generativos.
- Diseñar prompts estructurados y eficientes.
- Minimizar el número de consultas a la API.
- Permitir la replanificación ante cambios imprevistos.
- Generar visualizaciones del calendario mediante prompts de generación de imágenes.
- Evaluar la eficiencia del sistema en términos de coherencia y consumo de tokens.

---

# Metodología

El desarrollo del proyecto se llevó a cabo mediante las siguientes etapas:

1. **Definición del problema**
   - Identificación de la necesidad de mejorar la planificación personal.

2. **Diseño del sistema**
   - División en dos módulos principales:
     - generación de planificación
     - generación de prompt visual

3. **Diseño de prompts**
   - Creación de prompts estructurados para optimizar la respuesta del modelo.

4. **Implementación**
   - Desarrollo en Python utilizando Jupyter Notebook.

5. **Evaluación**
   - Verificación de coherencia del plan generado.
   - análisis de eficiencia del prompt.

---

# Herramientas y Tecnologías

- **Python**
- **Jupyter Notebook**
- **Google Generative AI SDK**
- **Gemini API**

### Modelo utilizado

- `gemini-1.5-flash`

### Técnicas de Fast Prompting utilizadas

- Role Prompting
- Structured Prompting
- Instruction Compression
- Context Reuse
- Temperature Control
- Modular Prompt Design
- Output Formatting Control

Estas técnicas permiten:

- reducir ambigüedad en las respuestas
- mejorar coherencia del modelo
- disminuir consumo de tokens
- optimizar rendimiento

---

# Implementación

La implementación se realizó mediante un **Jupyter Notebook** que integra:

1. Configuración del modelo Gemini.
2. Generación de planificación semanal mediante prompt estructurado.
3. Generación de un prompt de imagen basado en el plan obtenido.
4. Visualización del resultado.

El sistema permite:

- generar una planificación semanal equilibrada
- reorganizar el plan ante cambios
- producir una visualización del calendario

### Prompt utilizado para generación de imagen

"A high-quality, minimalist UI/UX design of a weekly digital planner interface, clean productivity app style similar to Notion or Google Calendar. The layout features a 7-column grid for "Monday" through "Sunday" with time stamps on the left axis from 07:30 to 20:00. The schedule uses a professional "Time Blocking" system with soft pastel colors:

GREEN blocks from 09:00 to 13:00 labeled "STUDIES" (Monday to Friday).

ORANGE blocks from 15:30 to 18:30 labeled "EDITING / WORK" (Monday to Friday), including an extra hour starting at 14:30 on Tuesday and Thursday.

PURPLE blocks at 14:30 on Monday, Wednesday, and Friday labeled "EXERCISE".

LIGHT BLUE blocks for "Morning Routine" at 07:30, "Lunch & Rest" at 13:00, and "Disconnection/Leisure" from 19:30 onwards.

Saturday and Sunday are filled with large light blue blocks labeled "Leisure & Relax".

The aesthetic is ultra-clean, flat design, white background, modern sans-serif typography, subtle shadows, 4k resolution, organized and professional atmosphere."


---

# Resultados

La implementación permitió generar automáticamente un **plan semanal estructurado** a partir de información básica proporcionada por el usuario.

Los resultados obtenidos demuestran que el uso de prompts bien diseñados permite:

- generar planes coherentes y equilibrados
- reducir la carga cognitiva del usuario al planificar
- visualizar el calendario mediante generación de imagen

El sistema logró cumplir con los objetivos planteados, demostrando la viabilidad del uso de técnicas de Fast Prompting para resolver problemas de organización personal.

---

# Conclusiones

El proyecto demuestra que la combinación de modelos generativos de lenguaje con técnicas de ingeniería de prompts permite desarrollar soluciones prácticas para problemas cotidianos como la organización del tiempo.

El uso de **Fast Prompting** permitió optimizar la interacción con el modelo, reduciendo la cantidad de consultas necesarias y manteniendo coherencia en los resultados.

Además, la integración de generación de texto y visualización mediante prompts de imagen evidencia el potencial de los sistemas multimodales para mejorar la comprensión de la información generada.

La Proof of Concept valida que este enfoque puede escalarse en el futuro hacia aplicaciones más completas de productividad asistida por inteligencia artificial.

---

