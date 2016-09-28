Entidades constituidas en la Inspección General de Justicia
===========================================================

En este conjunto de datos se detallan los datos de las entidades constituidas en la Inspección General de Justicia -IGJ.

La IGJ, en ejercicio de su función fiscalizadora de personas jurídicas, registra, controla y publica la información relativa a sociedades accionarias y no accionarias, sociedades constituidas en el extranjero, asociaciones civiles y fundaciones con domicilio legal en CABA. Las funciones que ejerce la IGJ son indelegables y se complementan con las realizadas por los organismos registrales de las provincias. Por la importancia de las funciones registrales y de control a su cargo, tiene un rol trascendente en la vida económica y social del país.

La IGJ tiene competencia federal en las Sociedades de Capitalización y Ahorro, y en la implementación del Registro Nacional de Sociedades.

Características
---------------

-   **Fecha de Publicación:** 14/09/2016

-   **Recurso:** Entidades constituidas en la Inspección General de Justicia

-   **Tags o Etiquetas:** entidades, sociedades, IGJ, personas jurídicas, SRL, fundación, asociación civil, sociedad anónima, etc.

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia.

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia.

-   **Responsable:** Inspección General de Justicia.

-   **Grupos:** Sistema Registral.

-   **Frecuencia de Actualización:** Eventual.

Recursos
--------

### Entidades

-   **Nombre:** igj-entidades.csv

-   **Descripción:** Entidades constituidas en la IGJ

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

#### Campos del recurso

-   **numero\_correlativo (int):** Número correlativo que identifica la entidad

-   **tipo\_societario (int):** Código del tipo societario

-   **descripcion\_tipo\_societario (string):** Descripción del tipo societario

-   **razon\_social (string):** Razón social de la entidad

### Domicilios

-   **Nombre:** igj-domicilios.csv

-   **Descripción:** Domicilios de las entidades

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -


#### Campos del recurso

-   **numero\_correlativo (int):** Número correlativo que identifica la entidad

-   **tipo\_societario (int):** Código del tipo societario

-   **descripción\_tipo\_societario (string):** Descripción del tipo societario

-   **razon\_social (string):** Razón social de la entidad

-   **tipo\_domicilio (string):** Tipo de domicilio que corresponde a la entidad (L Legal, S Sucursal)

-   **descripcion\_tipo\_domicilio (string):** Descripción del tipo de domicilio que corresponde a la entidad

-   **calle (string):** Calle del domicilio de la entidad

-   **numero (string):** Número del domicilio de la entidad

-   **localidad (string):** Localidad del domicilio de la entidad

-   **provincia (string):** Provincia del domicilio de la entidad

-   **codigo\_postal (string):** Código postal del domicilio de la entidad

### Autoridades

-   **Nombre:** igj-asambleas.csv

-   **Descripción:** Autoridades de las entidades

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

#### Campos del recurso

-   **numero\_correlativo (int):** Número correlativo que identifica la entidad

-   **apellido\_nombre (string):** Apellido y nombre de la autoridad

-   **tipo\_administrador (string):** Código de tipo de administrador (A Autoridades, R Representantes, S Socios)

-   **descripcion\_tipo\_administrador (string):** Descripción del tipo de administrador

-   **tipo\_documento (string):** Código de tipo de documento del administrador

-   **descripcion\_tipo\_documento (string):** Descripción del tipo de documento del administrador

-   **numero\_documento (string):** Número de documento del administrador

### Asambleas

-   **Nombre:** igj-asambleas.csv

-   **Descripción:** Presentación de Asambleas de las entidades

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

#### Campos del recurso

-   **numero\_correlativo (int):** Número correlativo que identifica la entidad

-   **tipo\_societario (int):** Código del tipo societario

-   **descripción\_tipo\_societario (string):** Descripción del tipo societario

-   **razon\_social (string):** Razón social de la entidad

-   **tipo\_asamblea (string):** Tipo de asamblea

-   **descripción\_tipo\_asamblea (string):** Descripción del tipo de asamblea

-   **fecha\_realizacion (date):** Fecha de realización de la asamblea

-   **fecha\_presentacion (date):** Fecha de presentación de la asamblea

### Balances

-   **Nombre:** igj-balances.csv

-   **Descripción:** Presentación de balances de las entidades

-   **Formato:** CSV delimitados por comas.

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

#### Campos del recurso

-   **numero\_correlativo (int):** Número correlativo

-   **tipo\_societario (int):** Código del tipo societario

-   **descripción\_tipo\_societario (string):** Descripción del tipo societario

-   **razon\_social (string):** Razón social de la entidad

-   **fecha\_balance (date):** Fecha de cierre del balance

-   **fecha\_presentacion (date):** Fecha de presentación del balance

-   **capital\_informado (float):** Número correlativo que identifica la entidad

Notas
-----

Los trámites a realizarse en la IGJ pueden consultarse iniciarse o iniciarse en [*http://www.jus.gob.ar/igj*](http://www.jus.gob.ar/igj)
