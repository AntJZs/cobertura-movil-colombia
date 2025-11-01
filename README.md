# Análisis de Cobertura Móvil en Colombia

Proyecto de ciencia de datos que analiza la evolución de la cobertura móvil por tecnología (2G, 3G, 4G, LTE, 5G) en Colombia, con enfoque en proveedores y distribución geográfica.

## Datos

- **Cobertura móvil**: Datos de cobertura por tecnología, departamento y municipio por proveedor
- **Datos geográficos**: DIVIPOLA - Centros poblados con coordenadas de latitud y longitud

## Análisis

El notebook `exploracion_de_datos.ipynb` incluye:

- Crecimiento de cobertura móvil por tecnología a lo largo de los años
- Evolución de cuota de mercado por proveedor
- Velocidad de adopción de tecnologías
- Identificación de líderes de mercado

## Gráficos Generados

Los gráficos interactivos se guardan en la carpeta `graficos/`:

- Crecimiento de cobertura móvil por tecnología
- Evolución de cuota de mercado interactiva
- Líderes de mercado por tecnología

## Requisitos

```
pandas
plotly
```

## Uso

1. Instalar dependencias: `pip install pandas plotly`
2. Ejecutar el notebook: `jupyter notebook exploracion_de_datos.ipynb`
