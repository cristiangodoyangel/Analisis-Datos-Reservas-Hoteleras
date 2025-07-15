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

# 📊 Análisis de Datos de Reservas Hoteleras

Este proyecto aplica técnicas de **Data Cleaning**, **Exploración de Datos** y **Visualización** utilizando Python. El objetivo es entender el comportamiento de las reservas hoteleras y detectar patrones útiles para la toma de decisiones en el sector.

---

## 🧰 Tecnologías y Herramientas

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook / Google Colab

---

## 📂 Dataset

Dataset: `Hotel Bookings`  
Fuente: [Kaggle – Hotel Bookings Dataset](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)  
Cantidad de registros: +100.000

---

## 🔧 Procesos aplicados

### 🧹 Limpieza de Datos
- Eliminación de duplicados
- Conversión de tipos de datos (fechas, enteros, categorías)
- Estandarización de valores categóricos
- Relleno de valores faltantes (`NaN`)
- Detección y tratamiento de *outliers*

### 📊 Análisis Exploratorio
- Visualizaciones univariadas: distribución de reservas, cancelaciones, tipos de clientes.
- Visualizaciones multivariadas: precios por segmento y tipo de hotel.
- Estadísticas descriptivas (medias, desvíos, máximos, mínimos).

### 📈 Detección de Tendencias
- Mayor número de reservas en **City Hotel**.
- Canal de reserva influye en el precio (Online TA y Direct = mayor ADR).
- Clientes individuales tienen mayor tasa de cancelación.
- Reservas largas y con mucha anticipación asociadas a empresas.

---

## 📌 Conclusiones

- Las **reservas corporativas** suelen ser más largas, estables y con mayor anticipación.
- Las cancelaciones están fuertemente ligadas al tipo de cliente.
- El **canal de venta** afecta significativamente el precio final de la reserva.
- La mayoría de las reservas son para **2 adultos sin niños**, lo que orienta posibles campañas de marketing.

---

## 🎯 Aprendizajes Clave

- Aplicación real de herramientas como `Pandas`, `Seaborn` y `Matplotlib`.
- Buenas prácticas en limpieza de datos.
- Capacidad de generar conclusiones útiles desde visualizaciones.
- Uso de lógica para detectar valores atípicos y justificar decisiones.

---

## 🔗 Repositorio y Recursos

- 🔗 [Repositorio del Proyecto](https://github.com/cristiangodoyangel/Analisis-Datos-Reservas-Hoteleras)
- 📂 Dataset original: [Hotel Bookings Dataset en Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand)

---

## ✍️ Autor

**Cristian Godoy Ángel**  
📍 Antofagasta, Chile  
🔗 [LinkedIn](https://www.linkedin.com/in/cristiangodoyangel)  
📂 [GitHub](https://github.com/cristiangodoyangel)  
🌐 [Portafolio Web](https://www.cristiangodoyangel.dev)

