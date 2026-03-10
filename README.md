# 📞 Proyecto Telecom X: Análisis de Evasión de Clientes (Churn)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=seaborn&logoColor=white)

## 📝 Descripción del Proyecto
Este proyecto tiene como objetivo analizar el comportamiento de los clientes de la empresa **Telecom X** para identificar los factores que influyen en la cancelación de servicios (Churn). A través de técnicas de limpieza de datos, análisis exploratorio (EDA) y visualización, se proponen estrategias para mejorar la retención de clientes.

## 🛠️ Tecnologías y Librerías Utilizadas
- **Python**: Lenguaje principal.
- **Pandas**: Manipulación y limpieza de datos.
- **Requests**: Extracción de datos desde APIs externas.
- **Seaborn & Matplotlib**: Visualización de datos estadísticos.
- **JSON**: Manejo de estructuras de datos jerárquicas.

## 🧹 Proceso de Datos
1.  **Extracción**: Los datos se obtuvieron en formato JSON desde una fuente externa.
2.  **Transformación**: Se normalizaron estructuras anidadas y se estandarizaron nombres de columnas.
3.  **Limpieza**: Gestión de valores nulos, eliminación de espacios en blanco y tratamiento de tipos de datos (conversión de texto a numérico).
4.  **Feature Engineering**: Creación de nuevas métricas como el total de servicios contratados.

## 📊 Hallazgos Clave (Insights)
*   **Contratos**: Los clientes con contratos mes a mes tienen una tasa de evasión significativamente más alta en comparación con contratos anuales.
*   **Antigüedad (Tenure)**: Existe una correlación negativa entre la permanencia y el churn; los clientes nuevos son los más propensos a irse.
*   **Servicios**: Los clientes con menos servicios contratados presentan mayor riesgo de cancelación.
*   **Cargos**: Cargos mensuales elevados actúan como un factor de presión para el abandono del servicio.

## 🚀 Recomendaciones Estratégicas
*   Implementar planes de fidelización para convertir clientes de contrato mensual a anual.
*   Crear programas de "Onboarding" u ofertas especiales para clientes en sus primeros 6 meses.
*   Optimizar la experiencia de usuario en los métodos de pago que muestran mayor fricción.
*   Utilizar los datos procesados para entrenar un modelo de Machine Learning que prediga el churn de forma proactiva.

---
*Proyecto desarrollado como parte del análisis de retención de clientes de Telecom X.*
