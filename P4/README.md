# Practica 4

## Introducción
Esta práctica tuvo como objetivo el uso de la FPU del microcontrolador para hacer un procesamiento de una señal analógica medida por el ADC. El ADC por su parte, funcionaba en modo scan, es decir podía medir dos canales uno después del otro. Los datos ya procesados eran enviados por UART a la computadora.
La práctica fue desarrollada en la **NUCLEO-H755ZI-Q**.

## ¿Qué deberías de ver?
El botón de la tarjeta de desarrollo marcaba las etapas del código, o los estados. Se medía, se preocesaba y se enviaba. El resultado final debía de ser observar en la terminal de STM32CubeIDE previamente configurada los resultados de diferentes operaciones a la señal obtenida.

## Observaciones:
- Los LEDs que se prendían en esta práctica estaban en la propia tarjeta de desarrollo.
- Se usaron dos LDR, conectadas a dos canales consecutivos del ADC.
- La terminal se configura desde antes en STM32CubeIDE, de otra forma no se podrán ver los datos sin un programa externo.
- Hay que incluir las librerías de la FPU y de ARM Math para que funcione el proyecto.
- Únicamente se utilizó el core Cortex-M7 del microcontrolador.
