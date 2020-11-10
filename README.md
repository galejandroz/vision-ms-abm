# #### Marked Safe Health - ABM

Sistema de gestión de contenidos para cuestionarios y control covid en tiempo real. Gestión de usuarios, organizaciones, grupos. Dos niveles de permisos. Reportes descargables xls, filtros y búsquedas.


# Desarrollo FrontEnd
React - Redux
API Rest Node - Sockets IO

Se crean cuestionarios y se envían a grupos dentro de organizaciones, generando reportes en tiempo real y alertas para posibles casos covid. También se pueden generar cuestionarios para usuarios anónimos. Todos los cuestionarios se envían mediante enlace externo.

## se utilizó librería material ui

Envío de foto de perfil de usuario, en base64

![material ui styles](https://bimagine.com.ar/cv/questionnaire/1.png)

Árbol de proyecto:

![enter image description here](https://bimagine.com.ar/cv/questionnaire/2.png)
![enter image description here](https://bimagine.com.ar/cv/questionnaire/3.png)

Uso de sockets cliente
![enter image description here](https://bimagine.com.ar/cv/questionnaire/4.png)

Control de acceso usando *interceptors* en peticiones para inyectar autorización en cabecera de petición:
![enter image description here](https://bimagine.com.ar/cv/questionnaire/5.png)

# Algunas pantallas

![enter image description here](https://bimagine.com.ar/cv/questionnaire/6.png)


![Question](https://bimagine.com.ar/cv/questionnaire/7.png)
