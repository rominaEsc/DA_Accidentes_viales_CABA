# <h1 align=center> **PROYECTO INDIVIDUAL Nº2** </h1>
# <p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center>**`DA_Accidentes_viales_CABA`**</h1>

<p align="center">

## Introducción:
Los siniestros viales, también conocidos como accidentes de tráfico o accidentes de tránsito, son eventos que involucran vehículos en las vías públicas y que pueden tener diversas causas, como colisiones entre automóviles, motocicletas, bicicletas o peatones, atropellos, choques con objetos fijos o caídas de vehículos. Estos incidentes pueden tener consecuencias que van desde daños materiales hasta lesiones graves o fatales para los involucrados.

El Observatorio de Movilidad y Seguridad Vial (OMSV), centro de estudios que se encuentra bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires, tiene como objetivo sistematizar y analizar información para comprender la situación actual en materia de seguridad vial y movilidad.

En este proyecto se nos propone, desarrollar el rol de un analista de datos al que el observatorio le solicita la elaboración de un proyecto de anális de datos, con el fin de generar información que le permita a las autoridades locales tomar medidas para disminuir la cantidad de víctimas fatales de los siniestros viales. Para ello, nos disponibilizan un dataset sobre homicidios en siniestros viales acaecidos en la Ciudad Autónoma de Buenos Aires (CABA) durante el periodo 2016-2021. 


# Herramientas y librerias utilizadas:
* VSC

* Python

  - Pandas
 
  - Seaborn
 
  - Matplotlib

# Contenido del repositorio.

El repositorio contiene dos carpetas data y notebooks. 

  - Data

La carpeta data contiene tres archivos, homicidios.xlsx, hechos.csv y victimas.csv y una carpeta llamada diccionarios. 

El archivo homicidios.xlsx fue provisto por el OMSV. Este contiene dos hojas llamadas 'hechos' y 'víctimas' con información sobre los accidentes viales con víctimas fallecidas en CABA entre los años 2016 y 2021. Además, contiene dos hojas adicionales con diccionarios sobre las variables de las hojas anteriormente vencionadas. 

El archivo llamado hechos.csv fue obtenido del procesamiento de la hoja 'hechos' del archivo homicidios y el archivo llamado victimas.csv fue obtenido del procesamiento de la hoja 'victimas' del archivo homicidios.xlsx.

La carpeta diccionarios contiene archivos cvs obtenidos a partir de las hojas DICCIONARIO_HECHOS Y DICCIONARIO_VICTIMAS del archivo homicidos.xlsx. Los dataset aquí contenidos nos permiten entender las variables y los valores en los datasets hechos.csv y victimas.csv.

 - Notebooks

La carpeta data contiene archivos .ipynb en los que se exploró y analizaron los datasets hechos.cvs y victimas.csv

# KPIS

  - KPI1: 

Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior

Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. 

Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000

  - KPI2:
    
Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior

Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. 

Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100

  - KPI3:
    
Reducir en un 6% la cantidad de victimas mortales en avenidas en el último año, en CABA, respecto al año anterior.

Definimos a la cantidad de victimas mortales en avenidas como el número de víctimas fatales en accidentes de tránsito ocurridos en un tipo de calle considerado avenida en un determinado período temporal.

Su fórmula es: (Número de accidentes mortales en avenidas en el año anterior - Número de accidentes mortales en avenidas en el año actual) / (Número de accidentes mortales en avenidas en el año anterior) * 100
