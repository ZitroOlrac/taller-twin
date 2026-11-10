# Taller Twin

Juego de taller con dos capas. Fuera, llevas el taller: llegan clientes y cada uno tiene una barra de paciencia; decides qué coche va a cada elevador. Dentro, en tu elevador, **investigas qué le pasa al coche** y lo reparas con tus manos, con pasos de seguridad evaluados como en un simulador de formación profesional.

**Jugar:** https://zitroolrac.github.io/taller-twin/

![Subiendo un coche al elevador con la parada de comprobación](preview.webp)

## El coche no te dice lo que tiene

El cliente solo cuenta lo que nota («hace un ruido raro», «le cuesta arrancar»). Cada coche tiene una o varias averías ocultas y tienes que encontrarlas todas:

- **En el suelo:** acelerar y escuchar (la correa chilla), pisar el freno (las pastillas rechinan, el pedal esponjoso delata falta de líquido), girar el volante (la rótula hace clonc), empujar la carrocería (un amortiguador gastado rebota), abrir el capó (varilla del aceite, depósitos de refrigerante y de líquido de frenos, batería con multímetro, correa), oler y conectar el escáner OBD.
- **Por debajo:** grosor de las pastillas, amortiguador que rezuma, holgura de la rueda y gotas en el suelo según su color.

Cada prueba se apunta en una libreta. Al final firmas un informe con todas las averías: si te dejas una, el coche se va roto; si marcas algo que está bien, cambias una pieza sin necesidad.

## Los 7 pasos de cada coche

1. **Entrar al elevador:** el coche entra solo y pones el freno de mano.
2. **Inspección en el suelo.**
3. **Brazos del elevador:** solo en los puntos de elevación reforzados del chasis.
4. **Subir el coche:** parada de comprobación a 20 cm, altura de trabajo y seguro mecánico.
5. **Mirar por debajo** y firmar el informe.
6. **Reparación:** piezas con apriete en estrella y llave dinamométrica, y líquidos rellenados entre MIN y MAX.
7. **Bajar y entregar:** quitar el seguro y despejar la zona antes de bajar.

## Mandos

Todo se juega tocando las cosas del taller con el ratón o el dedo: pedales y volante, capó, depósitos, botonera del elevador, candado, rueda, tornillos y botella. Con sonido: muchas averías se oyen.

## Cómo está hecho

JavaScript puro y Canvas 2D, sin dependencias, en un único `index.html`: bucle de juego con reloj de turno, cola de clientes con paciencia, mecánicos que trabajan en paralelo, generador de averías con sus pistas, máquina de estados para los 7 pasos, evaluación por criterios, sonido sintetizado con Web Audio (motor, chillido de correa, chirrido de frenos) y mandos táctiles.

## Autor

Carlo Prado Ortiz · [Portafolio](https://zitroolrac.github.io/Portfolio/)
