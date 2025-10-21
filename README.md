# Peru Minimum Temperature (Tmin) Raster Analysis + Public Policy
Este proyecto analiza las temperaturas mínimas del Perú a partir de un raster GeoTIFF (`tmin_raster.tif`), calcula estadísticas zonales por distrito y propone medidas de política pública para mitigar los impactos del friaje y las heladas.

## Estructura del Repositorio
├── app/ # Streamlit app

├── data/ # Raster y shapefiles

├── notebooks/ # Exploración y procesamiento de datos

├── requirements.txt # Dependencias

└── README.md # Instrucciones y despliegue

## Instalación y ejecución

### Paso 1: Clonar el repositorio
git clone https://github.com/AriannaNKZC/Minimum-Temperature-Raster.git

cd Minimum-Temperature-Raster

### Paso 2: Crear y activar entorno
conda create -n tmin python=3.10
conda activate tmin

### Paso 3: Instalar dependencias
pip install -r requirements.txt

### Paso 4: Ejecutar la app Streamlit
cd app
streamlit run app.py

## Descripción técnica
Raster: tmin_raster.tif (temperaturas mínimas)

Nivel de análisis: distrital (GeoJSON/shape)

Métricas: mean, min, max, std, p10, p90, custom metric

Librerías: geopandas, rasterio, rasterstats, rioxarray, streamlit

## Enlace de la aplicación
La app pública está disponible en:
"URL PENDIENTE"

## Integrantes del grupo:
GRUPO 10
- CAVERO RIVERA, EDUARDO DAVID
- CESPEDES ESPINOZA, LUIS RICARDO
- CONTRERAS VERGARA, LUIS GUILLERMO
- TALANCHA LUNA, ROSSY OFELIA
- ZAVALA CASTILLO, ARIANNA NICKOLE
