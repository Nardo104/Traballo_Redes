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




 Para cada uno de ellos, explícalo brevemente y aporta un esquema que ejemplifica su funcionamiento. Selecciona y configura el tipo de red que te permite conectar dos máquinas virtuales bajo una misma red LAN, aisladas del exterior. No deben tener acceso a Internet. Justifica que ambas máquinas pueden comunicarse entre ellas. Documenta todo el proceso y aporta las capturas de pantalla necesarias: 
Red Interna ya que permite conectar las dos máquinas virtuales sin conexión a internet (Esta explicación non creo que sirva).


![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/3c5769a7-56b6-4b72-b83c-6a0a1bc78e71)



![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/bbf9f7b6-aa20-4cb8-97ee-39fdf8d572a9)



![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/6924d275-8928-474d-8bce-d03d0817af6d)



![image](https://github.com/Nardo104/Traballo_Redes/assets/164507058/498e52a9-925f-4605-8bf9-e06258d5905b)




Todo esto sería a conexión de red interna










● Actividad 6.2 - Diseño de una red LAN:
 Diseña una red LAN física que interconecte 30 PCs de escritorio (conexión por cable) y 10 dispositivos inalámbricos (1 smartTV, 7 smartphones y 2 tablets) en una pequeña oficina de una PYME. La oficina dispone de conexión a Internet, instalada y configurada por parte del proveedor de telecomunicaciones con el que trabaja la empresa, el cual ha instalado un pequeño modem/router con 4 tomas ethernet y conexión para dispositivos WiFi (Router Smart WiFi HGU Mitrastar GPT-2541GNAC) La oficina ocupa una superficie completamente diáfana de 50 metros cuadrados.
 Está dotada de 15 mesas con capacidad para 2 puestos de trabajo cada una. Cada puesto de trabajo está separado a un máximo de 1 metro desde su correspondiente toma de red en la pared. La oficina dispone de cableado de red categoría 6 canalizado a través de las paredes, con 40 tomas de red ethernet distribuidas a través de las canalizaciones. Este cableado alcanza el rack de comunicaciones de la oficina, el cual sólo incorpora el router instalado por el proveedor de telecomunicaciones. 

Se pide:

● Representar gráficamente la red (mapa lógico de red), donde se indique la dirección IP y máscara de subred de cada host. 

● Enumera el listado de dispositivos (sólo electrónica de red) y medios de transmisión (cableado) necesarios para completar la instalación de la red. Indica: marca y modelo de cada dispositivo, tipo de cable utilizado, metros totales del cable utilizados, conectores RJ45 necesarios. 

● Realiza un presupuesto para todo el listado de dispositivos y medios de transmisión del punto anterior. Este presupuesto no incluirá el coste de mano de obra de la instalación y configuración de la red. Se incluirán las cantidades con y sin IVA para cada una de las líneas del presupuesto. El coste total indicará la cantidad con y sin IVA.




