# Red neuronal convolucional para la reconstrucción de la vorticidad superficial probada con observaciones aéreas
## Pérez-Corona, Y. y Torres, H.  

En este repositorio encontramos:
* Jupyter Notebook:
  - Exploración de datos: como su nombre indica, se muestra la descripción de los datos DopplerScatt y un análisis de ellos.
  - Proyecto: en este se muestra la reconstrucción dela vorticidad de las observaciones aéreas.
* Archivos de datos DopplerScatt:
  - dopplerscatt_20211020_140315.tomoL2CF: contiene los datos sin procesar para el ejercicio de exploración de datos.
  - SSH: contienen los datos de SSH previamente calculada. 
  - Smooting: contienen los datos de vorticidad real. 
* CNN:
  - model_cs
  - model_summer
  - model_winter

Los modelos pueden ser consultados directamente en el repositorio del artículo de Xiao et al. (2023) del cual fueron obtenidos https://github.com/qyxiao/CNN-for-SSH-reconstruction/, así como más detalles sobre su preentrenamiento.

### Referencias
Xiao, Q., Balwada, D., Jones, C. S., Herrero-González, M., Smith, K. S., Abernathey, R. (2023). Reconstruction of surface kinematics from sea surface height using neural networks. Journal of Advances in Modeling Earth Systems, 15, doi: 10.1029/2023MS003709.
