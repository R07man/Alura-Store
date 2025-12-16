📌 Introducción

Este proyecto tiene como objetivo analizar el desempeño de cuatro tiendas pertenecientes al Sr. Juan, con el fin de determinar cuál de ellas debería venderse.
La decisión se basa en un análisis de datos objetivos relacionados con ventas, satisfacción del cliente, categorías de productos, productos más y menos vendidos y costos de envío.

El análisis fue realizado utilizando Python, junto con las librerías Pandas y Matplotlib, apoyándose en visualizaciones para facilitar la interpretación de los resultados.

📂 Fuentes de datos

Los datos utilizados corresponden a cuatro archivos CSV, uno por tienda, provistos por Alura LATAM:

tienda_1.csv

tienda_2.csv

tienda_3.csv

tienda_4.csv

Cada dataset contiene información sobre:

Producto

Categoría del producto

Precio

Costo de envío

Fecha de compra

Calificación del cliente

Ubicación, vendedor y método de pago

🔍 Análisis realizados

A lo largo del proyecto se llevaron a cabo los siguientes análisis:

1️⃣ Ingresos totales por tienda

Se calcularon los ingresos totales de cada tienda a partir de la suma del precio de los productos vendidos.
Estos datos se visualizaron mediante un gráfico circular, permitiendo comparar la participación de cada tienda en el total de ingresos.

2️⃣ Ventas por categoría de producto

Se agruparon las ventas por categoría para cada tienda, identificando:

Las categorías más vendidas

Las categorías con menor cantidad de ventas

Este análisis permitió observar patrones de consumo similares entre las tiendas.

3️⃣ Productos más y menos vendidos

Para cada tienda se identificó:

El producto más vendido

El producto menos vendido

Además, se generaron gráficos horizontales del Top 10 de productos más vendidos, utilizando un gradiente de color azul para facilitar la lectura.

4️⃣ Calificaciones promedio de los clientes

Se calculó el promedio de calificaciones otorgadas por los clientes en cada tienda.
Los resultados se visualizaron mediante un gráfico combinado de barras y línea, lo que permite apreciar pequeñas diferencias entre tiendas con valores similares.

5️⃣ Costos de envío promedio

Se calculó el costo de envío promedio por tienda, analizando su relación con el volumen de ventas.
Este análisis permitió observar que los costos de envío tienden a incrementarse junto con la cantidad de ventas realizadas.

📈 Visualizaciones generadas

El proyecto incluye las siguientes visualizaciones principales:

Gráfico circular de participación de ingresos por tienda

Gráficos de barras horizontales del Top 10 de productos más vendidos

Gráfico combinado de barras y línea para calificaciones promedio

Tablas de ventas por categoría

Tablas comparativas de costos de envío promedio

Cada tienda mantiene un color consistente en los gráficos para mejorar la identificación visual.

🧠 Conclusión y recomendación

Del análisis se desprende que:

La Tienda 1 es la que presenta mayores ingresos, aunque también mayores costos de envío.

Todas las tiendas mantienen calificaciones promedio altas, entre 3.98 y 4.05 sobre 5.

Las categorías más vendidas siguen patrones similares en todas las tiendas.

La Tienda 4 es la que presenta el menor volumen de ventas totales, a pesar de contar con buenas calificaciones por parte de los clientes.

✅ Recomendación final

Dado que todas las tiendas muestran buen desempeño general, pero la Tienda 4 registra la menor cantidad de ventas, se recomienda que el Sr. Juan venda la Tienda 4, ya que es la que tiene menor impacto en los ingresos globales del negocio.

🛠️ Tecnologías utilizadas

Python

Pandas

Matplotlib

Google Colab
