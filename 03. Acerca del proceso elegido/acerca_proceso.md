# Migración de Analítica de Datos

## Principal servicio ofrecido

La migración de datos, esto se refiere a la transferencia de datos entre diferentes tipos de formatos de archivos, esquemas de bases de datos y sistemas de almacenamiento. Incluye asignaciones y transformaciones entre datos de origen y de destino si los datos son diversos.

Primero, se recibe la información _desordenada_.

Luego pasa por **calidad de datos**, debe evaluarse antes de la migración para garantizar una implementación exitosa sin pérdida de datos. La tasa de éxito de cualquier proyecto de migración de datos depende de la diversidad, el volumen y la calidad de los datos que se transfieren.

Por último, se entrega la información estructurada. Por información nos refirimos a tablas, aplicaciones, scores (conjunto de datos relacionados con un fin: perfil cliente, tipo de préstamo (hipotecario, vehicular, personal), etc).

## Responsables del proceso

**1. Data architec:** Estructura el flujo de información de inicio a fin.

**2. Data governance:** Solicita, recibe y transforma la información del usuario origen. Relevamiento de información.

**3. Data modeler:** Modelar los objetos (esquemas, tablas, base de datos, etc).

**4. Data engieneer:** Recibe la info del data governance y en base al modelamiento de datos crea las tablas con sus respectivos esquemas dentro de DB.

**5.Data quality:** Responsable de verificar que lo que hizo el data engieneer en base a lo proporcionado por el data governance es correcto.

## Descripción del proceso

Procesos para migrar datos en base a los roles:

- [Ver el Flujograma Completo en LucidChart](https://lucid.app/lucidchart/29fab1dd-40e5-4da9-84bc-d9a41e26717b/edit?viewport_loc=-9379%2C-1461%2C8710%2C3790%2C0_0&invitationId=inv_ad1e5fc2-becf-482e-b4bc-954471623807)

<img src="Flujograma actual.png" alt="DiagramaDeFlujo" style="width: 100%; height: auto;"/>

| Secuencia | Actividad                                          | Descripción         | Responsable  |
| --------- | -------------------------------------------------- | ------------------- | ------------ |
| 1         | Elaborar Documento de Alcance DDV | Este paso representaría la intención de crear o modificar un documento de alcance DDV a pedido de un usuario de origen o por alguna modificación que quiera hacer un integrante del squad encargo de esta tarea. De acuerdo con lo que se necesita hacer, se va a crear un nuevo documento o se va a modificar uno ya existente | Data Steward |
| 2         | Tomar última versión del documento DDV | Si lo que se quiere es solo agregar o modificar campos, se tomará la última versión del documento  que se encuentra en el SharePoint | Data Steward |
| 3         | Generar nuevo documento DDV | Si se quiere agregar tablas nuevas o el formato de la última versión que se encuentra en el SharePoint no es el actual, se descarga una plantilla del Documento de Alcance de la plataforma Confluence (plataforma virtual de BCP) para apartir de allí crear un nuevo Documento de Alcance | Data Steward |
| 4         | Ingresar historial de versiones | En el documento de Alcance, en una sección del Excel, se especificará qué versión es la modificación que se está haciendo. Asimismo, se tiene que detallar cuál ha sido, en qué fecha se realizó los cambios, cuál Squad lo ha hecho, qué miembro del Squad lo ha hecho y quién fue que solicitó el cambio. Si es la primera versión del documento, esto será solo de llenado de datos| Data Steward |
| 5         | Solicitar actualización de la lista de desplegables | Inserte Descripción | Data Steward |
| 6         | Actualizar lista de desplegables | Inserte Descripción | Data Gobernance Expert |
| 7         | Ingresar información general, del aplicativo y de referencia | Inserte Descripción | Data Steward |
| 8         | Ingresar conceptos de negocio | Inserte Descripción | Data Steward |
| 9         | Ingresar información del modelo DDV | Inserte Descripción | Data Modeler |
| 10        | Definir reglas funcionales de pre carga y carga | Inserte Descripción | Data Stewart |
| 11        | Definir reglas técnicas de pre carga | Inserte Descripción | Custodio Técnico |
| 12        | Complementar definciones técnicas | Inserte Descripción | Data Engineer |
| 13        | Elaborar lógica pre carga | Inserte Descripción | Data Engineer |
| 14        | Registrar seguridad de datos y consumo de aplicativo | Inserte Descripción | Data Stewart |
| 15        | Evaluar criticidad de los datos | Inserte Descripción | Data Stewart |
| 16        | Ingresar información adicional de proceso | Inserte Descripción | Data Engineer |
| 17        | Actualizar Documento de Alcance DDV | Inserte Descripción | Data Stewart |
| 18        | Validar Documento de Alcance con macro | Inserte Descripción | Data Stewart |
| 19        | Corregir errores | Inserte Descripción | Data Stewart |
| 20        | Corregir errores de modelamiento | Inserte Descripción | Data Modeler |
| 21        | Generar Metadata y Linaje | Trazabilidad de los errores presentados en todo el proceso con una explicación del error presentado | Data Stewart |
| 22        | Actualizar Documento de Alcance DDV | Se actualiza el documento de alcance libre de errores para la posterior revisión del Data Stewart Senior | Data Gobernance Expert |
| 23        | Revisar documentos de Alcance DDV | Validación de los documentos de alcance presentando observaciones (generalmente no se encuentran errores en este punto) | Data Stewart Senior |
| 24        | Actualizar Governance Catalog | Se suben los documentos de alcance a InfoSphere Information Governance Catalog, que es una herramienta de IBM para el gobierno de datos | Data Stewart |







[Regresar al índice](../README.md)
