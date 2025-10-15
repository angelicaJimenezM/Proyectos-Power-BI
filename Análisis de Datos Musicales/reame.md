###**Análisis de Datos Musicales**

##**Objetivo**

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