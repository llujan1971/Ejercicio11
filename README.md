# Ejercicio11
Detalle ejercicio 11 curso Kubernetes

Startup probes:

se utilizan para determinar cuándo se ha inicializado correctamente una aplicación contenedora. Si falla el inicio, el pod se reinicia. Cuando los contenedores de pod tardan demasiado en estar listos, las readiness probes pueden fallar repetidamente. En este caso, los contenedores corren el riesgo de ser finalizados antes de que estén en funcionamiento. En ese caso el startup probe es util. El StartUp probe obliga a las verificaciones de actividad y preparación a esperar hasta que tenga éxito, para que el inicio de la aplicación no se vea comprometido. Eso es especialmente beneficioso para las aplicaciones heredadas que tardan en iniciar.
