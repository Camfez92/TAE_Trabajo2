# Segundo trabajo de Técnicas de Aprendizaje Estadístico

Se ha desarrollado un modelo predictivo que permita proyectar el número de vehículos a ser registrados en el RUNT durante el año 2018 a partir de los datos de los años 2012 a 2018 (inclusive). En este repositorio se debe dirigir a la carpeta **RUNT** para poder acceder a los archivos importantes. En este repositorio se encuentran los siguientes archivos:

* *Autos.RData.* Es un documento que incluye la cantidad de vehículos registrados en el RUNT en cada día entre los años 2012 y 2017 y en formato *RData*, el cual es un formato menos pesado y que es procesado por *R* más rápidamente.
* *PredObNN.RData.* Predicción del número de vehículos que son registrados en el RUNT para cada año en el 2018 mediante redes neuronales.
* *RUNT.RData.* Es un documento semejante a *Autos.RData*, pero incluye las variables nuevas: vehículos registrados, día, mes, año, día de la semana, semana del año, TRM y día laborable.
* *Reporte_tecnico.Rmd.* Archivo con el que se creó el informe técnico presentado.
* *Reporte_tecnico.html.* Archivo de lectura del informe técnico. Disponible en https://rpubs.com/scuartasr/TAE_T2_RUNT2018.
* *TRM.xlsx.* Reporte del valor de la TRM al final de cada día por el Banco de la República.
* *TRM18.xlsx.* Reporte del valor de la TRM al final de cada día por el Banco de la República para el año 2018 únicamente.
* *autos.xlsx.* Archivo original entregado para poder desarrollar el modelo predictivo. Solo contiene el número de vehículos registrados en el RUNT cada día entre el 2012 y el 2017.
* *prediccion_2012-2017.csv.* Archivo plano con la puesta en práctica del modelo KNN empleado para predicr el número de vehículos registrados en el RUNT entre el 2012 y el 2017.
* *prediccion_2018.csv.* Archivo plano con la puesta en práctica del modelo KNN empleado para predicr el número de vehículos registrados en el RUNT para el año 2018
* *yr18.RData.* Tabla que tiene los valores de las variables regresoras para cada día del año 2018 para poder conseguir el número de vehículos registrados en el RUNT para el año 2018 con el modelo predictivo que mejor desempeño presenta.
