# Taller de Algoritmos de Ordenamiento - Equipo 1

## Descripción
Desarrollo, análisis y comparación de algoritmos de ordenamiento de datos. El objetivo principal es evaluar el comportamiento teórico y experimental de diferentes métodos utilizando datos reales.

## Dataset
Se utilizó el archivo `customer_master.csv`, extrayendo específicamente la columna numérica `customer_postal_code` para realizar las pruebas de rendimiento con códigos postales.

## Tecnologías
- Python
- Librerías utilizadas: `pandas`, `time`

## Implementación
Se programaron 5 algoritmos de ordenamiento:
1. Bubble Sort
2. Selection Sort
3. Insertion Sort
4. Merge Sort
5. Quick Sort

Cada script se encarga de cargar el archivo CSV, aislar los códigos postales, ejecutar el algoritmo de ordenamiento midiendo su tiempo en segundos de los 25.000 datos e imprimir los primeros 10 esultados ordenados.

## Cómo ejecutar en diferentes entornos

## VisualStudio
1. Descarga la carpeta completa a tu computadora.
Abre Visual Studio Code.
2. Ve a Archivo > Abrir carpeta y selecciona la 3ra carpeta del proyecto.
3. Abre la terminal con Ctrl + ñ.
4. Escribe: python estructuras_de_datos_parcial_3.py en la terminal y presiona enter

## COLAB
1. Abre Google Colab y crea un notebook nuevo.
En la primera celda, pega este código y ejecútalo:
   from google.colab import files
   uploaded = files.upload()
2. Haz clic en el botón que aparece y sube el archivo customer_master.csv desde tu computadora.
3. En una nueva celda, pega el contenido del archivo .py.  Shift + Enter.

## Spyder
1. Descarga la carpeta completa del proyecto
2. Abrir spyder
3. Ve a Archivo > Abrir y selecciona el archivo estructuras_de_datos_parcial_3.py.
Verifica que el archivo customer_master.csv se encuentre en la misma carpeta que el script .py.
4. Run o Ejecutar

## Desde la terminal
1. Ubica la carpeta del proyecto (cd)
2. Ejecuta: python estructuras_de_datos_parcial_3.py o python3 estructuras_de_datos_parcial_3.py
(El archivo de datos debe estar disponible en la misma carpeta del programa)

Estructura recomendada:

```bash
python estructuras_de_datos_parcial_3.py
