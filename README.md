# Trabajo 3: Análisis de datos con NumPy y Pandas

## Objetivo
Analizar los datos de ventas, inventarios y satisfacción del cliente para una cadena de tiendas minoristas (RetailNow) utilizando Pandas y NumPy.

## Estructura del análisis

### Carga y limpieza de datos (Pandas)
- Cargar archivos CSV: sales.csv, inventories.csv, satisfaction.csv
- Eliminar filas con valores nulos usando dropna()

### Exploración de datos (Pandas)
- Ventas totales por producto
- Ingresos totales por tienda (Cantidad × Precio)
- Resumen estadístico con describe()
- Ventas totales por tienda

### Análisis de inventarios (Pandas)
- Calcular rotación de inventarios (Ventas / Stock)
- Filtrar tiendas con inventario crítico (< 10%)

### Satisfacción del cliente (Pandas)
- Analizar satisfacción por tienda
- Filtrar tiendas con satisfacción < 60%
- Recomendaciones de mejora

### Operaciones con NumPy
- Mediana de ventas totales
- Desviación estándar de ventas
- Simulación de proyecciones futuras (arrays aleatorios)
- Estadísticas de las proyecciones

## Archivos
- `analisis_red_tiendas.ipynb` - Notebook principal con todo el análisis

## Datos
Los archivos CSV se encuentran en:
- `python-tema-3-programacion-basica/plantilla/sales.csv`
- `python-tema-3-programacion-basica/plantilla/inventories.csv`
- `python-tema-3-programacion-basica/plantilla/satisfaction.csv`

## Requisitos
- Python
- Pandas
- NumPy
- Jupyter Notebook

## Uso
Abrir el archivo `analisis_red_tiendas.ipynb` en Jupyter o VS Code con plugin de Jupyter.
