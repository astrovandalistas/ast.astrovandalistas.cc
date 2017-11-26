---
title: Posibles interfaces para la versión 2
cover: /assets/posts/bangMTY_map.jpg
---
![](/assets/posts/bangMTY_map.jpg)

Estas son algunas de las opciones para el hardware que controlara la segunda versión del arma sonora:
  
**1 Raspberry pi + twitter + proyector mini (conectividad con wifi y android como router)**

  * Generar un [interface gráfica con phyton](https://www.pygame.org/docs/){:target="_blank"} para proyectar como tipografías

  * Controlar los pins gpio con una [librería de twitter para phyton](https://github.com/ryanmcgrath/twython){:target="_blank"}

**2 Arduino ethernet (o wifi) + twitter + [pantalla de leds](http://www.amplus.com.hk/LED_%20AM03127-H13.htm){:target="_blank"}**

  * Adaptar el código de la librería para que también reciba las ordenes de on/off para los pin digitales que activan el motor.

  * Revisar como se comporta los pins tx/rx si estan conectados al wifi shield o al ethernet shied.

  * En caso de que el wifi shield genere un problema para la conectividad del arduino, se podría utilizar una [red compartida desde el raspberry pi](http://www.raspberrypi.org/phpBB3/viewtopic.php?f=36&t=25268){:target="_blank"}.

**3 Raspberry pi + twitter + pantalla de leds (conectividad con wifi y android como router)**

  * [Controlar la pantalla de leds con los pins gpio](http://luisgg79.blogspot.com.uy/2014/03/ola-raspberry-pi-led-ws2810-artnet.html){:target="_blank"}

  * Controlar los pins gpio con una [librería de twitter para phyton](https://github.com/ryanmcgrath/twython){:target="_blank"}
