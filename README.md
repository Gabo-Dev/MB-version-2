# Versión 2: Cisi Enriquecido mediante Gate
Antes de iniciar la aplicación se deben seguir los siquientes pasos:
1.  Abrir la consola de comandos en  la routa donde este la carpeta bin de  la carpeta de instalación de Solr.
2.  Iniciar Solr mediante el código:  start -all

    Por ejemplo, mi ruta es: C:\solr-9.2.0\bin>solr.cmd start -all
    
3.  Crear el core llamado micoleccion a través del comando: create -c micoleccion

     Por ejemplo: C:\solr-9.2.0\bin>solr.cmd create -c micoleccion
  
4.  A partir de este punto puede ejecutar el programa, el programa se podrá conectar a Solr para realizar consultas o indexar documentos.

######    **Al terminar de usar Solr se debe poner en la consola de comandos el codgio: stop -all**

    Por ejemplo: C:\solr-9.2.0\bin>solr.cmd stop -all
