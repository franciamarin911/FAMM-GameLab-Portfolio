<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=800&size=30&pause=2000&color=22D3EE&center=true&vCenter=true&width=600&lines=LA+TORMENTA+DIGITAL" alt="La Tormenta Digital Title">
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&colors=6D28D9,7C3AED,8B5CF6,A78BFA,22D3EE&height=4&section=header" width="100%"/>
</div>

<br><br>

<table align="center" width="100%" style="border: 2px solid #22D3EE; border-radius: 16px;" cellpadding="25">
  <tr>
    <td valign="top">
      <h2>📖 Información del Juego</h2>
      <b>🎯 Objetivo del jugador:</b> Sobrevivir a 5 días de ciberacoso escolar gestionando la "Resistencia Emocional" del protagonista. El jugador debe bloquear comentarios de odio, guardar evidencias de amenazas y agradecer el apoyo genuino, evitando engancharse en discusiones.<br><br>
      <b>📝 Descripción:</b>
      <blockquote>
        <b>¿De qué trata?:</b> La Tormenta Digital es un simulador narrativo y educativo sobre la prevención del ciberacoso. Acompañas a Rubén, un estudiante cuyo proyecto de ciencias (un sensor ambiental) se vuelve el blanco de burlas y "funa" en las redes sociales de su colegio.<br><br>
        <b>Mecánica principal:</b> El juego simula el <i>feed</i> de una red social en vivo. Los comentarios aparecen dinámicamente y se dividen por colores (Rojo = Odio, Amarillo = Doxxing, Verde = Apoyo, Azul = Info)[cite: 1]. El jugador debe leer y reaccionar rápidamente usando botones de acción: "Bloquear" (+5% de salud), "Evidencia" (+10% de salud), "Responder" (penaliza con -25%) y "Agradecer". A nivel técnico, utilicé JavaScript nativo gestionando un sistema de colas (`pendingEvents`) y temporizadores (`setInterval`) para generar los posts dinámicamente e ir actualizando la barra de progreso de la salud mental del jugador.
      </blockquote>
      <br>
      <img src="https://img.shields.io/badge/G%C3%A9nero-Serious%20Game%20%2F%20Simulador%20Narrativo-0A0A0F?style=flat-square&labelColor=22D3EE">
    </td>
  </tr>
</table>

<br><br>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&colors=6D28D9,7C3AED,8B5CF6,A78BFA,22D3EE&height=4&section=header" width="100%"/>
</div>

<br><br>

<div align="center">
  <h2>🎮 Controles</h2>
</div>

<br>

<table align="center" width="100%" style="border: 2px solid #A855F7; border-radius: 16px;" cellpadding="20">
  <tr>
    <td>
      <ul>
        <li><b>CLICK / TAP</b> - Interactuar con los botones de acción en cada publicación (Bloquear, Evidencia, Responder, Agradecer).</li>
        <li><b>Lectura rápida</b> - Prestar atención a las etiquetas y colores de los mensajes para tomar la decisión correcta antes de que la pantalla se llene.</li>
      </ul>
    </td>
  </tr>
</table>

<br><br>

<div align="center">
  <h2>🛠️ Desarrollo y Aprendizaje</h2>
</div>

<br>

<table align="center" width="100%" style="border: 2px solid #22D3EE; border-radius: 16px;" cellpadding="20">
  <tr>
    <td>
      <ul>
        <li><b>Tecnologías utilizadas:</b> HTML5, CSS3 (Bootstrap 5, Bootstrap Icons) y JavaScript Vanilla[cite: 1]. Animaciones en Canvas para el fondo de partículas.</li>
        <li><b>Apoyo de IA:</b> Utilicé la asistencia de IA para estructurar el guion narrativo de los 5 días, generar los perfiles de los "haters" y "aliados", y optimizar la lógica del DOM dinámico.</li>
        <li><b>¿Qué aprendí?:</b> En este proyecto profundicé en la creación de "Serious Games" (juegos con propósito educativo). Comprendí cómo analizar el tema del ciberacoso a través de los siguientes elementos:
          <ul>
            <br>
            <li><b>Diseño UI/UX inmersivo:</b> Aprendí a construir una interfaz que imita la presión y el estrés de una red social real mediante notificaciones rápidas y códigos de color visuales.</li>
            <li><b>Manipulación del DOM:</b> Mejoré mi lógica en JavaScript para crear, inyectar y destruir elementos HTML en tiempo real, basándome en las acciones del usuario.</li>
            <li><b>Manejo de Estados:</b> Implementé un sistema robusto para rastrear el día actual, la salud del jugador y los eventos pendientes de la historia.</li>
          </ul>
        </li>
        <br>
        <li><b>Mejoras futuras:</b> Implementar un sistema de decisiones ramificadas donde guardar evidencias específicas desbloquee finales diferentes, o agregar un modo "Infinito" para ver cuánto tiempo puede resistir el jugador.</li>
      </ul>
    </td>
  </tr>
</table>

<br><br>

<div align="center">
  <h2>📸 Capturas de pantalla</h2>
<div align="center">
  <table>
    <tr>
      <td align="center">
        <!-- REEMPLAZA "PONER_AQUI_TU_LINK_DE_IMAGEN" POR EL LINK DE TU IMAGEN DE INICIO -->
        <img width="380" alt="Pantalla Inicial" src="PONER_AQUI_TU_LINK_DE_IMAGEN" />
        <br><b>🏠 Guía y Reglas</b>
      </td>
      <td align="center">
        <!-- REEMPLAZA "PONER_AQUI_TU_LINK_DE_IMAGEN" POR EL LINK DE TU IMAGEN DEL FEED SOCIAL -->
        <img width="380" alt="Feed Social" src="PONER_AQUI_TU_LINK_DE_IMAGEN" />
        <br><b>📱 Feed Social en Vivo</b>
      </td>
      <td align="center">
        <!-- REEMPLAZA "PONER_AQUI_TU_LINK_DE_IMAGEN" POR EL LINK DE TU IMAGEN TOMANDO ACCIONES -->
        <img width="380" alt="Interacción" src="PONER_AQUI_TU_LINK_DE_IMAGEN" />
        <br><b>🛡️ Interacción y Bloqueo</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <!-- REEMPLAZA "PONER_AQUI_TU_LINK_DE_IMAGEN" POR EL LINK DE TU IMAGEN DE FIN DE DÍA -->
        <img width="380" alt="Fin de día" src="PONER_AQUI_TU_LINK_DE_IMAGEN" />
        <br><b>🌙 Resumen del Día</b>
      </td>
      <td align="center">
        <!-- REEMPLAZA "PONER_AQUI_TU_LINK_DE_IMAGEN" POR EL LINK DE TU IMAGEN DE VICTORIA -->
        <img width="380" alt="Victoria" src="PONER_AQUI_TU_LINK_DE_IMAGEN" />
        <br><b>🏆 Victoria y Apoyo Total</b>
      </td>
      <td align="center">
        <!-- REEMPLAZA "PONER_AQUI_TU_LINK_DE_IMAGEN" POR EL LINK DE TU IMAGEN DE DERROTA -->
        <img width="380" alt="Derrota" src="PONER_AQUI_TU_LINK_DE_IMAGEN" />
        <br><b>☠️ Agotamiento Emocional</b>
      </td>
    </tr>
  </table>
</div>

<br><br>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&colors=7C3AED,8B5CF6,A78BFA,67E8F9,22D3EE&height=120&section=footer" width="100%"/>
</div>
