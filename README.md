# Primer-Repositorio
Modelo DL visión por computadora para clasificar la calidad de los crimpados eléctricos automotrices según la norma USCAR-21

<img width="853" height="224" alt="image" src="https://github.com/user-attachments/assets/71a0cebd-0243-445f-b7ca-f29cc1da022f" />

Indice
1. Introducción
2. Estructura del proyecto

   2.1. Dataset y scripts de soporte
3. Análisis comparativo de modelos


# 1 Introducción

Para realizar la actividad 4 del curso gestión de proyectos de inteligencia artificial es de mi interés poner en práctica el uso de redes neuronales en la detección de imágenes especialmente en discriminar muestras conformes y no conformes de los resultados de pruebas de crimpado bajo la norma SAE USCAR-21 la cual evalúa la calidad del proceso de crimpado entre cables y terminales para uso en la industria automotriz asegurando que los crimpados cumplan con los requisitos de retención de fuerza y resistencia a lo largo del tiempo bajo condiciones rigurosas de uso de los vehículos.

La importancia del proceso de crimpado entre cables y terminales SAE USCAR-21 para uso en la industria automotriz es de gran importancia para asegurar la correcta distribución de señales eléctricas evitando intermitencia de las señales.

La sección transversal K-K muestra el resultado del proceso de crimpado y es la sección o imagen para análisis de calidad y confirmar que la unión entre cable y terminal es correcta.
<img width="943" height="361" alt="image" src="https://github.com/user-attachments/assets/c297599e-881f-4868-9015-dcf7ff1203f3" />

La norma SAE USCAR-21 establece los parámetros requeridos para evaluar la calidad del proceso de crimpado mediante el análisis visual de la sección transversal del crimpado como se muestra a continuación:
<img width="709" height="298" alt="image" src="https://github.com/user-attachments/assets/bef53e26-31bd-4eff-8bf6-ebd93a88e90f" />

<img width="689" height="391" alt="image" src="https://github.com/user-attachments/assets/566372ae-8e12-49fa-8564-8066501a0fcf" />

<img width="889" height="344" alt="image" src="https://github.com/user-attachments/assets/0acf5e70-2ca6-416e-a6e0-f8ec62b3e5ea" />

<img width="862" height="934" alt="image" src="https://github.com/user-attachments/assets/40ea8050-fd8d-4098-9377-b0e3d41d89a6" />
https://uscar.org/wpfd_file/uscar-21-report-template/



# 2 Estructura del proyecto

2.1 Dataset y scripts de soporte

Desafortunadamente no pude localizar un dataset ya existente en la red debido a que muchos de estos resultados son considerados información protegida por cada uno de los fabricantes de automóviles, sin embargo, me di a la tarea de tratar de generar imágenes fotorrealistas o renderizadas usando inteligencia artificial (chatGPT, Dalle, etc) sin embargo las imágenes resultantes no fueron las esperadas o requeridas como se muestra a continuación.

“generar dataset conjunto de imágenes sintéticas fotorrealistas o renderizadas tipo .jpg resolución 640x640 pixeles vista lateral de crimpados  conformes y no conformes de acuerdo al estándar USCAR21 para entrenar un modelo Deep learning que clasifique la calidad de los crimpados”

“Lateral close-up view of a metallic automotive crimp terminal, correctly crimped wire according to USCAR-21 standard, high detail, studio lighting, 640x640 pixeles”

“Lateral close-up view of a metallic automotive crimp terminal with visible defects, loose wire strands, incorrect crimp height, damaged insulation, photorealistic, studio lighting, 640x640 pixeles”

<img width="481" height="411" alt="image" src="https://github.com/user-attachments/assets/75b39104-8c2e-45a1-b43f-7a8bbcd508a2" />

Finalmente termine buscando en la red todas aquellas imágenes disponibles de resultados de pruebas USCAR-21 para comenzar a crear mi dataset con imágenes CONFORMES y NO CONFORMES a la norma SAE USCAR-21.

Dataset link: https://drive.google.com/drive/folders/18dPr7dtrLWA3Qso4UI7ruTAkaNJ_XWY4?usp=sharing

<img width="830" height="444" alt="image" src="https://github.com/user-attachments/assets/83d6d630-cae5-4256-9302-26226c743c86" />

<img width="938" height="632" alt="image" src="https://github.com/user-attachments/assets/9325a9c3-118b-4bf7-a724-a5de4b5a6256" />


# 3. Análisis comparativo de modelos











