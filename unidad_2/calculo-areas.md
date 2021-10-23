# Cálculo de Áreas
## Análisis

El programa empezará preguntando al usuario de que polígono va a querer calcular el área (1. Triángulo; 2. Cuadrado; 3. Rectángulo;
4. Rombo; 5. Romboide; 6. Trapecio; 7. Pentágono; 8. Círculo). Después utilizaremos la sentencia “switch” para calcular el área dependiendo de la opción elegida:

- Triángulo: pedirá la base y la altura, y calcula el área siguiendo la fórmula `A = (b*h)/2`.

- Cuadrado: pedirá la longitud de un lado y calcula el área siguiendo la fórmula `A = l^2`.

- Rectángulo: pedirá la base y la altura, y se calcula el área siguiendo la fórmula `A = b*h`.

- Rombo: pedirá las longitudes de las diagonales (D → diagonal mayor; d → diagonal menor) y se calcula el área siguiendo la fórmula `A = (D*d)/2`.

- Romboide: pedirá la base y la altura, y se calcula el área siguiendo la fórmula `A = b*h`.

- Trapecio: pedirá la longitud de las dos bases y la altura, y calcula el área siguiendo la fórmula `A = ((b+b)/2)*h`.

- Pentágono: pedirá la longitud de un lado y la distancia desde el centro hasta la mediatriz de un lado, primero se calculará el perímetro (P) 
y después el área siguiendo la fórmula `A = (P*a)/2`.

- Círculo: pedirá el radio del círculo y se calcula el área siguiendo la fórmula `A = π * r^2`.

Una vez calculado el área de la figura la mostrará por pantalla.
