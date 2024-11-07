# 🎮 Análisis de ventas de videojuegos

## Descripción del Proyecto

Este proyecto analiza los datos históricos de ventas de videojuegos, con información sobre plataformas, géneros, ventas por región, reseñas de usuarios y críticos, y clasificaciones de la ESRB. El objetivo es identificar patrones que permitan predecir qué juegos tienen más éxito y, con esta información, planificar campañas publicitarias eficaces para el año 2017.

## Objetivos
El análisis incluye la preparación, limpieza y transformación de los datos, junto con un examen detallado de las ventas por plataforma y género, las variaciones en diferentes regiones y la influencia de las reseñas en las ventas. Además, se llevan a cabo pruebas de hipótesis para comparar las calificaciones de usuarios entre plataformas y géneros.
- Identificar patrones de éxito en videojuegos
- Predecir tendencias de ventas
- Optimizar campañas publicitarias
- Analizar el impacto de las reseñas
- Estudiar diferencias regionales en preferencias de videojuegos
- Realizar pruebas de hipótesis sobre calificaciones de usuarios:
  
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

## Herramientas utilizadas
- **Python**: pandas, stats (scipy), matplotlib.
- **Jupyter Notebooks**: para análisis interactivo.

## Pasos de análisis
- **Descripción de los datos**: se examinan los datos iniciales en games.csv, verificando estructura, tipos de datos y posibles problemas como valores ausentes o datos incorrectos.
- **Preprocesamiento de datos**: se normalizan los nombres de las columnas a minúsculas, se ajustan los tipos de datos según las necesidades de análisis, se manejan los valores ausentes y se eliminan los duplicados, se calcula una columna adicional de ventas totales (sumando las ventas en todas las regiones).
- **Análisis de plataformas y lanzamientos**: se estudia la cantidad de lanzamientos por año y se identifican las plataformas más populares, se seleccionan plataformas de interés para el periodo de análisis y se examinan las tendencias de crecimiento o disminución.
- **Distribución de géneros y ventas**: se revisa la distribución de ventas globales para cada plataforma mediante diagramas de caja, se observa la distribución de géneros para identificar los más rentables y comparar entre ellos.
- **Impacto de las reseñas en las ventas**: se analiza la relación entre las reseñas de usuarios y profesionales y las ventas de juegos en una plataforma específica mediante correlación y gráficos de dispersión.
- **Perfil de usuario por región (NA, UE, JP)**: se identifican las cinco principales plataformas y géneros en cada región, se estudia el impacto de la clasificación ESRB en las ventas en cada región.
- **Prueba de hipótesis**: se comparan las calificaciones promedio de los usuarios entre Xbox One y PC, y entre los géneros de Acción y Deportes, se utiliza un nivel de significancia (alfa) para validar las hipótesis y definir conclusiones.

## Conclusiones
Se concluye que existen varias tendencias y patrones en la industria de los videojuegos que pueden ser útiles para la toma de decisiones en la tienda Ice. Por ejemplo, identifiqué las plataformas y géneros más populares en diferentes regiones, así como la influencia de las reseñas en las ventas. Este proyecto proporcionó una visión general de la industria de los videojuegos y permitió identificar patrones importantes que pueden ayudar a la tienda Ice a planificar estrategias de marketing y selección de productos para el futuro.

**Nota**: Este proyecto fue desarrollado como parte de mi formación en el bootcamp de Tripleten en el área de análisis de datos.

## Visualizaciones
![juegos_año](https://github.com/user-attachments/assets/be1485a2-1b44-4391-88ff-72f88efcc42e)
![juegos](https://github.com/user-attachments/assets/5f340620-3c17-44cc-8cf4-8fa6daa23981)
![juegos_plat](https://github.com/user-attachments/assets/3ee7bc9c-63b9-4e0d-a9d2-3623be27e028)

