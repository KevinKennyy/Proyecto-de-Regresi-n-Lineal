# Predicción del Coste del Seguro Médico
Descripción del Proyecto
Este proyecto tiene como objetivo predecir el coste del seguro médico de una persona utilizando técnicas de regresión lineal. La importante compañía de seguros 4Geeks Insurance S.L. ha reunido datos fisiológicos de clientes y desea calcular la prima que debe asignar a cada uno de ellos. Para ello, se ha reunido un equipo de médicos y se ha recopilado un conjunto de datos para entrenar un modelo predictivo.

Instrucciones
Paso 1: Carga del Conjunto de Datos
El conjunto de datos se encuentra en la carpeta del proyecto con el nombre medical_insurance_cost.csv. Puedes cargarlo directamente desde el siguiente enlace:
medical_insurance_cost.csv
O puedes descargarlo y añadirlo manualmente a tu repositorio. Este conjunto de datos contiene las siguientes variables:

age: Edad del beneficiario principal (numérico)
sex: Género del beneficiario principal (categórico)
bmi: Índice de masa corporal (numérico)
children: Número de niños/dependientes cubiertos por el seguro médico (numérico)
smoker: ¿Es fumador? (categórico)
region: Área residencial del beneficiario en USA: noreste, sureste, suroeste, noroeste (categórico)
charges: Prima del seguro médico (numérico)
Paso 2: Realiza un EDA Completo
Realiza un Análisis Exploratorio de Datos (EDA) completo para seleccionar las variables relevantes y eliminar aquellas que no aporten información. Utiliza el Notebook de ejemplo proporcionado y adáptalo a este caso de uso. Asegúrate de dividir adecuadamente el conjunto de datos en entrenamiento y prueba como se ha visto en lecciones anteriores.

Paso 3: Construye un Modelo de Regresión Lineal
Construye un modelo de regresión lineal sin optimizar los hiperparámetros. Comienza con la configuración por defecto y mejora el modelo en el siguiente paso.

Paso 4: Optimiza el Modelo Anterior
Si los resultados del modelo no son satisfactorios, optimízalo según sea necesario.

Archivo del Proyecto
El archivo que contiene el proyecto se llama Proyecto.ipynb.
