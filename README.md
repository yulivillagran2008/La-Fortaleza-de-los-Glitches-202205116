# Yuli Villagrán
Soy programador Jr. con conocimientos y buenas prácticas en POO.

# Proyecto Integrador (VIDEO JUEGO)
- Proyecto integrador basado a la estructura de un video juego, realizado por medio del ciclo de vida del software.

# La-Fortaleza-de-los-Glitches: Pixel Adventures-202205116
La Fortaleza de los Glitches: Pixel Adventure" es un videojuego educativo de aventura en consola de Python dirigido a usuarios de 8 a 12 años, donde los jugadores exploran mapas, recolectan recursos y resuelven acertijos lógicos para derrotar al Rey Glitch. 
El objetivo principal es guiar al héroe (Vector, representado por 🤖) a través de tres mundos infestados por fallos de código (Glitches, representados por 👾) hasta superar al Jefe Final (el Rey Glitch) y restaurar la lógica del sistema.

¿En qué consiste cada nivel? 
El flujo del juego se divide en tres niveles secuenciales con mecánicas distintas:

-- Nivel 1: El Mapa del Bosque (Mundo 1):

Es un nivel de exploración en una cuadrícula  de 6x6. Junta 3 bloques de madera (🪵) antes de que la energía (que inicia en 25 puntos
y resta 1 por cada paso) o la vida (3 corazones) lleguen a cero.
Eventos aleatorios: Al moverte por el mapa puedes hallar maderas, cofres con monedas o emboscadas de un Glitch que te resta 1 corazón de vida si no llevas un Escudo Protector 🛡️.



-- Nivel 2: La Carrera de los Números (Mundo 2)

Una carrera de velocidad mental con un obstáculo en el camino.   Objetivo: Superar la tubería que bloquea la pista resolviendo un
patrón matemático. Si respondes mal o ingresas texto no numérico, el personaje tropieza y pierde 1 corazón de vida.

  
-- Nivel 3: El Núcleo de la Fortaleza (Mundo 3 - Jefe Final):

Un examen final de lógica en consola contra el Rey Glitch. El objetivo es desbloquear los 3 candados lógicos respondiendo correctamente
a un cuestionario de tres preguntas sobre conceptos de programación en Python
  
  
      Victoria: Al acertar las 3 preguntas, el juego despliega un trofeo en arte ASCII celebrando la victoria final.  


  --   Opciones del Menú Principal: Además del modo de juego principal, el menú incluye:
  
    Jugar: Inicia la aventura secuencial desde el Nivel 1 hasta el Nivel 3.   
    Inventario: Permite equipar objetos como el Pico de Datos, Escudo Protector o consumir Pociones de Energía (+10 pts).
    Opciones: Muestra la configuración de sonido, estado del soporte y créditos.
    Modo 3 Jugadores: Permite registrar hasta tres perfiles en la sesión.
    Tabla de Referencias: Leyenda con la función de cada tecla y el significado de los emojis.
    Salir: Pide confirmación previa antes de cerrar la ejecución



- ¿Cómo ejecutar el programa en consola? Requisitos previos: Tener instalado Python 3.x en el equipo. y para abrir la terminal: Abre la consola de tu sistema (CMD o PowerShell en Windows, o la Terminal integrada de VS Code).


  # 1. Análisis
  En esta fase inicial se definió la propuesta del juego, decidiendo que estaría dirigido a usuarios entre 8 a 12 años y que
  se ejecutaría en consola de Python. Diseñe el concepto del videojuego "La Fortaleza de los Glitches: Pixel Adventure",
  dividiéndolo en 3 niveles: explorar un mapa,  una carrera de acertijos numéricos y responder preguntas lógicas. También
  definiendo los personajes y dejar claros los requerimientos, asegurándose que el juego usara emojis y pueda controlarse
  fácilmente con las teclas (W, A, S, D, E y Q).
  
  # 2. Diseño
  Para el diseño del videojuego elaboré un diagrama de flujo que detalla el recorrido del usuario, desde la bienvenida y el
  menú principal, hasta el paso a paso para completar cada nivel. También aplicando la Programación Orientada a Objetos:
  Estableciendo la clase padre ElementoJuego y sus subclases hijas (Personaje, Enemigo u ObjetoInteractuable), definiendo
  los atributos heredados (coordenadas, emojis) y los métodos donde aplicaría polimorfismo (como mostrar_info() para cambiar
  lo que se muestra en pantalla según el objeto.

  # 3. Desarrollo/Código
  Se programa el videojuego en Python en un  archivo .py estructurado en tres etapas. Empecé haciendo la bienvenida y el
  menú principal dentro de un ciclo para que el usuario pudiera navegar fácil entre las opciones. Luego desarrollé la lógica
  de los 3 niveles usando condicionales, ciclos, listas para la mochila de herramientas, la librería random para eventos
  aleatorios y os.system para ir limpiando la consola y que todo se viera fluido. Para evitar que el juego se trabara si
  alguien presionaba una tecla equivocada, usé bloques try-except en los controles, y fui dejando comentarios en el código
  marcando dónde estaba la clase padre, las clases hijas y el polimorfismo.
  
  # 4. Presentación en GitHub
  Se organiza y publica el proyecto final por medio de un repositorio en Github dentro de cuatro carpetas (Fase 1 - Analisis,
  Fase 2 - Diseño, Fase 3 - Desarrollo y Fase 4 - Presentacion). Subí los documentos de mi trabajo y creé un archivo
  README.md con el nombre del proyecto, mis datos, la descripción del juego, las instrucciones para ejecutar el código
  main.py desde la terminal y capturas de cómo se ve el juego corriendo en la consola.
