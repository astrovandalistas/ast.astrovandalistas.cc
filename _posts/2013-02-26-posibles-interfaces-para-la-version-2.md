---
title: Posibles interfaces para la versión 2
cover: /assets/posts/bangMTY_map.jpg
---
![](/assets/posts/bangMTY_map.jpg)

Estas son algunas de las opciones para el hardware que controlara la segunda versión del arma sonora.

**Interface:**
  
 **1 Raspberry pi + twitter + proyector mini (conectividad con wifi y android como router)**

  * Generar un interface gráfica con phyton para proyectar como tipografías

  1. <http://stackoverflow.com/questions/5414639/python-imaging-library-text-rendering>

  * Controlar los pins gpio con la librería de twitter para phyton

  1. <https://github.com/ryanmcgrath/twython>
  2. <https://github.com/tweepy/tweepy>
  3. <http://learn.adafruit.com/raspberry-pi-e-mail-notifier-using-leds>

**2 Arduino ethernet (o wifi) + twitter + pantalla de leds**

  1. <http://www.sundh.com/blog/2012/04/arduino-library-for-led-message-display/>
  2. <http://www.amplus.com.hk/LED_%20AM03127-H13.htm>

  * Adaptar el código de la librería para que también reciba las ordenes de on/off para los pin digitales que activan el motor

  * Revisar como se comporta los pins tx rx si estan conectados al wifi shield o al ethernet shied.

  * En caso de que el wifi shield genere un problema para la conectividad el arduino ethernet, se podría utilizar una red compartida desde el raspberry pi. http://www.raspberrypi.org/phpBB3/viewtopic.php?f=36&t=25268 ( compartir el wifi del pi )

**3 Raspberry pi + twitter + pantalla de leds (conectividad con wifi y android como router)**

  * Controlar la pantalla de leds con los pins gpio

  1. <http://luisgg79.blogspot.ca/>

  * Controlar los pins gpio con la librería de twitter para phyton

  1. <https://github.com/ryanmcgrath/twython>
  2. <https://github.com/tweepy/tweepy>
  3. <http://learn.adafruit.com/raspberry-pi-e-mail-notifier-using-leds>
  