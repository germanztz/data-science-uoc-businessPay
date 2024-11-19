### **1. Código en Python**

#### **Tareas Necesarias**
1. **Carga de datos:**
   - Leer los datos proporcionados (archivos CSV, bases de datos, etc.) utilizando Pandas.
   - Examinar las primeras filas para entender la estructura del dataset.
   
2. **Preprocesamiento:**
   - Manejar valores faltantes (imputación o eliminación).
   - Estandarizar formatos (fechas, nombres de columnas, tipos de datos).
   - Filtrar datos irrelevantes o fuera del alcance del análisis.

3. **Análisis de cohortes:**
   - Definir cohortes basadas en la fecha del primer adelanto de efectivo.
   - Calcular métricas iniciales (frecuencia de uso, tasa de incidentes, ingresos).

4. **Cálculo de insights:**
   - Generar métricas acumuladas por cohorte (por ejemplo, promedio de ingresos, tasa de retención).
   - Analizar correlaciones entre métricas clave.

5. **Visualizaciones:**
   - Crear gráficos para ilustrar tendencias de uso, ingresos, incidentes y métricas acumuladas por cohorte (e.g., gráficos de líneas, barras y heatmaps).

#### **Requerimientos**
- Librerías: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn.
- Estilo del código: Documentación clara (docstrings y comentarios), adherencia a PEP 8.

---

### **2. Informe del Análisis Exploratorio de Datos (EDA)**

#### **Tareas Necesarias**
1. **Estadísticas descriptivas:**
   - Resumir datos (media, mediana, desviación estándar, percentiles).
   - Identificar distribuciones de variables clave.

2. **Identificación de patrones y valores atípicos:**
   - Graficar histogramas y boxplots para variables continuas.
   - Analizar distribuciones categóricas con gráficos de barras.

3. **Correlación y dependencia:**
   - Calcular matrices de correlación entre variables numéricas.
   - Usar heatmaps para representar correlaciones.

4. **Visualizaciones clave:**
   - Distribución de cohortes a lo largo del tiempo.
   - Evolución temporal de métricas clave.

5. **Documentación:**
   - Crear un informe en formato markdown con gráficos y conclusiones.

#### **Requerimientos**
- Markdown bien estructurado y visualmente claro.
- Inclusión de gráficos exportados desde Python.

---

### **3. Informe del Análisis de Calidad de Datos**

#### **Tareas Necesarias**
1. **Detección de problemas:**
   - Identificar valores faltantes y calcular su proporción.
   - Detectar inconsistencias en tipos de datos, duplicados o errores evidentes.

2. **Resolución de problemas:**
   - Manejar valores faltantes (relleno, eliminación o categorización de "desconocido").
   - Corregir formatos y eliminar duplicados.

3. **Documentación:**
   - Resumir en markdown los problemas encontrados y las soluciones aplicadas.
   - Detallar qué transformaciones fueron necesarias y por qué.

#### **Requerimientos**
- Inclusión de ejemplos específicos de problemas y transformaciones realizadas.

---

### **4. Modelos de Regresión Personalizados**

#### **Tareas Necesarias**
1. **Preparación de datos:**
   - Seleccionar y transformar características relevantes para el modelo.
   - Dividir los datos en conjuntos de entrenamiento y prueba.

2. **Diseño y entrenamiento del modelo:**
   - Entrenar modelos de regresión lineal, de árbol o regularizados (Lasso, Ridge).
   - Realizar validación cruzada y ajustar hiperparámetros.

3. **Evaluación:**
   - Calcular métricas de evaluación (R², MAE, MSE).
   - Realizar análisis de residuos y gráficos de dispersión.

4. **Optimización:**
   - Implementar búsqueda de hiperparámetros (GridSearchCV o RandomizedSearchCV).
   - Justificar la selección final basada en los resultados.

#### **Requerimientos**
- Uso de Scikit-learn.
- Visualizaciones claras de resultados.

---

### **5. Presentación Ejecutiva y Repositorio de GitHub**

#### **Tareas Necesarias**
1. **Creación del informe ejecutivo:**
   - Resumir hallazgos clave del EDA, análisis de calidad y modelos.
   - Destacar insights clave y recomendaciones accionables para Business Payments.

2. **Diseño del README:**
   - Introducción al proyecto y su alcance.
   - Explicación de los entregables y cómo ejecutarlos.
   - Ejemplos de resultados clave (gráficos y métricas).

3. **Organización del repositorio:**
   - Estructurar el código, datos y documentos en carpetas claras.
   - Incluir un archivo `requirements.txt` con todas las dependencias necesarias.

#### **Requerimientos**
- Markdown amigable para stakeholders no técnicos.
- Repositorio limpio y bien documentado.
