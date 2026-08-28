# Global Video Game Market Analysis

Análisis exploratorio del mercado global de videojuegos para identificar patrones de ventas y factores relevantes para la planificación de campañas para 2017.

## Objetivo

Analizar datos históricos de ventas de videojuegos para identificar plataformas, géneros y mercados regionales relevantes, así como estudiar la relación entre las calificaciones y las ventas.

## Tecnologías y Herramientas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- GitHub

## Habilidades demostradas

- Limpieza y preparación de datos
- Análisis Exploratorio de Datos (EDA)
- Agrupación y análisis de datos con Pandas
- Visualización de datos con Matplotlib y Seaborn
- Análisis de tendencias de ventas
- Análisis de correlación
- Segmentación por regiones y géneros
- Pruebas de hipótesis estadísticas

## Análisis realizado

- Evolución de las ventas por plataforma
- Comparación de ventas típicas mediante medias, medianas y distribuciones
- Relación entre calificaciones de usuarios y críticos y las ventas globales
- Comparación de juegos multiplataforma
- Análisis de ventas por género
- Perfiles de mercado de Norteamérica, Europa y Japón
- Análisis de clasificaciones ESRB por región
- Pruebas de hipótesis

## Principales resultados

- PS4 y Xbox One se encontraron entre las plataformas con mayor actividad comercial durante 2013–2016.
- Las calificaciones de los críticos presentaron una correlación positiva moderada con las ventas globales (`r = 0.407`), mientras que las calificaciones de los usuarios mostraron una correlación prácticamente nula (`r = -0.032`).
- Platform presentó la mayor mediana de ventas por juego con 0.27 millones de unidades, seguido de Shooter con 0.24 y Sports con 0.22 millones.
- Se identificaron diferencias importantes entre los mercados de Norteamérica, Europa y Japón.
- Las pruebas estadísticas encontraron diferencias significativas entre las calificaciones promedio de usuarios de Xbox One y PC, mientras que no se encontraron diferencias estadísticamente significativas entre Action y Sports con un nivel de significancia del 5 %.

## Dataset

El proyecto utiliza el archivo `games.csv`, que contiene información histórica sobre videojuegos, plataformas, géneros, ventas regionales y globales, calificaciones de usuarios y críticos, y clasificaciones ESRB.

## Estructura del proyecto

```text
.
├── README.md
├── games.csv
└── global_video_game_market_analysis.ipynb
```

## Conclusión

El análisis muestra que el potencial comercial de un videojuego no depende de un único factor. La evolución reciente de las plataformas, el género, las preferencias regionales y la recepción de la crítica aportan información relevante para orientar decisiones de mercado y la planificación de campañas para 2017.
