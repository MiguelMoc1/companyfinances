# Proyecto de Análisis Financiero con Power BI

## 📈 Descripción del Proyecto
Este proyecto consiste en la creación de un **dashboard financiero interactivo** utilizando **Power BI**. Se basa en un análisis detallado del **dataset de Company Financials** obtenido directamente desde **Kaggle** a través de su **API**. El objetivo es proporcionar una visión clara y visualmente atractiva del rendimiento de la empresa a través de métricas clave y gráficos interactivos.

## 🚦 Objetivo del Proyecto
El objetivo principal es analizar las **ventas** y la **rentabilidad** de la empresa a través de diversas dimensiones, tales como:
- **Países**
- **Segmentos de mercado**
- **Productos**
- **Meses y años**

## 🔍 Proceso del Proyecto
1. **Extracción de Datos:** 
   - Se utilizó la **API de Kaggle** para descargar el dataset **'Company Financials Dataset'** sin necesidad de realizar la descarga manual.
   - El proceso se realizó íntegramente en **VS Code** utilizando **Jupyter Notebook** con celdas **Markdown** para documentar cada paso.

2. **Limpieza y Transformación de Datos:**
   - Los datos se limpiaron y transformaron en **Python**, eliminando valores nulos, convirtiendo columnas numéricas y aplicando una **transformación logarítmica** para normalizar las distribuciones de ciertas métricas.

3. **Almacenamiento en SQL Server:**
   - Los datos limpios se almacenaron en una **base de datos SQL** llamada **FinancialsDB**.
   - Se utilizó **SQL Server Management Studio (SSMS)** para crear la base de datos y cargar los datos.

4. **Visualización en Power BI:**
   - Se conectó **Power BI** directamente a la base de datos **SQL Server**.
   - Se crearon dos páginas en el **dashboard**:
     - La primera página proporciona una **visión general de las ventas y ganancias** por país y segmento.
     - La segunda página se enfoca en el **análisis de productos** y la **estacionalidad de ventas**.

## 📊 Visualizaciones Clave
- **Tarjetas:** Muestran las **ventas totales**, la **ganancia total** y el **margen de ganancia**.
- **Gráficos de Barras:** Comparan las **ventas** y el **margen de ganancia** por **país** y **segmento**.
- **Gráfico de Líneas:** Muestra la **tendencia de ventas por mes**.
- **Gráfico de Mapa:** Visualiza el **rendimiento por país** con burbujas de tamaño proporcional.
- **Gráficos de Pastel:** Muestran la **distribución de ventas por segmento**.
- **Filtros Dinámicos:** Se incluyeron filtros de **Año**, **Segmento** y **Producto** para facilitar la exploración interactiva de los datos.

## 🚦 Insights Obtenidos
- **Ventas Totales:** El mayor volumen de ventas proviene de **Estados Unidos**, pero con el **menor margen de ganancia** (11.97%).
- **Margen de Ganancia:** **Alemania** tiene el **mayor margen de ganancia**, aunque el volumen de ventas es relativamente bajo.
- **Segmento de Mayor Ventas:** El **gobierno** es el segmento al que más se vende en todos los países.
- **Estacionalidad de Ventas:** Se observan **picos de ventas en noviembre y diciembre**, indicando una tendencia estacional fuerte hacia fin de año.
- **Popularidad de Productos:** El producto **Paseo** es el más popular en **América**, mientras que **Amarilla** y **Carretera** tienen mejor rendimiento en **Europa**.

## 💻 Herramientas Utilizadas
- **Python:** Para la **limpieza** y **transformación de datos**.
- **Jupyter Notebook:** Documentación y **análisis exploratorio**.
- **Kaggle API:** Extracción automatizada del dataset.
- **SQL Server:** Almacenamiento de datos.
- **Power BI:** Creación del **dashboard interactivo**.

