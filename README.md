# Análisis de Rendimiento de Tiendas Alura Store

## 🚀 Visión General del Proyecto

Este repositorio contiene el análisis de datos realizado para el Sr. Juan, dueño de las tiendas Alura Store, con el objetivo de identificar la tienda con el rendimiento más bajo y recomendar su posible venta. El análisis abarca diversas métricas clave como ingresos totales, popularidad de categorías y productos, calificaciones de clientes y costos de envío promedio, proporcionando una justificación clara basada en datos para la decisión final.

## 🎯 Objetivo Principal

El propósito de este análisis es:
* Evaluar el desempeño individual de cada una de las cuatro tiendas Alura Store.
* Identificar la tienda con el rendimiento más débil.
* Proporcionar una recomendación fundamentada al Sr. Juan sobre qué tienda debería considerar vender, respaldada por visualizaciones y métricas clave.

## 📊 Metodología y Análisis Realizados

El análisis se llevó a cabo utilizando Python y las librerías `pandas`, `matplotlib` y `seaborn` para la manipulación, visualización y análisis de los datos. Se exploraron los siguientes factores clave:

### 1. Facturación Total por Tienda
Se calculó la suma de los ingresos generados por cada tienda para identificar la de mayor y menor contribución económica.

### 2. Categorías de Productos Más y Menos Populares (por Conteo de Transacciones)
Se analizó la frecuencia de ventas por categoría de producto en cada tienda para entender la demanda y las tendencias de consumo. Se identificaron las 5 categorías más y menos vendidas.

### 3. Calificación Promedio de Clientes por Tienda
Se calculó el promedio de las calificaciones de los clientes para evaluar la satisfacción general y la calidad percibida del servicio en cada ubicación.

### 4. Productos Más y Menos Vendidos
Se identificaron los 5 productos más y menos vendidos por número de transacciones en cada tienda para entender el rendimiento de artículos específicos.

### 5. Costo Promedio de Envío por Tienda
Se calculó el costo de envío promedio para cada tienda, un factor importante que afecta la rentabilidad.

## 📈 Resultados Clave del Análisis

Basado en los datos y visualizaciones obtenidas:

* **Facturación Total:** La **tienda 4** es la que presenta la facturación más baja (\$1,038,375,700.00), mientras que la **tienda 1** es la de mayor facturación (\$1,150,880,400.00).
* **Categorías de Productos:** Categorías como **Artículos para el hogar**, **Libros** e **Instrumentos musicales** mostraron consistentemente baja demanda en todas las tiendas. **Muebles**, **Electrónicos** y **Juguetes** fueron las más populares. No se observaron diferencias significativas en la popularidad de categorías entre las tiendas.
* **Calificación Promedio de Clientes:** Las calificaciones son muy similares entre todas las tiendas, oscilando entre 4.05 y 3.98. La **tienda 1** tiene un promedio de 3.98, la más baja, pero la diferencia es mínima.
* **Productos Vendidos:** Existe una dispersión en los productos más y menos vendidos entre las tiendas, lo que sugiere que este indicador por sí solo no es un factor decisivo para la recomendación.
* **Costo Promedio de Envío:** Los costos de envío son muy similares entre todas las tiendas. La **tienda 1** tiene el costo promedio ligeramente más alto (\$26,018.61), y la **tienda 4** el más bajo (\$23,459.46).

## 💡 Conclusión y Recomendación

Considerando todos los factores analizados, se recomienda al Sr. Juan **vender la tienda 4**.

**Justificación de la Decisión:**

La **tienda 4** se identifica como la candidata más adecuada para la venta por las siguientes razones fundamentales:

* **Baja Facturación Total:** Es consistentemente la tienda con los **menores ingresos totales** (\$1,038,375,700.00), lo que indica una deficiencia en la generación de ventas en comparación con sus pares. Aunque las diferencias no son abismales, es el punto más bajo en esta métrica crucial.
* **Baja Satisfacción del Cliente (aunque marginal):** Si bien la diferencia es pequeña, la tienda 4 presenta el segundo promedio de calificación más bajo (4.00), solo por encima de la tienda 1 (3.98). Aunque no es el factor decisivo por sí solo, contribuye al panorama general de su desempeño relativamente menor.
* **Costos de Envío:** Es importante destacar que la tienda 4 no es la que tiene los costos de envío más altos; de hecho, tiene los más bajos (\$23,459.46). Esto significa que su bajo rendimiento no se debe a una ineficiencia en los gastos de envío, sino más bien a problemas relacionados con la generación de demanda o la gestión de su inventario de productos.

Mientras que otras tiendas pueden tener áreas de mejora, la **tienda 4** muestra una combinación crítica de la **menor generación de ingresos y una baja satisfacción del cliente**, lo que la convierte en la opción más lógica para desinvertir. Desinvertir en esta tienda permitiría al Sr. Juan reasignar recursos a las tiendas más rentables y con mayor potencial de crecimiento, donde la inversión puede generar un retorno más significativo.

## 🛠️ Tecnologías Utilizadas

* **Python**
* **Pandas:** Para manipulación y análisis de datos.
* **Matplotlib:** Para creación de gráficos estáticos.
* **Seaborn:** Para visualizaciones estadísticas atractivas.

## ⚙️ Cómo Ejecutar el Código

1.  **Clona el repositorio:**
    ```bash
    git clone <URL_DEL_REPOSITORIO>
    ```
2.  **Navega al directorio del proyecto:**
    ```bash
    cd <NOMBRE_DEL_REPOSITORIO>
    ```
3.  **Instala las dependencias:**
    Asegúrate de tener Python instalado. Luego, instala las librerías necesarias:
    ```bash
    pip install pandas matplotlib seaborn
    ```
4.  **Abre el notebook en Google Colab o Jupyter:**
    Sube el archivo `.ipynb` (que contiene el código de análisis) a Google Colab o ábrelo con Jupyter Notebook.
5.  **Ejecuta todas las celdas:**
    Ejecuta las celdas en orden. Asegúrate de que las URLs de los archivos CSV sean correctas y estén accesibles.

## 📧 Contacto

Para cualquier pregunta o comentario, puedes contactar a:

**Román Ignacio Escobar Pizarro**
* roman.escobar.p@gmail.com


---
