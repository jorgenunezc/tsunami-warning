<p align="center">
  <img src="https://www.lavanguardia.com/r/GODO/LV/p6/WebSite/2019/06/03/Recortada/img_mrius_20190603-104334_imagenes_lv_terceros_ola_estefania-kYzH-U462635134170IYH-992x558@LaVanguardia-Web.jpg">
</p>

<h2 align="center">tsunami warning</h2>

Este repositorio contiene códigos escritos en jupyter notebook para la crear un dataframe a partir de series de tiempo en formato .nc, resulatdo de escenarios generados con el software HySea, el cual sera utilizado en la calibración de modelos sequence to sequence con tecnicas de deep Learning. Posterios visualización y análisis de resultados. 
## Descripción Archivos.

### Visualización
- **mapas_inundacion :** Se utiliza para la visualización de series de mapas de inundación del área en estudio, esta inundación contempla solo altura de agua ya que se resto la cota topográfica y desnivel producto del sismo. Se pueden ejecutar n-archivos contenidos en una carpeta, generando una carpeta para los resultados de cada archivo. 

- **series_de_tiempo_boyas :** Se utiliza para visualizar series de tiempo de boyas en mar e inundación de un mismo archivo o escenario escalable para n-archivos, las imágenes generadas quedan guardadas en sus respectivas carpetas y según tipo de boya (mar o inundación).

- **boyas_3.0 :** Se utiliza en la ubicación de las distintas boyas virtuales ya sea en mar o tierra, generando un archivo .dat con las coordenadas geográficas de estas y una imagen con las boyas enumeradas.

### Análisis

- **crear_dataframe :** Crea dataframe con las boyas y escenarios especificados, se guarda en formato .json

