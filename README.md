# 🎮 Análisis de ventas de videojuegos

## Descripción del Proyecto

Este proyecto analiza los datos históricos de ventas de videojuegos, con información sobre plataformas, géneros, ventas por región, reseñas de usuarios y críticos, y clasificaciones de la ESRB. El objetivo es identificar patrones que permitan predecir qué juegos tienen más éxito y, con esta información, planificar campañas publicitarias eficaces para el año 2017.

El análisis incluye la preparación, limpieza y transformación de los datos, junto con un examen detallado de las ventas por plataforma y género, las variaciones en diferentes regiones y la influencia de las reseñas en las ventas. Además, se llevan a cabo pruebas de hipótesis para comparar las calificaciones de usuarios entre plataformas y géneros.

## Estructura del Proyecto

1. Preparación de los datos:   
2. Análisis Exploratorio de Datos (EDA):
3. Análisis de ventas por región:
4. Pruebas de hipótesis:
5. Conclusiones:
  
## Dataset

El dataset contiene las siguientes columnas:

- `name`: Nombre del juego
- `platform`: Plataforma en la que se lanzó el juego (por ejemplo, Xbox, PlayStation)
- `year_of_release`: Año de lanzamiento
- `genre`: Género del juego (por ejemplo, Acción, Deportes)
- `na_sales`: Ventas en Norteamérica (en millones de dólares)
- `eu_sales`: Ventas en Europa (en millones de dólares)
- `jp_sales`: Ventas en Japón (en millones de dólares)
- `other_sales`: Ventas en otras regiones (en millones de dólares)
- `critic_score`: Puntuación de la crítica (máximo de 100)
- `user_score`: Puntuación de los usuarios (máximo de 10)
- `rating`: Clasificación ESRB (por ejemplo, E para todos, T para adolescentes)

## Librerías necesarias

- pandas, matplotlib, scipy (para pruebas estadísticas)

## Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/video-game-sales-analysis.git
