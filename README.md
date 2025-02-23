# Prototype of a Teleassistance System for Dependent Individuals
Nowadays, the use of mobile phones with internet connectivity has become widespread. This project aims to take advantage of this fact by using the mobile phone of dependent individuals as an intermediary node that receives data from sensors and makes it accessible to those responsible for supervision (family members, teleassistance operators, healthcare personnel, etc.).

The main objective of the project is to develop a low-cost teleassistance system prototype based on the use of a mobile phone and a set of sensors. By carrying out this project, the student will gain experience in Android application development, wireless communication technology (e.g., Bluetooth), and embedded application development.

The author of this work is **Roberto González Jiménez**.

**RemoteSoft**: This is the application that the dependent person will have installed on their mobile phone. This app will collect data from sensors and the activity wristband and send it to the supervising person.

<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Recursos/logo_app.png?raw=true" width="300">
</p>

**RemoteSoft Receives**: This is the application that the supervising person will have installed on their mobile phone. The app will receive sensor data collected by the RemoteSoft app and display it to the user so that the supervisor can monitor the dependent person and stay informed about their current state.

<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Recursos/logo_app_receives.png?raw=true" width="300">
</p>

In summary, this is how the two applications work together:

<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Diagramas/Diagrama_app.png?raw=true" width="600">
</p>

In more detail, these are the calls made in each case:

<p align="center">
  <img src="https://github.com/robergj/remotesoft/blob/main/Docs/Diagramas/Diagrama_detallado.png?raw=true" width="600">
</p>

## Repository Structure:

* **Docs**: Documents and resources used in the project.

* **Releases**: APKs of both Android applications.

* **RemoteSoft**: Android project for the RemoteSoft app.

* **RemoteSoft_Receives**: Android project for the RemoteSoft Receives app.

![image](https://user-images.githubusercontent.com/60737807/109425388-4dd35080-79e8-11eb-90bd-ada8e34a3cc0.png)

