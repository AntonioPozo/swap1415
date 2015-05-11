#EJERCICIOS PROPUESTOS DEL TEMA 7



##Ejercicio T7.1:
¿Qué tamaño de unidad de unidad RAID se obtendrá al configurar un RAID 0 a partir de dos discos de 100 GB y 100 GB?
¿Qué tamaño de unidad de unidad RAID se obtendrá al configurar un RAID 0 a partir de tres discos de 200 GB cada uno?

1- 100 + 100
2- 200 + 200 + 200


##Ejercicio T7.2:
¿Qué tamaño de unidad de unidad RAID se obtendrá al configurar un RAID 1 a partir de dos discos de 100 GB y 100 GB?
¿Qué tamaño de unidad de unidad RAID se obtendrá al configurar un RAID 1 a partir de tres discos de 200 GB cada uno?
1- 100 + 100 + 100 + 100
2- 200 + 200 + 200 + 200 + 200 + 200


##Ejercicio T7.3:
¿Qué tamaño de unidad de unidad RAID se obtendrá al configurar un RAID 5 a partir de tres discos de 120 GB cada uno?
120 + 120 + 120

##Ejercicio T7.4:
Buscar información sobre los sistemas de ficheros en red más utilizados en la actualidad y comparar sus características. Hacer una lista de ventajas e inconvenientes de todos ellos, así como grandes sistemas en los que se utilicen.

-SSA: Es una forma simple de almacenamiento externo. Existen dispositivos específicos que incluyen varios disos en rack. Posee una interfaz para conectar los discos a las controladoras (normalmente SCSI). Número limitado de puertos para hacer la conexión entre servidores y almacenamiento. Se suele usar para disponer del almacenamiento necesario para archivos y BD en clusters. La posibilidad de manejo y la flexibilidad de un SSA es limitada. Aceptan cambios en caliente de discos y varias configuraciones RAID. Dispositivos desarrollados por una empresa con unas especificaciones y herramientas propietarias.

-SAN: Red de almacenamiento especializada que conecta dispositivos de almacenamiento a los servidores. Conjunto de dispositivos interconectados (discos, cintas, etc.) y servidores conectados a un canal de comunicación e intercambio de datos común (concentrador de alta velocidad). Este tipo de almacenamiento en red tiene una gran flexibilidad y facilidad de manejo del almacenamiento. Se puede actualizar cualquier componente. Red de alta velocidad (mínimo de 1Gbps). Es como un bus de un ordenador, pero compartido entre varias máquinas. A continuación se exponen algunas características:
Utiliza hardware de red muy especializado. Una SAN ofrece una capa de abstracción entre los dispositivos de almacenamiento y los servidores, y permite que el espacio físico de almacenamiento crezca. Se puede usar para almacenar archivos, compartir datos entre los servidores, mirroring de discos y backups. Puede operar con SSA y NAS. Permite que se añadan nuevos dispositivos al sistema (servidores o almacenamiento).

-NAS: Dispositivo que actúa como un servidor de ficheros, pero ahorrando los recursos de tener una máquina más. Se suele usar para almacenar copias de seguridad, y para ofrecer espacio de almacenamiento compartido entre servidores o aplicaciones. Conjunto de discos organizados en un dispositivo de red con IP y que puede conectarse a una red Ethernet. Utilizando algún protocolo, como Internetwork Packet Exchange (de Microsoft), NetBEUI (de Microsoft), Network File System (NFS, de Sun) o IPE (de Novell). Aparece como otro servidor más en la red. Usan software específico para configurarlos y manejarlos (creación de unidades, gestión de permisos, etc). Utilizan configuraciones RAID.

FUENTE: diapositivas de clase: Tema 7 Almacenamiento de datos Pedro A. Castillo Valdivieso. Depto Arquitectura y Tecnología de Computadores. Universidad de Granada. pacv@ugr.es



