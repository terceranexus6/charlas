<!-- $theme: default -->
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=1)

Rubber Ducky
===
![](https://images.duckduckgo.com/iu/?u=https%3A%2F%2Fwww.pentestingshop.com%2Fwp-content%2Fuploads%2F2015%2F02%2Fduckme-600x450.jpg&f=1)
Paula de la Hoz
[@Terceranexus6](www.twitter.com/terceranexus6)

---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# ¿Quién soy?  :alien:

- Estudiante de ingeniería informática
- Programadora Junior 
- Activista por los derechos digitales
 ![](https://pbs.twimg.com/profile_images/812738313413160960/1lojLr9O.jpg)
 
 ---
 ![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
 # Índice
 
 - **¿Qué es Rubber Ducky?**
 - **¿Cómo funciona?**
 	- Procedimiento
 	- Ejemplo de programación
 - **Pentesting**
 	- Concepto
 	- Ingeniería social
 	- Ética
 - **Pros y Contras**
 - **Demostración**

---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)

# ¿Qué es Rubber Ducky?  :hatched_chick:
![](https://cdn-images-1.medium.com/max/1200/1*LxlmHycPbysH9w3ezFnEzw.jpeg)

---
# ¿Qué es Rubber Ducky?
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
Rubber Ducky es un pen drive que imita la entrada de un humano por teclado para inyectar comandos en ordenadores, móviles y otros sistemas. 


---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)

# ¿Cómo funciona?

![](https://cdn-images-1.medium.com/max/800/1*0dFQs9g3YLSiy64yxBN_4Q.jpeg)

---
# ¿Cómo funciona?
## Procedimiento
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)

1- Creamos un **programa** con el lenguaje de programación diseñado para el pen. 
2- **Compilamos** el programa con el compilador online del dispositivo.
3- Guardamos el _.bin_ en la **micro SD** del pen-drive.
4- Metemos la micro SD en el pen-drive, y lo conectamos por **USB** al dispositivo objetivo. 
5- El pen-drive ejecutará los **comandos** que le hayamos programado imitando entrada por teclado de un humano.

---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# ¿Cómo funciona?
## Comandos

    DELAY x — Retraso en milisegundos
    STRING xyz — escribir
    GUI — system
    GUI r — Windows cmd
    UP | UPARROW — tecla arriba
    DOWN | DOWNARROW — tecla abajo
    LEFT | LEFTARROW — tecla izda
    RIGHT | RIGHTARROW — tecla derecha
    CAPS |CAPSLOCK — Bloquear mayusc
    ENTER — Enter
    SPACE — Espacio
    REPEAT x — repetir comandos anteriores X veces.

---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# ¿Cómo funciona?  :floppy_disk:
## Ejemplo de programación (linux)

	DELAY 300 //espera 300 ms
    GUI t	  //abre terminal [S]+t
    DELAY 750 //espera 750 ms
    STRING cd //escribe cd en la terminal
    DELAY 200
    ENTER     //ejecuta Enter
    DELAY 200
    STRING loquesea...   
    // y así ejecutamos los comandos que queremos
    
---
# Pentesting

![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)  

![](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fcdn.geekwire.com%2Fwp-content%2Fuploads%2F2016%2F08%2FRubber-Ducky.png&f=1)


---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# Pentesting  :lock:  :unlock:
## Concepto 

Del inglés "_penetration test_", consiste en una prueba controlada para **testear la seguridad** de un sistema. Hay muchas técnicas de pentesting, dependiendo del objetivo. 

En nuestro caso se requiere una mezcla de **habilidad técnica**, para programar el ataque, e **_ingeniería social_**.

---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# Pentesting
## Ingeniería social  :speech_balloon:

La capacidad de usar **habilidades no técnicas**, si no sociales (forma de **hablar**, de vestir, psicología, contexto, etc) para alcanzar un objetivo, en nuestro caso de testeo de **seguridad** informática.

# :person_with_blond_hair::speech_balloon::girl::woman::man::older_man::speech_balloon::boy::man_with_gua_pi_mao::speech_balloon:



---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# Pentesting
## Ética  :smiling_imp:

En informática, aún siendo una especialidad técnica, está tan presente en nuestras vidas, que requiere un control moral y ético en muchos aspectos.

**La seguridad**, concretamente, necesita un control ético especialmente alto.

---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# Pros y Contras de Rubber Ducky  :performing_arts:
## PROS  :+1:
- Es una herramienta fácil de transportar y pasa **desapercibida**.
- Muy **flexible** a la hora de ser programada.
- **Documentación** completa y colaborativa en [GITHUB](https://github.com/hak5darren/USB-Rubber-Ducky/wiki). 
## CONTRAS  :-1:
- Requiere **acceso físico** al sistema.
- Está limitado a acciones por comando sin una **interacción** directa del programador.
- Se debe conocer bien el sistema a testear (poca portabilidad)
---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# Demostración  :warning:


---
![bg](https://images.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.fg-a.com%2Fwallpapers%2Fgeo-shapes-black-1280b.jpg&f=11)
# ¿Preguntas?  :point_up:
