# Análisis AB Testing - Cookie Cats

Este repositorio contiene un análisis AB Testing sobre el juego **Cookie Cats**, evaluando el impacto de dos versiones del juego (gate_30 y gate_40) en la retención de jugadores.

## Gráficos de Análisis AB Testing

### Retención 1 día
![Retención 1 día](images/retention_1day.png)

El gráfico muestra la proporción de jugadores retenidos un día después de instalar el juego, comparando ambas versiones. Esto nos permite evaluar si el cambio de nivel del "gate" afecta la retención temprana.

### Retención 7 días
![Retención 7 días](images/retention_7day.png)

Aquí se observa la retención a los 7 días, un indicador de retención a mediano plazo. Las diferencias pueden sugerir el impacto en la experiencia del jugador.

### Distribución de niveles jugados
![Distribución de niveles jugados](images/levels_played_distribution.png)

Este histograma muestra cuántos niveles jugaron los usuarios antes de abandonar el juego, comparando ambas versiones.

## Conclusiones
- Se realizaron pruebas estadísticas (t-test) para comparar las tasas de retención entre versiones.
- Los resultados ayudan a tomar decisiones sobre el diseño del juego y el lugar óptimo para colocar el "gate".
