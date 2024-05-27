# Traballo_Redes

● Actividad 6.1 - Creación de una red LAN utilizando máquinas virtuales: 

Configurar VirtualBox para establecer una red de área local (LAN) en la que se conecten dos máquinas virtuales: 




Investiga sobre los siguientes tipos de red que permite establecer VirtualBox:


 ● NAT: 
 

Network Address Translation (NAT):Proceso que traduce las direcciones IP y puerto cuando el paquete se dirige a través del router o firewall.


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/beef8f77-e12c-4a16-ad63-42d145922418)




● Adaptador puente. 

Adaptador Puente: El que hace que la máquina virtual sea conectada a la misma red que el anfitrión,entonces la MV se comportará como si fuera un PC más conectado a la red real. Este nos permite conectar entre MV, desde el anfitrión y a Internet bidireccionalmente.


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/9cde1bc9-aeaf-44bb-86bb-2585d0827810)



● Red interna.

Red Interna: Forma de conectar varias MV entre ellas mismas, creando una red privada y de esta forma las máquinas virtuales no podrán comunicarse con el anfitrión ni viceversa.


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/9d0b5173-0557-47a4-ac1f-8761a7c7cf87)


● Red NAT.

Red NAT: Red que creará VirtualBox donde permite compartir esta red con varias MV de este mismo anfitrión. Asimismo, VB en este tipo de red proporciona una puerta de enlace con salida a internet en la dirección de host número 1 de la red.


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/06ce15b8-6c71-46bb-9f20-a5a461c78889)




 Para cada uno de ellos, explícalo brevemente y aporta un esquema que ejemplifica su funcionamiento. Selecciona y configura el tipo de red que te permite conectar dos máquinas virtuales bajo una misma red LAN, aisladas del exterior. No deben tener acceso a Internet. Justifica que ambas máquinas pueden comunicarse entre ellas. Documenta todo el proceso y aporta las capturas de pantalla necesarias.


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/3c5769a7-56b6-4b72-b83c-6a0a1bc78e71)



![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/bbf9f7b6-aa20-4cb8-97ee-39fdf8d572a9)


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/57cfa7f1-2876-46d8-95a6-4c912e1036cf)


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/2f6db74f-6e5a-459f-9bfa-927dc43d6aa3)




Se utilizara la Red Interna ya que permite conectar las dos máquinas virtuales sin conexión a internet. 

Para crearlos se utilizo una mascara de red tipo C, luego comando *ping* y la IP de la Maquina a la cual nos queremos contactar para que estas mismas se comuniquen.

Se comprobó en ambas maquinas de que funcionara la comunicacion (1 Windows y 1 Ubuntu)










● Actividad 6.2 - Diseño de una red LAN:
 Diseña una red LAN física que interconecte 30 PCs de escritorio (conexión por cable) y 10 dispositivos inalámbricos (1 smartTV, 7 smartphones y 2 tablets) en una pequeña oficina de una PYME. La oficina dispone de conexión a Internet, instalada y configurada por parte del proveedor de telecomunicaciones con el que trabaja la empresa, el cual ha instalado un pequeño modem/router con 4 tomas ethernet y conexión para dispositivos WiFi (Router Smart WiFi HGU Mitrastar GPT-2541GNAC) La oficina ocupa una superficie completamente diáfana de 50 metros cuadrados.
 Está dotada de 15 mesas con capacidad para 2 puestos de trabajo cada una. Cada puesto de trabajo está separado a un máximo de 1 metro desde su correspondiente toma de red en la pared. La oficina dispone de cableado de red categoría 6 canalizado a través de las paredes, con 40 tomas de red ethernet distribuidas a través de las canalizaciones. Este cableado alcanza el rack de comunicaciones de la oficina, el cual sólo incorpora el router instalado por el proveedor de telecomunicaciones. 

Se pide:

● Representar gráficamente la red (mapa lógico de red), donde se indique la dirección IP y máscara de subred de cada host. 


![image](https://github.com/Nardo104/Traballo_Redes/assets/164192169/84c51ff3-52b2-4c28-9eba-c208da55d1d8)




● Enumera el listado de dispositivos (sólo electrónica de red) y medios de transmisión (cableado) necesarios para completar la instalación de la red. Indica: marca y modelo de cada dispositivo, tipo de cable utilizado, metros totales del cable utilizados, conectores RJ45 necesarios. 


**Ordenadores:**
	30 x Torre: PC HP Slim S01-aF2001ns sin sistema operativo con 3 años de garantía. 219,00€

 
	30 x Pantalla: Monitor HP V22ve de 54,5 cm (21,45" ). 129,00€

	30 x Teclado Y Ratón: Combo de teclado y ratón inalámbricos HP 230. 39,99€

	7 x Telefono: Móvil - Xiaomi Redmi A2, Azul, 32 GB, 2 GB RAM, 6.52" HD+ Dot Drop Display, MediaTek Helio G36, 5000 mAh, Android 69€ 

	2 x Tablet: Tablet Blackview Tab 50 Wifi | 8 GB (4GB+4GB) RAM 128 GB ROM 79,99€


	1 x SmartTV: TD SYSTEMS Televisor 32 Pulgadas HD, USB Grabador reproductor, Sintonizador digital DVB-T2/C/S2 - TD Systems PRIME32C19H= 109.00€



	1 x Router: Router WiFi - TP-Link Archer C6, 1200 Mbps, Doble Banda, MU-MIMO, Beamforming, Gigabit, WPS, WPA3. 42,99€
 

	9 x Switch:Switch - TP-Link TL-SG108, 8 puertos RJ-45, Gigabit Ethernet (10/100/1000), Negro 22,90€ 
 

	30 x Cable: Cable de red - ISY IPC-6015-1, Cat-6, S/FTP, 1.5 m, 10 Gbit / s, 250 MHz, Blanco 2,99€
 

	15 x cable2:Cable de red - ISY IPC-6100-1, Cat-6, 10 Gbit / s, 250 MHz, 10 m, Blanco 12,99€



● Realiza un presupuesto para todo el listado de dispositivos y medios de transmisión del punto anterior. Este presupuesto no incluirá el coste de mano de obra de la instalación y configuración de la red. Se incluirán las cantidades con y sin IVA para cada una de las líneas del presupuesto. El coste total indicará la cantidad con y sin IVA.



+ Ordenadores: 9.195,36€ (Sin IVA) 11.639,70€  (Con IVA)
+ Móviles:  381,57€(Sin IVA)  438.0€ (Con IVA)
+ Tablets:  126,38€(Sin IVA) 159.98€(Con IVA)
+ SmartTV:  86,11€(Sin IVA) 109.00€(Con IVA)
+ Router: 33,96€(Sin IVA)  42,99€(Con IVA)
+ Switch: 162,81€(Sin IVA)  206,1€(Con IVA)
+ Cable 1m: 70,86€(Sin IVA)  89,7€(Con IVA)
+ Cable 10m: 153,9€(Sin IVA)  194,85€(Con IVA)
+ **COSTE TOTAL= 10.210,95€(Sin IVA)  12.879,92€(Con IVA)**









