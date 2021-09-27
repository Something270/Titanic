En este proyecto realizaremos una prediccion de quienes sobreviviran en el titanic.

Iniciamos importando los librerias del proyecto junto con el data set del titanic,
vemos primero los pasajeros que sobrevivieron y los visualizamos en un countplot

![Image Info](./images/Capture1.png)
![Image Info](./images/Capture2.png)
hacemos nuestra primer division , dividiendo los pasajeros por por su clase y sexo, los visualizamos tambien.
Survival rate por clase
![Image Info](./images/Capture3.png)
Survival rate por clase y sexo VISUAL
![Image Info](./images/Capture4.png)
Los sobrevivientes por clase
![Image Info](./images/Capture5.png)
Sobrevivientes por clase, sexo, edad
![Image Info](./images/Capture6.png)

Despues visualizamos los pagos que hicieron los pasajeros de cada clase.
Pagos realizados por clase
![Image Info](./images/Capture7.png)

Continuamos con el conteo de los valores vacios de cada columna para despues eliminarlos,
 Visualizamos los tipos de data y vemos que existen dos columnas con valores tipo objeto,
los convertimos en valores 'int64' para poder utilizarlos.

Ahora podemos comenzar a dividir los datos en training y testing, creamos los modelos para
entrenar los datos, despues realizamos el entrenamiento y vemos el accuracy de training que tuvo cada modelo.

Despues realizamos un confusion matrix y vemos el accuracy de los modelos para el data de test
nos damos cuenta que el Random Forest tuvo el mejor accury en el test data.

Visualizamos la importancia del modelo de forest 
![Image Info](./images/Capture8.png)
Concluimos imprimiendo la prediccion de los sobrevivientes
![Image Info](./images/Capture9.png)
