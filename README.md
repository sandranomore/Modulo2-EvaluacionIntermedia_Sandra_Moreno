# promoA-DA-modulo2-evaluacionI-sandra_moreno

Ejercicio Intermedio Módulo 2

Instrucciones:
Esta evaluación consta de una serie de ejecicios para poner en práctica herramientas de
extracción de datos con Python y en la creación de BBDD con SQL.
Tiempo asignado: 2 horas y 40 minutos.
Puedes usar recursos externos, incluyendo internet y materiales de referencia o tus
propias notas.
Completa los ejercicios en un jupyter notebook y el MySQL Workbench.
Entrega: Tienes que crearte un repositorio en la organización de Adalab que tenga el
siguiente nombre promo-X-DA-modulo2-evaluacion-intermedia-vuestronombre.

Ejercicios
Parte 1: Web Scraping con BeautifulSoup
Utilizando la biblioteca BeautifulSoup en Python, extrae información de la siguiente. Debes
extraer la siguiente información:
1. El nombre de las rutas que aparecen en la página web.
2. Donde esta ubicada la ruta.
3. El tipo de ruta. Si esta información añadir "Desconocido".
4. Duración de la ruta.
5. Los kilometros de la ruta.
6. La dificultad de la ruta.
7. El esfuerzo de la ruta.
8. La descripción de la ruta.
9. Tendrás que obtener un DataFrame similar al que observas a continuación
    ![image](https://github.com/sandranomore/promoA-DA-modulo2-evaluaci-ni-sandra_moreno/assets/159695823/d412da6a-e9bc-4d96-96f9-4c259ecb3b09)


    
Parte 2: Obtención de Datos Climatológicos con la API de AEMET
Utiliza la API de AEMET para obtener información climatológica de la Sierra de Gredos. En
concreto deberás usar el endpoint de "predicciones-especificas" la predicción de montaña para
la sierra de gredos.

Debe realizar las siguientes tareas:
  
1. Incluir la temperatura máxima en la Sierra de Gredos.
2. Incluir la temperatura mínima en la Sierra de Gredos.
3. Incluir la fecha en la que se recopilaron los datos.
4. Incluir la sierra de donde vienen los datos.
Tendrás que obtener un DataFrame similar al que observas
![image](https://github.com/sandranomore/promoA-DA-modulo2-evaluaci-ni-sandra_moreno/assets/159695823/666fd9b2-0db0-4b44-8e06-df5ed6f98d4b)


Parte 3: Diseño de una Base de Datos en SQL
Tu objetivo es diseñar una base de datos para almacenar la información de las rutas de
montaña y los datos climatológicos de la Sierra de Gredos, pero debes de tener en cuenta que
en un futuro podremos incluir más información de otras sierras de la Península Ibérica. Debes
diseñar al menos dos tablas y definir las relaciones entre ellas.
BONUS: Escribir el código de la creación y relación entre las tablas.

