y nm# Requerimientos

### Caso de uso (ingresar nro) : Ingreso información general

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

### Caso de uso (ingresar nro) : Ingreso información de referencia

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

### Caso de uso (ingresar numero) : Ingreso conceptos de negocio
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

### Caso de uso (ingresar numero) : Ingresar información del modelo DDV

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

### Caso de uso (ingresar numero) : Buscar y colocar equivalencias


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
