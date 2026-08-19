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
* **Tecnologías utilizadas:** HTML5, CSS3 y JavaScript nativo *(puedes cambiar esto si usaste otro motor o lenguaje)*.
* **Apoyo de IA:** Utilicé la asistencia de Claude, Gemini y ChatGPT para la estructuración de la lógica del juego, generación de ideas y la definición analítica del perfil del jugador ideal.
* **¿Qué aprendí?:** En este proyecto profundicé en el diseño centrado en el usuario, aprendiendo a definir y aplicar el marco del **Player Persona**. Comprendí cómo analizar a mi público objetivo a través de los siguientes elementos:
  * **Player Persona:** Aprendí a crear una representación semi-ficticia del jugador ideal. Es vital porque sirve como brújula para tomar decisiones de diseño, asegurando que el juego realmente conecte con su audiencia.
  * **Objetivos del jugador (Goals):** Identifiqué lo que el jugador busca lograr dentro de la experiencia. Es importante para diseñar metas claras que mantengan el interés y brinden satisfacción.
  * **Frustraciones (Pain points):** Analicé los obstáculos que pueden generar enojo o aburrimiento. Su importancia radica en poder pulir la curva de dificultad y la interfaz para evitar que el usuario abandone el juego.
  * **Motivaciones:** Comprendí el "por qué" el usuario decide jugar (competencia, relajación, curiosidad). Esto es fundamental para construir mecánicas y sistemas de recompensas efectivos.
  * **Comportamientos y hábitos:** Evalué el contexto del jugador (cuánto tiempo juega, en qué plataforma). Es esencial para adaptar la duración de las partidas y el diseño de los controles a su rutina real.
* **Mejoras futuras:** Realizar pruebas de juego (playtesting) con personas reales que encajen en el perfil del Player Persona para validar si el diseño cumple con sus motivaciones y resuelve sus frustraciones.

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

