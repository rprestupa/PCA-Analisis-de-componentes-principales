# PCA-Analisis-de-componentes-principales
En este repo se aplica la técnica de PCA para trabajar con un archivo de 30 variables.
<br><br>
Se aplicó el PCA para reducir la dimensionalidad del dataset, que consistía originalmente en 30 variables mas una variable dicotómica que determina si el registro corresponde a una imagen maligna o benigna. 
Se obtienen 3 Componentes, y se calcula el peso que aporta cada variable original a las nuevas variables, y se visualiza en el siguiente gráfico: 
<br><br>
![](https://github.com/rprestupa/PCA-Analisis-de-componentes-principales/blob/main/images/mapa%20de%20calor%20-%20componentes.png)
<br><br>
Posteriormente, se calcula el porcentaje de la varianza original que logra retenerse con las nuevas variables (Componentes). Se observa que el primer comopnente explica el 44% de la varianza, mientras que el segundo explica el 19% y el último alrededor de un 10%, sumando entre los tres un 72% de la variabilidad original del dataset, por lo que se concluye que es viable reducir la cantidad de variables a solo 3, sin perder una cantidad significativa de información:
<br><br>
![](https://github.com/rprestupa/PCA-Analisis-de-componentes-principales/blob/main/images/Gr%C3%A1fico%20de%20la%20varianza%20explicada%20por%20CP.png)
<br><br>
Finalmente, se grafica la dispersión de los datos, en donde se observa que las dos primeras Componentes, permiten discriminar los registros en función de la variable Tipo (maligno/benigno):  
<br><br>
![]()
<br><br>
