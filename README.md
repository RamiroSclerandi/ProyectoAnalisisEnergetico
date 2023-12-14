# Proyecto de análisis energético

## Descripción del proyecto
Este proyecto implica un análisis integral de datos relacionados con la energía utilizando varias técnicas de aprendizaje automático, incluido el análisis de datos exploratorios (EDA), agrupación y regresión. El objetivo principal es obtener información sobre los patrones y tendencias energéticos globales.

El proyecto abarca:
* Análisis exploratorio de datos (EDA): Se realizó un examen exhaustivo del conjunto de datos, explorando estadísticas clave, identificando patrones y visualizando tendencias para comprender la estructura subyacente de los datos.
* Análisis de agrupación: Utilizando técnicas de agrupación como K-means y DBSCAN, el proyecto identifica grupos de países con características energéticas similares. Se presenta la metodología de agrupamiento y sus resultados, ofreciendo una perspectiva novedosa sobre los paisajes energéticos globales.
* Análisis de Regresión: Se implementaron modelos de regresión para predecir ciertas variables relacionadas con la energía. La elección del modelo de regresión y su justificación se detallan en el proyecto.

Además, este proyecto sirve como ejemplo práctico de cómo se puede estructurar con fines de asesoramiento un análisis exhaustivo, que incluya EDA y diversas técnicas de aprendizaje automático. Ofrece un modelo para abordar datos relacionados con la energía, obtener conocimientos significativos y presentar hallazgos de manera coherente.

## Cómo instalar y ejecutar el proyecto
Para configurar y ejecutar el proyecto localmente, siga estos pasos:

1. Debes instalar git lfs para poder descargar el archivo original automáticamente. Esto se puede hacer siguiendo los pasos en el siguiete URL: https://git-lfs.com/

2. Abre una terminal y navega hasta el directorio donde quieras tener el repositorio local:
`cd proyecto-análisis-energético`

3. Clonar el repositorio en tu máquina local:
`git clone https://github.com/RamiroSclerandi/ProyectoAnalisisEnergetico.git`

4. Inicializar git LFS con el siguiente comando en el directorio seleccionado:
`git lfs install`

5. Verifica que tengas el archivo 'ProyectoEndToEnd.ipynb' con el siguiente comando:
`git ls`

6. Instalar las dependencias necesarias:
`pip install -r requisitos.txt`

7. Ejecutar los Jupyter Notebooks para ejecutar análisis de regresión y agrupamiento.

* Paso extra: Si llegaste hasta el paso 5 y no pudiste obtener correctamente el archivo mencionado, puede ir al repositorio en github (link del paso 3), seleccionar el archivo y descargarlo como RAW.

## Cómo utilizar el proyecto
Los Jupyter Notebooks proporcionan una guía paso a paso para los análisis de regresión y agrupamiento. Consulte los siguientes notebooks para tareas específicas:

* proyectoEndToEnd.ipynb: Este notebook abarca todo el proyecto, cubriendo limpieza de datos, preprocesamiento, análisis de datos exploratorios (EDA), análisis de regresión y técnicas de agrupamiento como K-Means, agrupamiento jerárquico, DBSCAN y propagación de afinidad. Asegúrese de revisar los comentarios y la documentación dentro del cuaderno para obtener información adicional.

## Resultados y conocimientos
Los resultados y conocimientos obtenidos del proyecto están disponibles en el cuaderno 'proyectoEndToEnd.ipynb'. La visualización de los resultados se facilita a través de diversos gráficos y tablas incorporados directamente dentro del cuaderno.

## Licencia
Este proyecto es una iniciativa de código abierto. Siéntete libre de contribuir, modificar y utilizar el código para tus proyectos.

## Desarrolladores
Ignacio Bértola, Francisco Franco y Ramiro Sclerandi. Todos estudiantes de la carrera Ingeniería en Computaicón en la Universidad Nacional de Rafaela.