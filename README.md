# Dashboard de Presupuestos de Viaje: Análisis Comparativo España 🇪🇸

Este proyecto es un dashboard interactivo diseñado para visualizar y comparar presupuestos de viaje entre ciudades españolas (Madrid vs Sevilla, Madrid vs Valencia), basado en informes generados por múltiples modelos de Inteligencia Artificial (GPT, Gemini, Manus, Perplexity).

## 🚀 Ver Online

**[Madrid vs Sevilla](https://hackbug38.github.io/An-lisis-de-Informes-IA/)** | **[Madrid vs Valencia](https://hackbug38.github.io/An-lisis-de-Informes-IA/index_madrid_valencia.html)** | **[Alojamiento Detallado](https://hackbug38.github.io/An-lisis-de-Informes-IA/alojamiento_detallado.html)** | **[Alojamiento Seleccionado](https://hackbug38.github.io/An-lisis-de-Informes-IA/alojamiento_seleccionado.html)**

## 🎯 Comparativas Disponibles

### 1. **Madrid vs Sevilla** (`index.html`)

Análisis para viaje de un mes (2 adultos mayores) desde Pekín con enfoque en experiencia cultural y costos de vida.

**Consenso IA:** 🏆 **Sevilla** (3 de 4 modelos)

- Mejor relación calidad-precio
- Alojamiento más económico
- Costo de vida 6% menor

### 2. **Madrid vs Valencia** (`index_madrid_valencia.html`)

Análisis detallado para adultos mayores con énfasis en seguridad logística y accesibilidad.

**Consenso IA:** 🏆 **Madrid** (3 de 4 modelos)

- Vuelo directo desde Pekín (Air China)
- Mejor conectividad para perfil senior
- Transporte público gratuito para +65 años

## 📋 Funcionalidades

- **Comparativa de Costos**: Visualización clara de los costos totales estimados por cada IA con gráficos interactivos.
- **Desglose Detallado**:
  - ✈️ **Vuelos**: Opciones de rutas desde Pekín con **precios por persona** y **total para 2 personas** claramente identificados.
  - 🏠 **Alojamiento**: Comparativa entre estudios, Airbnb y alquileres con **precio mensual total para 2 personas**.
  - 🍽️ **Vida y Gastos**: Costos de alimentación, transporte, amenidades culturales y otros con desglose completo.
- **Selector de Moneda**: Alterna instantáneamente entre **Euros (€)** y **Dólares ($)** con conversión automática en todas las secciones (tasa de cambio: 1 EUR = 1.05 USD).
- **Vista de Comparación**: Nueva pestaña "Comparar" que permite visualizar categorías específicas (vuelos, alojamiento, vida, otros) lado a lado entre modelos.
- **Análisis de IA**: Resúmenes, recomendaciones y citas clave de cada modelo con contexto específico.
- **Fuentes**: Enlaces directos a las referencias utilizadas (Skyscanner, Airbnb, Numbeo, Idealista, etc.).

## ✨ Características Técnicas

- **Estructura de Datos Pura**: Todos los precios se almacenan como números puros con campo de moneda, eliminando bugs de formateo.
- **Conversión Automática**: El toggle EUR/USD convierte todos los precios en tiempo real respetando la moneda original del dato.
- **Etiquetas Explícitas "2 personas"**:
  - Vuelos: "Precio por persona: €XXX" y "Total 2 personas: €XXX"
  - Alojamiento: "Precio mensual (Total 2 personas): €XXX"
  - Vida y Gastos: "Costos mensuales (Total 2 personas)"
- **Validación de Datos**:
  - ✅ Todos los valores verificados contra informes originales
  - ✅ Corrección de discrepancias en datos de Gemini (Madrid-Valencia)
  - ✅ Trazabilidad completa con referencias a líneas de archivos fuente

## 🔍 Proceso de Validación

El proyecto incluye un proceso riguroso de validación de datos:

1. **Extracción Manual**: Datos extraídos directamente de informes PDF/TXT de cada IA
2. **Verificación Cruzada**: Comparación sistemática HTML vs archivos fuente
3. **Corrección de Discrepancias**:
   - **Caso Gemini (Madrid-Valencia)**: Totales corregidos de €5,250/€4,790 a **€6,000/€5,550** según documento fuente (líneas 168 + 52)
4. **Documentación**: Cada valor incluye comentarios con referencias a archivos fuente

## 🛠️ Tecnologías

- **HTML5 & CSS3**: Diseño moderno, responsivo y con animaciones suaves (Glassmorphism).
- **JavaScript (Vanilla)**: Lógica para el cambio de pestañas, conversión de moneda, comparación entre categorías y renderizado dinámico.
- **Chart.js**: Gráficos de barras interactivos con colores temáticos por ciudad.
- **Google Fonts**: Tipografía Outfit para mejor legibilidad.

## 📂 Estructura del Proyecto

```bash
.
├── index.html                          # Madrid vs Sevilla
├── index_madrid_valencia.html          # Madrid vs Valencia
├── alojamiento_detallado.html          # Alojamiento Detallado (Multi-fuente)
├── alojamiento_seleccionado.html       # Alojamiento Seleccionado (Panel Personalizado)
├── README.md                           # Este archivo
├── Comparación viaje Madrid Sevilla GPT II.txt
├── Comparación viaje Madrid Sevilla Gemini.txt
├── Comparación viaje Madrid Sevilla Manus II.txt
├── Comparación viaje Madrid Sevilla Perplexity.txt
├── Madrid-Valencia GPT.txt
├── Madrid-Valencia Gemini.txt
├── Madrid vs. Valencia-Manus.md
└── Madrid-Valencia Perplexity.md
```

## 🎨 Diseño

El dashboard utiliza un diseño moderno con:

- **Glassmorphism**: Tarjetas con efecto cristal y blur
- **Gradientes**: Acentos con colores temáticos (azul para Madrid, verde para Valencia/Sevilla)
- **Responsivo**: Adaptable a móviles, tablets y escritorio
- **Dark Theme**: Esquema oscuro para reducir fatiga visual
- **Animaciones suaves**: Transiciones y efectos hover para mejor UX

## 📊 Modelos de IA Analizados

### GPT-4

- Enfoque en datos estructurados y matriz de decisión cuantitativa
- Análisis detallado de opciones de vuelos y alojamiento
- Recomendaciones basadas en ratios costo/beneficio

### Gemini

- Análisis profundo de seguridad logística para perfil senior
- Énfasis en vuelos directos y minimización de riesgos
- Presupuestos con margen de imprevistos del 15%

### Manus

- Perspectiva práctica con enfoque en transporte público gratuito
- Cálculos optimizados para adultos mayores (+65 años)
- Recomendaciones considerando beneficios por edad

### Perplexity

- Desglose más detallado con múltiples fuentes verificadas
- Análisis comparativo exhaustivo ciudad por ciudad
- Puntuaciones ponderadas y matrices de decisión

## ✨ Cambios Recientes

### Revisión de Enlaces de Alojamiento

- Se identificaron **23 alojamientos** distribuidos entre 3 fuentes: GPT, Comet y Manus.
- Se validaron los enlaces de Airbnb, Booking y otras plataformas.
- Se documentaron inconsistencias en plataformas y enlaces rotos en `REVISION_ENLACES_ALOJAMIENTOS.md`.

### Actualización de `alojamiento_detallado.html`

- Se añadió soporte para alternar entre fuentes de datos (GPT, Comet, Manus).
- Se implementó un selector de moneda con conversión automática (EUR/USD).
- Se mejoró la visualización de resultados con paginación y orden por precio.

### Implementación de Panel de Selección Personalizada (`alojamiento_seleccionado.html`)

- Se creó un nuevo tablero para la selección manual y comparación de alojamientos específicos.
- Se añadieron **12 alojamientos seleccionados** con detalles de accesibilidad y precios unificados.
- Se implementó una **función de ordenación dinámica por precio** (menor a mayor).
- Se integró soporte multi-moneda (EUR/USD) sincronizado con el renderizado dinámico.

## 🚀 Uso Local

Para ejecutar el proyecto localmente:

```bash
# Clonar el repositorio
git clone https://github.com/hackbug38/An-lisis-de-Informes-IA.git

# Navegar al directorio
cd An-lisis-de-Informes-IA

# Abrir con un servidor local (opcional)
# Con Python 3:
python -m http.server 8000

# Con Node.js:
npx http-server

# O simplemente abrir index.html en tu navegador
```

Accede a:

- Madrid vs Sevilla: `http://localhost:8000/index.html`
- Madrid vs Valencia: `http://localhost:8000/index_madrid_valencia.html`
- Alojamiento Detallado: `http://localhost:8000/alojamiento_detallado.html`
- Alojamiento Seleccionado: `http://localhost:8000/alojamiento_seleccionado.html`

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Para cambios importantes:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Notas sobre Datos

- Los precios de vuelos pueden variar significativamente según temporada y anticipación de compra
- Los costos de alojamiento son estimados basados en promedios de mercado (abril-mayo 2025)
- El tipo de cambio EUR/USD (1.05) es referencial y debe verificarse al momento del viaje
- Los beneficios de transporte para +65 años requieren acreditación en cada ciudad

## 📄 Licencia

Este proyecto es de código abierto y está disponible bajo la [Licencia MIT](LICENSE).

### hackbug38

- GitHub: [@hackbug38](https://github.com/hackbug38)
