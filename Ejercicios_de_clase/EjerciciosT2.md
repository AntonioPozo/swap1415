#EJERCICIOS PROPUESTOS DEL TEMA 2


##Ejercicio T2.1: 
Calcular la disponibilidad del sistema descrito en edgeblog.net si tenemos dos réplicas de cada elemento salvo para el centro de datos (en total 3 elementos en cada subsistema).

Para calcular la disponibilidad cualquier sistema se multiplica la disponibilidad de cada uno de sus componentes.

NOTA: no encuentro los datos necesarios para el problema en la referencia.


##Ejercicio T2.2: 
Buscar frameworks y librerías para diferentes lenguajes que permitan hacer aplicaciones altamente disponibles con relativa facilidad. Como ejemplo, examina PM2: https://github.com/Unitech/pm2 que sirve para administrar clústeres de NodeJS.

- HADOOP [http://hadoop.apache.org]
- Gearman [http://gearman.org]


##Ejercicio T2.3: 
¿Cómo analizar el nivel de carga de cada uno de los subsistemas en el servidor? Buscar herramientas y aprender a usarlas.

Hay muchas herramientas para dicho propósito. Para windows encontramos el Server Manager por ejemplo. Para distribuciones libres encontramos Munin, Nagios, Zabbix.
Estos software se probaron en la asignatura Ingeniería de Servidores (primer cuatrimestre del tercer curso del grado en Ingeniería Informática).

Si bien la instalación de Server Manager en windows es fácil y rápida, la de los software mencionados es una tarea muy tediosa.

[https://technet.microsoft.com/en-us/library/cc732455.aspx]
[munin-monitoring.org/]
[www.nagios.org/]
[www.zabbix.com/]


##Ejercicio T2.4: 
En este ejercicio debemos buscar diferentes tipos de productos: (1) Buscar ejemplos de balanceadores software y hardware (productos comerciales). (2) Buscar productos comerciales para servidores de aplicaciones. (3) Buscar productos comerciales para servidores de almacenamiento.

(1)
	- Software: 
		Zen Load Balancer 	[http://www.zenloadbalancer.com]
		HAProxy 		[http://www.haproxy.org]
		BalanceNG		[http://www.inlab.de/balanceng/]
	- Hardware:
		LoadMaster LM-5400
		Big IP LTM-4000sBIG
		IP LTM-4200V
		NETSCALER MPX-11520
		NETSCALER MPX 8015
(2)
	WebSphere Application Server de IBM
	JBoss
	Oracle Internet Application Server
	
(3)
	Red Hat Storage Server
	FalconStor
	TeraStation
		







