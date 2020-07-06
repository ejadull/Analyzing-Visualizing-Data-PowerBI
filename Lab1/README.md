GUIÓN
VanArsdel es una empresa que fabrica y vende artículos deportivos. La compañía tiene oficinas en los Estados Unidos (EE. UU.) Y en varios otros países. Sus ventas comprenden ventas en los Estados Unidos y ventas internacionales. Las ventas de VanArsdel provienen de sus productos manufacturados, así como de productos de otros fabricantes.

La oficina de VanArsdel en EE. UU. Almacena los datos de ventas en una base de datos de Access. Las transacciones de ventas de VanArsdel International están disponibles como archivos separados por comas (CSV). Podrían ser generados diariamente, ya sea manualmente por alguien o automáticamente por un proceso automatizado. Están disponibles en una carpeta dedicada. Estos archivos CSV tienen la misma estructura de columnas que la tabla de ventas para las ventas en EE. UU. Que proviene de la Base de datos SQL.

Desea realizar un análisis de los datos de ventas mundiales de VanArsdel para el año 2000 a 2015. Debe incorporar todos estos datos a Power BI Desktop antes de poder realizar cualquier análisis. Finalmente, desea comparar las ventas de VanArsdel en el país con la población del país. Debe importar los datos de población del país desde un informe Excel menos estructurado a Power BI.

RESUMEN DE LABORATORIO
Este laboratorio consta de tres ejercicios:

En el primer ejercicio, importará datos a Power BI Desktop desde un archivo de base de datos de Access.
En el segundo ejercicio, importará datos de archivos CSV que residen en una carpeta de archivos. Agregará estos nuevos datos a los datos existentes correspondientes que provienen de la Base de datos de Access.
En el tercer ejercicio, importará datos a Power BI Desktop desde un archivo de Excel menos estructurado.
Antes de comenzar esta práctica de laboratorio, debe revisar el módulo Transformaciones de datos de escritorio de Power BI en este curso. Luego, si aún no lo ha hecho, siga las instrucciones en la sección Configurar el entorno de laboratorio de este curso para configurar el entorno de laboratorio.

LO QUE NECESITARÁS
Una computadora con la última versión de Power BI Desktop instalada.

Una copia de la base de datos de acceso que contiene los datos de ventas de VanArsdel en EE. UU.

4 archivos CSV que contienen los datos de ventas internacionales de VanArsdel :

CA Sales.csv
FR Sales.csv
DE Sales.csv
MX Sales.csv

Un archivo de Excel que contiene datos de población del país .

NOTA : Si tiene problemas con el enlace directo, diríjase al repositorio de github y descárguelo desde allí. https://github.com/MicrosoftLearning/Analyzing-Visualizing-Data-PowerBI

Conexión a una base de datos de acceso por primera vez
Si se conecta a una base de datos de Access por primera vez, es posible que deba instalar el paquete redistribuible de Access.

Si tiene una máquina de 32 bits, debe instalar el Power BI Desktop de 32 bits y el redistribuible de 32 bits de Access.
Si tiene instalada una oficina de 32 bits (independientemente de su máquina), debe instalar el Power BI Desktop de 32 bits y el redistribuible de acceso de 32 bits.
De lo contrario, puede instalar el escritorio Power BI de 64 bits y el redistribuible de acceso de 64 bits.
Siga el enlace proporcionado por Power BI Desktop cuando intente conectarse a la base de datos de Access.
Para obtener más información, puede ver:
Motor de base de datos de Microsoft Access: https://aka.ms/edx-dat207x-made
Power BI: https://aka.ms/edx-dat207x-pbi01
Resolver problemas al importar archivos Access y .XLS en Power BI Desktop: https://docs.microsoft.com/en-us/power-bi/desktop-access-database-errors
