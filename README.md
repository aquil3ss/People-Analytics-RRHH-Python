# People Analytics – Rotación y Retención de Empleados (Python)

📌 **Descripción del proyecto**  
Análisis de datos de recursos humanos para identificar factores que influyen en la rotación laboral.  
Se aplicaron técnicas de limpieza, exploración y visualización de datos con Python y Pandas para generar insights que apoyen decisiones de retención de talento.

🎯 **Objetivo**  
Analizar patrones de rotación y retención considerando factores demográficos, económicos y de satisfacción laboral.

🧠 **Actividades realizadas**  
- Limpieza e imputación de datos faltantes  
- Exploración inicial del dataset (dimensiones, tipos de datos, valores nulos)  
- Eliminación de columnas irrelevantes (`Unnamed:0`, `EmployeeCount`, `StandardHours`, `Over18`)  
- Análisis descriptivo y detección de outliers (IQR, boxplots)  
- Visualización de distribuciones y relaciones entre variables clave  
- Desarrollo de insights sobre factores que afectan la rotación: edad, ingresos, horas extra, balance vida-trabajo, experiencia laboral  

📂 **Estructura del repositorio**

- `data/` → Contiene el dataset original CSV (`PFDA_People_analytics.csv`)  
- `docs/` → Documentación con hallazgos, insights y conclusiones (`Informe.pdf`)  
- `notebook/` → Notebook de análisis exploratorio (`ProyectoPython.ipynb`)  
- `README.md` → Explicación general del proyecto y estructura del repositorio

📊 **Insights principales**
1. **Horas Extra y Rotación:** Mayor probabilidad de renuncia en quienes hacen horas extra.  
2. **Edad:** Menores de 30 años presentan la rotación más alta (>25%).  
3. **Ingresos:** El bajo salario es el factor más determinante para renunciar, independiente del género.  
4. **Balance Vida-Trabajo:** Nivel 3 es el más estable; Nivel 1 muestra alta rotación (31%).  
5. **Experiencia Laboral:** Menos años de experiencia se relacionan con mayor riesgo de rotación.

📅 **Fecha**  
Noviembre 2025
