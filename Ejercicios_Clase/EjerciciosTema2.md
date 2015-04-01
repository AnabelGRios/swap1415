Ejercicios Tema 2
=================

Ejercicio 1
-----------
Vamos a replicar dos veces cada componente (excepto el centro de datos).  
Replicamos el servidor web, que tenía una disponibilidad del 85%:  
85% + (1-85%) * 85% = 97.75%  
97.75% + (1-97.75%) * 85% = 99.6625%  

Replicamos aplicaciones, que tenían una disponibilidad del 90%:  
90% + (1-90%) * 90% = 99%  
99% + (1-99%) * 90% = 99.9%  

Replicamos la base de datos, que tenía una disponibilidad del 99.9%:  
99.9% + (1-99.9%) * 99.9% = 99.9999%  
99.9999% + (1-99.9999%) * 99.9% = 99.9999999%

Replicamos DNS, que tenía una disponibilidad del 98%:  
98% + (1-98%) * 98% = 99.96%  
99.96% + (1-99.96%) * 98% = 99.9992%

Replicamos el cortafuegos, que tenía una disponibilidad del 85:  
85% + (1-85%) * 85% = 97.75%  
97.75% + (1-97.75%) * 85% = 99.6625%  

Replicamos el switch, que tenía una disponibilidad del 99%:  
99% + (1-99%) * 99% = 99.99%  
99.99% + (1-99.99%) * 99% = 99.9999%

Replicamos el proveedor de Internet (ISP), que tenía una disponibilidad del 95%:  
95% + (1-95%) * 95% = 99.75%  
99.75% + (1-99.75%) * 95% = 99.9875% 

Y calculamos la disponibilidad del sistema (añadiendo la disponibilidad del centro de datos, que es del 99.99%):  
disponibilidad = 99.6625% * 99.9% * 99.9999999% * 99.9992% * 99.6625% * 99.9999% * 99.9875% * 99.99% = 99.16627%  



Ejercicio 2
-----------


Como ejemplos de frameworks y librerías he encontrado los siguientes:  

* **JQuery**: biblioteca de JavaScript para ayudar en el manejo de documentos HTML, manejo de eventos, animación e interacciones Ajax para el desarrollo web rápido.  
* **MooTools**: framework de JavaScript compacto, orientado a objetos utilizados para el intermedio con JavaScript.  
* **Prototype**: framework de JavaScript para facilitar el desarrollo de aplicaciones web dinámicas.  
* **gvNIX**: framekwork de código abierto para el desarrollo rápido de aplicaciones web con lenguaje Java.  
* **Apache Struts**: framework para aplicaciones web bajo la plataforma Java EE.  
* **Grails**: framework para aplicaciones web lbre desarrollado sobre el lenguaje de programación Groovy, que a su vez se basa en Java Platform.  


Ejercicio 3
-----------

* **Top**: Sirve para conocer en tiempo real la actividad del procesador, así como una lista con los procesos que hacen un mayor uso de la CPU.  
* **Gnome-System-Monitor**: es una aplicación (no instalada previamente) que permite monitorizar tanto los procesos como los sistemas de memoria y red.  
* **Munin**: es un sistema de monitorización de código libre, que permite monitorizar la infraestructura y la red, y avisa de cualquier cambio o problema. Presenta además toda la información en gráficos a través de una interfaz web.  
* **Nagios**: es un sistema de monitorización de código libre, que permite monitorizar servicios de red y recursos de sistemas hardware.  
* **Ganglia**: permite monitorizar sistemas de cómputo distribuidos y permite una gran escalabilidad.  
* **Zabbix**: es también de código libre y permite monitorizar el sistema.  
* **Awstats**: es un monitor específico de servidores web.  


Ejercicio 4
-----------

Entre los balanceadores de carga por software tenemos, como ya hemos visto, HaProxy, Nginx y Linux Virtual Servers, entre otros.  
En los balanceadores de carga por hardware destacan los fabricados por empresas como [KEMP](http://kemptechnologies.com/es/server-load-balancing-appliances/product-matrix.html), que tiene en este momento hasta balanceadores de carga con distintas especificaciones y precios, como podemos ver en su página web, [Citrix](http://www.citrix.com/), [f5](https://f5.com/es/products/big-ip) y [Barracuda](https://www.barracuda.com/products/loadbalancer?&a=[google_emea_spain_spanish]app_delivery_search&grp=balance_de_carga&ad=58937633427&kw=%2Bbalanceador%20de%20%2Bcargas&L=ES&gclid=CIvg8sqQ1cQCFejJtAodSlMAGw). KEMP tiene, además, balanceadores de carga virtual y ADC, como podemos ver [aquí](http://kemptechnologies.com/es/loadmaster-family-virtual-server-load-balancers-application-delivery-controllers/)

