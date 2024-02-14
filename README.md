<h1 align=center> Proyecto Individual 2: DATA ANALYSIS </h1>
<h1 align=center> SINIESTROS VIALES EN CIUDAD DE BUENOS AIRES </h1>

## Introduccion : 
En un mundo cada vez más interconectado, la seguridad vial se ha convertido en una prioridad para las autoridades locales. Los siniestros viales no solo afectan la movilidad de las personas, sino que también pueden tener consecuencias devastadoras para la vida de los ciudadanos. En este contexto, surge el siguiente proyecto que consiste en asumir el rol de un Data Scientist y Data Analyst para analizar los siniestros viales en la Ciudad de Buenos Aires y proporcionar información valiosa que permita tomar medidas concretas para reducir la cantidad de víctimas fatales.

El objetivo principal es utilizar la base de datos oficial del gobierno de la Ciudad de Buenos Aires para realizar un análisis exhaustivo de los siniestros viales. A través de técnicas de procesamiento y visualización de datos, se busca identificar patrones, tendencias y relaciones que ayuden a comprender mejor las causas y consecuencias de estos eventos. Con esta información, las autoridades locales podrán implementar estrategias más efectivas para prevenir accidentes y salvar vidas.

## Tecnologias utilizadas 
- SQLAlchemy
- Sql 
- MySql
- Python 
- Pandas 
- Numpy 
- Seaborn 
- Matplotlib 
- Power Bi
- BeautifulSoup

## Archivo necesario para ejecutar el dashboar en Power Bi
1.  [Archivo .pbix(Power Bi)](PI02DA.pbix)
2.  [Data Set final ](DataSetFinal.csv)

## Resolucion: 
### 1. [Web Scraping](ETL.ipynb):
Durante este proceso se obtienen los datos directamente de la página oficial del gobierno de la Ciudad de Buenos Aires. Este proceso proporcionará la información necesaria para el análisis.

### 2. [EDA](EDA.ipynb): 
Se realiza un análisis exploratorio de los datos para descubrir patrones ocultos. Se Utilizan librerías como Pandas, Numpy, Seaborn y Matplotlib para visualizar y resumir la información relevante.

### 2.1. [ETL](ETL.ipynb): 
SE procesan los datos extraídos mediante técnicas de extracción, limpieza, transformación y carga. Esto permite obtener un conjunto de datos final listo para su análisis.

### 3.[Base de Datos - MySql](SQL.ipynb):
Se crea una base de datos utilizando MySQL para almacenar los datos procesados. Esta base de datos será la fuente de información para el dashboard en Power BI.

### 4. [Creación del Dashboard](PI02DA.pbix):
Se Utiliza Power BI para crear un dashboard interactivo que muestre los resultados del análisis. El dashboard incluye gráficos, tablas y visualizaciones que permitirán a las autoridades tomar decisiones informadas.
Resultados
El producto final del proyecto será un dashboard en Power Bi que presentará los siguientes aspectos:
1. el DashBoard principal donde se pueden realizar todo tipo de consultas al DataSet y configurar los filtros creados.
2.  La segunda página es el KPIs 1: 
* Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.
Definimos a la tasa de homicidios en siniestros viales como el número de víctimas fatales en accidentes de tránsito por cada 100,000 habitantes en un área geográfica durante un período de tiempo específico. Su fórmula es: (Número de homicidios en siniestros viales / Población total) * 100,000
3. La tercera página es el KIps 2: 
* Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.
Definimos a la cantidad de accidentes mortales de motociclistas en siniestros viales como el número absoluto de accidentes fatales en los que estuvieron involucradas víctimas que viajaban en moto en un determinado periodo temporal. Su fórmula para medir la evolución de los accidentes mortales con víctimas en moto es: (Número de accidentes mortales con víctimas en moto en el año anterior - Número de accidentes mortales con víctimas en moto en el año actual) / (Número de accidentes mortales con víctimas en moto en el año anterior) * 100
4. La cuarta página es el KPIs 3: 
* Reducir en un 25% la cantidad de victimas menores de 25 años en CABA , respecto al año anterior. Su fórmula para medir la evolución de los accidentes mortales con víctimas menores a 25 años es: (Número de accidentes mortales con víctimas <= 25 años del año anterior - poblacion total ) / (poblacion total ) * 100 
4. La quinta página son las conclusiones y recomendaciones: 
* En resumen, el proyecto busca combinar la ciencia de datos con la seguridad vial para lograr un impacto positivo en la comunidad. Se espera que las conclusiones ayuden a salvar vidas y a crear una ciudad más segura para todos.

## Contacto : 
- [Repositorio](https://github.com/marygaby147)