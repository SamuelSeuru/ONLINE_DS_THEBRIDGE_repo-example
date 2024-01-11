# EXPLORATORY DATA ANALYSIS EDA

### Autor
* [Samuel Seuru](https://github.com/SamuelSeuru)


**Primer EDA para el Bootcamp de Data Science.**




#### El contexto

Cada año se producen en todo el mundo numerosos terremotos que pueden llegar a causar numerosos daños de diversa consideración, tanto humana como material. Desgraciadamente, cuando los seres humanos pierden la vida a consecuencia de estas catástrofes naturales, un sentimiento de incapacidad frente al timing de un terremoto nos lleva inevitablemente a querer anticipar el lugar y la magnitud del próximo seísmo para evitar futuras víctimas. 

Como geólogo, sé que es imposible anticipar un terremoto menos de 4 segundos antes de que emanen las ondas que causan los daños. Lo que no es necesariamente útil para hacer planes de evacuación...

#### Pero...

Pero, ¿podemos deducir cuáles son las zonas de riesgo y con mayor probabilidad de terremotos? La respuesta es SÍ, sobre todo en las dorsales oceánicas y, más en general, allí donde confluyen dos placas tectónicas. Pero, ¿y en España o Francia? ¿Ha habido terremotos de gran magnitud en el pasado? ¿Siempre en la misma zona? ¿Es probable que se produzca un terremoto de gran magnitud en el futuro?

#### Objetivo

Mi objetivo es que un análisis del censo de terremotos ocurridos en el siglo XXI en España podría darnos pistas para identificar posibles zonas donde parece que la frecuencia de terremotos es mayor. Esto podría ser útil para investigar si existen en estas zonas planes de emergencia y/o de evacuación, adaptados a la potencial peligrosidad y vulnerabilidad sísmica de estas zonas.

#### Herramientas

Como herramientas, he usado diferentes librerías de Python, como por ejemplo pandas o seaborn. Todos los mapas creados son interactivos, gracias a la librería Folium. Las estadísticas las he hecho con el sub-package stats de la librería Scipy.