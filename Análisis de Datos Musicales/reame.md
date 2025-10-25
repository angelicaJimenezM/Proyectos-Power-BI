###**Análisis de Datos Musicales**
    **La base de datos que se utilizo para realizar este ejercicio es esta**

  Dataset: [Chinook Database](https://github.com/lerocha/chinook-database)

##**objetivos**

Analizar la base de datos Chinook para identificar patrones en la cantidad de canciones, géneros más producidos, artistas más activos y distribución de álbumes, presentando los hallazgos en un dashboard interactivo desarrollado en Power BI.

### Lo que hice en este paso:

**Conexión de datos**

- Importé las tablas principales: Artist, Album, Track y Genre.
- Establecí relaciones entre ellas (Artista → Álbum → Canción → Género).
- Limpieza y preparación
- Seleccioné solo los campos relevantes (nombres, títulos, duraciones, géneros).
- Seleccione una tabla para que sea macro con las columnas necesarias para el análisis general.

**Creación de KPIs iniciales**
- Total de artistas.
- Total de álbumes.
- Total de canciones.
- Número de géneros distintos.

**Creación de filtros y segmentaciones**

- Filtros dinámicos por artista, género y álbum.
- Segmentadores que permiten analizar cuántos álbumes y canciones tiene cada artista.

**Visualizaciones**

- Tabla dinámica: detalle de canciones por artista y género.

![alt text](image.png)

**---------------------------------------------------------------------------------------------**
### Lo que hice en este paso: 

  **Esto se puede ver en la carpeta SQL**
Después de tener un enfoque más claro sobre los objetivos —como cuál es el propósito del dashboard y qué decisiones se tomarán a partir de él—, realicé un proceso más profundo de depuración y fortalecimiento de la base de datos.

- Se realizó una limpieza completa de la base de datos SQL usando SQL Server, reemplazando los valores nulos para mantener coherencia en los registros.

- Se configuró la base para que no acepte valores nulos, evitando así inconsistencias o datos incompletos en futuras cargas.

- Se revisaron las llaves foráneas y primarias, reforzando las relaciones entre las tablas Track, Album, Artist y Genre.

- Se documentaron las dependencias y restricciones aplicadas para garantizar la integridad referencial de la información.

- Se validaron los datos de forma cruzada, verificando que no existieran artistas sin canciones, álbumes sin referencias o géneros sin asignación.

Con esto, la base de datos quedó lista para conectarse con Power BI de forma estable y confiable, permitiendo construir indicadores sólidos y visualizaciones más precisas.