# Redes neuronales convolucionales para la reconstrucción de la vorticidad superficial probadas con observaciones aéreas
## Pérez-Corona, Y. y Torres, H.  

En este repositorio encontramos:
1. Jupyter Notebook:
   - Exploración de datos: como su nombre indica, se muestra la descripción de los datos DopplerScatt y un análisis de ellos.
   - Proyecto: en este se muestra la reconstrucción de la vorticidad de las observaciones aéreas, tiene una sección donde si se quiere reconstruir a partir de datos satelitales, se pueden ingresar.
   - Datos satelitales: gráficos de las variables de los datos satelitales. 
2. Pesos de modelos:
   - vort_cs: preentrenado con la vorticidad de channel simulation.
   - vort_summer: preentrenado con la vorticidad de verano de LLC4320.
   - vort_winter: preentrenado con la vorticidad de invierno de LLC4320.

Los modelos pueden ser consultados directamente en el repositorio del artículo de Xiao et al. (2023) del cual fueron obtenidos https://github.com/qyxiao/CNN-for-SSH-reconstruction/, así como más detalles sobre su entrenamiento.

3. Archivos de datos se encuentran en Google Drive: https://drive.google.com/drive/folders/1xm-3yU5F9ion-ozwXg2dcWX_yR4lzXT5?usp=drive_link.
   - dopplerscatt_20211020_140315.tomoL2CF: contiene los datos DopplerScatt del 20 de octubre de 2021 sin procesar para el ejercicio de exploración de datos. Obtenidos de: https://podaac.jpl.nasa.gov/dataset/SMODE_L2_DOPPLERSCATT_WINDS_CURRENT_V1#. También se pueden consultar otros días.
   - dt_global_allsat_phy_l4_19970215_20210726.nc: contiene los datos satelitales de adt para el 15 de febrero de 1997. Obtenidos de: https://data.marine.copernicus.eu/products. También se pueden consultar para otros días.
   - Los demás archivos son datos de SSH y vorticidad para días específicos a partir de datos de DopplerScatt.

### Referencias
Xiao, Q., Balwada, D., Jones, C. S., Herrero-González, M., Smith, K. S., Abernathey, R. (2023). Reconstruction of surface kinematics from sea surface height using neural networks. Journal of Advances in Modeling Earth Systems, 15, doi: 10.1029/2023MS003709.
