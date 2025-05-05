# Alura Store Latam: Análisis para la Decisión de Venta de Tienda

<p align="center">
  <img src="https://github.com/herbertturpo/alura-store-latam/blob/main/imagenes/Ingresos%20totales%20por%20tienda.png?raw=true" alt="Ingresos Totales por Tienda" width="600" height="400" />
</p>


Este repositorio contiene el análisis de datos realizado para ayudar al Sr. Juan a decidir qué tienda de su cadena Alura Store debería vender para iniciar un nuevo emprendimiento. El objetivo principal fue identificar la tienda menos eficiente basándose en diversas métricas y proporcionar una recomendación fundamentada.

## Contenido del Repositorio

* **`imagenes/`:** Carpeta que contiene archivos de imagen `.png` de las visualizaciones generadas durante el análisis.
* **`Informe_Alura_Store.md`:** Informe final detallado  ([Informe de Análisis de Datos](Informe_Alura_Store.md)) en formato Markdown con el análisis de datos, referencias a las visualizaciones y la recomendación sobre qué tienda vender.
* **`alura_store_latam.ipynb`:** Cuaderno de Jupyter/Google Colab que contiene el código en Python utilizado para realizar el análisis de datos y generar las visualizaciones.
* **`README.md`:** Este archivo, que proporciona una descripción general del proyecto.


## Resumen del Análisis

Se analizaron datos de las cuatro tiendas de Alura Store utilizando las funciones incorporadas propias de Python (como un desafío en la aplicación de los conocimientos fundamentales de Python desarrollados en Alura), la biblioteca Pandas de Python para la manipulación de datos, seaborn y Matplotlib para la creación de visualizaciones. El análisis se centró en las siguientes métricas:

* **Ingresos Totales:** Se comparó la facturación total de cada tienda.
* **Costo Promedio por Transacción:** Se analizó la eficiencia del envío en relación con los ingresos.
* **Calificación Promedio y Distribución de Reseñas de los Clientes:** Se evaluó la satisfacción del cliente con cada tienda.
* **Categorías y Productos Más Vendidos (y su contribución a la facturación):** Se identificaron los productos y categorías clave para cada tienda.

## Hallazgos Clave

El análisis reveló diferencias en el rendimiento de las cuatro tiendas en varias métricas. La **Tienda 4** mostró consistentemente la menor facturación total. Además, la **Tienda 1** presentó la calificación promedio más baja de los clientes y el costo de envío promedio por transacción más alto. El análisis de las categorías y productos más vendidos mostró algunas variaciones en el enfoque de ventas entre las tiendas.

## Recomendación

Basado en el análisis exhaustivo de los datos disponibles, el informe final recomienda al Sr. Juan considerar la **venta de la Tienda 4**. Esta recomendación se fundamenta principalmente en su menor rendimiento en términos de ingresos totales, aunque otros factores como la estructura de ventas ligeramente diferente y una satisfacción del cliente aceptable también fueron considerados.

## Visualizaciones

Se generaron varias visualizaciones para apoyar el análisis, incluyendo:

* Gráfico de barras comparativo de facturación.
* Gráfico de barras de calificación promedio por tienda.
* Gráfico de barras agrupadas de porcentaje de facturación por categoría (comparativa entre tiendas).
* Gráfico de barras horizontales de porcentaje de facturación por producto estrella (top 3 por tienda).

Estas visualizaciones se encuentran detalladas en el informe final y (opcionalmente) en la carpeta `visualizaciones/`.


## Cómo Utilizar este Repositorio

1.  **Clonar el repositorio:**
    ```bash
    git clone https://github.com/herbertturpo/alura-store-latam.git
    cd alura-store-latam
    ```
2.  **Revisar el informe:** Abre el archivo `Informe_Alura_Store.md` para leer el análisis completo, ver las tablas de datos y las interpretaciones, con referencias a las visualizaciones.
3.  **Explorar el código:** Abre el cuaderno `alura_store_latam.ipynb` en Google Colab o Jupyter Notebook para revisar y ejecutar el código de Python utilizado para el análisis y la generación de las visualizaciones.
4.  **Ver las visualizaciones:** Examina las imágenes `.png` en la carpeta `imagenes/` para ver los gráficos generados.

## Librerías Utilizadas

* **Pandas:** Para la manipulación y análisis de datos tabulares.
* **Matplotlib:** Biblioteca base para la creación de gráficos y visualizaciones. Se utiliza como base para Seaborn.
* **Seaborn:** Biblioteca de visualización de datos de alto nivel construida sobre Matplotlib. Proporciona una interfaz concisa para crear gráficos estadísticos informativos y atractivos.

## Contribuciones

* **Autor:** Este análisis fue realizado por [Heriberto Turpo]. Cualquier contribución o sugerencia para mejorar el análisis es bienvenida.
* **Datos:** Repositorio público de Alura Latam.
* **Inspiración:** Reto de análisis de datos de Alura Latam.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT.
