# 🏷️ Gotitas Mágicas

## 📖 Descripción
* **¿De qué trata?:** Gotitas Mágicas es un juego educativo de habilidad donde el jugador debe recolectar gotas de agua puras mientras evita la contaminación, ayudando a Ajolí el Ajolote a salvar su hábitat acuático de la basura, toxinas y químicos dañinos.
* **Objetivo del jugador:** Alcanzar la mayor puntuación posible recolectando 💧 gotas puras, 🌱 plantas, 🌺 flores y 🌟 estrellas, mientras esquivas elementos contaminantes como 🗑️ basura, 🧪 toxinas y ☣️ smog. Sube de nivel llenando la barra de pureza del agua.
* **Mecánica principal:** El jugador mueve una canasta de izquierda a derecha con el mouse o tacto para atrapar los elementos que caen. Cada objeto tiene un valor positivo o negativo. Power-ups como ❄️ Congelación (reduce velocidad), 🛡️ Escudo (bloquea contaminación) y 💖 Vida extra ayudan en la partida. Para la lógica de colisiones y detección de captura, utilicé variables en español como basket, items, particles y floatingTexts con comparaciones de distancia mediante Math.sqrt(dx*dx + dy*dy), manteniendo un control total sobre el comportamiento del juego.

## 🎭 Género
Arcade / Educativo (Habilidad)

## 🎮 Controles
* **MOUSE / DEDO** - Mover la canasta horizontalmente
* **CLICK / TAP** - Interactuar con menús y botones
* **BOTÓN DE SONIDO** - Activar/desactivar audio

## 🛠️ Desarrollo y Aprendizaje
* **Tecnologías utilizadas:** HTML5 / CSS3 / JavaScript (Canvas 2D), Web Audio API para efectos de sonido.
* **Apoyo de IA:** Asistencia en lógica de colisiones, organización de código y diseño de UI con ChatGPT y Claude
* **¿Qué aprendí?:** Manejo de animaciones en Canvas, sistemas de partículas, gestión de estados del juego, implementación de power-ups y efectos visuales dinámicos. Además, aprendí a diseñar y desarrollar un juego basado en un Player Persona, creando una conexión emocional con el jugador a través de un personaje carismático (Ajolí el Ajolote) que motiva la acción y da sentido a la mecánica central, haciendo que cada interacción refuerce el vínculo con la historia y el propósito del juego.
* **Mejoras futuras:** Añadir más power-ups, niveles con obstáculos fijos, tabla de puntuaciones en línea y efectos de sonido más variados.

## 📸 Capturas de pantalla

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img width="380" alt="Pantalla Inicial" src="https://github.com/user-attachments/assets/5d37373e-53ca-485d-9f4b-c69ac4c51156" />
        <br><b>🏠 Niveles de Juego</b>
      </td>
      <td align="center">
        <img width="380" alt="Gameplay" src="https://github.com/user-attachments/assets/bef9c9ec-6e91-4f4f-9607-5cef64291443" />
        <br><b>🎮 Inicio</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="380" alt="Power-ups" src="https://github.com/user-attachments/assets/941c5b27-aee4-4f52-92c7-2e1e5455ec4c" />
        <br><b>❄️ Power-ups</b>
      </td>
      <td align="center">
        <img width="380" alt="Victoria" src="https://github.com/user-attachments/assets/2d676cff-5eb9-4ea3-b58b-740d6fddca4e" />
        <br><b>⚠️ Derrota</b>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        <img width="380" alt="Contaminación" src="https://github.com/user-attachments/assets/5657c902-f8c6-43cc-bab4-796566480ae4" />
        <br><b>🏆 Victoria</b>
      </td>
    </tr>
  </table>
</div>


