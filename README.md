# Mercado Libre Ecuador - Web Scraping de Ofertas

Este proyecto es una herramienta de **Web Scraping** desarrollada en Python para extraer datos estructurados de la sección de ofertas de [Mercado Libre Ecuador](https://www.mercadolibre.com.ec/ofertas).

## Características
- **Extracción Multipágina:** El script recorre automáticamente las páginas de ofertas (paginación).
- **Precisión de Precios:** Maneja la estructura compleja de Mercado Libre, uniendo la parte entera y los centavos para obtener el precio real.
- **Limpieza de Datos:** Procesa la información y elimina caracteres innecesarios.
- **Exportación:** Genera un archivo `csv` con formato UTF-8 listo para abrirse en Excel sin errores de caracteres.

## Tecnologías utilizadas
* **Python 3.x**
* **BeautifulSoup4:** Para la navegación y extracción del DOM HTML.
* **Requests:** Para la gestión de peticiones HTTP.
* **Pandas:** Para la estructuración y limpieza de los datos en DataFrames.

## Requisitos e Instalación

1. Clona este repositorio o descarga el archivo `.py`.
2. Instala las dependencias necesarias ejecutando:
    pip install -r requirements.txt
