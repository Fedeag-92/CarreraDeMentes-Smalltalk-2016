# CarreraDeMentes Smalltalk 2016

  Trabajo Práctico Final Libre para la materia Programación Orientada a Objetos de la Universidad Nacional del Comahue (UNCo).

  _Esta es una aplicación del juego de mesa Carrera de Mentes, para jugar entre 3 y 6 jugadores._
  </br></br>
  ![alt ejemplo](https://github.com/Fedeag-92/CarreraDeMentes-Smalltalk-2016-/blob/main/ejemplo.JPG?raw=true)
  ![alt clases](https://github.com/Fedeag-92/CarreraDeMentes-Smalltalk-2016/blob/main/Clases.JPG?raw=true)

## Construido con 🛠️

  - [Smalltalk](http://www.smalltalk.org/) - Lenguaje utilizado.

  - [Squeak](https://squeak.org/) - Entorno de desarrollo utilizado.

## Instalación - Iniciar 🎲

  - Arrastrar el archivo .st a Squeak.
  - FileIn.<br />
    ![alt imagenFileIn](https://github.com/Fedeag-92/CarreraDeMentes-Smalltalk-2016-/blob/main/FileIn.JPG?raw=true)
  - openInWorld (Workspace). Ctrl + d (do it) para ejecutar el código.<br />
    ![alt imagenIniciar](https://github.com/Fedeag-92/CarreraDeMentes-Smalltalk-2016-/blob/main/Iniciar.JPG?raw=true)
    
## Requerimientos del juego 📄
Es un juego de preguntas y respuestas, sobre diversos temas: deportes y pasatiempos,
geografia, historia, espectáculos, arte y literatura, ciencias y naturaleza. Cada tema tiene
asociado un color: naranja (cambalache), marrón (arte), rosado (espectáculos), amarillo
(naturaleza), verde (deporte) y celeste (geografía).</br>
El juego consta de un tablero, 1 dado, 6 mástiles (uno de cada color), y 6 fichas de cada color.
Para cada tema hay un libro con las preguntas.</br>
El tablero consta de 42 casilleros, cada casillero tiene un número (a los efectos de poder
ubicar al jugador), y un color, que puede ser alguno de los indicados en el párrafo anterior o
gris. El tablero tiene un casillero de salida (que será el casillero número 0).</br>
El juego consiste en ir contestando preguntas de los diversos temas para avanzar y ganar
fichas. Cada jugador tiene un mastil, y debe conseguir una ficha de cada color para apilar en
su mastil. Gana el jugador que consigue primero completar su mastil con las 6 fichas.
Intervienen entre 3 y 6 jugadores.</br>
Cada jugador comienza su turno tirando el dado para decidir cuantos casilleros debe avanzar.
Una vez en el casillero, tira el dado 3 veces para decidir que pregunta debe contestar. La
combinación de números obtenidos dan el número de pregunta. La pregunta debe hacerse
sobre el tema correspondiente al color del casillero en el que se encuentra el jugador. Es decir,
si el jugador está en un casillero verde, y al tirar el dado obtiene 2, 4, 1, tendrá que responder
la pregunta 241 del tema "deportes". Si la pregunta se contesta correctamente el jugador
avanza 5 posiciones y sigue jugando (sigue en su turno). Si la pregunta se contesta de manera
incorrecta el jugador pierde su turno.</br>
Algunas preguntas tienen opciones, y en este caso cuando se contesta correctamente el
jugador avanza solo 1 casillero.</br>
Algunos casilleros en el tablero tiene un '*', que indica que ese casillero tiene premio. Cuando
un jugador esta en un casillero con premio, y contesta bien la pregunta correspondiente, gana
una ficha del color del casillero. El jugador sólo puede obtener una ficha de cada color.</br>
Cuando un jugador esta en un casillero gris debe elegir sobre que tema desea contestar la
pregunta.</br>
Cuando un jugador pasa por la salida, es decir que ha completado una vuelta gana 1 ficha del
color que él seleccione entre los que le faltan.</br>
Cuando un jugador llega a un casillero que está ocupado por otro jugador que tiene fichas y
contesta correctamente le quita una ficha al otro jugador, si es que alguna le sirve.</br>
Observación: la última ficha solo puede obtenerse contestando correctamente una pregunta,
NO al pasar por la salida.
## Autores ✒️

- **Federico Aguilera** - [Fedeag-92](https://github.com/Fedeag-92)
