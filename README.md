# Proyecto de Metodología de la Investigación

**Exposición a pantallas, hábitos posturales y síntomas físicos en estudiantes de Ingeniería de Sistemas y Computación de la UPTC** 

## Integrantes

- Gabriel Alejandro Gamba Leguizamón — 202510297
- José Fernando Barreto Franco — 202510341
- Daniel Felipe Molina Barajas — 202424582

## Idea de investigación (versión ajustada — cierre de la Fase 1)

Queremos saber **si** el número de horas diarias de exposición a pantallas y los hábitos posturales autorreportados durante las jornadas de estudio se relacionan con la frecuencia de fatiga visual y de molestias osteomusculares en los estudiantes de Ingeniería de Sistemas y Computación de la UPTC (sede Tunja), **porque eso importaría para** que los propios estudiantes, la Escuela y Bienestar Universitario decidan qué medidas de ergonomía y pausas activas vale la pena promover.

El recorrido completo (cómo surgió la idea, prueba de investigabilidad y filtro de viabilidad) está en el Anexo A del documento.

## Estado del proyecto

| Fase | Contenido | Estado |
|---|---|---|
| 1 | Ideación y exploración inicial (Anexo A) | Redactada — faltan 3 datos del equipo marcados como `\pendiente` |
| 2 | Diagnóstico y planteamiento del problema (sección 1) | Redactada — falta validar la matriz del numeral 1.2 y completar la referencia [4] |
| 3 | Formulación de la propuesta (secciones 2 a 6) | Redactada — falta validar objetivos, hipótesis y variables como equipo |
| 4 | Marco referencial (sección 7) | Redactada — falta registrar el embudo real de la búsqueda del estado del arte |
| 5 | Diseño metodológico (sección 8) | Redactada — faltan matrícula, piloto y permiso del CVS-Q |
| 6 | Resultados (sección 9) | Parcial — plan de ejecución y de análisis redactado; faltan los datos reales de la encuesta |
| 7 | Cierre y memoria final (sección 10) | Por hacer |

## Pendientes del equipo

Lo que falta y solo el equipo puede completar. Cada uno está marcado en el documento como `\pendiente` o descrito en el lugar indicado.

| Fase | Pendiente | Dónde |
|---|---|---|
| 1 | Registrar la lluvia de ideas real, una observación real de compañeros y las entrevistas cortas | Anexo A |
| 2 | Validar como equipo la matriz de correlación y el filtro de ruido; completar la referencia [4] (Zhunio Suin) | Numeral 1.2 y referencias |
| 3 | Validar objetivos, hipótesis y variables; decidir si la pregunta se formula con "si" en vez de "cómo" | Secciones 2 a 6 y numeral 1.3 |
| 4 | Registrar el embudo real de la búsqueda del estado del arte; confirmar con el docente la clasificación del riesgo (Resolución 8430) | Numerales 7.2 y 7.5 |
| 5 | Registrar el número de estudiantes matriculados en el programa | Numeral 8.4 |
| 5 | Confirmar los términos de uso del CVS-Q (Colombia) | Numeral 8.5 |
| 5 | Validar los ocho ítems de hábitos posturales con dos docentes y hacer la prueba piloto (número de participantes, tiempo, ajustes y alfa de Cronbach) | Numeral 8.5 |
| 5 | Definir las fechas exactas de aplicación de la encuesta | Numeral 1.5 y sección 8 |
| 5 | Comprobar los datos de las referencias [23] (Cuestionario Nórdico) y [24] (Cronbach) | Referencias |
| 6 | Aplicar la encuesta y consolidar los datos en un único conjunto | Numeral 9.1 |
| 6 | Registrar desviaciones, tasa de respuesta y encuestas excluidas | Numeral 9.1 |
| 6 | Calcular y reportar las estadísticas descriptivas | Numeral 9.2 |
| 6 | Aplicar las pruebas, reportar el tamaño del efecto y decidir cada hipótesis nula | Numeral 9.3 |
| 6 | Insertar las tablas y figuras reales | Numeral 9.4 |
| 6 | Redactar la discusión frente al estado del arte y las limitaciones | Numeral 9.5 |
| 7 | Redactar las conclusiones, las recomendaciones y la memoria final con los resultados reales | Sección 10 |

## Estructura del repositorio

```
documentos/proyecto-icontec/
├── main.tex          archivo que se compila
├── main.pdf          última versión compilada
├── preambulo.tex     paquetes, colores y comandos
├── portada.tex
├── contenido.tex     tabla de estado por sección
├── secciones/        una sección numerada por archivo (01 a 10)
├── referencias.tex   lista única de referencias (IEEE)
└── anexos.tex        Anexo A: ideación (Fase 1)
```

## Cómo compilar

```
cd documentos/proyecto-icontec
pdflatex main.tex
pdflatex main.tex
```
