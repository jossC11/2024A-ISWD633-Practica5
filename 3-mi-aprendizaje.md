# COMPLETAR

En mi archivo docker-compose.yml, configure los siguientes servicios:
SonarQube: mapeé el puerto 9000 para acceder a la interfaz web de SonarQube. Configure un healthcheck para asegurarme de que el servicio esté funcionando correctamente.
PostgreSQL: configure un healthcheck para asegurarme de que el servicio esté funcionando correctamente. También configure las variables de entorno necesarias.
Finalmente entonces se logró configurar correctamente SonarQube con Docker Compose, lo que me permitió acceder a la interfaz web de SonarQube y utilizar sus funcionalidades para analizar código. Además, pude verificar que los servicios estuvieran funcionando correctamente gracias a los healthchecks configurados.
Durante la práctica, encontré un problema con la configuración del contenedor que hacía que el CPU usage estuviera en 0%. Después de investigar y leer los logs del contenedor, descubrí que el problema se debía a que el contenedor no estaba recibiendo ninguna solicitud o tarea. Solucioné este problema verificando la configuración del contenedor y asegurándome de que estuviera configurado correctamente.

![image](https://github.com/jossC11/2024A-ISWD633-Practica5/assets/94476123/f28180ad-2d5f-4f12-984f-0bbbdad6e2bc)


![image](https://github.com/jossC11/2024A-ISWD633-Practica5/assets/94476123/6af14411-6e29-418e-812b-608ff8dba923)

