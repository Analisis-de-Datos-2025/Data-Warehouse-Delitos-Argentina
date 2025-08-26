# Data-Warehouse-Delitos-Argentina

**Descripción del proyecto**: Este proyecto es la implementación de un Data Warehouse con el objetivo de analizar los delitos en la Ciudad de Buenos Aires, Argentina. Nuestro Datawarehouse permite visualizar y comparar los distintos delitos segun metricas,tales como : 
-Horario/Fecha 
-Latitud y longitud 
-Por comuna/por barrio 
-Tipo de delito 

**DATOS:** 
Compuesto por 7 archivos de tipo CSV, correspondiendo un archivo por cada año de los delitos en la Ciudad de Buenos Aires.
   **ATRIBUTOS:**


**Herramientas:** 
Para el proyecto utilizaremos Supabase como base de datos remota. El proceso ETL se implementará mediante una función en Supabase que contiene un script en Python, el cual podrá ejecutarse de forma automática cada vez que se suba un nuevo archivo o con una programación definida previamente. Para la visualización de los datos trabajaremos con Power BI, que permitirá construir dashboards dinámicos y actualizados en tiempo real. 
Para el diseño del modelo dimensional utilizaremos para DRAW.IO 
Para la gestión de versiones y como repositorio utilizaremos GitHub. 
La organizaciones de tareas y responsabilidades lo haremos mediante Jira implementando la metodologia Scrum para la planificación de los Sprints. 
Para la presentación final y gestión del proyecto (Caso negocio, Acta de constitución, Registro de interesados, etc) mediante Google drive.

**Estructura del Proyecto:** 
El repositorio cuenta con distintas carpetas que surgen a partir la carpeta Datawarehouse-Delitos. 
-/data/raw -> Contiene todos los archivos CSV de todos los años (2016-2022) de los delitos ocurrido en la Ciudad de Buenos Aires.
-/Gestion_De_Proyecto -> Contiene todos los docuementos necesarios para una Gestión de un proyecto, tales como Caso de negocio, Acta consitucionales, etc. 
-/REDMI -> Para formalizar toda la información en un documento. 
-/Power_BI -> Archivos .pbix con los dashboards creados
