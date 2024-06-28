# Creacion del dashboard

### 1. Fuente de Datos
Debido a los inconvenientos que se fueron presentados en cuanto a la conexion con la base de datos (al trabajar de manera remota los analistas no tenian acceso a la base de datos en SQL por cuestiones de espacio en el ordenador) se realizo una limpieza extra para poder crear las visualizaciones correctamente 
- Conección del Power BI a la fuente de datos: con un script de python. [Limpieza+Script](https://github.com/PalomaOrtizm/Drinks-Basket/blob/main/Data%20Analysis/LimpiezaDataAnalysis.ipynb)
- La coneccion se comprobo en 2 computadoras extrayendo la base de datos de SQL tambien.
- Se adjuntan csv creados a partir del script [Acceso CSV](https://drive.google.com/drive/folders/1hhqxaTdul2z9jY-BFsLlhlr6dEB2Ovfm?usp=drive_link)

### 2. Tecnologías
- **Power Bi**: Para crear el tablero interactivo.
- **VSC (Python)**":  Fuente de datos.

### 3. ETL (Extract, Transform, Load)
- **Extracción**: Importación de datos con script de python.
- **Transformación**: Limpieza de datos, tratamiento de valores nulos, normalización y creación de nuevas columnas calculadas, como así
- también de tablas como la de calendario.
- **Carga**: Inserción de los datos limpios y transformados en las tablas correspondientes.

### 4. Análisis Exploratorio de Datos ([EDA](https://github.com/PalomaOrtizm/Drinks-Basket/blob/main/EDA.ipynb)) : Exploración Inicial
- Análisis descriptivo utilizando Python (Pandas, Matplotlib, Seaborn).
- Se realizaron las primeras visualizaciones para ver primeros insights y plantear el futuro analisis.

### 5. Visualizaciones del EDA
- Creación de gráficos de dispersión, histogramas, gráficos de barras y mapas de calor para identificar patrones y tendencias.

### 6. [Dashboard Interactivo](https://github.com/PalomaOrtizm/Drinks-Basket/blob/main/Data%20Analysis/TableroFinal.pbix)
- Creación de dashboards en Power BI para visualizar los resultados del análisis.
- Implementación de segmentadores, gráficos interactivos y reportes dinámicos.
- Incorporacion de analisis externo para evaluar la posibilidad de expansion. 

### 7. Documentación y Presentación
- Documentación detallada del proceso de análisis y resultados obtenidos.
- Presentación de hallazgos clave utilizando técnicas de storytelling y visualización atractivas.

De esa manera se realizo la parte de analisis, hubo muchas trabas tecnicas al principio pero se llego al resultado final en el tiempo planteado.
Seguramente sea mejorado con el paso del tiempo para futuros lectores.
