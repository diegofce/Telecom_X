# 📊 Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte de un desafío para analizar la tasa de cancelación de clientes en **Telecom X**, utilizando herramientas de análisis de datos en Python. El objetivo principal fue identificar patrones asociados al churn, limpiar y transformar los datos, generar visualizaciones estratégicas e interpretar insights relevantes que puedan informar decisiones futuras en la empresa.

---

## 📁 Contenido

- `telecomx_churn_limpio.csv`: Dataset procesado y listo para modelos y visualización.
- `notebook.ipynb`: Notebook con el código completo, visualizaciones e informe.
- `README.md`: Este documento.

---

## 🧰 Tecnologías utilizadas

- Python 3.x
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly Express
- Google Colab / Jupyter Notebook
- Git para control de versiones

---

## 🚀 Objetivos del Proyecto

- Importar datos desde una API (archivo JSON en GitHub).
- Aplicar procesos ETL para limpieza y transformación de datos.
- Realizar un análisis exploratorio (EDA) visual y estadístico.
- Detectar correlaciones entre características y churn.
- Comunicar hallazgos a través de informes y gráficos.

---

## 📦 Proceso de análisis

### 1. Extracción y carga de datos
Los datos fueron extraídos desde una API pública en formato JSON, luego normalizados y estandarizados.

### 2. Limpieza de datos
- Eliminación de duplicados.
- Manejo de valores nulos y vacíos.
- Conversión de columnas categóricas (`sí/no`) a binarios (1/0).
- Unificación de formato y nombres (`snake_case`, `.lower()`).

### 3. Análisis Exploratorio (EDA)
- Distribución general de churn.
- Recuento de evasión por variables categóricas y numéricas.
- Visualizaciones con histogramas, gráficos de dispersión y boxplots.

### 4. Correlaciones adicionales
Se analizó la relación entre variables como `total_services`, `charges_monthly` y `tenure` con respecto al churn.

---

## 📈 Principales Insights

- **Los contratos mensuales** tienen mayor tasa de cancelación.
- Clientes con **baja antigüedad** (tenure) y múltiples servicios presentan mayor probabilidad de churn.
- Métodos de pago como **débito automático** pueden estar asociados a mayor evasión.
- Variables como `charges_monthly` y `total_services` muestran correlación significativa con churn.
![Gráfico de distribución de Tenure](/Imagenes/distribucion.png)
![Gráfico de distribución de Evasión](/Imagenes/evasion.png)


---

## ✅ Recomendaciones

1. Incentivar contratos de largo plazo con beneficios exclusivos.
2. Reforzar la experiencia de pago y atención en los primeros meses del cliente.
3. Implementar campañas de fidelización en segmentos vulnerables.
4. Desarrollar modelos predictivos supervisados con estas variables como input.

---

## 📚 Créditos

Este proyecto fue desarrollado por **Diego F Chacón** como parte del curso de análisis de datos. El desafío fue proporcionado por [Alura LATAM](https://www.aluracursos.com/) y ejecutado en entornos colaborativos con herramientas modernas de ciencia de datos.

---

## 📎 Licencia

Este proyecto es de uso académico y formativo. Los datos fueron extraídos de fuentes públicas con fines educativos.
