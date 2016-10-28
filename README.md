Entidades constituidas en la Inspección General de Justicia
===========================================================

En este conjunto de datos se detallan los datos de las entidades constituidas en la Inspección General de Justicia -IGJ.

La IGJ, en ejercicio de su función fiscalizadora de personas jurídicas, registra, controla y publica la información relativa a sociedades accionarias y no accionarias, sociedades constituidas en el extranjero, asociaciones civiles y fundaciones con domicilio legal en CABA. Las funciones que ejerce la IGJ son indelegables y se complementan con las realizadas por los organismos registrales de las provincias. Por la importancia de las funciones registrales y de control a su cargo, tiene un rol trascendente en la vida económica y social del país.

La IGJ tiene competencia federal en las Sociedades de Capitalización y Ahorro, y en la implementación del Registro Nacional de Sociedades.

Características
---------------

-   **Fecha de Publicación:** 19/09/2016

-   **Tags o Etiquetas:** entidades, sociedades, IGJ, personas jurídicas, SRL, fundación, asociación civil, sociedad anónima, etc.

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia
-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** eventual

Recursos disponibles
--------------------

### Entidades

-   **Nombre del archivo:** igj-entidades.csv

-   **Descripción del contenido:** entidades constituidas en la IGJ

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

### Campos del recurso

-   **numero\_correlativo (int):** número correlativo que identifica la entidad

-   **tipo\_societario (int):** código del tipo societario

-   **descripcion\_tipo\_societario (string):** descripción del tipo societario

-   **razon\_social (string):** razón social de la entidad

### Domicilios

-   **Nombre:** igj-domicilios.csv

-   **Descripción:** domicilios de las entidades

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

### Campos del recurso

-   **numero\_correlativo (int):** número correlativo que identifica la entidad

-   **tipo\_societario (int):** código del tipo societario

-   **descripción\_tipo\_societario (string):** descripción del tipo societario

-   **razon\_social (string):** razón social de la entidad

-   **tipo\_domicilio (string):** tipo de domicilio que corresponde a la entidad (L Legal, S Sucursal)

-   **descripcion\_tipo\_domicilio (string):** descripción del tipo de domicilio que corresponde a la entidad

-   **calle (string):** calle del domicilio de la entidad

-   **numero (string):** número del domicilio de la entidad

-   **localidad (string):** localidad del domicilio de la entidad

-   **provincia (string):** provincia del domicilio de la entidad

-   **codigo\_postal (string):** código postal del domicilio de la entidad

### Autoridades

-   **Nombre:** igj-asambleas.csv

-   **Descripción:** autoridades de las entidades

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

### Campos del recurso

-   **numero\_correlativo (int):** número correlativo que identifica la entidad

-   **apellido\_nombre (string):** apellido y nombre de la autoridad

-   **tipo\_administrador (string):** código de tipo de administrador (A Autoridades, R Representantes, S Socios)

-   **descripcion\_tipo\_administrador (string):** descripción del tipo de administrador

-   **tipo\_documento (string):** código de tipo de documento del administrador

-   **descripcion\_tipo\_documento (string):** descripción del tipo de documento del administrador

-   **numero\_documento (string):** número de documento del administrador

### Balances

-   **Nombre:** igj-balances.csv

-   **Descripción:** presentación de balances de las entidades

-   **Formato:** CSV delimitados por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

### Campos del recurso

-   **numero\_correlativo (int):** número correlativo

-   **tipo\_societario (int):** código del tipo societario

-   **descripción\_tipo\_societario (string):** descripción del tipo societario

-   **razon\_social (string):** razón social de la entidad

-   **fecha\_balance (date):** fecha de cierre del balance

-   **fecha\_presentacion (date):** fecha de presentación del balance

-   **capital\_informado (float):** número correlativo que identifica la entidad

### Asambleas

-   **Nombre:** igj-asambleas.csv

-   **Descripción:** presentación de Asambleas de las entidades

-   **Formato:** CSV delimitado por comas

-   **Rango temporal:** -

-   **Fecha de Actualización:** 31/08/2016

### Campos del recurso

-   **numero\_correlativo (int):** número correlativo que identifica la entidad

-   **tipo\_societario (int):** código del tipo societario

-   **descripción\_tipo\_societario (string):** descripción del tipo societario

-   **razon\_social (string):** razón social de la entidad

-   **tipo\_asamblea (string):** tipo de asamblea

-   **descripción\_tipo\_asamblea (string):** descripción del tipo de asamblea

-   **fecha\_realizacion (date):** fecha de realización de la asamblea

-   **fecha\_presentacion (date):** fecha de presentación de la asamblea


### Notas

Los trámites a realizarse en la IGJ pueden consultarse iniciarse o iniciarse en [*http://www.jus.gob.ar/igj*](http://www.jus.gob.ar/igj)
