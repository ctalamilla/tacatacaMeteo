## Procesamiento de Datos de Estaciones Meteorológicas
1. Se organizaron los datos según origen.
   1. Estaciones Davis (Taca Taca, Vendaval)
   2. Estaciones Campbel (Arizaro, Caipe)
   3. Estaciones Eolicas (Eolica1 Eolica2)
2. Dentro de cada carpeta según el origen de datos se procedio a:
   1. Identficar las columnas, 
   2. Identicar el formato de fecha de cada archivos. Existian archivos con formato dd/mm/yy y mm/dd/yy. Fueron separados para tratarlos de manera separada. 
   3. Los archivos excel fueron convertidos a CSV. El separador decimal designado fue el punto.
   4. Los Archivos de la estaciones Campbell fueron separados segun la granularidad del dato (5m, 60m, diario).
3. Se definieron funciones de Extracción y Transformación de los datos según origen. La salida de la función retorna un archivo CSV sin duplicados, y con un formato de fecha uniforme.
4. A todos los archivos se les agrego una columna de direccion de viento expresada en cuadrantes. 
5. Todos los archivos fueron unificados segun la fuente citada en el item 1. 
6. El total de archivos procesados fue:
   1. Eolica 1: 10 archivos, 336.542 registros sin duplicados.
   2. Eolica 1: 9 archivos, 241.453 registros sin duplicados.
   3. Davis Taca Taca: 3 archisos, 253.895 registros sin duplicados.
   4. Davis Vendaval: 2 archivos, 4300 registros sin duplicados. 
   5. Campbell Caile 60 m: 2 archivos, 23.685 registros sin duplicados.
   6. Campbell Caipe 5 m: 2 archivos, 284.211 registros sin duplicados.
   7. Caipe 24 h: 1 archivo, 987 registos sin duplicados.
   8. Campbell Arizaro 5 m: 2 archivos, 247.642 registros sin duplicados.
   9. Campbell Arizaro 24 h: 2 archivos, 987 registros sin duplicados.
   10. Campbell Arizaro 60 m: 2 archivos, 23.684 registros sin duplicados.
   
