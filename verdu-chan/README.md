# 🏷️ Verdu-CHAN

## 📖 Descripción
* **¿De qué trata?:** Verdu-Chan es un survival arcade con temática de comida saludable vs. comida chatarra, donde controlas a una adorable zanahoria kawaii que debe defender la nevera de una invasión de alimentos ultraprocesados. El juego combina mecánicas de "survivor-like" con un sistema de oleadas, mejoras y combos.
* **Objetivo del jugador:** Sobrevivir a todas las oleadas de comida chatarra (hamburguesas, pizzas, donuts, etc.) durante el tiempo límite de cada nivel, recolectando verduras que curan y otorgan experiencia para subir de nivel y elegir mejoras que potencien al personaje.
* **Mecánica principal:** El jugador se mueve libremente por el escenario con WASD o flechas, mientras el ataque es automático (dispara proyectiles al enemigo más cercano). Al derrotar enemigos, estos sueltan verduras que al recogerse restauran vida y dan EXP. Al subir de nivel, se abren 3 mejoras aleatorias para elegir. Para la lógica de colisiones y detección de enemigos, utilicé variables en español como game.enemies, game.player, game.projectiles y game.fruits con comparaciones de distancia mediante dist2(x1,y1,x2,y2) y estructuras de datos organizadas para mantener un control total sobre el comportamiento del juego.

## 🎭 Género
Survival / Arcade (Roguelite)

## 🎮 Controles
* **WASD / FLECHAS** - Movimiento del personaje
* **JOYSTICK TÁCTIL** - Movimiento en dispositivos móviles
* **CLICK** - Interactuar con menús y mejoras
* **Ataque automático** - No requiere botón, se dispara solo al enemigo más cercano

## 🛠️ Desarrollo y Aprendizaje
* **Tecnologías utilizadas:** HTML5, CSS3 y JavaScript nativo (Web development, sin uso de motores de videojuegos externos).
* **Apoyo de IA:** Asistencia de Claude y Gemini para la estructuración del código, la lógica matemática y el diseño visual (UI/CSS), como parte de la asignatura de Introducción al desarrollo de videojuegos.
* **¿Qué aprendí?:** Manejo de matrices bidimensionales para crear el tablero, lógica para detectar la selección de celdas vecinas y uso de temporizadores (`setInterval`) para el manejo del tiempo de juego en JavaScript.
* **Mejoras futuras:** Agregar efectos de sonido al acertar operaciones, guardar la puntuación máxima (High Score) en el navegador y añadir más niveles de dificultad.

## 📸 Capturas de pantalla

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img width="380" alt="Pantalla Inicial" src="https://github.com/user-attachments/assets/67955e9f-26fb-4ed3-9261-588b3f1af5cc" />
        <br><b>🏠 Inicio</b>
      </td>
      <td align="center">
        <img width="380" alt="Gameplay 1" src="https://github.com/user-attachments/assets/90e1f79e-2e1f-4059-a322-9efc232689cf" />
        <br><b>⚔️ Combate</b>
      </td>
      <td align="center">
        <img width="380" alt="Gameplay 2" src="https://github.com/user-attachments/assets/bc9f0aed-674a-47cc-b13d-7a74e6c7389e" />
        <br><b>📈 Mejoras</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="380" alt="Gameplay 3" src="https://github.com/user-attachments/assets/7655bf52-9033-48cc-a366-c34fc8c4cd72" />
        <br><b>💥 Oleada Completada</b>
      </td>
      <td align="center">
        <img width="380" alt="Gameplay 4" src="https://github.com/user-attachments/assets/aa9ee284-c091-43fa-b342-42daf9235262" />
        <br><b>💌 Mensajes motivadores</b>
      </td>
      <td align="center">
        <img width="380" alt="Gameplay 5" src="https://github.com/user-attachments/assets/7806a6ee-bef8-4455-b605-a422f9a00175" />
        <br><b>🏆 Victoria</b>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="3">
        <img width="380" alt="Gameplay 6" src="https://github.com/user-attachments/assets/384afc9c-d108-44c9-aea0-c711e4a685d4" />
        <br><b>☠️ Derrota</b>
      </td>
    </tr>
  </table>
</div>

