# Art Obby!

**Descripción breve del juego**: Es un juego Obby de arte, en el cual tienes que cruzar varios obstáculos como lápices, y dos plataformas móviles.

**Género y perspectiva del juego, indicando si es 3D o 2.5D**: 3D

**Condición de victoria**: La condición de victoria es llegar a la meta pasando los obstaculos que vienen en el camino.

**Condición de derrota**: Al caer de las plataformas, ya sean móviles o no, nuestra vida bajará causando que al perder tres vidas, perdamos.

**Controles del juego**: Para movernos usamos las teclas W A S D, para saltar se usa espacio y para mover la cámara usamos el mouse.

**Lista de Blueprints principales**: BP_MenuGameMode, BP_ObbyCharacter, BP_ObbyGameMode, BP_ObbyGameState, BP_KillZone, BP_Checkpoint.

**Explicación del Game Mode personalizado**: Da las indicaciones de vida o muerte. Si nos caemos perderemos una vida pero podemos continuar ya que tenemos dos más y así hasta llegar a la última vida, lo que va a activar nuestra pantalla de derrota.

**Explicación del Game State personalizado**: Usé los checkpoints y las vidas, los checkpoints guardan tu posicion actual, si te caes reiniciarás nuevamente donde te quedaste, a no ser que no hayas guardado checkpoint te regresará al inicio. Y las vidas, cada que caes podemos observar como se resta una vida y se puede ver en el BluePrint específico del GameState.

**Explicación de la UI principal**: En el menú principal agregué dos botones que se usan para salir o para entrar al juego, el de jugar te lleva al inicio del Obby y el de salir se sale del juego.

**Explicación de la pantalla de victoria y derrota**: Como expliqué en el Game Mode sobre la vida o muerte, las pantallas fueron justamente hechas para el propósito de ver cuando pierdes o ganas. La primera que explicaré es la de victoria, en la cual aparece un gatito dando un corazón el cual es un premio. En la de derrota es es un gatito triste y con pintura en la cabeza ya que al no llegar a la meta la pintura se le cayó. Ambas pantallas tienen botones de reiniciar o ir al menú principal.

**Explicación del enemigo, obstáculo o mecánica principal**: Lo mío fue un obstáculo, el cual le dí una animación de movilidad, de punto A al punto B se nota que la animación tiene un ligero deslizamiento, cuando viene de vuelta o de regreso. La plataforma es una libreta.

**Capturas de pantalla del juego**:

![Captura1](/Screenshot1.png)
![Captura2](/Screenshot2.png)
![Caputra3](/Screenshot3.jpg)
