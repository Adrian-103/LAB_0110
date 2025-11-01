# Práctica 1

## Introducción
Esta práctica tuvo como objetivo la intruducción a STM32. Se usó la placa de desarrollo **NUCLEO-H755ZI-Q**.

## ¿Qué deberías de ver?
Los LEDs de usuario en la placa se prenden con diferentes secuencias dependiendo de cuántas veces se presione el botón.
El número de secuencias es limitado y se repiten en el mismo orden después de que se llegó a la última.

## Observaciones:
- Los LEDs que se prendían en esta práctica estaban en la propia tarjeta de desarrollo.
- Para esta práctica se usaron delays, lo cual es una mala práctica en sistemas embebidos, dado que el procesador no hace nada en ese lapso de tiempo
- El botón no se lee por interrupción, lo cual puede generar ciertos errores en cuanto a la pulsación.
- Únicamente se utilizó el core Cortex-M7 del microcontrolador.
