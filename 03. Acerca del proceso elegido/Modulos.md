# Módulos

## Módulo de Interfaz de Usuario

Se encarga de la interacción del usuario con el software creado, encargándose de la disposición de los elementos visuales y sus respectivas funciones.

#### Interracción con otros módulos: 
Esta presente como estrategias de diseño para cada funcionalidad en todos los módulos.

#### Responsabilidades
* Diseñar funciones y elementos de interacción en la interfaz web.
* Presentar información de manera clara y comprensible para el usuario.
* Facilitar la interacción del usuario con el sistema o la aplicación.
* Garantizar la consistencia en el diseño y la experiencia del usuario en toda la aplicación.
* Validar y procesar la entrada del usuario de manera adecuada.
* Proporcionar retroalimentación instantánea sobre las acciones del usuario.
* Adaptarse a diferentes dispositivos y tamaños de pantalla para garantizar la accesibilidad y la usabilidad en diversas plataformas.
* Mantener un diseño visual atractivo y coherente con la identidad de la marca o el estilo de la aplicación.
* Optimizar el rendimiento para garantizar una respuesta rápida y fluida durante la interacción del usuario.
* Integrarse de manera efectiva con otros módulos del sistema para lograr funcionalidades completas y sin problemas.
* Evolucionar y actualizarse según las necesidades del usuario y los cambios en los requisitos del sistema o la aplicación.

## Módulo de Inicialización de Documento

Este módulo es el responsable de dar comienzo a la elaboración del documento de Alcance DDV a pedido del usuario de origen para garantizar la migración de datos y a la cual se debe entregar al usuario destino.

#### Interracción con otros módulos: 
Módulo de Ingreso de Información y Equivalencias

#### Responsabilidades

* Crear nuevo Documento de Alcance a partir de una platilla ya establecida.
* Modificar Documento de Alcance.
* Actualizar la versión  del Documento de Alcance.


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

Se encargará de mostrar el uso de las reglas de precarga obligatorias, así como considerar los casos de aplicación de las demás reglas, facilitará el aplicar las reglas de precarga opcionales al encargado mediante una lista desplegable, así como mostrar una descripción de en qué consiste cada una de estas reglas. 

Sobre las reglas de carga se mostrará una pantalla que reciba el codigo en SQL, PySpark, pseudocódigo, etc. Por los lineamientos de la empresa cada paso podrá ser explicado.

Este modulo interacciona con el de Ingreso de información y equivalencias, pues en las reglas de carga se hacen los joins entre las referencias y el universo.

#### Responsabilidades

Verificar las reglas de precarga obligatorias y consultar sobre las opcionales.

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
