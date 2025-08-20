# Telecom X - Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto
Este proyecto tiene como objetivo analizar la **evasión de clientes (Churn)** en Telecom X, identificando patrones y factores que influyen en la cancelación de servicios.  
A partir de los datos de clientes, se realizaron procesos de limpieza, transformación y visualización para obtener **insights estratégicos** que ayuden a reducir la tasa de evasión.

---

## 🛠 Tecnologías y Librerías
- **Python 3.x**  
- **Pandas**: manipulación y análisis de datos.  
- **NumPy**: operaciones numéricas.  
- **Matplotlib y Seaborn**: visualización de datos.  
- **Jupyter / Google Colab**: entorno de desarrollo interactivo.  

---

## 📊 Estructura del Proyecto
1. **Carga de datos**  
   - Datos obtenidos desde la API de Telecom X en formato JSON.  
   - Conversión a DataFrame para manipulación con Pandas.

2. **Limpieza y Transformación**  
   - Aplanado de columnas anidadas (`customer`, `phone`, `internet`, `account`, `charges`).  
   - Conversión de columnas numéricas (`Total`, `Monthly`) a `float`.  
   - Manejo de valores nulos y duplicados.  
   - Transformación de variables binarias (`Yes/No`) a enteros (`1/0`).  
   - Creación de columna `Cuentas_Diarias` para análisis detallado de gasto diario.

3. **Análisis Exploratorio de Datos (EDA)**  
   - Distribución general de Churn (clientes que cancelaron vs. los que permanecen).  
   - Análisis de Churn según variables categóricas: género, tipo de contrato, método de pago y servicios contratados.  
   - Análisis de variables numéricas (`Total`, `Monthly`, `tenure`, `Cuentas_Diarias`) entre clientes que cancelaron y los que no.  
   - Visualizaciones: gráficos de pastel, barras, boxplots y densidad (KDE).

4. **Insights y Conclusiones**  
   - Clientes con contratos cortos o menor gasto mensual presentan mayor riesgo de Churn.  
   - Ciertos servicios adicionales aumentan la retención.  
   - Tipo de contrato y método de pago son variables clave para predecir evasión.

5. **Recomendaciones Estratégicas**  
   - Implementar campañas de fidelización para clientes de alto riesgo.  
   - Ofrecer servicios adicionales que incrementen la retención.  
   - Monitorear patrones de Churn para ajustar estrategias de retención.  
   - Utilizar modelos predictivos basados en los insights obtenidos.

---

