# Práctica 2

## Introducción
Esta práctica tuvo como objetivo el uso de timers, interrupciones y ADC básico. Se usó la placa de desarrollo **NUCLEO-H755ZI-Q**.

## ¿Qué deberías de ver?
Diferentes estados que tienen diferentes funciones (Son ejemplos y no están en orden):
- Generar diferentes pulsos de PWM
- El uso del ADC para leer valores analógicos
- Uso de timers para prender y apagar LEDs en la placa
- Adaptar el ancho de un pulso PWM dependiendo del valor leído por el ADC

## Observaciones:
- Los LEDs que se prendían en esta práctica estaban en la propia tarjeta de desarrollo.
- Esta práctica implementa timers e interrupciones, haciéndola más eficiente y más agradable al usuario
- Para poder recrearlo, es necesario **leer la datasheet y el user manual del microcontrolador** ya que en caso de querer usar otros canales de ADC o timers, es necesario saber cuáles tienen conectores en la placa.
- Únicamente se utilizó el core Cortex-M7 del microcontrolador.
