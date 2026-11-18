<img width="1280" height="640" alt="WhatsApp Image 2026-11-17 at 3 00 46 PM (5)" src="https://github.com/user-attachments/assets/4bc7372e-11c8-49e6-8354-216775f1b54e" />

# 🎮 Análisis del Mercado Global de Videojuegos (Ice)

## 📋 Descripción
**Ice** es una tienda online dedicada a la comercialización de videojuegos en diferentes mercados internacionales. La empresa dispone de información histórica sobre ventas, plataformas, géneros, reseñas de usuarios y críticos profesionales, así como clasificaciones ESRB.

El objetivo de este proyecto fue identificar los factores asociados al éxito comercial de un videojuego y detectar patrones que puedan utilizarse para planificar campañas publicitarias más efectivas. Para ello, se analizaron datos históricos hasta 2016 con el fin de generar recomendaciones orientadas a la toma de decisiones estratégicas para 2017.

## 🎯 Objetivos
- ✅ Evaluar la calidad, consistencia e integridad de los datos disponibles.
- ✅ Analizar la evolución histórica global de las ventas de videojuegos.
- ✅ Identificar las plataformas con mejor desempeño comercial en el mercado.
- ✅ Estudiar el ciclo de vida y transición de las plataformas de videojuegos.
- ✅ Analizar la relación e impacto entre las reseñas (críticos y usuarios) y las ventas.
- ✅ Identificar los géneros más rentables y populares.
- ✅ Construir perfiles de consumo detallados para diferentes regiones (Norteamérica, Europa y Japón).
- ✅ Evaluar el impacto de las clasificaciones ESRB sobre las ventas.
- ✅ Validar hipótesis mediante pruebas estadísticas.
- ✅ Generar recomendaciones de negocio orientadas a optimizar futuras campañas de marketing.

## 🛠️ Herramientas y Habilidades Utilizadas
* **Lenguaje:** Python
* **Librerías:** Pandas, NumPy, Matplotlib, Seaborn y SciPy
* **Entorno:** Jupyter Notebook
* **Técnicas:** Análisis Exploratorio de Datos (EDA), Estadística descriptiva, Pruebas de hipótesis estadísticas y Visualización avanzada de datos.

## 📊 Fuente de Datos
El proyecto utiliza información histórica de videojuegos comercializados en distintas plataformas y mercados internacionales:
* **Archivo utilizado:** `games.csv`
* **Variables principales:** `name`, `platform`, `year_of_release`, `genre`, `na_sales`, `eu_sales`, `jp_sales`, `other_sales`, `critic_score`, `user_score`, `rating`.

## ⚙️ Metodología
1. **Preparación de datos:** Revisión general del dataset, estandarización de nombres de columnas, conversión de tipos de datos, tratamiento de valores ausentes, análisis de duplicados y creación de la variable analítica `total_sales`.
2. **Análisis exploratorio:** Estudio de las ventas globales por año, evolución del mercado y tendencias recientes.
3. **Análisis de plataformas:** Identificación de líderes de mercado, evolución anual, comparación mediante diagramas de caja y detección de plataformas con potencial para 2017.
4. **Influencia de las reseñas:** Evaluación mediante diagramas de dispersión y correlaciones estadísticas entre las calificaciones de críticos/usuarios y el volumen de ventas.
5. **Análisis de géneros:** Distribución de títulos por género, rentabilidad y comparación de ventas entre categorías.
6. **Perfil regional de usuario:** Estudio de preferencias de plataformas, géneros e impacto de clasificaciones ESRB en Norteamérica (NA), Europa (UE) y Japón (JP).
7. **Pruebas estadísticas:** Evaluación de hipótesis sobre diferencias en calificaciones promedio de usuarios entre plataformas y géneros.

## 💡 Principales Hallazgos
* **Evolución del mercado:** La industria experimentó un crecimiento sostenido hasta alcanzar un pico de ventas entre 2008 y 2009, seguido de una disminución gradual posterior a 2010.
* **Plataformas líderes:** Las consolas con mayores ventas en el período relevante fueron **PS4, PS3, Xbox 360, Nintendo 3DS y Xbox One**.
* **Ciclo de vida:** Mientras PS3 y Xbox 360 entraron en una clara fase de declive, PS4 y Xbox One se consolidaron como las plataformas de nueva generación con mayor proyección.
* **Reseñas vs. Ventas:** 
  * Se confirmó una **relación positiva** entre las calificaciones de los críticos y las ventas (los títulos mejor valorados registraron mejor desempeño).
  * La correlación con las reseñas de usuarios fue prácticamente nula (`-0.032`), lo que indica que la opinión de los usuarios no predice de forma confiable el éxito comercial.
* **Diferencias regionales:**
  * **Norteamérica y Europa:** Marcado predominio de PlayStation/Xbox y preferencia por géneros de Acción y Deportes.
  * **Japón:** Fuerte inclinación hacia plataformas portátiles y géneros específicos del mercado local.

## 🧪 Resultados de las Pruebas Estadísticas
- **Calificaciones de usuarios (Xbox One vs. PC):** Se evaluó si las medias de puntuación son iguales para entender el comportamiento de los jugadores en ambas plataformas.
- **Calificaciones por género (Acción vs. Deportes):** Se analizaron las diferencias en la valoración de los usuarios entre ambas categorías comerciales.

## 📈 Visualizaciones Desarrolladas
* Ventas globales por año y evolución histórica del mercado.
* Comparación de plataformas líderes y diagramas de caja de ventas.
* Gráficos de dispersión y análisis de correlación entre calificaciones (críticos/usuarios) y ventas.
* Distribución de géneros y comparativas de consumo por región (NA, EU, JP).

## 📂 Archivos Principales
* `zeta_video_game_market_analysis.ipynb`
* `games.csv`

## 🏁 Conclusión
El análisis permitió identificar patrones clave en la industria global de videojuegos y los factores determinantes del éxito comercial. El mercado mostró una transición generacional clara hacia **PS4** y **Xbox One**. Dado que las valoraciones de los críticos influyen positivamente en las ventas —mientras que las de los usuarios tienen un impacto marginal— y existen marcadas diferencias regionales, se recomienda enfocar las campañas publicitarias y de marketing para 2017 en plataformas con alto potencial como **PlayStation 4, Xbox One, Nintendo 3DS y PC**.
