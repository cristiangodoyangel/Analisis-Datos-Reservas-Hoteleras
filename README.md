# 📊 Análisis Exploratorio de Datos de Reservas Hoteleras



🧾 Descripción General
Este proyecto aborda un proceso completo de análisis exploratorio de datos (EDA) sobre un dataset de más de 119 mil reservas hoteleras. El trabajo cubre:


- Limpieza profunda de datos

- Conversión y corrección de tipos de datos

- Normalización de valores categóricos

- Análisis univariado y multivariado

- Visualizaciones comparativas y explicativas

- Estadísticas descriptivas

- Detección de tendencias clave

Todo esto realizado con Python en Google Colab, empleando pandas, matplotlib y seaborn.


🔍 Objetivos

- Depurar y preparar el dataset para análisis.

- Entender el comportamiento de las reservas según tipo de hotel, canal de distribución y segmento de cliente.

- Visualizar relaciones entre variables categóricas y numéricas.

- Detectar patrones o tendencias que puedan aportar valor en la toma de decisiones.


📂 Contenido del Análisis

✅ Limpieza y Preparación

- Eliminación de duplicados (más de 30k)

- Imputación de valores faltantes (ej. países desconocidos → "unknown")

- Conversión a tipos de datos adecuados (datetime, category, int, etc.)

- Revisión de outliers y valores extremos



📈 Visualizaciones Realizadas

- Histogramas de tiempos de espera (lead_time)

- Conteos por tipo de hotel

- Gráficos de barras comparando clientes según tipo

- Boxplots del precio por noche (adr) según tipo de hotel y canal de distribución

- Gráfico de violín para ver dispersiones de precios



📊 Estadística Descriptiva

Se presenta un resumen con:

- Promedio (mean)

- Mediana (50%)

- Rango, desviación estándar, valores máximos y mínimos por variable numérica



🔍 Detección de Tendencias

Se identificaron patrones como:

- El hotel de ciudad tiene más reservas que el de resort

- Clientes "Transient" son los más frecuentes

- Algunos canales como Online TA dominan el mercado

- Existen outliers en precios y duración de estadías, pero en contexto son razonables



🧰 Tecnologías Utilizadas
- Python 3

- Pandas

- Matplotlib

- Seaborn

- Google Colab para entorno de ejecución



📁 Archivos Usados
hotel_bookings.csv: Dataset original con 119,390 registros y 32 columnas


🟢 Estado del Proyecto
✔️ Completado: el dataset está limpio, analizado y visualizado. Preparado para ser usado en modelos predictivos o dashboards.

