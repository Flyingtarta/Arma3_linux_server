# ARMA 3 - server montado en linux

La siguiente guia esta hecha con el fin de ayudar a la comunidad latina a montar servidores, y por medio de la cual voy a trasmitir lo que aprendi en el ultimo año de la utilizacion del mismo.

## **Elección de servidor:**

Arrancando desde lo mas basico, a la hora de querer montar un servidor es importante tener en claro cuales son los requisitos minimos para un servidor de arma 3.

Algo que es necesario entender es que los servidores montados en un vps o dedicados,si bien no tienen un tope de jugadores ( le podemos poner los slots que querramos) la limitacion viene por las especificaciones del mismo.

como requisitos basicos para que el servidor funcione correctamente, este debe tener: 

    -CPU con 2 cores de 2Ghz
    -3Gb de ram

si bien estos son requisitos minimos, no son recomendados, ya que a la hora de jugar con mods el servidor consumira mas recursos, principalmente **CPU**.

La ram no es importante en capacidad si solo se va a correr en linux, ya que en este sistema operativo, solo se dispone de 32bits, por lo que el consumo de ram se ve limitado a maximo 2gb ( aunque si sea importante la velocidad de la misma, donde yo pondria el minimo en ddr3 ) tener 8gb de ram, nos permite poder correr mas de una instancia de servidor a la vez (2 servidores dentro de 1).

Si bien se puede instalar un emulador de windows en linux para correr la version 64bits del servidor, es recomendable alquilar un **VPS** ( es basicamente una pc virtual dentro de un servidor mucho mas grande) por sobre un Dedicado ( un cpu y memorias ram dedicadas exclusivamente a uno)

**Orden de prioridad a la hora de elegir el vps:**
-Velocidad del cpu
-Cantidad de cores ( 2 = suficiente, 4= ideal , 8> overkill)
-Ram ( 3 = minimo , 8 = ideal , 8> permite tener mas de una instancia en el servidor)
-Disco ( espacio suficiente para servidor 9gb aprox y todos los mods que vayamos a usar, si es SSD mejor)

**Conclucion:** 
-Servidor dedicado no vale la pena si vamos a montarle linux, lo mejor es contratar un vps (mas barato y suficiente) 


 **- Ideal:**

> 	 4 cores de +3ghz 	 
> ram: 8gb	 
> hdd /ssd :100gb espacio

 **- Minimo:**

>2 cores  de +2ghz
>3gb de ram
>hhd de 10gb + 

