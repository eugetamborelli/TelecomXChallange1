# TelecomXChallange1
Este repositorio contiene una notebook de colab con el desafío Telecom X , parte 1 para el programa Oracle Next Education.
# 📊 TelecomX – Análisis de Evasión de Clientes (Churn)

## 📌 Descripción del Proyecto
Este proyecto forma parte del **Telecom Challenge – Parte 1** del curso de *Data Analysis* de Oracle Next Education.  
El objetivo es analizar los datos de clientes de **Telecom X** para identificar patrones y factores que influyen en la evasión (**churn**) y proponer recomendaciones estratégicas para reducirla.

---

## 📂 Organización de la Notebook
La notebook está dividida en las siguientes secciones:

1. **Importación de Datos**
   - Carga del dataset en formato JSON desde GitHub.
   - Conversión a DataFrame de Pandas y aplanado de columnas anidadas.

2. **Limpieza y Tratamiento**
   - Eliminación de valores nulos y registros inválidos.
   - Conversión de variables categóricas a formato binario.
   - Creación de nuevas columnas (`Cobro_Diario`).

3. **Análisis Exploratorio de Datos (EDA)**
   - Distribución de la evasión.
   - Análisis por variables categóricas y numéricas.
   - Cálculo de métricas descriptivas.

4. **Conclusiones e Insights**
   - Resumen de hallazgos y patrones detectados.

5. **Recomendaciones**
   - Estrategias propuestas para reducir la evasión de clientes.

---

## ▶️ Instrucciones de Ejecución
1. Abrir el archivo `.ipynb` en **Google Colab** o en un entorno local con Jupyter Notebook.
2. Asegurarse de tener instaladas las librerías necesarias:
   ```bash
   pip install pandas requests
