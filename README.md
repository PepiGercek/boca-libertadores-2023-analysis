# Boca Juniors - Copa Libertadores 2023

## Pregunta central

**¿Cómo llegó Boca Juniors a la final de la Copa Libertadores 2023 sin ganar ningún partido de eliminación directa en los 90 minutos?**

Este proyecto analiza el recorrido de Boca en la Libertadores 2023 combinando estadísticas de partido, datos individuales, contexto táctico y rendimiento en definiciones por penales.

## Fuentes de datos

- FotMob
- SofaScore
- LanusStats
- El Gráfico, para el historial de penales de Sergio Romero

## Herramientas

- Python
- pandas
- matplotlib
- mplsoccer
- scipy
- LanusStats

## Principales hallazgos

- Boca redujo considerablemente su producción ofensiva entre la fase de grupos y el mata-mata.
- El equipo mostró una diferencia muy marcada según la localía: fue más dominante en la Bombonera y mucho más reactivo como visitante.
- Las series frente a Nacional, Racing y Palmeiras tuvieron desarrollos diferentes, por lo que no existió una única fórmula para llegar a los penales.
- Sergio Romero fue el factor diferencial más extraordinario de las eliminatorias: atajó 6 de 11 penales en tandas, un 54,55%.
- En el resto de las tandas de su carrera su efectividad fue del 15%.
- Usando únicamente su rendimiento histórico previo a la Copa, la probabilidad estimada de atajar al menos 6 de 11 penales fue de aproximadamente 0,348% bajo un modelo binomial.
- En comparación, Óscar Córdoba atajó 5 de 13 penales en las tandas de las Libertadores campeonas de 2000 y 2001.
- La final contra Fluminense mostró nuevamente dificultades de Boca para transformar volumen de juego en ocasiones claras, mientras el campeón fue más eficiente en momentos decisivos.

## Conclusión

Boca llegó a la final porque fue un equipo difícil de eliminar, adaptable y competitivo, capaz de resistir contextos adversos y mantenerse dentro de partidos cerrados.

Sin embargo, tuvo dificultades para transformar su juego en ventajas definitivas durante los 90 minutos.

En ese contexto, Sergio Romero se convirtió en un factor decisivo: Boca llevó tres series consecutivas hasta los penales y contó con una actuación excepcional de su arquero en las definiciones.

## Notebook

El análisis completo, incluyendo preparación de datos, métricas, visualizaciones y conclusiones, se encuentra en:

`boca_libertadores_2023_ordenado_final.ipynb`
