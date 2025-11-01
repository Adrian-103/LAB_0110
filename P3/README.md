# Practica 3

## Introducción
Esta práctica tuvo como objetivo el uso de la interfaz de I2C y DMA. Se usó la placa de desarrollo **NUCLEO-H755ZI-Q**.

Es importante mencionar que esta práctica y este código funciona únicamente para el sensor BME280.

## ¿Qué deberías de ver?
Si bien el código tiene diferentes estados y funciones, en general se debería de observar cómo cambian los LEDs dependiendo del estado de ciertas variables ambientales que mide el BME280. El botón determina qué variable es la que está midiendo en ese momento.

Otra forma de revisar que el código funciona correctamente es mediante el uso de la herramienta de **STM32CubeIDE**  *"instancias"*, dodne podemos ver el valor de cada variable.

## Observaciones:
- Los LEDs que se prendían en esta práctica estaban en la propia tarjeta de desarrollo.
- El sensor tiene que ser específicamente el BME280, ya que se trabaja directamente con el ID del sensor 
- Se recomienda mucho **leer la datasheet y el user manual del microcontrolador y del sensor** ya que es necesario para poder encontrar los registros necesarios y el canal de I2C correspondiente que se está usando. 
- Únicamente se utilizó el core Cortex-M7 del microcontrolador.
