# Clasificacion de imagenes de habitaciones de hotel en base a un algoritmo hibrido

# Resumen
La trata de personas es un problema que radica en todo el mundo, en algunos casos los traficantes suelen tener aprisionadas a sus víctimas en habitaciones de hotel y publicar fotos de ellas en el mercado negro. Estas fotos suelen llegar como evidencia en las investigaciones, por lo que, una de las principales tareas de las autoridades es ubicar el hotel donde fue tomada la fotografía de la víctima.
La clasificación de imágenes mediante Inteligencia Artificial es una tarea que trata de comprender una imagen con el objetivo de asignarla a una categoría en específico. En este proyecto de investigación se desarrollaron múltiples algoritmos de clasificación híbrida con el objetivo de identificar que algoritmo funciona mejor al clasificar imágenes de habitaciones de hotel y de esta manera facilitar la identificación de en qué cadena hotelera fue tomada la fotografía. Los algoritmos que se desarrollaron utilizaron una red neuronal convolucional entrenada desde cero y la red pre entrenada VGG16, y se hizo uso de los algoritmos Random Forest (RF) y Support Vector Machine (SVM) para la clasificación híbrida.
En los resultados obtenidos se logró observar que para la clasificación de imágenes sobre habitaciones de hotel resulta efectivo utilizar una clasificación hibrida ya que, al aplicar RF o SVM sobre la red neuronal se obtuvieron mejores resultados de clasificación que cuando se realizó una clasificación no hibrida.

Fuente de los datos: https://www.kaggle.com/c/hotel-id-2021-fgvc8
