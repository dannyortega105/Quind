# Quind
Prueba tecnica en Quind
Proyecto: ETL para renta de películas
Este proyecto realiza un ETL y un análisis exploratorio de datos para un conjunto de datos que incluye información sobre clientes, tiendas, inventario y rentas de películas. Utiliza PySpark para manejar y analizar grandes volúmenes de datos, y Pandas para exportar los resultados a archivos Excel.

Estructura del Proyecto

Prueba_Quind.ipynb: Este notebook contiene el código y los análisis realizados. Se incluyen la carga de datos, trasformacion de los datos, el análisis exploratorio, la integración de datos entre tablas, y la exportación de resultados a archivos Excel.
Función exportar: Una funcion personalizada en Python que extrae la información de un archivo de Excel segmetandolo en DataFrames a cada una de sus hojas.
Función trasformacion: Una funcion personalizada en Python para realizar trasformaciones como quitar caracteres que esten afectando los datos, quitar nulos, cambiar el formato de fecha y separar la fecha y hora.
Función cargar: Una función personalizada en Python que exporta DataFrames de PySpark a archivos Excel para facilitar el análisis y la visualización de resultados en hojas de cálculo.
output/: Carpeta donde se almacenan los archivos Excel generados.
Requisitos del Proyecto
Para ejecutar este proyecto, asegúrate de tener instalados los siguientes paquetes:

PySpark
Pandas
XlsxWriter (para la exportación a Excel)
Para instalar los paquetes necesarios:

pip install pyspark pandas xlsxwriter

Ejecución del Proyecto
Clona este repositorio en tu máquina local.
Abre el archivo Prueba_Quind.ipynb en Jupyter Notebook o en un entorno compatible.
Es necesario validar que la ruta para consumir el archivo quede correcto.
Ejecuta cada celda para realizar el análisis exploratorio y generar los archivos Excel con los resultados.
