# DataWarehouse_Hospital
Data Warehouse diseñado para integrar y analizar información de medicamentos del hospital. Permite detectar quiebres de stock, optimizar abastecimiento y mejorar la trazabilidad mediante modelos dimensionales y reportes en Power BI.

## Cómo abrir el proyecto
1. **Base de datos (SSMS)**
   - Abrir SQL Server Management Studio.
   - Ejecutar los scripts del proyecto en este orden:
     - 01_creacion_bd.sql
     - 02_dimensiones.sql
     - 03_hechos.sql

2. **ETL (SSIS - Visual Studio)**
   - Abrir Visual Studio.
   - Importar la carpeta ETL_HOSPITAL.
   - Actualizar la cadena de conexión al servidor.
   - Ejecutar el paquete ETL_Hospital.dtsx.

3. **Dashboard (Power BI)**
   - Abrir Power BI Desktop.
   - Cargar el archivo .pbix del proyecto.
   - Actualizar la conexión al servidor SQL.
   - Visualizar los indicadores de stock, consumo y proveedores.
