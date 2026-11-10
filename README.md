# Taller Twin

Juego de taller con dos capas. Fuera, llevas el taller: llegan clientes con averías y cada uno tiene una barra de paciencia; decides qué coche va a cada elevador. Dentro, en tu elevador, reparas el coche con tus manos, con pasos de seguridad evaluados como en un simulador de formación profesional.

**Jugar:** https://zitroolrac.github.io/taller-twin/

![Subiendo un coche al elevador con la parada de comprobación](preview.webp)

## Los 6 pasos de cada reparación

1. **Entrar al elevador**: conduces despacio y centrado, sin golpear las columnas, y frenas dentro de la zona.
2. **Brazos del elevador**: solo en los puntos de elevación reforzados del chasis.
3. **Subir el coche**: parada de comprobación a 20 cm, altura de trabajo y seguro mecánico.
4. **Diagnóstico**: lees la medida (multímetro, escáner OBD, manómetro…) y la comparas con el valor correcto.
5. **Reparación**: aflojas y aprietas en estrella con la llave dinamométrica, dentro del par del fabricante.
6. **Bajar y entregar**: quitas el seguro y despejas la zona antes de bajar.

Cada paso crítico mal hecho quita estrellas y dinero. Los coches que pasas a los mecánicos Luis y Andrés tardan más y cobran menos, pero te liberan.

## Cómo está hecho

JavaScript puro y Canvas 2D, sin dependencias, en un único `index.html`: bucle de juego con reloj de turno, cola de clientes con paciencia, mecánicos que trabajan en paralelo, máquina de estados para los 6 pasos, evaluación por criterios, sonido con Web Audio y mandos de teclado y táctiles.

## Autor

Carlo Prado Ortiz · [Portafolio](https://zitroolrac.github.io/Portfolio/)
