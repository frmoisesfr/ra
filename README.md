<h1>REALIDAD AUMENTADA</h1>

<b>¿Qué es A-Frame?</b> Es un framework web de código abierto para crear experiencias de realidad virtual (VR). Los desarrolladores pueden crear escenas 3D y WebVR usando HTML. HTML proporciona una herramienta de autoría familiar para desarrolladores y diseñadores web al tiempo que incorpora un popular patrón de desarrollo de juegos utilizado por motores como Unity 3D.

![Captura de pantalla 2021-03-06 a las 23 04 51](https://user-images.githubusercontent.com/65786438/110222140-694ec780-7ed0-11eb-9f1f-fbf432228bc5.png)

https://aframe.io/blog/arjs/#customize-your-marker

https://aframe.io/docs/1.0.0/guides/building-a-basic-scene.html

<h2>COMENCEMOS</h2>

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

<h2>INTRODUCCIÓN</h2>
<ul>
    <li>
        <h3>Position: </h3>Es la posición de nuestro objeto medido siempre en las coordenadas "x y z"
    </li>
    <li>
        <h3>Rotation: </h3>Nos permite rotar el objeto los grados que queramos y en relación al eje que elijamos.
    </li>
    <li>
        <h3>Width, Height: </h3> La propiedad Width sirve para indicar la anchura del objeto y height la altura, si tuviéramos un cubo estaríamos hablando de la base por la altura. Se utiliza para crear un objeto con las dimensiones que queramos.
    </li>
    <li>
        <h3>Scale</h3>
        Es la escala de nuestro objeto medido en las coordenadas "x y z"
    </li>
    <li>
        <h3>Herencia</h3>
        Podemos crear herencia con A-frame, podemos tener padres e hijos fácilmente. Por ejemplo, en el siguiente código, la esfera es hija de la caja, por tanto todo lo que hagamos a la caja afecta también a la esfera por ser su hijo. 
        
          <a-scene>
            <a-box position="0 2 0" rotation="0 45 45" scale="2 4 2">
                <a-sphere position="1 0 3"></a-sphere>
            </a-box>
          </a-scene>
Este código va dentro del body
    </li>
    <li>
        <h3>Posición de Origen</h3>
    Debes tener cuidado a la hora de posicionar los objetos, por defecto son creados en el punto "0 0 0" eso significa que nuestra cámara también estará situada ahí, si no desplazamos los objetos no podremos verlos al principio.
    </li>
    <li>
        <h3>Abrir el inspector</h3>
        Puedes pulsar las telcas ctrl+alt+i automáticamente se abrirá el inspector de propiedades. Te sorprenderá todo lo que puedes hacer desde ahí.
    </li>
    <li>
        <h3>Movimiento dentro de la escena</h3>
        Los controles por defecto permiten clickear y arrastrar con el ratón y moverte con las teclas WASD o las teclas con flechas. También podemos movernos en dispositivos móviles girando y haciendo un paneo del dispositivo.
    </li>    
</ul>

<h2>PRÁCTICAS</h2>

![Escena3D](https://user-images.githubusercontent.com/65786438/110517197-d5b50b00-810a-11eb-8c49-f5d35bab2a59.png)
<ol>
    <li>
        <h3>Tu primera escena virtual</h3>
        Bienvenid@ a tu primera práctica, accede al código, míralo, modifícalo y estúdialo. Tu primera misión es crear una escena parecida pero con tus propias primitivas: añade tus propias texturas y colores, rota los objetos. ¿Eres capaz de crear una habitación? ¿Eres capaz de crear una ventana, una silla o incluso un pequeño avatar? En tus manos lo dejo.  
    </li>
    <li>
        <h3>Segunda escena virtual</h3>
        Aquí podrás crear una escena más avanzada, con sistema de partículas y texturas.
    </li>
    <li>
        <h3>Foto esférica 360</h3>
        Crea una fotografía esférica o de 360 grados e insértala en tu web. Puedes crear fotos con Google Street, por ejemplo.
    </li>
    <li>
        <h3>Realidad Aumentada cubo</h3>
        Utiliza tu tarjeta o marcador Hiro y haz aparecer una primitiva, en este caso un cubo 3D. Inserta una fotografía artística y un texto personalizado sobre tu marcador Hiro, un vídeo en movimiento y un sin fin de posibilidades. Prueba el código de ejemplo.
    </li>
</ol>


![P1](https://user-images.githubusercontent.com/65786438/110252032-c5beef00-7f83-11eb-9650-e03ed7489b49.png)

