## 📝 Informe explicativo del análisis

### 📌 Resumen del proyecto
En este proyecto he realizado un análisis de ventas de videojuegos a partir de un dataset extraído de Kaggle.  
El trabajo se ha desarrollado en Excel e incluye todo el proceso: limpieza de datos, análisis descriptivo y creación de un dashboard final.

El objetivo principal ha sido transformar los datos originales en información clara y visual para identificar tendencias del mercado y destacar los elementos más relevantes del dataset.

---

### 🎯 Objetivos
Con este análisis se ha buscado:

- limpiar y preparar los datos para poder trabajarlos correctamente
- analizar las ventas desde distintos puntos de vista
- detectar plataformas, géneros y distribuidoras más relevantes
- observar la evolución de las ventas a lo largo del tiempo
- identificar el juego más vendido
- resumir todo en un dashboard visual y fácil de interpretar

---

### 📂 Dataset utilizado
Se ha utilizado el dataset **Video Game Sales**, obtenido desde Kaggle.

**Fuente original:**  
[Video Game Sales - Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales?resource=download)

**Variables principales del dataset:**
- `Name`
- `Platform`
- `Year`
- `Genre`
- `Publisher`
- `NA_Sales`
- `EU_Sales`
- `JP_Sales`
- `Other_Sales`
- `Global_Sales`

---

### 🧹 Limpieza y transformación de los datos
Antes de empezar el análisis, fue necesario revisar y preparar el dataset.

Durante esta fase se realizaron tareas como:

- comprobación de columnas y formatos
- revisión de valores vacíos o inconsistentes
- ajuste del campo `Year`
- validación de las columnas de ventas
- creación de una base final limpia para el análisis
- generación de una columna auxiliar por décadas

Esta parte fue importante para asegurar que tanto los cálculos como las visualizaciones partieran de una base consistente.

---

### 📊 Análisis descriptivo
Una vez preparada la base de datos, se realizó un análisis descriptivo para extraer la información más relevante.

Se analizaron principalmente los siguientes puntos:

- **ventas globales por año**, para ver la evolución del mercado
- **ventas por plataforma**, para identificar las más fuertes
- **ventas por género**, para ver qué categorías destacan más
- **ventas por distribuidora**, para comparar el peso de cada publisher
- **ventas por región**, para analizar diferencias entre mercados
- **juego más vendido**, para destacar el título con mayor volumen de ventas

---

### 🔍 Hallazgos principales
A partir del análisis realizado, se pueden destacar varios resultados:

- el dataset contiene más de **16.000 registros**
- las ventas globales acumuladas superan los **8.900 millones**
- el juego más vendido del dataset es **Wii Sports**
- **Wii Sports** alcanza unas ventas globales de **82,74 millones**
- algunas plataformas concentran gran parte del volumen total de ventas
- ciertos géneros destacan claramente por encima del resto
- Norteamérica y Europa tienen un peso muy relevante dentro del mercado total

---

### 🏆 Juego más vendido
El juego más vendido del dataset es:

- **Nombre:** Wii Sports
- **Plataforma:** Wii
- **Año:** 2006
- **Género:** Sports
- **Distribuidora:** Nintendo
- **Ventas globales:** 82,74 M

Por su importancia dentro del análisis, se incluyó una tarjeta específica para este juego dentro del dashboard.

---

### 📈 Dashboard final
Como resultado del proyecto, se creó un dashboard en Excel para resumir toda la información de forma visual.

El panel incluye:

- tarjetas KPI superiores
- gráficos de evolución de ventas
- ranking de plataformas
- ranking de géneros
- ranking de distribuidoras
- comparación de ventas por región
- tarjeta con el juego más vendido

Además, se trabajó el diseño para darle un aspecto más profesional, mejorando:
- colores y estilo visual
- separación entre tarjetas
- jerarquía de títulos
- uso del espacio del panel
- coherencia entre gráficos y fondos

---

### 💡 Interpretación general
El análisis muestra que el mercado de los videojuegos está muy concentrado en torno a determinadas plataformas, géneros y distribuidoras.

También se observa que no todas las regiones tienen el mismo comportamiento, y que algunos títulos concretos llegan a destacar muy por encima del resto, como ocurre con **Wii Sports**.

En conjunto, el dashboard permite entender de forma rápida qué elementos tienen más peso dentro del dataset y cómo se reparten las ventas globales.

---

### ⚠️ Limitaciones
Aunque el proyecto permite obtener conclusiones útiles, hay que tener en cuenta que:

- se trata de un análisis descriptivo
- no se han aplicado modelos predictivos
- los resultados dependen del dataset original utilizado
- las conclusiones reflejan el contenido de esa base de datos concreta

---

### ✅ Conclusión
Este proyecto ha permitido aplicar las fases principales de un análisis de datos:

1. limpieza y transformación  
2. análisis descriptivo  
3. visualización  
4. comunicación de resultados  

El resultado final es un dashboard en Excel que resume de forma clara y visual la información más importante del dataset de ventas de videojuegos.
