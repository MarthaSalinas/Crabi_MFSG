![Logo Crabi](Image/logo.png)

# Crabi_MFSG
Este notebook realiza un análisis completo de los siniestros de Crabi, enfocándose en **frecuencia**, **severidad** y **segmentación de riesgo**.  

---

## 🔹 Características principales
- Limpieza y validación de datos
- Integración de claims, services y people
- Generación de métricas:
    - Siniestralidad mensual (loss ratio)
    - Métricas por cobertura
    - Métricas por partner
    - Métricas por rango etario
- Exportación a CSV para Power BI

## 🔹 Herramientas utilizadas
- Python: pandas, numpy, matplot
- Jupyter Notebook
- Power BI
  
## 🔹 Fuentes de datos
- claim.xlsx 
- service.xlsx 
- people.xlsx 
- Diccionario de Datos.xlsx 
- status.xlsx
- status_type.xlsx
- status_cause.xlsx

## 🔹 Flujo de trabajo
1. Cargar los archivos originales (`claim.xlsx`, `service.xlsx`, `people.xlsx`) sin modificarlos
2. Limpiar, validar y transformar los datos en memoria
3. Calcular métricas de siniestralidad, severidad, analisís Etario
4. Exportar los resultados a CSV
5. Importar CSVs en Power BI para dashboards interactivos

## 🔹 Insights principales
- Segmentos de baja frecuencia pueden generar alto riesgo financiero
- Los extremos de edad (`<25` y `65+`) presentan mayor severidad
- Segmentación por partner y cobertura permite control de riesgo y ajuste de primas
- Meses atípicos pueden distorsionar la siniestralidad mensual
