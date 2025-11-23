# Dashboard de Presupuestos de Viaje: Madrid vs Sevilla 🇪🇸

Este proyecto es un dashboard interactivo diseñado para visualizar y comparar presupuestos de viaje entre Madrid y Sevilla, basado en informes generados por múltiples modelos de Inteligencia Artificial (GPT, Gemini, Manus, Perplexity).

## 🚀 Ver Online

**[Acceder al Dashboard en Vivo](https://hackbug38.github.io/An-lisis-de-Informes-IA/)**

## 📋 Funcionalidades

* **Comparativa de Costos**: Visualización clara de los costos totales estimados por cada IA.
* **Desglose Detallado**:
  * ✈️ **Vuelos**: Opciones de rutas desde Pekín con **precios por persona** y **total para 2 personas** claramente identificados.
  * 🏠 **Alojamiento**: Comparativa entre Airbnb, hoteles y alquileres tradicionales con **precio mensual** explícito.
  * 🍽️ **Vida y Gastos**: Costos de alimentación, transporte y ocio con desglose detallado.
* **Selector de Moneda**: Alterna instantáneamente entre **Euros (€)** y **Dólares ($)** con conversión automática en todas las secciones (tasa de cambio: 1 EUR = 1.05 USD).
* **Análisis de IA**: Resúmenes, recomendaciones y citas clave de cada modelo.
* **Fuentes**: Enlaces directos a las referencias utilizadas (Skyscanner, Airbnb, Numbeo, etc.).

## ✨ Características Técnicas

* **Estructura de Datos Pura**: Todos los precios se almacenan como números puros con campo de moneda, eliminando bugs de formateo.
* **Conversión Automática**: El toggle EUR/USD convierte todos los precios en tiempo real respetando la moneda original del dato.
* **Etiquetas Explícitas**:
  * Vuelos: "Precio por persona" y "Total 2 personas"
  * Alojamiento: "Precio mensual"
* **Validación de Datos**: Todos los valores han sido verificados contra los informes originales de cada IA.

## 🛠️ Tecnologías

* **HTML5 & CSS3**: Diseño moderno, responsivo y con animaciones suaves (Glassmorphism).
* **JavaScript (Vanilla)**: Lógica para el cambio de pestañas, conversión de moneda y renderizado dinámico de datos.
* **Chart.js**: Gráficos interactivos para la visualización de datos.

## 📂 Estructura del Proyecto

* `index.html`: El núcleo de la aplicación, contiene toda la estructura, estilos y lógica.
* Archivos `.txt`: Informes originales de cada modelo de IA (GPT, Gemini, Manus, Perplexity).
