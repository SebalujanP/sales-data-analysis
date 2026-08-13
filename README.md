# 📊 Análisis de Ventas de Tienda Online & Dashboard Interactivo

![Streamlit App](https://sales-data-analysis-kkobbplgfvwcyxwpan458v.streamlit.app)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-FF4B4B.svg)

Análisis exploratorio de datos (EDA) y desarrollo de un dashboard interactivo sobre un dataset transaccional de e-commerce (+10.000 registros). El proyecto combina análisis estadístico en Jupyter Notebook y visualización interactiva en Streamlit para identificar fuga de ingresos y optimizar la rentabilidad del negocio.

---

## 🎯 Objetivo del Proyecto

Identificar patrones de ventas, evaluar la rentabilidad por categoría/región y detectar ineficiencias en las políticas de descuentos comerciales que afecten el margen operativo neto.

---

## 💡 Principales Hallazgos (Business Insights)

* **Impacto crítico de los descuentos excesivos:** Los descuentos iguales o superiores al **30% destruyen la rentabilidad**, generando pérdidas sistemáticas en el producto.
* **Fuga de ingresos masiva:** El **18.6% del total de transacciones (1,901 ventas)** registraron ganancia negativa debido a promociones mal estructuradas.
* **El volumen no garantiza margen:** Ciertas subcategorías de alto volumen de ventas representan un aporte marginal muy bajo o negativo al beneficio neto de la empresa.

---

## 🚀 Dashboard Interactivo (Streamlit App)

El proyecto incluye un dashboard dinámico desarrollado con **Streamlit** que permite a directivos y analistas explorar los datos en tiempo real:

* **Filtros dinámicos:** Por categoría, región geográfica y año.
* **Monitoreo de KPIs clave:** Ventas Totales, Ganancia Total, Margen de Ganancia (%), Pedidos y Transacciones con Pérdida.
* **Análisis visual:** Distribución de rentabilidad por producto, estacionalidad mensual e impacto directo de niveles de descuento.

---

## 🛠️ Stack Tecnológico

* **Lenguaje:** Python
* **Análisis de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Dashboard App:** Streamlit
* **Entorno de Desarrollo:** Jupyter Notebook, VS Code

---

## 📁 Estructura del Repositorio

```text
├── Proyecto_Analisis_de_Datos.ipynb  # Notebook con el análisis exploratorio (EDA) completo
├── app.py                             # Aplicación interactiva de Streamlit
├── samplesuperstore.csv               # Dataset transaccional
├── requirements.txt                   # Librerías y dependencias del proyecto
└── README.md                          # Documentación del proyecto
