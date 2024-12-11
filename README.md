# VideoGameProject
Análisis de Ventas de Videojuegos y Planificación de Campañas Publicitarias

Descripción del Proyecto

Trabajamos con datos históricos de ventas de videojuegos para identificar patrones que determinen el éxito de un juego. Este análisis permite detectar proyectos prometedores y planificar campañas publicitarias para maximizar las ventas en 2017 (considerando que nos encontramos en diciembre de 2016).

El análisis se realiza utilizando datos sobre plataformas, géneros, reseñas de usuarios y críticos, ventas regionales, y clasificaciones ESRB (como Adolescente o Adulto).

Objetivos del Proyecto
Preparación de los Datos:

Limpieza y preprocesamiento de los datos.
Manejo de valores ausentes y datos pendientes ("TBD").
Cálculo de ventas totales por juego.
Análisis Exploratorio de Datos:

Análisis de tendencias históricas en las ventas de videojuegos.
Identificación de plataformas y géneros rentables.
Evaluación de cómo las reseñas afectan las ventas.
Creación de Perfiles Regionales:

Identificación de plataformas y géneros principales en Norteamérica (NA), Europa (UE) y Japón (JP).
Evaluación del impacto de las clasificaciones ESRB en las ventas regionales.
Pruebas de Hipótesis:

Comparación de las calificaciones de usuarios entre plataformas (Xbox One vs. PC).
Comparación de las calificaciones de usuarios entre géneros (Acción vs. Deportes).
Conclusión General:

Resumen de hallazgos clave y recomendaciones para la planificación de campañas.
Descripción de los Datos
El conjunto de datos se encuentra en el archivo games.csv y contiene las siguientes columnas:

Name: Nombre del juego.
Platform: Plataforma (ej. Xbox, PlayStation).
Year_of_Release: Año de lanzamiento.
Genre: Género del juego.
NA_sales: Ventas en Norteamérica (millones de dólares).
EU_sales: Ventas en Europa (millones de dólares).
JP_sales: Ventas en Japón (millones de dólares).
Other_sales: Ventas en otras regiones (millones de dólares).
Critic_Score: Calificación de críticos (máximo 100).
User_Score: Calificación de usuarios (máximo 10).
Rating: Clasificación ESRB (ej. E, T, M).
Nota: Los datos de 2016 pueden estar incompletos.

Metodología
Paso 1: Preparación de Datos
Reemplazo de nombres de columnas: Convertir nombres a minúsculas.
Conversión de tipos de datos: Ajustar columnas a tipos adecuados.
Manejo de valores ausentes:
Identificar valores "TBD" y decidir su tratamiento.
Rellenar o descartar valores según corresponda.
Cálculo de ventas totales: Sumar las ventas regionales y almacenar en una nueva columna.
Paso 2: Análisis Exploratorio de Datos
Tendencias de lanzamiento:
Número de juegos lanzados por año.
Identificación de períodos significativos.
Plataformas y géneros rentables:
Análisis de ventas por plataforma.
Comparación de ventas promedio y tendencias de plataformas.
Identificación de géneros con mayores ventas globales.
Paso 3: Creación de Perfiles Regionales
Análisis por región (NA, UE, JP):
Identificación de las cinco principales plataformas y géneros.
Evaluación de diferencias regionales en preferencias y cuotas de mercado.
Análisis del impacto de clasificaciones ESRB en cada región.
Paso 4: Pruebas de Hipótesis
Hipótesis 1:
Calificaciones promedio de usuarios en Xbox One y PC son iguales.
Hipótesis 2:
Calificaciones promedio de usuarios en los géneros Acción y Deportes son diferentes.
Método:
Formulación de hipótesis nula y alternativa.
Prueba de hipótesis usando t-tests.
Interpretación de resultados y comparación con un umbral de significancia (
𝛼
α).
Paso 5: Conclusión General
Resumen de hallazgos clave.
Recomendaciones para campañas publicitarias y desarrollo futuro de videojuegos.