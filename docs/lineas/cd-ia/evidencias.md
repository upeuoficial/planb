# Evidencias por competencia de la línea de Ciencia de Datos e IA

Este documento registra las competencias, evidencias y artefactos verificables de la línea de Ciencia de Datos e IA. Sirve como base para construir guías de entrega, revisión y sustentación.

Las cuatro competencias específicas (CE041 a CE044) corresponden a la formulación de la línea. Los cursos que hoy las cubren (BI y Big Data) se declaran en su propio sílabo bajo `CE04: Ciencia de Datos e Inteligencia Artificial`.

## CE04: Ciencia de Datos e Inteligencia Artificial

Diseña y gestiona sistemas inteligentes basándose en metodologías, estándares y herramientas a fin de lograr estrategias de mejora para la organización.

## Proyecto integrador de la línea

La evidencia final de la línea se organiza como una solución basada en datos o inteligencia artificial. Puede adoptar la forma de análisis avanzado, tablero, modelo predictivo, sistema de recomendación, clasificador, solución de visión, procesamiento de lenguaje, automatización inteligente o prototipo analítico.

El producto integrador debe demostrar coherencia entre problema, datos, preparación, modelado, evaluación, comunicación, uso responsable y mejora.

Entregables de referencia:

- Entregable 1: Dossier de requerimientos de la solución analítica, alineado con CE0411.
- Entregable 2: Infraestructura de extracción, integración y preparación de datos, alineado con CE0421.
- Entregable 3: Modelos predictivos, descriptivos o prescriptivos entrenados y evaluados, alineado con CE0431.
- Entregable 4: Indicadores, visualización y recomendaciones estratégicas, alineado con CE0441.

## Distribución por curso de referencia

Esta distribución viene del Plan Matricial oficial (`Plan Matricial - Sistemas 2024 - V 3.0.xlsx`, pestañas Plan 2024/2025), que asigna un nivel de logro (1 introductorio, 2 intermedio, 3 dominado) por curso y por competencia — no de un mapeo hecho a mano. No reemplaza la programación académica vigente del semestre en curso; el detalle completo de la ruta por ciclo está en [la página principal de la línea](index.md#5-ruta-de-construcción-y-evaluación-durante-la-carrera).

| Curso | Ciclo | CE041 | CE042 | CE043 | CE044 |
| --- | --- | ---: | ---: | ---: | ---: |
| Introducción a la Ingeniería de Computación | C1 | 1 | — | — | — |
| Administración de Base de Datos I | C3 | — | 1 | — | — |
| Administración de Base de Datos II | C4 | — | 2 | — | — |
| Estadística para la Investigación | C5 | 1 | — | 1 | 1 |
| Métodos Numéricos | C6 | 1 | — | 1 | — |
| Análisis Multivariado | C7 | 2 | — | 2 | 2 |
| Inteligencia de Negocios | C8 | 2 | 2 | 2 | 2 |
| Inteligencia Artificial | C8 | 2 | 2 | 2 | 2 |
| Proyecto Integrador I | C8 | 2 | 2 | 2 | 2 |
| Minería de Datos | C9 | 3 | 3 | 3 | 3 |
| Big Data | C10 | 3 | 3 | 3 | 3 |
| Proyecto Integrador II | C10 | 3 | 3 | 3 | 3 |

Administración de Base de Datos I y II son compartidos con la línea de Software (CE022); ahí solo aportan a CE042. Inteligencia Artificial y Minería de Datos no tienen repositorio en este workspace todavía — no se encontró carpeta ni sílabo con esos nombres.

Hay una tensión sin resolver: el sílabo propio de Inteligencia de Negocios (BI) no menciona modelado entre sus dimensiones ("define requerimientos, construye datasets, analiza los datos y define estrategias" — sin CE043), pero el Plan Matricial le asigna nivel 2 en las cuatro. Puede deberse a que el nivel se registra junto con Proyecto Integrador I, evaluado en el mismo ciclo.

## CE041: Define Requerimientos de Inteligencia Analítica

Analiza necesidades y procesos organizacionales para definir requerimientos de soluciones de analítica de datos e inteligencia artificial.

Rol asociado: Data/AI Consultant – Business Analyst.

### CE0411: Necesidades organizacionales y requerimientos de la solución

Propósito:

Demostrar que el estudiante puede convertir una necesidad organizacional en un problema analítico claro, viable y sustentado en datos.

Artefactos de la evidencia:

- Necesidad organizacional y proceso identificado.
- Problema analítico formulado.
- Requerimientos de la solución de analítica o IA.
- Variables, supuestos e hipótesis de trabajo.

Formato sugerido:

Documento técnico breve o notebook documentado.

Estructura sugerida del producto:

- Contexto organizacional, proceso involucrado y necesidad de mejora.
- Pregunta analítica o problema de predicción, clasificación, segmentación, recomendación o análisis.
- Requerimientos de la solución: qué información, indicadores o capacidades hacen falta.
- Variables disponibles, variable objetivo si aplica e hipótesis de trabajo.

## CE042: Construye Infraestructura de Datos

Diseña e implementa procesos de extracción, integración, transformación, almacenamiento y preparación de datos para soluciones analíticas y de inteligencia artificial.

Rol asociado: Data Engineer.

### CE0421: Infraestructura de extracción, integración y preparación de datos

Propósito:

Demostrar que el estudiante puede diseñar e implementar una infraestructura de datos reproducible, desde la extracción hasta la preparación final.

Artefactos de la evidencia:

- Fuentes de datos identificadas, extraídas e integradas.
- Dataset construido y almacenado.
- Transformaciones, limpieza y feature engineering.
- Pipeline reproducible y versionado de datos.

Formato sugerido:

Notebook, scripts o repositorio técnico con documentación de transformaciones, dependencias y ejecución reproducible.

Estructura sugerida del producto:

- Identificación, extracción e integración de fuentes internas o externas.
- Criterios de selección, transformación y combinación de variables.
- Limpieza, tratamiento de nulos, codificación y escalamiento si aplica.
- Almacenamiento y pipeline reproducible para carga, transformación y preparación de datos.
- Evidencias de versionamiento o trazabilidad de datos y código.

## CE043: Desarrolla Modelos de Analítica

Explora, prepara y modela datos mediante técnicas estadísticas, aprendizaje automático e inteligencia artificial para generar modelos predictivos, descriptivos y/o prescriptivos.

Rol asociado: Data Scientist / ML Engineer.

### CE0431: Modelos predictivos, descriptivos o prescriptivos entrenados y evaluados

Propósito:

Demostrar que el estudiante puede modelar datos con técnicas estadísticas o de IA, generar modelos predictivos, descriptivos o prescriptivos, y evaluarlos con trazabilidad técnica.

Artefactos de la evidencia:

- Modelos entrenados.
- Notebooks o bitácora de experimentos.
- Métricas de evaluación del modelo.
- Comparación de enfoques y propuesta de mejora o reentrenamiento.

Formato sugerido:

Repositorio o carpeta técnica con notebooks, scripts, datasets versionados o referencias controladas, resultados de ejecución y bitácora de experimentos.

Estructura sugerida del producto:

- Modelos entrenados (regresión, clasificación u otra técnica pertinente al problema predictivo, descriptivo o prescriptivo).
- Registro de experimentos, parámetros, resultados y decisiones.
- Métricas pertinentes según el problema: accuracy, precision, recall, F1, AUC, MAE, RMSE u otras.
- Comparación de modelos o enfoques.
- Análisis de errores, sesgos, límites y riesgos.
- Propuesta de mejora, actualización o reentrenamiento.

## CE044: Genera Inteligencia para la Toma de Decisiones

Analiza e interpreta datos y resultados analíticos para generar indicadores, visualizaciones, reportes y recomendaciones estratégicas que apoyen la toma de decisiones.

Rol asociado: Data Analyst / BI Analyst.

### CE0441: Indicadores, visualización y recomendaciones estratégicas

Propósito:

Demostrar que el estudiante puede analizar datos y resultados analíticos para comunicar indicadores, visualizaciones y recomendaciones accionables conectadas con decisiones organizacionales.

Artefactos de la evidencia:

- Indicadores o KPI definidos.
- Visualización o tablero estratégico.
- Interpretación de resultados en lenguaje de negocio.
- Recomendaciones y estrategias accionables.

Formato sugerido:

Informe ejecutivo, tablero, presentación, demo o sustentación técnica con visualizaciones y recomendaciones accionables.

Estructura sugerida del producto:

- Indicadores o KPI y visualizaciones o tablero de resultados.
- Explicación del problema, datos, método y hallazgos.
- Interpretación de métricas o indicadores en lenguaje de negocio.
- Recomendaciones para usuarios, responsables o tomadores de decisión.
- Limitaciones, consideraciones éticas y próximos pasos.
