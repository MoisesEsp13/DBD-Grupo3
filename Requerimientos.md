# Requerimientos

### Caso de uso 1 : Desarrollo de Interfaz de Usuario

| Objetivo | Administrar la interfaz de usuario para permitir una interacción efectiva con el sistema |
|:----------:|-------------------|
| Descripción | Proceso por mediante el cuál se gestionan los elementos de la interfaz de usuario para garantizar una experiencia de usuario intuitiva y eficaz. |
| Actor | <p align="center"> Diseñador de la interfaz de usuario |
| Precondición | <p align="center"> El administrador del sistema (Ej. BCP) deberá registrar a los usuarios involucrados y proporcionarles las credenciales de inicio de sesión. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El sistema está listo para la modificación de la interfaz a través de las herramientas de desarrollo como React. |
| 2 | El diseñador de la interfaz de usuario diseña una propuesta de implementación al software desarrollado.|
| 3 | Se presenta la propuesta a los encargados de los demás módulos y usuarios involucrados. |
| 4 | Si el equipo acepta la propuesta, se realizan pruebas con las modificaciones realizadas para garantizar que no afecte negativamente al sistema de carga de datos. |
| 5 | Se implementan las modificaciones sugeridas y se actualiza el Software. |
| 6 | El caso de uso termina. |


### Caso de uso 2 : Creación o modificación del Documento de Alcance

| Objetivo | Dar inicio al proceso. |
|:----------:|-------------------|
| Descripción | Proceso donde se da inicio a la creación o modificación de un documento que sirve como garantía para el proceso de migración de datos y este pueda ser entregado al usuario de destino. |
| Actor | <p align="center"> Data Steward |
| Precondición | <p align="center"> El usuario debió iniciar sesión con sus credenciales. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El usuario una vez registrado, estará en la página principal del sistema el cual mostrará dos opciones: “Crear Nuevo Documento de Alcance” y “Modificar nuevo Documento de Alcance”. El usuario deberá escoger una de las dos opciones. |
| 2 | Si ha escogido la opción de “Modificar nuevo Documento de Alcance” deberá escoger el documento que se quiera modificar.|
| 3 | Luego de haber escogido, saldrá una ventana emergente para detallar la versión del documento. Los campos que tendrá serán para especificar qué cambios se va realizar y por quien fue solicitado esos cambios. |

### Caso de uso 3 : Ingreso información general

| Objetivo | Completar la sección de información general con lo datos requeridos en su totalidad. |
|:----------:|-------------------|
| Descripción | Proceso por el cual el usuario podrá seleccionar datos en cada campo requerido. |
| Actor | <p align="center"> Data Steward |
| Precondición | <p align="center"> El usuario debió iniciar sesión con sus credenciales y haber inicializado el documento de alcance que completará. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El sistema muestra la sección de información general con los campos a rellenar. |
| 2 | El usuario selecciona el campo "tecnología" y le da click a una de las opciones dependiendo del caso.|
| 3 | El usuario selecciona el campo "producto owner" y le da click a una de las opciones dependiendo del caso. |
| 4 | El usuario selecciona el campo "squad" y le da click a una de las opciones dependiendo del caso. |
| 5 | El usuario selecciona el campo "responsable" y le da click a una de las opciones dependiendo del caso. |
| 6 | El usuario le dará click a "Siguiente", para poder ingresar los datos de la siguiente sección. |
| 7 | El caso de uso culmina. |

### Caso de uso 4 : Ingreso información de referencia

| Objetivo | Completar los campos de información de referencia. |
|:----------:|-------------------|
| Descripción | Proceso por el cual el usuario podrá seleccionar datos o insertarlos, dependiendo del caso, en cada campo requerido. |
| Actor | <p align="center"> Data Steward |
| Precondición | <p align="center"> Haber llenado la seccion de información general. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El sistema muestra la sección de información de referencia con los campos a rellenar. |
| 2 | El usuario selecciona el campo "tipo de referencia" y le da click a una de las opciones dependiendo del caso. |
| 3 | El usuario selecciona el campo "esquema de referencia" e inserta el dato pedido. |
| 4 | El usuario selecciona el campo "tabla de referencia" e inserta el dato pedido.  |
| 5 | El usuario selecciona el "campo de referencia" e inserta el dato pedido. |
| 6 | El usuario le dará click a "Siguiente". |
| 7 | El caso de uso culmina. |

### Caso de uso 5 : Ingreso conceptos de negocio
| Objetivo | Completar los campos respectivos de los conceptos de negocio. |
|:----------:|-------------------|
| Descripción | Proceso por el cual el usuario podrá seleccionar datos o insertarlos, dependiendo del caso, en cada campo requerido. |
| Actor | <p align="center"> Data Steward |
| Precondición | <p align="center"> Haber llenado la sección de información de referencia e información general. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El sistema muestra la sección de conceptos de negocio con los campos a rellenar. |
| 2 | El usuario selecciona el campo "dominio" y le da click a una de las opciones dependiendo del caso. |
| 3 | El usuario selecciona el campo "subdominio" e inserta el dato pedido. |
| 4 | El usuario selecciona el campo "producto de datos" e inserta el dato pedido.  |
| 5 | El usuario selecciona el "historia" y selecciona la fecha. |
| 6 | El usuario selecciona el "Nombre del elemento de dato" e inserta el dato pedido. |
| 6 | El usuario selecciona el "Nombre del elemento de dato" e inserta el dato pedido. |
|  7| El usuario selecciona el "Definición del campo" e inserta la información pedida. |
| 8 | El usuario selecciona el "Definición de la tabla" e inserta la información pedida. |
| 9 | El usuario le dará click a "Siguiente". |
| 10 | El caso de uso culmina. |

### Caso de uso 6 : Ingresar información del modelo DDV

| Objetivo | Completar los campos de información del modelo DDV |
|:----------:|-------------------|
| Descripción | Proceso por el cual el usuario podrá seleccionar datos o insertarlos, dependiendo del caso, en cada campo requerido. |
| Actor | <p align="center"> Data Modeler |
| Precondición | <p align="center"> Haber llenado la información de conceptos de negocio, referencia e información general. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El sistema muestra la sección de información del modelo DDV con los campos a rellenar. |
| 2 | El usuario selecciona el campo "Esquema DDV" e inserta el dato pedido. |
| 3 | El usuario selecciona el campo "Tipología" y le da click a una de las opciones dependiendo del caso. |
| 4 | El usuario selecciona el campo "Tabla DDV" e inserta el dato pedido.  |
| 5 | El usuario selecciona el campo "Campo DDV" e inserta el dato pedido. |
| 6 | El usuario selecciona el campo "Llave entidad DDV" y selecciona la opción "Si" o "No", dependiendo del caso. |
| 7 | El usuario selecciona el campo "Descartado" y selecciona la opción "Si" o "No", dependiendo del caso. |
| 9 | El usuario selecciona el campo "Comentarios Descarte/Otros" e inserta el comentario solicitado en caso se requiera. |
| 10 | El usuario le dará click a "Guardar". |
| 11 | El caso de uso culmina. |

### Caso de uso 7 : Buscar y colocar equivalencias


| Objetivo | Buscar las equivalencias de los campos de referencia en una base de datos y autocompletarlas en los campos requeridos.|
|:----------:|-------------------|
| Descripción | Proceso por el cual el sistema podrá autocompletar las equivalencias de los campos de referencia en el DLK para que se logre la migración de datos. |
| Actor | <p align="center"> Sistema |
| Precondición | <p align="center"> Haber llenado la sección de información de referencia. |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El sistema recorré cada campo de referencia completado anteriormente.|
| 2 | El sistema busca la equivalencia de cada campo en una base de datos interna.|
| 3 | El sistema asigna a cada campo su respectiva equivalencia. |
| 4 | El sistema autocompleta los campos requeridos con las equivalencias asignadas en el documento DDV.|
| 5 | El caso de uso culmina |
### Caso de uso 8 : Registrar la Seguridad de datos

| Objetivo | Completar la información de seguridad de datos  |
|:----------:|-------------------|
| Descripción | En este proceso se ingresan los datos de seguridad definidos anteriormente.  |
| Actor | <p align="center"> Data Steward |
| Precondición | <p align="center"> Que esté completa la sección de información de referencias |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El usuario selecciona la condición del dato DAC (SI/NO) |
| 2 | El usuario selecciona la criticidad del dato. |
| 3 | El usuario selecciona el sustento de criticidad |
| 4 | El usuario selecciona el nivel de seguridad |
| 5 | El usuario selecciona la frecuencia de actualización |
| 6 | El usuario selecciona el uso en reporte regulatorio |
| 7 | El usuario selecciona la entidad regulatoria|
| 8 | El usuario le dará click a "Actualizar Doc DDV", para poder actualizar los datos y tener una versión preliminar. |
| 9 | El usuario le dará click a "Siguiente", para poder ingresar los datos de la siguiente sección. |
| 10 | El caso de uso culmina. |

### Caso de uso 9 : Registrar información adicional

| Objetivo | Ingresar los datos de la información adicioanal  |
|:----------:|-------------------|
| Descripción | En este proceso se ingresan los datos de la información adicional de proceso |
| Actor | <p align="center"> Data Steward |
| Precondición | <p align="center"> Tener el Doc. de alcance preliminar |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El usuario ingresa el nombre de la tabla DDV|
| 2 | El usuario ingresa el combre del Aplicativo |
| 3 | El sistema genera el Nombre del proceso. |
| 4 | El usuario ingresa el Nombre del Job@ |
| 5 | El usuario selecciona la Frecuencia de ejecución |
| 6 | El usuario selecciona el Detalle de la Frecuencia |
| 7 | El usuario indica un comentario alusivo a la frecuencia de ejecución del job predecesor. |
| 8 | El usuario le dará click a "Siguiente", para poder ingresar los datos de la siguiente sección. |
| 9 | El caso de uso culmina. |
### Caso de uso 10 : Definir Reglas funcionales de precarga y carga


| Objetivo | Enlazar el Universo y la tabla de equivalencias mediante llaves, usar las reglas de precarga preestablecidas para validar los datos|
|:----------:|-------------------|
| Descripción | Proceso en el que se hacen los joins de las tablas, mediante SQL, PySpark, Pseudocódigo. Aplicar validación con las reglas de precarga, mandando a la tabla Reject a los registros que no pasen|
| Actor | <p align="center"> Data Steward/Sistema|
| Precondición | <p align="center"> Haber hallado las tablas de equivalencias con las referencias y haber definido el universo |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El Data Steward se encarga de escribir las reglas de carga como en el lenguaje que prefiera, explicando paso a paso para que sea entendible a los usuarios del negocio|
| 2 | El Sistema se encarga de validar primero las reglas de precarga obligatorias, analizando los casos|
| 3 | Una vez finalizado, el data Governance se encaraga de analizar la casuística de la situación para determinar si se deben aplicar o no las reglas de precarga opcionales |
| 4 | De ser determinado necesario se aplican las reglas de precarga opcionales|
| 5 | El caso de uso culmina |

### Caso de uso 11: Definir Reglas técnicas de carga


| Objetivo | Formalizar las reglas de carga para que puedan ser ejecutadas y realizar un query a la base de datos|
|:----------:|-------------------|
| Descripción | Proceso que consiste en escribir o reescribir el código planteado en el caso de uso 8, para que pueda ser ejecutado por el Data Engineer|
| Actor | <p align="center"> Custodio Técnico|
| Precondición | <p align="center"> Haber pasado las reglas de precarga |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El Custodio Técnico se encarga de llevar el codigo hecho por el Data Steward a uno ejecutable|
| 2 | El caso de uso culmina |

### Caso de uso 12: Complementar definiciones técnicas


| Objetivo | Comprobar el buen funcionamiento de las reglas de carga formalizadas que se tienen en el Caso de uso 11|
|:----------:|-------------------|
| Descripción | El Data Engineer ejecuta el codigo y le da feedback al Custodio técnico, de tal manera que corrige y se lo vuelve a mandar, hasta que cumpla los requerimientos del cliente|
| Actor | <p align="center"> Custodio Técnico/Data Engineer|
| Precondición | <p align="center"> Haber pasado las reglas de precarga |
| <p align="center">  Paso | <p align="center">  Acción </p> |
| 1 | El Data Engineer recibe el codigo de parte del Custodio técnico para ejecutar un query en su basa de datos|
| 2 | El Data Engineer corrige y manda de vuelta el codigo al Custodio técnico, con las observaciones|
| 3 | El Custodio técnico revisa las correcciones y las corrige, para volverlo a mandar.|
| 4 | El ciclo continua hasta que el query haga lo que debería hacer|
| 5 | El caso de uso culmina|