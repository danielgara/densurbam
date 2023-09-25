# REGLAS PARA DEFINICIÓN DE LOS DATASETS Y SUS CONTENIDOS

A continuación, se presentan las reglas para definir cualquier dataset del proyecto.

## 1. ARCHIVOS
1.1. **Nombramiento:** se deben definir utilizando el formato `CapitalCase`. Ejemplo: `DemandaColombia.xls`.
1.2. **Ubicación:** se deben ubicar en la carpeta de `/Datasets`. Y se debe almacenar tanto la versión .xsl como la versión .csv.

## 2. ENCABEZADOS
2.1. **Encabezados:** se deben definir utilizando el formato `UPPER_SNAKE_CASE`. Ejemplo: `NOMBRE_BARRIO`.
2.2. **Idioma:** todos los encabezados deben ir en español, no realizar mezcla de idiomas.
2.3. **Completitud:** los nombres de las columnas no deben ser ambiguos, debe tratarse de utilizar palabras completas cuando una abreviación no sea lo suficiente clara. Ejemplo: evitar `BARRIO_VER` -> donde `VER` significaba `VEREDA` pero era ambiguo.

