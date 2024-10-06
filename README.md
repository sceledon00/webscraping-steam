# webscraping-steam
## _Analítica Descriptiva - Factores de éxito en los géneros de videojuegos_

#### Descripción
El presente proyecto explora los factores que contribuyen al éxito de los videojuegos, con un enfoque principal en el análisis de género. Se profundiza en cómo los géneros de videojuegos como de acción, aventura e indie influyen en métricas como reseñas, calificaciones, precios y participación de los jugadores. Utilizando datos de Steam, el estudio investiga las relaciones entre estas variables, ofreciendo información valiosa para desarrolladores, editores y distribuidores a la hora de optimizar sus estrategias para alcanzar el éxito en el mercado. Se trabajo con mas 7000 datos y los hallazgos se presentaron mediante análisis estadísticos, incluidas pruebas ANOVA y Levene ente otras.

## Contenido
- Webscpraing steam.ipynb: Codigo utilizado tanto para la extracción de los datos como su posterior limpieza y analisis.
  
- Analitica Webscraping Steam.pdf: Informe realizado en latex donde se menciona todo el desarrollo del proyecto y el porqué se escogieron ciertos parametros.
  
- df_juegos_limpio.csv: Archivo que contiene los datos extraidos de la pagina de steam, especificamente la sección de novedades, como indica su nombre ya cuenta con su respectiva limpieza (960 juegos y 8 columna de datos)


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

## _Webscapring steam.ipynb_:  
Este nootebook cuenta con la extracción de los datos y la posterior manipulación de estos, ademas cuenta con las instalaciones de las librerias necesarias en caso de no contar con estas, por ende su uso se limita al navegador web, el cual se utilizó "Brave" y se recomienda configurarlo como predeterminado.

## _df_juegos_limpio.SCV_:
Archivo csv utilizado para el análisis su visualizacion, si se desea no realizar el webscraping, puede implementar este archivo desde la sección de "Visualización y Analisis de datos" que se encuentra en el codigo pricipal (Webscraping steam.ipynb)

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

## Autores

Proyecto realizado por **Thiare Guerrero** [Thivre](https://github.com/thivre) y **Sebastián Celedón** [sceledon00](https://github.com/sceledon00)

**2024-s2 ANALÍTICA INFB6100**
