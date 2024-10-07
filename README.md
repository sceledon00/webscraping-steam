# webscraping-steam
## _Analítica Descriptiva - Factores de éxito en los géneros de videojuegos_

#### Descripción

El presente proyecto explora los factores que contribuyen al éxito de los videojuegos, con un enfoque principal en el análisis de género. Se profundiza en cómo los géneros de videojuegos como de acción, aventura e indie influyen en métricas como reseñas, calificaciones, precios y participación de los jugadores. 

Utilizando datos de Steam, el estudio investiga las relaciones entre estas variables, ofreciendo información valiosa para desarrolladores, editores y distribuidores a la hora de optimizar sus estrategias para alcanzar el éxito en el mercado. 
Se trabajó con más 7000 datos y los hallazgos se presentaron mediante análisis estadísticos, incluidas pruebas ANOVA y Levene entre otras.


## Contenido

- Webscraping steam V1.ipynb: Versión número 1, donde solamente se extraen los datos y se realizan visualizaciones para encontrar errores para su posterior limpieza.
- Webscpraing steam V2.ipynb: Codigo final utilizado tanto para la extracción de los datos como su posterior limpieza y análisis.
  
- Analitica Webscraping Steam.pdf: Informe realizado en latex donde se menciona todo el desarrollo del proyecto y el porqué se escogieron ciertos parametros.
  
- df_juegos_limpio.csv: Archivo que contiene los datos extraidos de la pagina de steam, especificamente la sección de novedades del primero de Octubre del 2024, como indica su nombre ya cuenta con su respectiva limpieza (960 juegos y 8 columna de datos)


## Teconologías aplicadas 
- Google colab.
- Python.
- BeautifulSoup.
- Pandas
- Seaborn
- Numpy
- matplotlib.ticker
- scipy
- plotly.graph_objects

```sh
!pip install --upgrade matplotlib seaborn
!pip install plotly
```
>Este proyecto fue creado y aplicado %100 en colab, facilitando su implementación remota y sencilla.

## Uso

## _Webscapring steam V2.ipynb_:  

Este notebook cuenta con la extracción de los datos y la posterior manipulación de estos, además cuenta con las instalaciones de las librerías necesarias en caso de no contar con estas, por ende su uso se limita al navegador web, el cual se utilizó "Brave" y se recomienda configurarlo como predeterminado.

## _df_juegos_limpio.csv_:

Archivo csv utilizado para el análisis su visualización, si se desea no realizar el webscraping, puede implementar este archivo desde la sección de "Visualización y Análisis de datos" que se encuentra en el código principal (Webscraping steam V2.ipynb)

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Autores

Proyecto realizado por **Thiare Guerrero** [Thivre](https://github.com/thivre) y **Sebastián Celedón** [sceledon00](https://github.com/sceledon00)

**2024-s2 ANALÍTICA INFB6100**
