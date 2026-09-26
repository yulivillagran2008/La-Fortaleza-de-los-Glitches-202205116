# La-Fortaleza-de-los-Glitches-202205116
La Fortaleza de los Glitches: Pixel Adventure es un videojuego educativo diseñado para consola de Python dirigido a usuarios de 8 a 12 años, donde los jugadores exploran mapas, recolectan recursos y resuelven acertijos lógicos para derrotar al Rey Glitch. Para jugar ejecuta "fase3_desarrollo.py" en la terminal y sigue las instrucciones en pantalla.

# Yuli Villagrán
Soy programador Jr. con conocimientos y buenas prácticas en POO.

# Proyecto Integrador (VIDEO JUEGO)
- Proyecto integrador basado a la estructura de un video juego, realizado por medio del ciclo de vida del software.


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
Fase 2 - Diseno, Fase 3 - Desarrollo y Fase 4 - Presentacion). Subí los documentos de mi trabajo y creé un archivo README.md
con el nombre del proyecto, mis datos, la descripción del juego, las instrucciones para ejecutar el código main.py desde la
terminal y capturas de cómo se ve el juego corriendo en la consola.
