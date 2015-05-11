#EJERCICIOS PROPUESTOS DEL TEMA 5



##Ejercicio T5.1:
Buscar información sobre cómo calcular el número de conexiones por segundo

Para la práctica 4 de la asignatura se instalaron diferentes herramientas para medir el rendimiento de nuestro sistema. Apache Benchmark, httperf, siege son algunas de ellas y todas nos aportan medidas de peticiones por segundo. En la siguiente figura se muestran los resultados medidos con el software jMeter:
![imagen valorespordefecto](https://github.com/AntonioPozo/swap1415/blob/master/P4/jmeter/graficoderesultados.png)


##Ejercicio T5.2:
Instalar wireshark y observar cómo fluye el tráfico de red en uno de los servidores web mientras se le hacen peticiones HTTP.

He optado por instalar el software requerido en el servidor 1 para la asignatura. Para instalar Wireshark tecleamos sudo apt-get install wireshark.
En la siguiente imagen observarmos la captura de paquetes. Desde la máquina anfitriona se ha hecho una petición al servidor de la página index.html. Resaltado en rojo todo el proceso de petición y respuesta.
![imagen valorespordefecto](https://github.com/AntonioPozo/swap1415/blob/master/Ejercicios_de_clase/cap_wireshark_T5-ej5point2.png)


##Ejercicio T5.3:
Buscar información sobre características, disponibilidad para diversos SO, etc de herramientas para monitorizar las prestaciones de un servidor.

jMeter, utilizada en la práctica 4 de la asignatura (como ya se ha comentado anteriormente) es una aplicación java, la cual podemos instalar en cualquier sistema operativo si se dispone de la herramienta Java instalada en el sistema. 
Para comprobar el rendimiento de un servidor web Apache existe la herramienta ab (Apache Benchmark) que también se ha utilizado en la práctica 4. Para comprobar el rendimiento de un servidor web ISS (Windows), existe la herramienta propia de Microsoft CIS Benchmark
