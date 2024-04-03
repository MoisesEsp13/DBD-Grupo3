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


