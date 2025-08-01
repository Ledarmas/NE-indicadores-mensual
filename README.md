# NE-indicadores-mensual
NE-indicador-mensual  Esta carpeta contiene el script principal en Python y las 3 queries SQL necesarias para el análisis de métricas de Boti NE.

## Uso

1. Ejecutar las tres queries en AWS Athena para obtener los datasets:  
   - **query-mensajes.txt**  
   - **query-botones.txt**  
   - **query-clicks.txt**

2. Descargar los resultados y guardarlos como archivos CSV con los mismos nombres (`mensajes.csv`, `botones.csv`, `clicks.csv`).

3. Abrir el script `Métricas_Boti-NE-script.ipynb` en VSCode o Jupyter Notebook.

4. Cargar los 3 datasets generados por las queries en la carpeta indicada dentro del script.

5. Ejecutar todo el notebook para obtener el análisis.
