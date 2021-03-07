<h1>Realidad Aumentada</h1>

<b>¿Qué es A-Frame?</b> Es un framework web de código abierto para crear experiencias de realidad virtual (VR). Los desarrolladores pueden crear escenas 3D y WebVR usando HTML. HTML proporciona una herramienta de autoría familiar para desarrolladores y diseñadores web al tiempo que incorpora un popular patrón de desarrollo de juegos utilizado por motores como Unity 3D.

![Captura de pantalla 2021-03-06 a las 23 04 51](https://user-images.githubusercontent.com/65786438/110222140-694ec780-7ed0-11eb-9f1f-fbf432228bc5.png)

<h2>Comencemos</h2>

Para crear una escena virtual necesitamos importar una librería dentro del head de tu documento .html: 
<i><script src="https://aframe.io/releases/1.0.4/aframe.min.js"></script></i>

A continuación debes insertar el contenido en el body, primero una escena y dentro de ella todos sus elementos: primitivas o entidades, cámara, luz, cielo, etc.
Pequeño ejemplo:

    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>

Puedes crear tu propio mundo virtual

![Captura de pantalla 2021-03-06 a las 23 04 41](https://user-images.githubusercontent.com/65786438/110222138-65bb4080-7ed0-11eb-9d40-5867a06a3483.png)

Propiedades de Transformación


