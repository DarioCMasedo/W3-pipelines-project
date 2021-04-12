# Liga de futbol español en la temporada 2018-2019

Pipelines Project - Bootcamp Data Analytics Ironhack

En este proyecto sacaremos datos de un data set de laliga de futbol española de la temporada 2018-2019.
Teniendo datos de todos los equipos, partidos, goles, asistencias, penaltis, etc....
Gracias a la API obtenida podremos ver la fecha de los partidos, en que cmapo se jugo, quien gano, etc....

# Limpieza

Primero he limpiado el dataset, eliminando las columnas que no eran necesarias para el análisis, he recategorizado las condiciones de la muerte para evaluar si el tipo de muerte está influido por las condiciones climáticas y he renombrado los países para que estuvieran bien agrupados los lugares. Después me he quedado con columnas necesarias para recopilar datos.


# API:

He utilizado la api de la pagina: https://www.football-data.org/documentation/quickstart

Con esta API podremos obtener cualquier dato de la temporada 2018-2019 de la liga española de futbol,
puediendo asi sacar todo lo que queremos para este proyecto.

Para la API he utilizado un programa llamado postman, el cual te facilita ver los datos de la api obtenida
gracias a su interfaz.

# Analisis

Con todo lo anterior, hemos podido obtener a los 5 mejores equipos,
quien ha marcado mas goles, quien ha dado mas asistencias, quien ha marcado mas goles de penalti, etc...


# Librerias usadas

import requests
import pandas as pd
import json
import numpy as np
import matplotlib.pyplot as plt
import matplotlib.patches as mpatches
import seaborn as sns
import difflib