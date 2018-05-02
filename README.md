# sistemas-emergentes

Notebooks Jupyter con dos sistemas emergentes simples: el juego de la vida y colonias de hormigas

Ambos ejemplos permiten comprobar las capacidades auto-organizativas de dos conocidos sistemas emergentes:

- **El juego de la vida**: el juego se desarrolla sobre un tablero con cuadrículas (como el del ajedrez) que en teoría se extiende hasta el infinito. Las celdas pueden contener vida, o no. Cada celda tiene 8 celdas vecinas que son las que determinarán, en cada momento, su evolución. A partir de una configuración inicial (denominada semilla) el juego evoluciona de manera determinista siguiendo tres sencillas reglas. Solo con estas reglas, algunas semillas pueden dar lugar a patrones que se replican de forma indefinida.

- **Colonias de hormigas**: los algoritmos basados en colonias de hormigas son un tipo de algoritmo de inteligencia de enjambre en el que un grupo de agentes presentan un comportamiento colectivo complejo. Este comportamiento emerge a partir de un comportamiento indiviual simple, y
una toma de decisiones individuales basada en algún tipo de información compartida. En este notebook se aplicará esta idea a un pequeño juego consistente en conducir las hormigas desde el hormiguero a la comida y viceversa. No se trata de reproducir exactamente el comportamiento de las hormigas reales, sino de mostrar cómo con unas reglas de decisión simples se puede conseguir un objetivo colectivo.

Ambas implementaciones son sencillas y están diseñadas para que cualquier persona (aunque no tenga conocimientos de programación) pueda experimentar con distintas semillas (configuraciones iniciales tanto para el juego de la vida como para la colonia de hormigas) e incluso crear sus propias semillas.

Para poder ejecutar los notebooks lo más cómodo es instalar Anaconda (https://conda.io/docs/user-guide/install/download.html) que incluye el intérprete de Python y Jupyter.
