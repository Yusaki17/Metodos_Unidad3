# Integración numérica

Proyecto educativo en HTML, CSS y JavaScript para el curso de Métodos Numéricos.

## Sesiones

- **Sesión 12:** regla del trapecio compuesto aplicada al tráfico de red.
- **Sesión 13:** regla de Simpson 1/3 compuesta aplicada al consumo energético de un centro de datos.

Los botones superiores permiten alternar entre las dos sesiones. La sesión 13 incluye validación de subintervalos pares, tabla de evaluación, análisis de convergencia para n = 2, 4, 6, 12 y 24, y exportación CSV.

## Uso

Abre `index.html` en un navegador o mediante Live Server en Visual Studio Code. No requiere instalación ni compilación. La sesión 12 utiliza Chart.js y fuentes cargadas desde Internet.

## Observación sobre la guía

Para Simpson con n = 6, la energía aproximada es 128.921195 kWh. El M = 0.45 proporcionado en la guía produce una cota de 0.015 kWh, pero no acota la cuarta derivada de la función indicada. La aplicación distingue esa cota de una cota conservadora válida y muestra el error real respecto de la integral analítica.

