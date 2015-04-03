Ejercicios tema 3
=================

Ejercicio 1
------------

Para configurar el enrutamiento en Linux podemos utilizar el comando `iptables`, que permite, entre otras cosas, filtrar paquetes. Esta herramienta est� construida sobre Netfilter, un framework disponible en el n�cleo de Linux que permite interceptar y manipular paquetes de red.  
Para manipular las tablas de enrutamiento se puede utilizar tambi�n el comando `route`. Adem�s, para que el ordenador funcione como un router y permita realizar el reenv�o de paquetes es necesario modificar la variable `ip_forward` del sistema y ponerla a 1.  

Para configurar el enrutamiento en Windows se puede utilizar tambi�n el comando `route`. Sin embargo, tambi�n podemos utilizar herramientas gr�ficas como el servicio de enrutamiento y acceso remoto. Existe una tercera opci�n, que es el contexto IP de enrutamiento Netsh, que incluye 
varios comandos para mostrar y administrar la tabla de enrutamiento IP.  


Ejercicio 2
------------

En Linux podemos utilizar el comando `iptables`, que permite filtrar y bloquear paquetes tanto por direcci�n IP como por n�mero de puerto o incluso por direcci�n MAC.  
En Windows tenemos la herramienta IPsec, que permite filtar por IP y por n�mero de puerto.