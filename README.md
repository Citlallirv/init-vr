# Citlalli Rodríguez Vega
## Descripción del Proyecto 
Este proyecto consiste en el desarrollo de una aplicación de Realidad Virtual utilizando Unity y XR Interaction Toolkit, orientada a dispositivos Oculus Quest 1.

El entorno permite la interacción básica en VR mediante:

- Movimiento con XR Origin.
- Controladores basados en acciones (Action Based Controllers).
- Animación de manos utilizando Input System.
- Interacción con objetos (Grab y Release).
- Colisiones físicas mediante Rigidbody y Colliders.

## Instrucciones para ejecutar el proyecto
Para ejecutar el proyecto en el visor Oculus Quest 1, se requiere realizar los siguientes pasos:

Primero, activar el modo desarrollador desde la aplicación Meta Horizon en el dispositivo móvil. 
Encender el visor.
Después, conectar el visor al computador mediante cable USB y aceptar dentro del visor los permisos de acceso a datos y depuración USB.

En Unity, ir a:

File > Build Settings

Seleccionar la plataforma “Android” y presionar “Switch Platform”.

Posteriormente, verificar en Player Settings:

Scripting Backend: IL2CPP

Target Architectures: ARM64

Active Input Handling: New

En XR Plug-in Management debe estar activado OpenXR con soporte para Meta Quest.

Finalmente, seleccionar:

File > Build and Run.
Unity generará el archivo APK e instalará la aplicación directamente en el visor.

## Imágenes del resultado 
<img width="1206" height="1190" alt="image" src="https://github.com/user-attachments/assets/83c61c8d-82d9-4185-96c0-14215ab98232" />
<img width="1206" height="1190" alt="image" src="https://github.com/user-attachments/assets/a68cf263-c415-4959-a68e-abb43f57ecde" />
<img width="1206" height="1177" alt="image" src="https://github.com/user-attachments/assets/934b2f4b-a43c-4946-ac9d-68c032c56616" />
<img width="1206" height="1162" alt="image" src="https://github.com/user-attachments/assets/423d5b76-a865-4291-a7ea-2df52d8658f7" />
<img width="1206" height="1188" alt="image" src="https://github.com/user-attachments/assets/94b76a64-4157-43b8-9b42-41066a1b41ed" />





