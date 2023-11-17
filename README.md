# Red neuronal convolucional para la reconstrucción de la vorticidad superficial probada con observaciones aéreas
## Pérez-Corona, Y. y Torres, H.  

En este repositorio encontramos:
* Jupyter Notebook:
  _ Exploración de datos: como su nombre indica, se muestra la descripción de los datos DopplerScatt y un análisis de ellos.
  _ Proyecto: en este se muestra la reconstrucción dela vorticidad de las observaciones aéreas.
* Archivos de datos DopplerScatt:
  *_ dopplerscatt_20211020_140315.tomoL2CF: contiene los datos sin procesar para el ejercicio de exploración de datos.
  _ SSH: contienen los datos de SSH previamente calculada. 
  _ Smooting: contienen los datos de vorticidad real. 
* CNN:
  _ model_cs
  _ model_summer
  _ model_winter

Los modelos pueden ser consultados directamente en el repositorio del artículo de Xiao et al. (2023) del cual fueron obtenidos https://github.com/qyxiao/CNN-for-SSH-reconstruction/, así como más detalles sobre su preentrenamiento.
