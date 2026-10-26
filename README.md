# Solenme-N-2
Solemne N°2 Progamación avanzada
## Requisitos para la Instalación 

"Apache-tomcat-9.0.123-windows-x64"
"Apache-maven-3.10.0-bin"
"JDk 17 o versiónes SUPERIORES"
"PostgreSQL (PGADMIN 4)"
"GIT"
"Windows 10 o Superior"

## Instrucciones de Instalación 
 
"Primero se descargan y se descomprimen los Archivos Zip"

"Luego Se abren en Visual Studio Code."

"Se seleccionan los archivos y se abre la carpeta"

"Se abre la carpeta transporte-web, en la cual contiene pom.xml"

"Se espera a que VS Code importe el proyecto maven"

"Revisar la estructura e identificar las siguentes ubicaciones"

"" sql                                       ""
"" src/main                                  ""
"" src/main/java                             ""
"" src/main/java/cl/uss/transporte           ""

"Ademas de la ubicación pom.xml"
/////////////////////////////////////////////////////////////////////////////////////////

"luego se abre la terminal y se comprueban que esten instaladas las siguientes versiones"

"Ejercutar  (java -versión) / (javac -versión) / (mvn -versión)"
## Datos de conexión 

"Luego en su Equipo abra PgAdmin 4 y relaice las siguientes acciones:"

1. Conectarse a postgres como un usuario con permiso para crear bases.
2. Ejecutar sql/00_crear_base.sql por separado, fuera de una transaccion.
   Si transporte_db ya existe, omitir ese comando.
3. Abrir una conexion/Query Tool a transporte_db.
4. Ejecutar sql/01_tablas_datos.sql una sola vez en una base nueva.
5. Confirmar que existen viaje y bus, con tres registros en cada tabla.
