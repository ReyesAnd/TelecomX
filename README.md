# Proyecto: Evasion de Clientes en Telecom X

## Introducción
Este proyecto forma parte de la iniciativa de **Telecom X** para comprender y reducir la evasión de clientes (Churn).  
La empresa enfrenta una alta tasa de cancelaciones y necesita identificar los factores que influyen en la pérdida de clientes.  
El análisis realizado servirá como base para el desarrollo de modelos predictivos y estrategias de retención.

## Objetivos
- Importar y manipular datos desde una API de manera eficiente.  
- Aplicar procesos de **ETL (Extracción, Transformación y Carga)** para preparar los datos.  
- Realizar un **Análisis Exploratorio de Datos (EDA)** con visualizaciones estratégicas.  
- Identificar patrones y factores asociados con la evasión de clientes.  
- Generar un informe con conclusiones y recomendaciones.  

## Tecnologías utilizadas
- **Python 3.x**
- **Pandas** para manipulación y limpieza de datos.
- **Matplotlib / Seaborn** para visualizaciones.
- **Numpy** para cálculos numéricos.
- **Google Colab / Jupyter Notebook** como entorno de trabajo.

## Flujo del proyecto
1. **Importación de datos**: conexión a la API y carga en un DataFrame.  
2. **Limpieza de datos**: eliminación de duplicados, tratamiento de valores nulos, conversión de tipos.  
3. **Transformación de variables**: creación de nuevas columnas (ej. *Meses de servicio*, *Daily*).  
4. **EDA (Exploratory Data Analysis)**:  
   - Distribución general de churn.  
   - Análisis de variables categóricas (contrato, método de pago, etc.).  
   - Análisis de variables numéricas (total gastado, meses de servicio).  
   - Correlaciones entre variables y churn.  
5. **Informe final**: conclusiones, insights y recomendaciones estratégicas.

## Resultados principales
- Los clientes con contratos **mensuales** presentan mayor tasa de evasión.  
- La **antigüedad (Meses de servicio)** está negativamente correlacionada con churn: clientes más antiguos tienden a permanecer.  
- El **total gastado** es menor en clientes que se dieron de baja.  
- Los métodos de pago electrónicos muestran mayor asociación con churn.  

## Conclusiones e Insights
- La evasión está más relacionada con factores contractuales y de uso que con variables demográficas.  
- Los primeros meses de servicio son críticos para la retención.  
- El gasto total y mensual son indicadores clave para identificar clientes en riesgo.  

## Recomendaciones
- Incentivar contratos de mayor duración con beneficios adicionales.  
- Implementar programas de fidelización temprana para clientes nuevos.  
- Revisar métodos de pago y ofrecer alternativas más convenientes.  
- Segmentar clientes con bajo gasto total y ofrecer promociones personalizadas.  

---

**Este README resume el proyecto y facilita su comprensión para otros analistas, desarrolladores o directivos.**
