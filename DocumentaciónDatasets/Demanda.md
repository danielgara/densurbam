# DOCUMENTACIÓN DATASET DEMANDA

A continuación, se describe la información contenida en el dataset `Demanda`.

| **Encabezado** | **Descripción** | **Fuente** | **Basado en otra(s) variable(s)** |
| -- | -- | -- | -- |
| **ID** | Identificador de la fila de la demanda. | Propia | No |
| **ID_BARRIO** | Identificador de 10 digitos del barrio. | Dane | No |
| **NOMBRE_BARRIO** | Nombre del barrio. | Dane | No |
| **ID_MUNICIPIO** | Identificador de 3 digitos del municipio al que pertenece el barrio.  | Dane | No |
| **ID_SECTOR** | Identificador de 1 digito del sector al que pertenece el barrio. | Dane | No |
| **ID_CORREGIMIENTO** | Identificador de 3 digitos del corregimiento al que pertenece el barrio.  | Dane | No |
| **AGUA_TODOS_USOS_(L/HAB/DIA)** | Cantidad de litros de agua para todos los usos por habitante por día. | EPM | No |
| **AGUA_TODOS_USOS_(L/HAB/AÑO)** | Cantidad de litros de agua para todos los usos por habitante por año. | EPM | Se basa en `AGUA_TODOS_USOS_(L/HAB/DIA)` multiplicado por 365. |
| **AGUA_PARA_VERTIMIENTO_(L/HAB/AÑO)** | Cantidad de litros de agua para vertimiento por habitante por día. | EPM | No |
