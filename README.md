# laViejaEjercicioNueve
Esta aplicacion hecha con Java con la clase Swing es el famoso juego tres en raya, el gato ó también conocido como "La vieja" en Venezuela. Finalizado

Esta compuesto por dos jFrame, siendo el Login preguntando si jugaras con alguien o con una IA, si llegado caso es "si" se procedera y recorrera todo el codigo del jFrame y pediria los nombres de usuario de ambos. Si llegado caso es "no" omite el Login y al jugador lo llamara "humano" y se procedera a jugar contra la IA.

El siguiente jFrame es el del tablero, donde esta compuesto por botones no visibles para que la imagen de fondo se vea mas natural pero los botones son totalmente funcionales. Aqui es donde sucede la magia, los botones estan creados por serapado ( y no por una matriz como se podria hacer normalmente ) debido a que mantuve un control mas completo de que botones estaba usando. Al presionar un boton este realiza unos procedimientos para colocar la imagen, hacer que el boton no este vacio, y hacer que la IA juegue despues si llegado caso el booleano "vsIA" sea true, proceda a buscar algun lugar en el tablero para que el juego verifique si existe algun ganador y siga su curso.
