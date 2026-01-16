People Analytics – Rotación y Retención de Empleados (Python)

📌 **Descripción del proyecto**  
Proyecto académico enfocado en el análisis de datos de recursos humanos para identificar factores que influyen en la rotación laboral.  
Se aplicaron técnicas de limpieza, exploración y visualización de datos utilizando Python y Pandas, con el objetivo de generar insights para apoyar decisiones de retención de talento.

🎯 **Objetivo**  
Analizar los datos de RR. HH. para identificar patrones de rotación y retención de empleados, evaluando factores demográficos, económicos y de satisfacción laboral.

🧠 **Actividades realizadas**  
- Limpieza y preprocesamiento de datos con Pandas  
- Exploración inicial del dataset: dimensiones, columnas, tipos de datos y valores faltantes  
- Eliminación de columnas irrelevantes (`Unnamed:0`, `EmployeeCount`, `StandardHours`, `Over18`)  
- Imputación de valores faltantes en columnas categóricas (`OverTime` y `RelationshipSatisfaction`)  
- Análisis descriptivo y estadísticas generales de variables numéricas  
- Detección de outliers con boxplots e IQR  
- Visualización de distribuciones y relaciones entre variables clave (`Age`, `MonthlyIncome`, `JobSatisfaction`, `WorkLifeBalance`)  
- Generación de insights sobre factores que afectan la rotación laboral (edad, ingresos, horas extra, balance vida-trabajo)  

📂 **Estructura del repositorio**


### notebooks/
- `eda_rotacion_empleados.ipynb` → Notebook con análisis exploratorio de datos y visualizaciones    

### docs/
- `analisis_rotacion_retencion.docx` → Documentación con hallazgos, insights y conclusiones  

### README.md
- Archivo de explicación general del proyecto y estructura del repositorio

🛠 **Herramientas utilizadas**  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Jupyter Notebook para análisis interactivo  
- Word/Docs para documentación de insights  

📊 **Insights principales**
1. **Horas Extra y Rotación:** Los empleados que realizan horas extra con frecuencia tienen mayor probabilidad de renunciar.  
2. **Edad y Retención:** Empleados menores de 30 años presentan la mayor tasa de rotación (>25%).  
3. **Ingresos y Rotación:** El salario bajo es el factor más determinante para renunciar, independiente del género.  
4. **Balance Vida-Trabajo:** El nivel 3 de WorkLifeBalance es el más estable, con menor rotación; el nivel 1 muestra desgaste crítico (31% renuncia).  
5. **Experiencia Laboral:** Los empleados con menos años de experiencia y trayectoria profesional corta presentan mayor riesgo de rotación.  

📅 **Fecha**  
Noviembre 2025
