# Modulo2-EvaluacionIntermedia_SandraMoreno

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
Utilizando la biblioteca BeautifulSoup en Python, extrae información de la siguiente web. Debes
extraer la tabla de senderos de España con la siguiente información:
1. Identificador.
2. Denominación.
3. Itinerario.

   
Parte 2: Obtención de Datos Climatológicos con la API de AEMET
Utiliza la API de AEMET para obtener información climatológica de la Sierra de Gredos. En
concreto deberás usar el endpoint de "predicciones-especificas" la predicción de montaña para
la sierra de gredos. Debe realizar las siguientes tareas:
1. Incluir la temperatura máxima en la Sierra de Gredos.
2. Incluir la temperatura mínima en la Sierra de Gredos.
3. Incluir la fecha en la que se recopilaron los datos.
4. Incluir la sierra de donde vienen los datos.
Tendrás que obtener un DataFrame similar al que observas a continuación
![image](https://github.com/sandranomore/promoA-DA-modulo2-evaluaci-ni-sandra_moreno/assets/159695823/2c198059-cb81-4c0c-b833-ce5d71892574)

Tu objetivo es crear el código de dos tablas en SQL:
1. Tabla para almacenar los siguientes datos:
 ![image](https://github.com/sandranomore/promoA-DA-modulo2-evaluaci-ni-sandra_moreno/assets/159695823/026e42e8-e470-4aba-ac0c-0240ebdaf46a)
2. Tabla para almacenar la información recogida en los datos climatológicos de la Parte 2.
