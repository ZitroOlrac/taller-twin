# Taller Twin

Gemelo digital jugable de un taller mecánico. Eres el jefe de taller durante una semana y el objetivo es claro: que el sábado solo haya entregas con cita y a la una, a casa.

**Jugar:** https://zitroolrac.github.io/taller-twin/

![Vista de la nave con la campa y los tres elevadores](preview.webp)

## Qué simula

- **Pizarra de 8 estados**: recibido, diagnóstico, pendiente de presupuesto, esperando aprobación, esperando recambio, en reparación, terminado y entregado. Un coche que pasa más de 2 días en la misma columna se marca en rojo.
- **Tres elevadores y tres mecánicos** con distinto rendimiento.
- **Presupuestos**: si salen antes de las 13:00 el cliente contesta ese día; si no, al día siguiente. Algunos clientes no contestan hasta que les llamas.
- **Dos proveedores**: Reynasa (más barato, 1–2 días) y Repuestos Miguel (llega en el día, un 15 % más caro).
- **Urgencias** que piden un hueco. La regla es una al día como máximo.
- **Corte del jueves**: a las 16:00 decides qué se termina esta semana y a qué clientes avisas para el lunes.
- **Llamadas del viernes** para dar franjas de recogida el sábado.
- **Evaluación final** con criterios críticos, facturación, puntualidad, ocupación, horas extra y satisfacción.

## Cómo está hecho

Simulación por eventos discretos en JavaScript puro, sin dependencias: un reloj de jornada laboral, una cola de eventos (llegadas, respuestas de clientes, recambios, recogidas) y un motor de reglas que evalúa la semana. La nave se dibuja en Canvas 2D y la pizarra se genera a partir del mismo estado. Las reglas salen de un plan real de organización de un taller.

Todo está en un único `index.html`.

## Autor

Carlo Prado Ortiz · [Portafolio](https://zitroolrac.github.io/Portfolio/)
