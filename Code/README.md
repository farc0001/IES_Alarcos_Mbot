# DESCRIPCIÓN DE LAS MISIONES
La competición está compuesta por 3 misiones.

## MISIÓN 1. FUMIGACIÓN AUTÓNOMA DE CULTIVOS
<img width="775" height="738" alt="image" src="https://github.com/user-attachments/assets/4f169cc7-13ba-4529-87a6-3f6c8e47de0c" />
La misión consiste en:

* Fumigar las regiones de cultivo (marrón en la imagen anterior) siguiendo la línea verde por su derecha, es decir, con la línea verde a la izquierda. Correcto suma un punto por franja, incorrecto resta.
* No fumigar regiones de cultivo con línea azul, es decir, no seguir dejando a la izquierda, las líneas azules. Resta un punto no atender a este criterio.
* No se debe fumigar dos veces la misma zona de cultivo. Resta un punto no atender a este criterio.
* No debe salirse de la región de cultivo hasta terminar la misión. De salirse antes, se anotan los puntos conseguidos y tiempo infinito.
* La velocidad es importante. Es el criterio de desempate en caso de que haya más de un equipo que tenga el mismo número de puntos, es el que lo haya realizado en menos tiempo.

Para esta misión solo se ha empleado el cuádruple sensor RGB.
Para cumplir la misión correctamente, se ha encontrado la siguiente solución con el orden a la hora de seguir las líneas verdes según la imagen siguiente.
<img width="609" height="582" alt="image" src="https://github.com/user-attachments/assets/e7384a37-fda3-4361-8858-ce5fdc299fa9" />


## MISIÓN 2. TRASLADO AUTÓNOMO DE ALPACAS DE PAJA
Siguiendo las líneas negras y de color, hay que trasladar las alpacas que están en cada línea de color a la zona de graneros de su color. El blanco es la de la alpaca que no está en ninguna línea.
<img width="831" height="788" alt="image" src="https://github.com/user-attachments/assets/c8912d93-7d92-4f65-b83f-804ece486ced" />

Para hacer la misión 2, primero se coloca la alpaca de la línea azul, después la verde, la roja, la amarilla y finalmente la que va al color blanco. Se emplea combinado el sensor distancia de ultrasonidos con el cuádruple sensor de RGB.


## MISIÓN 3. EXTINCIÓN AUTOMÁTICA DE INCENDIOS
Dentro de cada uno de los 4 círculos hay una vela, tres de ellas encendidas (la blanca es una de ellas) y otra apagada.

Se deben apagar las velas encendidas (suma un punto por cada una) y penaliza intentar apagar la que está apagada.
<img width="852" height="822" alt="image" src="https://github.com/user-attachments/assets/dbf49c72-a427-42db-a2d7-f399a075bf3f" />

Para esta misión se emplea un sensor de llama en serie con el de ultrasonidos para la detección de las velas encendidas.

Para apagar las velas, se ha colocado una lámina de papel de aluminio y se pasa por encima de la vela.

