# 🎮 Análisis de Mercado para la Tienda Online "Ice"

### 📊 Descripción del Proyecto
Este proyecto analiza datos históricos de ventas de videojuegos, reseñas de expertos y usuarios, y clasificaciones de edad (ESRB) hasta el año 2016. El objetivo es identificar patrones que determinen el éxito de un videojuego para optimizar la planificación de la campaña publicitaria de 2017.

### 🎯 Objetivos
* Identificar las plataformas líderes y sus ciclos de vida.
* Analizar la correlación entre las puntuaciones de críticos/usuarios y las ventas globales.
* Crear perfiles de usuario por región (Norteamérica, Europa y Japón).
* Probar hipótesis estadísticas sobre las calificaciones de los usuarios en diferentes plataformas y géneros.

### 🛠️ Tech Stack
* **Python:** Pandas para limpieza de datos y NumPy para cálculos.
* **Visualización:** Matplotlib y Seaborn para mapas de calor, diagramas de caja (boxplots) y gráficos de dispersión.
* **Estadística:** Pruebas T de Student para comparación de medias independientes.

### 🔬 Hallazgos y Análisis Estadístico
El análisis incluyó la validación de dos hipótesis principales utilizando un nivel de significancia ($\alpha$) de 0.05:

1. **Hipótesis 1:** Las calificaciones promedio de los usuarios para las plataformas Xbox One y PC son las mismas.
  * **Resultado:** No existe diferencia estadísticamente significativa entre las calificaciones.
2. **Hipótesis 2:** Las calificaciones promedio de los usuarios para los géneros de Acción y Deportes son diferentes.
  * **Resultado:** Las calificaciones promedio son estadísticamente diferentes.

🌎**Resultados del Análisis Regional:**
* **NA & EU:** Dominio de consolas como PS4 y Xbox One, con preferencia por géneros de Disparos (Shooters) y Acción.
* **JP:** Mercado único liderado por consolas portátiles (3DS) y una marcada preferencia por los juegos de Rol (RPG).

### 📈 Recomendaciones Estratégicas para 2017
* **Mercado Occidental:** Centrar la inversión publicitaria en títulos de género *Shooter* para PS4 y Xbox One, ya que muestran la mayor rentabilidad promedio.
* **Mercado Japonés:** Priorizar juegos de Rol con clasificación ESRB apta para adolescentes (T) o todo público (E).
* **Foco en Crítica:** Se observó que las reseñas de los críticos tienen una correlación más fuerte con las ventas que las reseñas de los usuarios, por lo que deben ser un factor clave en la selección de títulos a promocionar.

---
## 📂 Estructura del Repositorio
* [`notebook.ipynb`](notebook.ipynb): Jupyter Notebook con el ciclo completo de análisis, desde el tratamiento de valores ausentes (TBD) hasta las conclusiones.
* [`datasets`](datasets): Dataset con información de ventas, plataformas y ratings (*games.csv*).

---
