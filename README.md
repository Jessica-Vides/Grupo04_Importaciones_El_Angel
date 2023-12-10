# Grupo04_Importaciones_El_Angel
Contiene la información del proyecto de la especialización de ingeniería de datos del grupo 04 2023

Integrantes:
Kevin Eliseo Arévalo Beltrán               AB12010
Elías Artuto Díaz Sorto                    DS13013
Jessica Esmeralda Vides Romero             VR12015

En este repositorio encontrará los archivos que forman parte de la segunda etapa de proyecto denominado: "Análisis de información sobre ventas de la empresa Importaciones El Ángel gestionada a través del sistema Magento Commerce."

Para cumplir con tal propósito se ha propuesto la creación de un DataWarehouse que contiene toda la información relevante acerca de las ventas realizadas en los años 2020 a 2023.

La solución consiste en seguir el proceso de modelado de DataWarehouse, desde la extracción de Datos hasta la presentacion de reportes en Power BI. La base de datos utilizada es MySQL desde la cual se extrae toda la data y esta es almacenada en un DataLake utilizando el servicio de AWS, Amazon S3. En este se ha creado una estructura de carpetas para cada etapa de transformación de los datos hasta la presentación, las cuales se han llevado a cabo con la herramienta Talend Open Studio (TOS). También, se utiliza el servicio de RedShift para almacenar la data transformada y la cual podrá ser consultada a través de Power BI.

-Métricas utilizadas
  -Las métricas de interés establecidas por Importaciones El Ángel son:
    o Volumen de ventas totales cada trimestre por tienda. 
    o Producto con mayores ventas durante los últimos 3 meses por tienda. 
    o Producto con mayores ventas durante los últimos 3 meses. (Acumulado de todas las tiendas). 
    o Servicio de pago más usado en los últimos 3 meses. 
    o Meses con mayores ventas al año por tienda. 
    o Porcentaje de clientes a los que se les completa una venta mayor a $600. 
    o Monto total de ventas mensuales por cliente. 
    o Ventas totales por cliente de un mismo departamento.
    o Total, de descuentos aplicados en los últimos meses por tienda.

-Tablero de datos
  El tablero que contiene las visualizaciones se encuentra en el archivo "Tablero Magento G04.pbix"
