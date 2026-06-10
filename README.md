# Tests de autoevaluación — Análisis Numérico II

Repositorio del proyecto de innovación docente **«Implementación de test de autoevaluación en Moodle para prácticas de Análisis Numérico II»**, desarrollado en el Grado en Matemáticas de la Universidad de Zaragoza durante el curso 2025/26.

## Descripción

Este repositorio contiene los bancos de preguntas de opción múltiple diseñados para ser realizados por los alumnos al finalizar cada práctica de la asignatura. Cada test se configura en Moodle para presentar 5 preguntas seleccionadas aleatoriamente del banco correspondiente, de modo que cada intento es diferente y se favorece la repetición reflexiva como herramienta de aprendizaje.

El objetivo de los cuestionarios no es calificador sino formativo: proporcionar retroalimentación inmediata al alumno sobre su comprensión de los contenidos trabajados en la práctica.

## Contenido del repositorio

| Archivo XML | Tema | Preguntas en el banco | Preguntas por intento |
|---|---|---|---|
| `test_splines.xml` | Interpolación mediante splines cúbicos | 7 | 5 (aleatorias) |
| `test_richardson.xml` | Extrapolación de Richardson | 7 | 5 (aleatorias) |
| `test_integracion.xml` | Integración numérica | 12 | 5 (aleatorias) |
| `test_euler.xml` | Método de Euler | 6 | 5 (aleatorias) |

## Importación en Moodle

1. Desde el curso de Moodle, acceder a **Banco de preguntas → Importar**.
2. Seleccionar el formato **Moodle XML** y cargar el archivo correspondiente.
3. Crear un cuestionario, añadir una pregunta aleatoria del banco importado y configurar el número de preguntas por intento (5) y el número máximo de intentos permitidos.

## Resultados — Curso 2025/26

Durante el primer curso de implementación participaron entre 26 y 46 alumnos por test. La tabla siguiente recoge los principales indicadores, tomando el mejor intento de cada alumno.

| Test | Alumnos | Intentos | Media (/5) | Mediana (/5) | ≥ 3/5 |
|---|---|---|---|---|---|
| Splines cúbicos | 46 | 73 | 2,72 | 3,00 | 60,9 % |
| Extrapolación de Richardson | 27 | 27 | 2,63 | 3,00 | 55,6 % |
| Integración numérica | 28 | 47 | 3,93 | 5,00 | 82,1 % |
| Método de Euler | 26 | 40 | 3,23 | 4,00 | 65,4 % |

La diferencia de participación entre el test de splines (realizado en el aula al término de la práctica) y los tres restantes (realizados de forma autónoma) pone de manifiesto que el contexto de realización es un factor determinante. En cursos sucesivos se recomienda reservar los últimos minutos de cada sesión práctica para completar el cuestionario correspondiente.

