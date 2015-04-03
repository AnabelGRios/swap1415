Ejercicios tema 3
=================

Ejercicio 1
------------

Para configurar el enrutamiento en Linux podemos utilizar el comando `iptables`, que permite, entre otras cosas, filtrar paquetes. Esta herramienta está construida sobre Netfilter, un framework disponible en el núcleo de Linux que permite interceptar y manipular paquetes de red.  
Para manipular las tablas de enrutamiento se puede utilizar también el comando `route`. Además, para que el ordenador funcione como un router y permita realizar el reenvío de paquetes es necesario modificar la variable `ip_forward` del sistema y ponerla a 1.  

Para configurar el enrutamiento en Windows se puede utilizar también el comando `route`. Sin embargo, también podemos utilizar herramientas gráficas como el servicio de enrutamiento y acceso remoto. Existe una tercera opción, que es el contexto IP de enrutamiento Netsh, que incluye 
varios comandos para mostrar y administrar la tabla de enrutamiento IP.  


Ejercicio 2
------------

En Linux podemos utilizar el comando `iptables`, que permite filtrar y bloquear paquetes tanto por dirección IP como por número de puerto o incluso por dirección MAC.  
En Windows tenemos la herramienta IPsec, que permite filtar por IP y por número de puerto.