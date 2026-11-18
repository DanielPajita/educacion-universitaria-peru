# Códigos

Esta carpeta reúne los notebooks utilizados para explorar, preparar y armonizar la información de los censos universitarios de 1996 y 2010 y de los registros administrativos del portal TUNI. El trabajo incluye la identificación y clasificación de programas académicos y la construcción de bases de análisis de pregrado y posgrado.

Los archivos se identifican mediante una numeración inicial y un nombre descriptivo. La numeración agrupa etapas de trabajo, pero no establece un orden de ejecución estrictamente secuencial, ya que algunos notebooks generan insumos que posteriormente se incorporan a las bases de cada fuente.

## Contenido

| Archivo | Contenido |
|---------|-----------|
| [01_exploracion_poblacion_estudiantil.ipynb](01_exploracion_poblacion_estudiantil.ipynb) | Exploración de los censos de 1996 y 2010 y de los registros de matrícula TUNI 2025-I. Revisa archivos, identificadores, registros y personas únicas, y compara la distribución de la matrícula por departamento y nivel académico. |
| [01_programas_tuni.ipynb](01_programas_tuni.ipynb) | Construcción de un catálogo de programas académicos a partir de los registros TUNI de postulantes, ingresantes, matriculados, egresados y oferta institucional. Consolida denominaciones y clasificaciones disponibles y separa los programas clasificados de los pendientes de clasificación. |
| [02_clasificar_programas.ipynb](02_clasificar_programas.ipynb) | Clasificación asistida de programas sin correspondencia en TUNI y en los censos de 1996 y 2010. Utiliza representaciones semánticas de texto y búsqueda del vecino más cercano para proponer campos de formación, con identificación de casos para revisión manual. |
| [02_preparar_censo1996.ipynb](02_preparar_censo1996.ipynb) | Preparación de las bases de pregrado y posgrado del Censo Universitario 1996. Integra módulos, revisa duplicados, selecciona variables, incorpora información institucional y calcula indicadores descriptivos. Genera listados de programas e incorpora su clasificación para exportar bases agregadas. |
| [02_preparar_censo2010.ipynb](02_preparar_censo2010.ipynb) | Preparación de las bases de pregrado y posgrado del Censo Universitario 2010. Revisa identificadores, selecciona y estandariza variables, construye listados de programas y utiliza las correspondencias de clasificación para generar bases agregadas y tablas descriptivas. |
| [02_preparar_tuni2024.ipynb](02_preparar_tuni2024.ipynb) | Preparación de los registros de matrícula TUNI 2024-I para pregrado y posgrado. Selecciona variables, revisa la situación de licenciamiento de las entidades, consolida registros e incorpora la clasificación de programas para generar bases agregadas y tablas descriptivas. |

## Relación entre notebooks

Los notebooks de preparación de los censos generan los listados de programas que, junto con el catálogo elaborado a partir de TUNI, sirven de insumo para la clasificación asistida. Las correspondencias obtenidas se incorporan posteriormente a las bases procesadas de 1996, 2010 y 2024-I.
