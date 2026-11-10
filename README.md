# Taller Twin

Simulador de diagnóstico de averías. Una jornada de 8 coches: el cliente solo cuenta lo que nota («hace un ruido raro», «le cuesta arrancar», «echa humo») y tú tienes que descubrir **todo** lo que tiene el coche, como en un taller de verdad.

**Jugar:** https://zitroolrac.github.io/taller-twin/

![Cuadro de instrumentos con el testigo de temperatura encendido](preview.webp)

## Las pruebas

- **En el suelo:** arrancar con la llave (arranque lento, solo «clic», ralentí que tiembla), acelerar (chillido de correa, escape como un tractor, tirones), frenar (chirrido, vibración, pedal esponjoso), girar el volante («clonc», «clac-clac», gemido de la dirección), cuadro de instrumentos con testigos, humo del escape (azul, blanco o negro), empujar la carrocería, presión y desgaste del neumático, faros prueba de luces (cruce, freno, intermitentes, marcha atrás, limpiaparabrisas) y escáner OBD con escaneo de todos los sistemas (motor, cambio, ABS, airbag, carrocería, climatización), códigos y datos en vivo.
- **Bajo el capó:** batería con multímetro (parado y en marcha), varilla del aceite (nivel y color), depósitos de refrigerante, líquido de frenos y de dirección, correa, filtro de aire, bujía, manguitos, caja de fusibles (filamento de cada fusible) y olor.
- **Por debajo:** pastillas y discos, amortiguador, escape, rótulas, fuelles de la transmisión y gotas en el suelo según su color.

## 27 averías

Frenos (pastillas, discos alabeados, falta de líquido), motor (bujía o bobina, filtro de aire, junta de culata, segmentos, fuga de aceite, correa), electricidad (batería, alternador, motor de arranque, sonda lambda), refrigeración (manguito con fuga), suspensión y dirección (amortiguador, rótula, homocinética, bomba de dirección), escape roto y ruedas y luces (pinchazo, alineación), ABS y airbag (sensor de rueda, conector del airbag) y luces y fusibles (bombillas de cruce, intermitente y freno, fusible fundido).

Desde el tercer coche puede haber dos averías a la vez, y hay falsas alarmas: las gotas transparentes sin olor son agua del aire acondicionado y no son avería. Al firmar el informe, el juego te explica qué pistas delataban cada avería.

## Cómo está hecho

JavaScript puro y Canvas 2D, sin dependencias, en un único `index.html`: modelo de averías con un resultado normal para cada prueba y modificadores por avería, combinación de varias averías, partículas (humo, vapor, gotas), sonido sintetizado con Web Audio (motor, arranque, correa, frenos, dirección, escape) y mandos táctiles de pulsación sostenida.

## Autor

Carlo Prado Ortiz · [Portafolio](https://zitroolrac.github.io/Portfolio/)
