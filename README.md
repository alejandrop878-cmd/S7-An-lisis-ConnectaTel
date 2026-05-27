# Análisis ConnectaTel – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.

Este proyecto consiste en un análisis ejecutivo y exploratorio de datos (EDA) para **ConnectaTel**, una compañía de telecomunicaciones con operaciones en México y Colombia. El objetivo principal es identificar patrones de uso, detectar comportamientos atípicos y comprender qué segmentos de clientes muestran necesidades diferenciadas, con el fin de optimizar la oferta comercial y mejorar la experiencia del usuario.

## 📂 Dataset del proyecto

- **plans.csv:** los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
- **users_latam.csv:** información de clientes: edad, ciudad, fecha de registro, plan contratado.
- **usage.csv:** el detalle de uso real: llamadas (duración) y mensajes (longitud).

## 💡 Preguntas del negocio

- ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
- ¿Qué usuarios presentan valores atípicos que puedan indicar comportamientos inusuales, fraude o errores de registro?
- ¿Cómo varía el uso según la edad y el tipo de plan contratado?
- ¿Qué patrones pueden ayudar a diseñar mejores planes, optimizar la oferta y mejorar la satisfacción del cliente?

## 📋 Estructura del Proyecto

El análisis se divide en tres fases críticas:
1. **Limpieza y Calidad de Datos:** Identificación y tratamiento de valores nulos, inconsistencias temporales y valores sentinels.
2. **Segmentación de Clientes:** Análisis del comportamiento según variables biológicas (edad) y niveles de uso (mensajes, llamadas y minutos).
3. **Implicaciones de Negocio y Recomendaciones:** Modelos de ofertas comerciales basados en patrones de consumo extremo (*outliers*).

## 🛠️ Tecnologías Utilizadas

*   **Python** 🐍
*   **Pandas** (Limpieza, manipulación de estructuras de datos y detección de nulos/centinelas)
*   **Matplotlib & Seaborn** (Visualización de distribuciones estadísticas e identificación visual de *outliers*)
*   **Jupyter Notebooks** (Entorno de desarrollo e investigación)

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alejandrop878-cmd/S7-analysis-ConnectaTel/blob/main/TU_NOTEBOOK.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**
