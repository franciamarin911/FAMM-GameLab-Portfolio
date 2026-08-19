# 🏷️ MATH CRUSH

## 📖 Descripción
* **¿De qué trata?:** Math Crush es un juego de puzzle matemático con estética RGB gamer donde los jugadores deben encontrar el número objetivo seleccionando dos números vecinos en un tablero de 5x5 y aplicando la operación correcta (+, -, ×, ÷).
* **Objetivo del jugador:** Alcanzar la mayor puntuación posible en 60 segundos, combinando números para igualar el objetivo y ganar 100 puntos por cada acierto.
* **Mecánica principal:** El jugador selecciona dos números adyacentes en la cuadrícula, elige una operación y si el resultado coincide con el número objetivo, las celdas desaparecen y se rellenan con nuevos números. Para la lógica de colisiones y vecindad, utilicé variables en español como primeraCelda y segundaCelda con comparaciones de posición mediante Math.abs(fila1-fila2) + Math.abs(col1-col2) === 1, manteniendo un control total sobre la selección de celdas adyacentes.

## 🎭 Género
Puzzle / Matemático (Educativo)

## 🎮 Controles
* **CLICK/TAP** - Seleccionar números vecinos
* **CLICK** - Elegir operación (+, -, ×, ÷)
* **Click en "INICIAR PARTIDA"** - Comenzar juego
* **Click en "VOLVER A JUGAR"** - Reiniciar partida

## 🛠️ Desarrollo y Aprendizaje
* **Tecnologías utilizadas:** HTML5, CSS3 y JavaScript nativo (Web development, sin uso de motores de videojuegos externos).
* **Apoyo de IA:** Asistencia de Claude y Gemini para la estructuración del código, la lógica matemática y el diseño visual (UI/CSS), como parte de la asignatura de Introducción al desarrollo de videojuegos.
* **¿Qué aprendí?:** Manejo de matrices bidimensionales para crear el tablero, lógica para detectar la selección de celdas vecinas y uso de temporizadores (`setInterval`) para el manejo del tiempo de juego en JavaScript.
* **Mejoras futuras:** Agregar efectos de sonido al acertar operaciones, guardar la puntuación máxima (High Score) en el navegador y añadir más niveles de dificultad.

## 📸 Capturas de pantalla

<div align="center">
  <table>
    <tr>
      <td><img width="400" alt="MATH1" src="https://github.com/user-attachments/assets/4bfbb07c-9a5d-4aa7-9f3b-59cccfcbfd55" /></td>
      <td><img width="400" alt="MATH2" src="https://github.com/user-attachments/assets/28511c85-ba86-4714-bc38-79fc3a156543" /></td>
    </tr>
    <tr>
      <td><img width="400" alt="MATH5" src="https://github.com/user-attachments/assets/f9c66708-88d3-458c-b045-f1db87186562" /></td>
      <td><img width="400" alt="MATH3" src="https://github.com/user-attachments/assets/4913b2ac-27e7-494b-8759-9fdb01629d9b" /></td>
    </tr>
    <tr>
      <td colspan="2" align="center"><img width="400" alt="MATH4" src="https://github.com/user-attachments/assets/e40ce4dc-d975-41b9-a4ed-c8fa5888b478" /></td>
    </tr>
  </table>
</div>



