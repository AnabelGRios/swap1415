Ejercicios Tema 2
=================

Ejercicio 1
-----------
Vamos a replicar dos veces cada componente (excepto el centro de datos).  
Replicamos el servidor web, que ten�a una disponibilidad del 85%:  
85% + (1-85%) * 85% = 97.75%  
97.75% + (1-97.75%) * 85% = 99.6625%  

Replicamos aplicaciones, que ten�an una disponibilidad del 90%:  
90% + (1-90%) * 90% = 99%  
99% + (1-99%) * 90% = 99.9%  

Replicamos la base de datos, que ten�a una disponibilidad del 99.9%:  
99.9% + (1-99.9%) * 99.9% = 99.9999%  
99.9999% + (1-99.9999%) * 99.9% = 99.9999999%

Replicamos DNS, que ten�a una disponibilidad del 98%:  
98% + (1-98%) * 98% = 99.96%  
99.96% + (1-99.96%) * 98% = 99.9992%

Replicamos el cortafuegos, que ten�a una disponibilidad del 85:  
85% + (1-85%) * 85% = 97.75%  
97.75% + (1-97.75%) * 85% = 99.6625%  

Replicamos el switch, que ten�a una disponibilidad del 99%:  
99% + (1-99%) * 99% = 99.99%  
99.99% + (1-99.99%) * 99% = 99.9999%

Replicamos el proveedor de Internet (ISP), que ten�a una disponibilidad del 95%:  
95% + (1-95%) * 95% = 99.75%  
99.75% + (1-99.75%) * 95% = 99.9875% 

Y calculamos la disponibilidad del sistema (a�adiendo la disponibilidad del centro de datos, que es del 99.99%):  
disponibilidad = 99.6625% * 99.9% * 99.9999999% * 99.9992% * 99.6625% * 99.9999% * 99.9875% * 99.99% = 99.16627%  



Ejercicio 2
-----------


Como ejemplos de frameworks y librer�as he encontrado los siguientes:  

* **JQuery**: biblioteca de JavaScript para ayudar en el manejo de documentos HTML, manejo de eventos, animaci�n e interacciones Ajax para el desarrollo web r�pido.  
* **MooTools**: framework de JavaScript compacto, orientado a objetos utilizados para el intermedio con JavaScript.  
* **Prototype**: framework de JavaScript para facilitar el desarrollo de aplicaciones web din�micas.  
* **gvNIX**: framekwork de c�digo abierto para el desarrollo r�pido de aplicaciones web con lenguaje Java.  
* **Apache Struts**: framework para aplicaciones web bajo la plataforma Java EE.  
* **Grails**: framework para aplicaciones web lbre desarrollado sobre el lenguaje de programaci�n Groovy, que a su vez se basa en Java Platform.  


Ejercicio 3
-----------

* **Top**: Sirve para conocer en tiempo real la actividad del procesador, as� como una lista con los procesos que hacen un mayor uso de la CPU.  
* **Gnome-System-Monitor**: es una aplicaci�n (no instalada previamente) que permite monitorizar tanto los procesos como los sistemas de memoria y red.  
* **Munin**: es un sistema de monitorizaci�n de c�digo libre, que permite monitorizar la infraestructura y la red, y avisa de cualquier cambio o problema. Presenta adem�s toda la informaci�n en gr�ficos a trav�s de una interfaz web.  
* **Nagios**: es un sistema de monitorizaci�n de c�digo libre, que permite monitorizar servicios de red y recursos de sistemas hardware.  
* **Ganglia**: permite monitorizar sistemas de c�mputo distribuidos y permite una gran escalabilidad.  
* **Zabbix**: es tambi�n de c�digo libre y permite monitorizar el sistema.  
* **Awstats**: es un monitor espec�fico de servidores web.  


Ejercicio 4
-----------

Entre los balanceadores de carga por software tenemos, como ya hemos visto, HaProxy, Nginx y Linux Virtual Servers, entre otros.  
En los balanceadores de carga por hardware destacan los fabricados por empresas como [KEMP](http://kemptechnologies.com/es/server-load-balancing-appliances/product-matrix.html), que tiene en este momento hasta balanceadores de carga con distintas especificaciones y precios, como podemos ver en su p�gina web, [Citrix](http://www.citrix.com/), [f5](https://f5.com/es/products/big-ip) y [Barracuda](https://www.barracuda.com/products/loadbalancer?&a=[google_emea_spain_spanish]app_delivery_search&grp=balance_de_carga&ad=58937633427&kw=%2Bbalanceador%20de%20%2Bcargas&L=ES&gclid=CIvg8sqQ1cQCFejJtAodSlMAGw). KEMP tiene, adem�s, balanceadores de carga virtual y ADC, como podemos ver [aqu�](http://kemptechnologies.com/es/loadmaster-family-virtual-server-load-balancers-application-delivery-controllers/)

