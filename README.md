
# Prototipo de sistema de teleasistencia para personas dependientes
En la actualidad, el uso de teléfonos móviles con conexión a internet se ha generalizado. Este proyecto pretende aprovechar este hecho para utilizar el teléfono móvil de las personas dependientes como nodo intermediario que recibe los datos de los sensores y les hace accesibles a las personas encargadas de la supervisión (familiares, operadores de teleasistencia, personal sanitario, etc.).

El principal objetivo del proyecto sería el desarrollo de un prototipo de sistema de teleasistencia de bajo coste basado en el uso del teléfono móvil y un conjunto de sensores. Con la realización de este proyecto, el alumno adquirirá experiencia en: desarrollo de aplicaciones en Android; tecnología de comunicaciones inalámbricas (p.ej., Bluetooth); desarrollo de aplicaciones empotradas.

El autor de este trabajo es **Roberto González Jiménez**.

**RemoteSoft**: Esta aplicación es la que tendrá instalada la persona dependiente en su teléfono móvil,
esta app se encargará de recoger la información de los sensores y de la pulsera de actividad para
enviárselo a la persona supervisora.

<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Recursos/logo_app.png?raw=true" width="300">
</p>

**RemoteSoft Receives**: Esta aplicación es la que tendrá instalada la persona supervisora en su
teléfono móvil, la app recibirá la información de los sensores captados por la app RemoteSoft y la
mostrará al usuario con el fin de que la persona supervisora pueda monitorizar a la persona
dependiente y estar informado de su estado actual.
<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Recursos/logo_app_receives.png?raw=true" width="300">
</p>

De manera resumida así funcionarían las dos aplicaciones entre sí:

<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Diagramas/Diagrama_app.png?raw=true" width="600">
</p>

De forma más detallada estas serían las llamadas que hacen en cada caso:
<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Diagramas/Diagrama_detallado.png?raw=true" width="600">
</p>

## La estructura del repositorio es la siguiente:

* **Docs**: Documentos y recursos utilizados en el proyecto.

* **Releases**: APKs de las dos aplicaciones Android.

* **RemoteSoft**: Proyecto Android de la app RemoteSoft.

* **RemoteSoft_Receives**: Proyecto Android de la app RemoteSoft Receives.

![image](https://user-images.githubusercontent.com/60737807/109425388-4dd35080-79e8-11eb-90bd-ada8e34a3cc0.png)

