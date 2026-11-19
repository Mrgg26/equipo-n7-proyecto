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
| 6 | Resultados (sección 9) | Por hacer |
| 7 | Cierre y memoria final (sección 10) | Por hacer |

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
