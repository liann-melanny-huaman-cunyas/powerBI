# 📊 Guía Completa de Power BI: De Principiante a Avanzado

## 🟢 Nivel Principiante

### ¿Qué es Power BI?
- Herramienta de Microsoft para análisis de datos y visualización interactiva.
- Permite conectar, transformar y visualizar datos de diferentes fuentes.

### Componentes principales
- **Power BI Desktop**: Herramienta de desarrollo (instalación en PC).
- **Power BI Service**: Plataforma online para publicar y compartir informes.
- **Power BI Mobile**: Aplicación para visualizar reportes en dispositivos móviles.
- **Power BI Gateway**: Conecta datos locales con el servicio online.

### Flujo básico de trabajo
1. Conectar a una fuente de datos.
2. Transformar y limpiar los datos (Power Query).
3. Modelar los datos (relaciones, medidas).
4. Crear visualizaciones.
5. Publicar y compartir informes.

### Fuentes de datos comunes
- Excel
- CSV
- SQL Server
- Web
- SharePoint
- Google Sheets (con conector externo)

---

## 🟡 Nivel Intermedio

### Power Query (Editor de consultas)
- Transformaciones básicas: filtrar, cambiar tipo de datos, dividir columnas.
- Combinar datos: `Merge` (unir) y `Append` (agregar).
- Crear columnas personalizadas.
- Usar el lenguaje M para personalizaciones avanzadas.

### Modelado de datos
- Crear relaciones entre tablas (uno a muchos, muchos a uno).
- Crear tablas calculadas.
- Jerarquías (por ejemplo, Año > Mes > Día).
- Columnas calculadas con DAX.

### Lenguaje DAX (Data Analysis Expressions)
- Funciones básicas:
  - `SUM`, `AVERAGE`, `COUNTROWS`, `DISTINCTCOUNT`
- Funciones de filtro:
  - `CALCULATE`, `FILTER`, `ALL`, `VALUES`
- Medidas temporales:
  - `TOTALYTD`, `SAMEPERIODLASTYEAR`, `DATEADD`

### Visualizaciones
- Tablas, matrices, tarjetas, gráficos de barras, líneas, áreas, etc.
- Slicers (segmentadores).
- Mapas.
- Visuales personalizados desde el marketplace.

### Interactividad
- Filtros cruzados entre visuales.
- Drill down / drill through.
- Páginas con navegación dinámica.

---

## 🔵 Nivel Avanzado

### DAX Avanzado
- Funciones de tiempo complejas:
  - `DATESYTD`, `PARALLELPERIOD`, `CLOSINGBALANCEMONTH`
- Variables (`VAR`) para expresiones optimizadas.
- Medidas con condiciones (`IF`, `SWITCH`, `ISFILTERED`).

### Optimización de modelo
- Modelos estrella vs copo de nieve.
- Minimizar el uso de columnas calculadas.
- Uso eficiente de relaciones y tablas de fechas.
- Deshabilitar Auto Date/Time.

### Seguridad a nivel de fila (RLS)
- Crear roles y reglas con expresiones DAX.
- Probar roles en Power BI Desktop.
- Publicar con RLS en Power BI Service.

### Publicación y colaboración
- Publicar desde Power BI Desktop al Servicio.
- Configurar actualización programada.
- Compartir informes y dashboards.
- Crear apps en Power BI Service.

### Power BI Service
- Workspaces.
- Dashboards vs Reports.
- Flujos de datos (Dataflows).
- Data lineage (linaje de datos).
- Métricas (Goals).

### Automatización e integración
- Power Automate (flujo de acciones basado en eventos).
- Integración con Power Apps.
- Uso de API de Power BI para tareas programadas.
- Embebido en aplicaciones externas (Power BI Embedded).

### Buenas prácticas
- Nombrar correctamente tablas, columnas y medidas.
- Evitar columnas innecesarias.
- Documentar las transformaciones.
- Usar descripciones y herramientas como Tabular Editor.

---

## 🧰 Recursos recomendados

### Cursos y documentación
- Microsoft Learn: [https://learn.microsoft.com/es-es/power-bi/](https://learn.microsoft.com/es-es/power-bi/)
- Curso gratuito: Power BI en YouTube
- Libros: 
  - "The Definitive Guide to DAX" – Marco Russo & Alberto Ferrari.
  - "Power BI Cookbook" – Brett Powell.

### Comunidades
- Power BI Community: https://community.powerbi.com/
- Reddit: https://www.reddit.com/r/PowerBI/
- LinkedIn y grupos en Facebook.

---

## 🏁 Conclusión

Power BI es una herramienta poderosa que va desde el análisis básico hasta el desarrollo de soluciones empresariales completas. Dominarla requiere práctica constante, dominio de DAX, modelado de datos y visualización efectiva.

