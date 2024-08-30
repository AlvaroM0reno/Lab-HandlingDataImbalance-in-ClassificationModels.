Laboratorio | Manejo de desequilibrios de datos en modelos de clasificación
Para este laboratorio y en las próximas lecciones, crearemos un modelo sobre el problema de clasificación binaria de abandono de clientes. Utilizará files_for_lab/Customer-Churn.csvel archivo.

Guión
Trabaja como analista en este proveedor de servicios de Internet. Se le proporcionan datos históricos sobre los clientes de su empresa y sus tendencias de abandono. Su tarea es crear un modelo de aprendizaje automático que ayude a la empresa a identificar a los clientes que tienen más probabilidades de incumplir o abandonar el servicio y, de esta forma, evitar pérdidas de dichos clientes.

Instrucciones
En este laboratorio, primero analizaremos el grado de desequilibrio en los datos y lo corregiremos utilizando las técnicas que aprendimos en la clase.

Aquí está la lista de pasos a seguir (construir un modelo simple sin equilibrar los datos):

Importe las bibliotecas y módulos necesarios que necesite.
Lea esos datos en Python y llame al marco de datos churnData.
Comprueba los tipos de datos de todas las columnas de los datos. Verás que la columna TotalChargeses de tipo objeto. Convierte esta columna en un tipo numérico mediante pd.to_numericuna función.
Compruebe si hay valores nulos en el marco de datos. Reemplace los valores nulos.
Utilice las siguientes funciones: tenure, SeniorCitizen, MonthlyChargesy TotalCharges:
Escale las características utilizando un normalizador o un escalador estándar.
Divida los datos en un conjunto de entrenamiento y un conjunto de prueba.
Ajuste un modelo de regresión logística a los datos de entrenamiento.
Verifique la precisión de los datos de prueba.
Nota : Hasta el momento no hemos equilibrado los datos.

Gestión del desequilibrio en el conjunto de datos

Verifique el desequilibrio.
Utilice las estrategias de remuestreo utilizadas en clase para sobremuestrear y reducir el tamaño del muestreo para crear un equilibrio entre las dos clases.
Cada vez ajuste el modelo y vea cómo es la precisión del modelo.
