---
title: V.2 casi lista
cover: /assets/posts/bangMTY_hardware.jpg
---
![](/assets/posts/bangMTY_hardware.jpg)

En esta ocasión estamos trabajando con Raspberry Pi para controlar los relays que manda la señal de giro al motor. Raspberry cuenta con pins Gpio los cuales envían una señal de 3.v, esta señal resulta insuficiente para un relay que se activa con 5.v. Para resolver esto utilizamos un arreglo con un transistor darlington bc337.

![](/assets/posts/bangMTY_schematics.jpg)

El arma está programado en Phyton y se corre directamente en el Raspberry Pi.

[El código está en Github](https://github.com/astrovandalistas/bangMTYRpiPy){:target="_blank"}
