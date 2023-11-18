# Red neuronal convolucional para la reconstrucción de la vorticidad superficial probada con observaciones aéreas
## Pérez-Corona, Y. y Torres, H.  

En este repositorio encontramos:
1. Jupyter Notebook:
   - Exploración de datos: como su nombre indica, se muestra la descripción de los datos DopplerScatt y un análisis de ellos.
   - Proyecto: en este se muestra la reconstrucción de la vorticidad de las observaciones aéreas.
2. Archivos de datos DopplerScatt:
   - dopplerscatt_20211020_140315.tomoL2CF: contiene los datos sin procesar para el ejercicio de exploración de datos. Obtenidos de: https://podaac.jpl.nasa.gov/dataset/SMODE_L2_DOPPLERSCATT_WINDS_CURRENT_V1#. También se pueden consultar otros días.
3. Pesos de modelos:
   - vort_cs: preentrenado con la vorticidad de channel simulation.
   - vort_summer: preentrenado con la vorticidad de verano de LLC4320.
   - vort_winter: preentrenado con la vorticidad de invierno de LLC4320.

Los modelos pueden ser consultados directamente en el repositorio del artículo de Xiao et al. (2023) del cual fueron obtenidos https://github.com/qyxiao/CNN-for-SSH-reconstruction/, así como más detalles sobre su entrenamiento.

### Referencias
Xiao, Q., Balwada, D., Jones, C. S., Herrero-González, M., Smith, K. S., Abernathey, R. (2023). Reconstruction of surface kinematics from sea surface height using neural networks. Journal of Advances in Modeling Earth Systems, 15, doi: 10.1029/2023MS003709.
