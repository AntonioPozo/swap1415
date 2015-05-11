#EJERCICIOS PROPUESTOS DEL TEMA 4



##Ejercicio T4.1:
Buscar información sobre cuánto costaría en la actualidad un mainframe. Comparar precio y potencia entre esa máquina y una granja web de unas prestaciones similares.

Indagando por Internet, encuentro dificultades para encontrar páginas recientes que solucionen mi consulta. Eso habla un poco de la "utilización de los mainframes en la actualidad". Una entrada del año 2011 anuncia que cuesta 75000$, con 232 servidores

##Ejercicio T4.2:
Buscar información sobre precio y características de balanceadores hardware específicos. Compara las prestaciones que ofrecen unos y otros.

| marca                          | KEMP     | KEMP     | F5 Networks | F5 Networks | Citrix      | Citrix      |
|--------------------------------|----------|----------|-------------|-------------|-------------|-------------|
| modelo                         | lm 3600  | lm 5400  | ltm4000s    | ltm4200v    | mpx 8015    | mpx 8005    |
| fuente alimentación redundante | no       | sdfsi    | opcional    | opcional    | opcional    | opcional    |
| consumo electrico              | 198.8W   | 184.5W   | 95W         | 95W         | 185W        | 185W        |
| almacenamiento                 | SSD      | SSD      | Hard Disk   | Hard Disk   | N/A         | N/A         |
| memoria                        | 4GB      | 8GB      | 16GB        | 16GB        | 32GB        | 32GB        |
| Garantía del hardware          | 1 año    | 1 año    | 1 año       | 1 año       | 1 año       | 1 año       |
| Garantía del software          | 1 año    | 1 año    | 90 días     | 90 días     | 1 año       | 1 año       |
| Soporte                        | incluido | incluido | incluido    | no incluido | no incluido | no incluido |
| Precio                         | 9800$    | 17990$   | 29995$      | 41995$      | 48000$      | 25000$      |


![imagen](https://github.com/AntonioPozo/swap1415/blob/master/Ejercicios/LB-comparison.jpg)


[1, http://kemptechnologies.com/es/compare-kemp-f5-big-ip-citrix-netscaler-hardware-load-balancers/?gclid=CjwKEAjw6Z2pBRCmvaXq6d7FjUoSJAAc5Lri24lt2h3uH1gWCKwpSLckSpYMmZAI8o4iC0HAyaKAIhoCs3Hw_wcB]


##Ejercicio T4.3:
Buscar información sobre los métodos de balanceo que implementan los dispositivos recogidos en el ejercicio 4.2
- KEMP lm 3600:Round robin, Weighted Round Robin, Last Connection, Weighted Last Connection
- KEMP lm 5400:Round robin, Weighted Round Robin, Last Connection, Weighted Last Connection, Agent-based Adaptive, Chained Failover, Source-IP Hash 
- F5 Networks ltm4000s: Round robin, Weighted Round Robin, Last Connection, Least response time
- F5 Networks ltm4200v: Round robin, Weighted Round Robin, Last Connection, Least response time
- Citrix mpx 8015:    Round Robin, Least Packets, Least Bandwidth, Least Connections, Response Time, Hashing (URL, Domain, Source IP, Destination IP, and CustomID), SNMP-provided metric, Server Application State Protocol (SASP)
- Citrix mpx 8005: Round Robin, Least Packets, Least Bandwidth, Least Connections, Response Time, Hashing (URL, Domain, Source IP, Destination IP, and CustomID), SNMP-provided metric, Server Application State Protocol (SASP)


##Ejercicio T4.4:
Instala y configura en una máquina virtual el balanceador ZenLoadBalancer. Compara con la dificultad de la instalación y configuración usando nginx o haproxy (práctica 3).

##Ejercicio T4.5:
Probar las diferentes maneras de redirección HTTP. ¿Cuál es adecuada y cuál no lo es para hacer balanceo de carga global? ¿Por qué?

##Ejercicio T4.6:
 Buscar información sobre los bloques de IP para los distintos países o continentes. Implementar en JavaScript o PHP la detección de la zona desde donde se conecta un usuario.

##Ejercicio T4.7:
Buscar información sobre métodos y herramientas para implementar GSLB.