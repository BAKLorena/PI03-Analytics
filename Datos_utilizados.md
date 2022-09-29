# PI03 - Datos utilizados

Los datos utilizados provienen de la REST API de FTX.

Se utilizó la información contenida en la sección de "Markets", en específico los ítems de "Get markets" y "Get historical prices":


* Get markets: Se utilizaron las variables "name" y "price", las cuales indican el nombre de la criptomoneda y el precio a la que se encuentra la misma en el momento de hacer el requerimiento a la API.
* Get historical prices: Se utilizaron todas sus variables, las cuales contienen los datos históricos de los precios del mercado "Open", "Close", "High", "Low" y "Volume". Para el requerimiento, se utilizó una resolución de 86400 segundos, lo que equivale a un día, una fecha de inicio en el 01-ene-2020 y una fecha final establecida en el 31-dic-22. Lo anterior se decidió a partir del límite de 5000 registros que tiene la API  de FTX, optando por una resolución fácil de trabajar y con la suficiente información para poder realizar análisis de los últimos meses.
