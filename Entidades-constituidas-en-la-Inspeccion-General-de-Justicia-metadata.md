Entidades constituidas en la Inspección General de Justicia
===========================================================

En este conjunto de datos se detallan los datos de las entidades constituidas en la Inspección General de Justicia -IGJ.

La IGJ, en ejercicio de su función fiscalizadora de personas jurídicas, registra, controla y publica la información relativa a sociedades accionarias y no accionarias, sociedades constituidas en el extranjero, asociaciones civiles y fundaciones con domicilio legal en CABA. Las funciones que ejerce la IGJ son indelegables y se complementan con las realizadas por los organismos registrales de las provincias. Por la importancia de las funciones registrales y de control a su cargo, tiene un rol trascendente en la vida económica y social del país.

La IGJ tiene competencia federal en las Sociedades de Capitalización y Ahorro, y en la implementación del Registro Nacional de Sociedades.

http://datos.jus.gob.ar/dataset/entidades-constituidas-en-la-inspeccion-general-de-justicia-igj

Características
---------------

-   **Fecha de Primera Publicación:** 19/09/2016

-   **Tags o Etiquetas:** entidades, sociedades, IGJ, personas jurídicas, SRL, fundaciones, asociaciones civiles, sociedades anónimas, asambleas, sociedades

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Subsecretaría de Asuntos Registrales. Inspección General de Justicia

-   **Grupo:** Sistema Registral

-   **Frecuencia de Actualización:** Mensualmente

Recursos disponibles
--------------------

### Entidades

-   **Nombre del archivo:** igj-entidades-AAAA-MM.csv

-   **Descripción del contenido:** detalle de las entidades dadas de alta y dasas de baja en IGJ

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero_correlativo (int):** número correlativo que identifica la entidad

-   **tipo_societario (int):** código del tipo societario

-   **descripcion_tipo_societario (string):** descripción del tipo societario

-   **razon_social (string):** razón social de la entidad

-   **dada_de_baja (string):** toma valor "S" si la entidad forma parte del Registro de Entidades Inactivas (incuído a partir de 2016-10)

-   **codigo_baja (int):** código que identifica la baja

-   **detalle_baja (string):** descripción del motivo de la baja

-   **cuit (int):** número de CUIT de la entidad. Este campo es informado a partir del mes de febrero de 2018

### Domicilios

-   **Nombre:** igj-domicilios-AAAA-MM.csv

-   **Descripción del contenido:** detalle de los domicilios de las entidades

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero_correlativo (int):** número correlativo que identifica la entidad

-   **tipo_societario (int):** código del tipo societario

-   **descripcion_tipo_societario (string):** descripción del tipo societario

-   **razon_social (string):** razón social de la entidad

-   **tipo_domicilio (string):** tipo de domicilio que corresponde a la entidad (L: Legal, S: Sucursal)

-   **descripcion_tipo_domicilio (string):** descripción del tipo de domicilio que corresponde a la entidad

-   **calle (string):** calle del domicilio de la entidad

-   **numero (string):** número del domicilio de la entidad

-   **localidad (string):** localidad del domicilio de la entidad

-   **provincia (string):** provincia del domicilio de la entidad

-   **codigo_postal (string):** código postal del domicilio de la entidad

### Autoridades

-   **Nombre:** igj-autoridades-AAAA-MM.csv

-   **Descripcióndel contenido:** detalle de las autoridades de las entidades

-   **Formato:** CSV delimitado por comas, codoficado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero_correlativo (int):** número correlativo que identifica la entidad

-   **apellido_nombre (string):** apellido y nombre de la autoridad

-   **tipo_administrador (string):** código de tipo de administrador (A Autoridades, R Representantes, S Socios)

-   **descripcion_tipo_administrador (string):** descripción del tipo de administrador

-   **tipo_documento (string):** código de tipo de documento del administrador

-   **descripcion_tipo_documento (string):** descripción del tipo de documento del administrador

-   **numero_documento (string):** número de documento del administrador

-   **sexo_autoridad (string):** sexo de la autoridad. Toma valores (M) para masculino y (F) femenino para femenino. Este campo es informado a partir del mes de febrero de 2018

### Balances

-   **Nombre:** igj-balances-AAAA-MM.csv

-   **Descripción del contenido:** detalle de los balances de las entidades

-   **Formato:** CSV delimitados por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero_correlativo (int):** número correlativo

-   **tipo_societario (int):** código del tipo societario

-   **descripción_tipo_societario (string):** descripción del tipo societario

-   **razon_social (string):** razón social de la entidad

-   **fecha_balance (date):** fecha de cierre del balance

-   **fecha_presentación (date):** fecha de presentación del balance

-   **capital_informado (float):** número correlativo que identifica la entidad

### Asambleas

-   **Nombre:** igj-asambleas-AAAA-MM.csv

-   **Descripción del contenido:** detalle de las asambleas de las entidades

-   **Formato:** CSV delimitado por comas, codificado en UTF-8

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **numero_correlativo (int):** número correlativo que identifica la entidad

-   **tipo_societario (int):** código del tipo societario

-   **descripcion_tipo_societario (string):** descripción del tipo societario

-   **razon_social (string):** razón social de la entidad

-   **tipo_asamblea (string):** tipo de asamblea

-   **descripcion_tipo_asamblea (string):** descripción del tipo de asamblea

-   **numero_asamblea (string):** número de la asamblea

-   **fecha_realizacion (date):** fecha de realización de la asamblea

-   **fecha_presentacion (date):** fecha de presentación de la asamblea


### Notas

Los trámites a realizarse en la IGJ pueden consultarse o iniciarse en [*http://www.jus.gob.ar/igj*](http://www.jus.gob.ar/igj).
