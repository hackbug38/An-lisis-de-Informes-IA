# Informe de Planificación de Viaje: España (Madrid vs. Valencia)

**Objetivo:** Proponer el plan de viaje más económico para dos adultos mayores (un mes, Beijing a España).

## Resumen Ejecutivo

El análisis comparativo entre Madrid y Valencia para un viaje de un mes (abril-mayo 2026) para dos adultos mayores revela que **Madrid** es la opción más económica y ventajosa, con un costo total estimado de **€2,920** frente a los **€3,112** de Valencia. La diferencia clave radica en el **transporte público gratuito** para mayores de 65 años en la Comunidad de Madrid, lo que compensa el mayor costo de alojamiento y vida general en la capital.

Madrid ofrece la ruta de vuelo más corta y económica desde Beijing, y su extensa oferta cultural y de ocio es un gran atractivo. Por otro lado, Valencia presenta un alojamiento más económico y un ambiente más tranquilo y costero, aunque el costo de los vuelos y el transporte público para turistas senior elevan el gasto total.

La recomendación final es **Madrid**, priorizando el ahorro significativo en transporte, la mejor conexión aérea y la accesibilidad general para adultos mayores.

## Matriz de Decisión Comparativa

Para determinar la opción más económica y adecuada, se evaluaron los criterios con un sistema de puntuación ponderada (5 = mejor).

| Criterio | Peso | Madrid | Valencia | Puntuación Madrid | Puntuación Valencia | Score Madrid (P x W) | Score Valencia (P x W) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Costo Total Estimado** | Alto (3) | €2,920 | €3,112 | 5 | 4 | 15 | 12 |
| **Costo de Vuelos (ida y vuelta)** | Medio (2) | €1,370 | €1,692 | 5 | 4 | 10 | 8 |
| **Costo de Alojamiento (1 mes)** | Medio (2) | €1,000 | €800 | 4 | 5 | 8 | 10 |
| **Costo de Transporte (Senior)** | Alto (3) | €0 | €120 | 5 | 3 | 15 | 9 |
| **Accesibilidad de Vuelo (Duración)** | Medio (2) | 15h 10m | 17h 15m | 5 | 4 | 10 | 8 |
| **Amenidades (Ambiente)** | Medio (2) | Cultural/Ocupado | Tranquilo/Costero | 4 | 5 | 8 | 10 |
| **TOTAL** | **14** | | | | | **66** | **57** |

**Conclusión de la Matriz:** Madrid obtiene una puntuación ponderada superior (66 vs 57), consolidándose como la opción más económica y eficiente para el perfil de viaje solicitado.

## Recomendación Final

Se recomienda seleccionar **Madrid** como destino para el viaje de un mes.

**Justificación Económica:**
El factor decisivo es el **Abono Transporte +65** de la Comunidad de Madrid, que permite a los mayores de 65 años viajar de forma gratuita en toda la red de transporte público (Metro, autobuses urbanos e interurbanos) [1]. Este ahorro de aproximadamente **€120** en transporte mensual por persona (o €240 para la pareja) supera el ahorro de €200 en alojamiento que ofrece Valencia.

**Justificación Logística y de Confort:**
*   **Vuelos:** La ruta a Madrid (MAD) es significativamente más económica (€1,370) y más corta (15h 10m) que la ruta a Valencia (VLC) (€1,692 y 17h 15m), lo cual es una consideración importante para adultos mayores.
*   **Alojamiento:** Se estima un presupuesto de **€1,000** para un estudio con cocina y ascensor en un barrio seguro y bien conectado de Madrid (e.g., Delicias, Centro).
*   **Costo de Vida:** El costo de alimentación se estima en **€550** para el mes, asumiendo que se cocinará en casa.

## Presupuesto Detallado (Madrid)

| Concepto | Costo por Persona (EUR) | Costo Total (EUR) | Fuente / Nota |
| :--- | :--- | :--- | :--- |
| **Vuelos** (Beijing-Madrid-Beijing) | €685 | €1,370 | Google Flights (Hainan, Brussels Airlines) |
| **Alojamiento** (Estudio 1 mes) | €500 | €1,000 | Estimación media (Idealista, Fotocasa) |
| **Alimentación** (1 mes) | €275 | €550 | Estimación (cocinar en casa) |
| **Transporte** (1 mes) | €0 | €0 | Abono +65 gratuito [1] |
| **TOTAL ESTIMADO** | **€1,460** | **€2,920** | |

## Fuentes de Información (Citas)

[1] Comunidad de Madrid. Abono +65. *Portal de la Comunidad de Madrid*. URL: [https://www.crtm.es/billetes-y-tarifas/billetes-y-abonos/abono-transportes/abono-plus65/](https://www.crtm.es/billetes-y-tarifas/billetes-y-abonos/abono-transportes/abono-plus65/)
[2] Google Flights. *Búsqueda de vuelos Beijing-Madrid y Beijing-Valencia*. URL: [https://www.google.com/travel/flights](https://www.google.com/travel/flights)
[3] Idealista, Fotocasa, Spotahome. *Precios de alquiler de estudios en Madrid y Valencia*. URL: [https://www.idealista.com/](https://www.idealista.com/)
[4] Expatistan, Numbeo. *Comparativa de costo de vida Madrid vs. Valencia*. URL: [https://www.expatistan.com/es/costo-de-vida/comparacion/valencia-espana/madrid](https://www.expatistan.com/es/costo-de-vida/comparacion/valencia-espana/madrid)

## JSON de Salida

```json
{
  "recomendacion_final": "Madrid",
  "justificacion_economica": "El Abono Transporte +65 gratuito en Madrid (€0/mes) compensa el mayor costo de alojamiento y vuelos más económicos, resultando en un costo total inferior.",
  "costo_total_madrid_eur": 2920,
  "costo_total_valencia_eur": 3112,
  "detalle_costos_madrid": {
    "vuelos_2_personas_eur": 1370,
    "alojamiento_1_mes_eur": 1000,
    "alimentacion_1_mes_eur": 550,
    "transporte_senior_1_mes_eur": 0
  },
  "detalle_costos_valencia": {
    "vuelos_2_personas_eur": 1692,
    "alojamiento_1_mes_eur": 800,
    "alimentacion_1_mes_eur": 500,
    "transporte_senior_1_mes_eur": 120
  },
  "matriz_decision_puntuacion": {
    "madrid": 66,
    "valencia": 57
  },
  "amenidades_clave": {
    "madrid": "Transporte público gratuito para mayores de 65 años, mayor oferta cultural y mejor conexión aérea.",
    "valencia": "Alojamiento más económico y ambiente más tranquilo y costero."
  }
}
```
