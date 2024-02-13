# piracy
https://www.codewars.com/kata/54fe05c4762e2e3047000add

### La Clase Ship: Esta es la plantilla para representar los barcos.

- **draft**: Un número que representa qué tan pesado es el barco (más peso = calado más profundo).
- **crew**: El número de marineros en el barco.
- **constructor**: Necesaria para crear un objeto Ship. Establece los valores iniciales para draft y crew.
- **The crew factor**: Cada miembro de la tripulación agrega 1.5 unidades de peso al calado del barco.

#### The Treasure Threshold 
Si el calado de un barco sigue por encima de 20 después de tener en cuenta el peso de la tripulación, es una señal de que el barco está cargado de tesoros.

#### El Método isWorthIt():
Esta función es donde pondrás tu lógica de búsqueda de tesoros. Así es como funciona:

1. Calcula el peso aportado por la tripulación (crew * 1.5)
2. Resta el peso de la tripulación del calado total.
3. Si el calado restante es superior a 20, vale la pena saquear el barco , de lo contrario, no lo es.

