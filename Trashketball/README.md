# 🏷️ TRASHKETBALL

## 📖 Descripción
* **¿De qué trata?:** Trashketball Extreme Pro es un simulador arcade de reciclaje con física avanzada, donde los jugadores deben lanzar residuos a contenedores móviles en un entorno urbano vivo. Cada residuo debe ir al contenedor correcto (orgánico, reciclable o no reciclable), con un sistema de viento dinámico, obstáculos rebotadores y multiplicadores de combo.
* **Objetivo del jugador:** Alcanzar la mayor puntuación posible en 60 segundos encestando residuos en sus contenedores correspondientes, manteniendo una racha de aciertos para multiplicar los puntos y evitando perder las 3 vidas disponibles.
* **Mecánica principal:** El jugador arrastra y suelta el residuo desde el punto de lanzamiento, calculando la trayectoria afectada por la gravedad y el viento. Para la lógica de colisiones y detección de encestes, utilicé variables en español como item, bins, obstacle y dragStart con comparaciones de posición mediante item.x > b.x && item.x < b.x + b.w, manteniendo un control total sobre la física del tiro y la interacción con contenedores y obstáculos.

## 🎭 Género
Juego de habilidad / Juego de trayectoria

## 🎮 Controles
* **MOUSE / DEDO** - Arrastrar residuo para apuntar
* **SOLTAR CLICK / TAP** - Lanzar el residuo
* **CLICK en "¡JUGAR AHORA!"** - Iniciar partida
* **CLICK en "REINTENTAR"** - Reiniciar juego

## 🛠️ Desarrollo y Aprendizaje
* **Tecnologías utilizadas:** HTML5, CSS3 y JavaScript nativo utilizando la API de Canvas.
* **Apoyo de IA:** Utilicé la asistencia de Claude y Gemini para estructurar la física del juego, el cálculo de trayectorias y el diseño visual, como parte de la asignatura de Introducción al desarrollo de videojuegos.
* **¿Qué aprendí?:** Durante este proyecto comprendí cómo se estructura un juego utilizando el marco MDA y exploré los distintos géneros de videojuegos (plataformas, puzle, simulación, aventura, arcade, rol, etc.), clasificando este título como un simulador arcade. En la práctica, esto se tradujo en:
  * **Mecánicas:** Implementación de físicas de gravedad. Desarrollo de un sistema de arrastre y lanzamiento. Lógica para clasificar objetos en contenedores específicos (orgánico, reciclable y no reciclable). Detección de colisiones con obstáculos móviles.
  * **Dinámicas:** Integración de un temporizador de 60 segundos. Sistema de 3 vidas para penalizar errores. Implementación de multiplicadores de puntaje mediante combos. Manejo de variables aleatorias, como el viento dinámico y contenedores en movimiento, que alteran la dificultad en cada tiro.
  * **Estética:** Creación de una experiencia inmersiva mediante fondos urbanos animados, como nubes y autos. Uso de partículas y notificaciones en pantalla para reforzar la sensación competitiva y de simulador arcade.
* **Mejoras futuras:** Integración de efectos de sonido (SFX) para los rebotes y aciertos, música de fondo urbana, y una tabla de puntuaciones máximas (Leaderboard) para fomentar la rejugabilidad.
  
## 📸 Capturas de pantalla

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img width="380" alt="Pantalla Inicial" src="https://github.com/user-attachments/assets/099d43c0-bce3-4f15-9575-29d826f40107" />
        <br><b>🏠 Inicio</b>
      </td>
      <td align="center">
        <img width="380" alt="Apuntando" src="https://github.com/user-attachments/assets/9cb8d686-b75b-4eb1-bd89-4ad01fad2b4d" />
        <br><b>🎯 Apuntando</b>
      </td>
      <td align="center">
        <img width="380" alt="Viento" src="https://github.com/user-attachments/assets/70c7c320-aff9-48e9-bd98-91a2ad9b27c8" />
        <br><b>💨 Viento</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="380" alt="Encestando" src="https://github.com/user-attachments/assets/bde92ff3-c7d6-41f0-aff3-4a5d86256a6a" />
        <br><b>🗑️ Encestando</b>
      </td>
      <td align="center">
        <img width="380" alt="Combo" src="https://github.com/user-attachments/assets/96a7f53f-fba4-4fc8-9cde-178c3e74b636" />
        <br><b>🔥 Encestado incorrecto</b>
      </td>
      <td align="center">
        <img width="380" alt="Obstáculo" src="https://github.com/user-attachments/assets/f9d457cf-e276-4d7f-a8c2-a6d68186fc6c" />
        <br><b>⚡ Obstáculo</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="380" alt="Fallo" src="https://github.com/user-attachments/assets/f9dd715f-f1cc-49a2-8b97-c3f1b775ac7a" />
        <br><b>❌ Fallo</b>
      </td>
      <td align="center">
        <img width="380" alt="Victoria" src="https://github.com/user-attachments/assets/cc7009ae-c157-4799-bbd6-fd32d630be6b" />
        <br><b>💀 Game Over</b>
      </td>
      <td align="center">
        <img width="380" alt="Game Over" src="https://github.com/user-attachments/assets/cda06a2e-6aac-42bc-90bf-d3aeca8f7298" />
        <br><b>🏆 Victoria</b>
      </td>
    </tr>
  </table>
</div>






