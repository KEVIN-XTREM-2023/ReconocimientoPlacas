# Sistema de reconocimiento de placas de automóviles




<center>

<img src="https://cdn.icon-icons.com/icons2/577/PNG/256/ExecutiveCar_Black_icon-icons.com_54904.png" alt="VB." width="200">
</center>

Sistema para reconocimiento de placas de automóviles.


Un sistema de reconocimiento de placas de automóviles es un sistema diseñado para identificar 
matrículas de vehículos de manera eficiente. Utilizando cámaras y algoritmos de procesamiento de 
imágenes, este sistema automatizado captura imágenes de las placas de los vehículos en tiempo real. El proceso comienza con la adquisición de la imagen, seguido por la segmentación de la placa para aislarla del entorno circundante. Luego, se aplica un reconocimiento óptico de caracteres para extraer 
los caracteres alfanuméricos de la placa. Este sistema se puede aplicar en diferentes áreas, como la gestión del tráfico, la seguridad pública, y el control de acceso. En la gestión del tráfico, por ejemplo, ayuda a monitorear el flujo vehicular, detectar infracciones y facilitar la aplicación de regulaciones de 
estacionamiento.


La eficacia del sistema de reconocimiento de placas se ve respaldada por la capacidad de procesar 
grandes volúmenes de datos en tiempo real y su capacidad para integrarse con sistemas de gestión de bases de datos. Además, las mejoras continuas en la inteligencia artificial y el aprendizaje profundo 
contribuyen a la precisión y confiabilidad del sistema.

Este proyecto fue realizado mediante Matlab dado que esta cuenta con librerías especializadas para la creación de redes neuronales.

### Librerías  
### Neural Net Pattern Recognition
La app Neural Net Pattern Recognition permite crear, visualizar y entrenar redes prealimentadas de dos capas para resolver problemas de clasificación de datos.

Con esta app, puede:

- Importar datos de un archivo o del espacio de trabajo de MATLAB®, o utilizar uno de los conjuntos de datos de ejemplo.

- Dividir datos en conjuntos de entrenamiento, validación y prueba.

- Definir y entrenar una red neuronal.

- Evaluar el rendimiento de la red utilizando error de entropía cruzada y el error de clasificación errónea.

- Analizar los resultados utilizando gráficas de visualización, como matrices de confusión y curvas características de funcionamiento del receptor.

- Generar scripts de MATLAB para reproducir resultados y personalizar el proceso de entrenamiento.

- Generar funciones adecuadas para el despliegue con las herramientas MATLAB Compiler™ y MATLAB Coder™, y exportarlas a Simulink® para su uso con Simulink Coder.

### Classification Learner

La app Classification Learner entrena modelos para clasificar datos. Con esta app, puede explorar el proceso de machine learning supervisado mediante varios clasificadores. Puede explorar los datos, seleccionar características, especificar esquemas de validación, entrenar modelos y evaluar los resultados. Puede llevar a cabo entrenamiento automatizado para buscar el mejor tipo de modelo de clasificación, incluyendo árboles de decisión, análisis discriminantes, máquinas de vectores de apoyo, regresión logística, vecinos más próximos, Naive Bayes, aproximación de kernel, ensemble y clasificación de redes neuronales.


## Software Utilizado
En este proyecto, se utilizó Matla , para Classification Learner y Neural Net Pattern Recognition se uso estos dos para comparar los resultados y ver con cual de los dos un error de probabilidad bajo , otras opciones de herramientas serian:

-   Python para el análisis e datos es un lenguaje especializado para este tema.

- Visual Studio Code 
Visual Studio Code (VS Code) es un entorno de desarrollo integrado (IDE) altamente popular y 
ampliamente utilizado.
## Lenguaje de Programación
<center>

<img src="https://cdn.icon-icons.com/icons2/2107/PNG/512/file_type_matlab_icon_130398.png" alt="VB." width="200">
</center>



El sistema fue implementado en Matlab porque ya venían integrado las herramientas necesarios para este proyecto.


## Materiales 
El sistema de reconocimientos de placas de automóviles aplica el siguiente esquema:
![Login.](https://github.com/Kevin-Saquinga/ImagenesGit/blob/main/4.png?raw=true)
### Conjunto de datos de Entrenamiento 
La precisión, la eficacia de un sistema de clasificación de imágenes usando inteligencia artificial, 
depende de varios factores, como la arquitectura, el tipo de clasificador que se use, el conjunto de datos 
empleado para su entrenamiento. Este último es el más importante y a su vez también puede 
representar el mayor problema que podemos tener al momento de entrenar.
Para entrenar una red neuronal del sistema propuesto se ha usado los datos de Chars74k creado por 
T.de Campos y M. Varma de Microsoft Research. Está conformado por más de 74.000 imágenes de 
letras y números en formato PNG cada una de ellas esta separada por carpetas de mayúsculas
minúscula.
![Login.](https://github.com/Kevin-Saquinga/ImagenesGit/blob/main/5.png?raw=true)


## Version Utilizada
Matlab versiones superiores o iguales a la 2022.

## Instalación del Matlab

1. Adquisición de MATLAB:

- Compra o adquiere una licencia para MATLAB en el sitio web oficial de MathWorks.
2. Requisitos del Sistema:

- Verifica que tu sistema cumple con los requisitos mínimos del sistema para la versión de MATLAB que estás instalando.
3. Descarga:

- Inicia sesión en tu cuenta de MathWorks y descarga el instalador de MATLAB desde el sitio web oficial.
4. Ejecución del Instalador:

- Ejecuta el instalador descargado. Puede ser un archivo ejecutable (.exe en Windows, .dmg en macOS, o .sh en Linux).
5. Inicio del Asistente de Instalación:

- Sigue las instrucciones del asistente de instalación. Puede pedirte que ingreses tu cuenta de MathWorks y la clave de licencia.
6. Selección de Productos:

- Selecciona los productos de MATLAB que deseas instalar. Puedes optar por instalar complementos adicionales si es necesario.
7. Ruta de Instalación:

- Elige la carpeta de destino donde deseas instalar MATLAB.
8. Licencia:

- Acepta los términos de la licencia.
9. Instalación:

- Inicia el proceso de instalación y espera a que se complete.
10. Activación:

- Después de la instalación, es posible que debas activar MATLAB. Sigue las instrucciones proporcionadas durante el proceso de activación.
11. Finalización:

- Una vez que la instalación y la activación se completen con éxito, deberías poder iniciar MATLAB desde el menú de inicio o la terminal, según tu sistema operativo.



## Anexos
### Porcentaje de entrenamiento y Testeo 

![Login.](https://github.com/Kevin-Saquinga/ImagenesGit/blob/main/3.png?raw=true)
### Entrenamiento de una red Neuronal 
![Login.](https://github.com/Kevin-Saquinga/ImagenesGit/blob/main/2.png?raw=true)

### Sistema de Reconocimiento

![Login.](https://github.com/Kevin-Saquinga/ImagenesGit/blob/main/1.png?raw=true)
