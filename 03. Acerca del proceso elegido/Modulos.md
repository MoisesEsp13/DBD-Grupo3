# Módulos

## Módulo de Registro de Usuario

Ingresar descripción

Ingresar interracción con otros módulos

Ingresar responsabilidades

## Módulo de Inicialización de Documento

Ingresar descripción

Ingresar interracción con otros módulos

Ingresar responsabilidades

## Módulo de Ingreso de Información y Equivalencias

Facilitará el ingreso de la información general, de referencia y los conceptos de negocio, así como la información del modelo DDV. Asimismo, buscará las equivalencias de las referencias dadas y las ingresará en los campos requeridos.

#### Interracción con otros módulos: 
Módulo de Inicialización de Documento.

#### Responsabilidades

Mostrar opciones de llenado de los campos del sector de información general.

Mostrar opciones de llenado de los campos tipo de referencia, esquema de referencia, tabla de referencia y campo de referencia.

Mostrar opciones de llenado de los campos dominio, subdominio, producto de dato, historia y todo lo restante del sector concepto de negocio.

Permitirá completar los datos del modelo DDV, ya sea con una opción para insertar datos o para seleccionarlos de una lista predeterminada, según sea el caso.

Buscar equivalencias de los campos de referencia.

Colocar equivalencias en los campos requeridos.

## Módulo de Reglas de Precarga y Carga 

Se trata de aplicar las reglas de precarga obligatorias y sus soluciones (Table Reject), así como considerar los casos de aplicación de las demás reglas (condiciones), considera casuítico aplicar las reglas de precarga opcionales, el encargado de decidir lo hace mediante una lista desplegable en excel,también se muestra una descripción de lo que hace cada una de las reglas.

Sobre las reglas de carga se trata de escribir el codigo en SQL, PySpark, pseudocódigo, etc. Además se debe explicar paso por paso y de manera que puedan ser entendidos por todos los usuarios del negocio. 

Este modulo interacciona con el de Ingreso de información y equivalencias, pues en las reglas de carga se hacen los joins entre las referencias y el universo.

#### Responsabilidades

Verificar las reglas de precarga obligatorias y enviar a la tabla Reject las que no cumplan.

Consultar la aplicación de las reglas de precarga opcionales.

Mostrar una descripción adecuada de las reglas de precarga.

Posibilitar la comprensión del usuario de negocio de las reglas de carga, explicando paso a paso la codificación.



## Módulo de Registro de Seguridad del Dato


Este módulo se encarga de registrar los datos sensibles así como la criticidad de cada uno de estos. Para ello, se basan de documentos de interfaz (mayormente) proporcionados por los usuaros, que son quienes definen la sensibilidad y criticidad.

### Interacción 

Este módulo interactúa con el Módulo de Ingreso de Información e Equivalencias.
### Responsabilidades
* Revisar el Documento de interfaz. 
* Identificar los datos de alta criticidad.
* Registrar dichos datos en la sección DAC mediante la lista despegable.
* Registrar la criticidad del dato de acuerdo al pedido del ususario.
* Registrar,el sustento de la criticidad del dato si es que es considerado crítico.
* Registrar el Nivel de seguridad de dicho dato.
* Registrar la frecuencia de actualización del dato en la fuente.
* Llenar el consumo aplicativo solo si aplica para su casi de negocio.
* Llenar la información adicional de acuerdo a los lineamientos.
* Actulizar el Documento de alcance DDV preliminar en el Sharepoint.
## Módulo de  Reporte y Registro de errores

Ingresar descripción

Ingresar interracción con otros módulos

Ingresar responsabilidades

# Diagrama UML