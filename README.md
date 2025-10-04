# Análisis de Vehículos Involucrados en Accidentes - Risaralda 

Este proyecto utiliza **Power BI** para analizar una base de datos de más de 3.000 registros de vehículos involucrados en accidentes en el departamento de Risaralda.

## Archivos
- `base_de_datos_limpia.csv` → Base de datos ya depurada (snake_case, sin duplicados, etc.).
- `analisis_accidentes.pbix` → Reporte en Power BI con las visualizaciones.

## 🔧 Proceso de limpieza
1. **Renombrar columnas** en formato `snake_case`.
2. **Estandarización de texto** (marcas, municipios, etc. en mayúsculas).
3. **Revisión de fechas** (aunque se dejaron en su formato original, se documenta).
4. **Eliminación de duplicados** para evitar sesgos.
5. **Validación de rangos** → Se verificó que los modelos estén entre 1990 y 2025.
6. **Consistencia entre edad_vehiculo y modelo_vehiculo** (se revisaron incoherencias).

## Visualizaciones
- **Gráfico 1:** Distribución de vehículos por tipo (`tipo_vehiculo`).
- **Gráfico 2:** Accidentes por municipio (`municipio_accidente`).

## Cómo abrir
1. Descargar el archivo `.pbix`.
2. Abrir con **Power BI Desktop**.
3. Explorar las visualizaciones y filtros.

--- Proyecto realizado para la asignatura de Arquitectura de datos_Universidad de Cundinamarca.
