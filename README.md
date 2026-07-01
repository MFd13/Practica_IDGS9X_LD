# Kit de clase: preparación de datos y entrada al análisis supervisado

Este kit utiliza únicamente la **fase de grupos** de los Mundiales masculinos de 2018, 2022 y 2026.

## Propósitos didácticos

- Detectar y documentar problemas de calidad.
- Unificar tres fuentes con esquemas diferentes.
- Limpiar fechas, textos, categorías, números y duplicados.
- Comparar torneos mediante métricas normalizadas.
- Preparar variables para un primer problema de clasificación supervisada.
- Identificar fuga de información (*data leakage*).

## Estructura

- `datos/`: archivos sucios y catálogo de equipos.
- `excel/`: libro de trabajo para estudiantes.
- `notebooks/`: tutorial de Python y solución.
- `guias/`: guía del alumno y guía docente.
- `solucion/`: base limpia, incidencias y libro del profesor.

## Regla de comparación

El Mundial 2026 tuvo 48 equipos y 72 partidos de fase de grupos; 2018 y 2022 tuvieron 32 equipos y 48 partidos de fase de grupos. Por ello, no se deben comparar solamente los goles totales. Deben calcularse también goles por partido, porcentajes y métricas por equipo.

## Fuentes y atribución

- Datos históricos 2018 y 2022: The Fjelstul World Cup Database, Joshua C. Fjelstul, Ph.D., CC-BY-SA 4.0.
- Resultados de la fase de grupos 2026: páginas de grupos A–L de Wikipedia, consultadas el 30 de junio de 2026, con enlaces a reportes de FIFA.
- Los archivos sucios son modificaciones didácticas deliberadas y no deben utilizarse como fuente estadística sin limpieza.
