Evidencias - Actividad 2: Auditoría de permisos de acceso

En esta carpeta se presentan las capturas de pantalla que demuestran el proceso de auditoría de permisos de acceso realizado en Linux.

1. Creación de carpetas y archivos
 
Se evidencia la creación de la estructura de directorios de la empresa, correspondientes a las áreas de Finanzas y Recursos Humanos, así como los archivos planilla.xlsx y empleados.csv.

3. Asignación de permisos incorrectos

Se muestra la ejecución del comando chmod 777 en ambos archivos, simulando una configuración incorrecta de permisos de seguridad.

5. Auditoría de permisos

Se presentan los resultados de los comandos ls -l, mediante los cuales se identificaron los permisos 777 en los archivos de Finanzas y Recursos Humanos.
Se identificó que cualquier usuario podía leer, modificar y ejecutar los archivos.

7. Corrección de permisos
   
Se evidencia la aplicación de los comandos chmod 640 para corregir los permisos de ambos archivos y restringir el acceso no autorizado.

9. Verificación final
   
Se muestran los resultados finales de los comandos ls -l, comprobando que los archivos tienen permisos rw-r----- (640).
Esto demuestra que el propietario tiene permisos de lectura y escritura, el grupo solamente puede leer y los demás usuarios no tienen acceso.
