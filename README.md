# PING PHP

## DATAGRAMA ICMP(8)
![datagramaICMP](img/datagrama1.PNG)

Tipo - Tipo de ICMP como se especifica a continuación.<br>
Código - Subtipo al tipo dado.<br>
Checksum - Datos comprobación de errores. Calculado a partir de la cabecera ICMP + datos, con un valor de 0 para este campo. El algoritmo de suma de comprobación se especifica en RFC 1071.<br>
Resto del Header - Cuatro campo byte. Puede variar en función del tipo y código ICMP.<br>


Código Valor <br>
0 Net unreachable<br>
1 Host unreachable<br>
2 Protocol unreachable<br>
3 Port unreachable<br>
4 Fragmentation needed and don’t fragment bit was set<br>
5 Source route failed<br>
6 Destination network unknown<br>
7 Destination host unknown<br>
8 Source host isolated<br>
9 Destination network is administratively prohibited<br>
10 Destination host is administratively prohibited<br>
11 Destination network unreacheable for type of service<br>
12 Destination host unreacheable for type of service<br>
13 Communication Administratively prohibited<br>
14 Host precedence violation<br>
15 Precedence cutoff in effect<br>




### Mas informacion sobre paquete icmp
(1) http://apuntesdenetworking.blogspot.com/2011/10/tipos-de-mensaje-icmp-internet-control.html <br>
(2) https://es.wikipedia.org/wiki/Protocolo_de_control_de_mensajes_de_Internet
