Escenario: Malvinas Argentinas (MA-113, gestión, sistemas) y Mantenimiento (uno en la UNAHUR, otro en La Patria)
MA (JS-113): Computadoras para los estudiantes y profesor, notebook (mía xd)
MA (Gestión): impresora, computadora 
Sistemas: servidores (DNS, FTP, DHCP, HTTP). Servidor HTTP = página con red clase A
Mantenimiento: VPN para conectar mantenimiento de La Patria a la red de la UNAHUR

Servidor DHCP (otorga IP a las computadoras, aula y para la red de sistemas)
Servidor DNS (sistemas, va a darle un registro A a la impresora, al servidor FTP para pasarle cosas a la impresora, a la página UNAHUR y al campus)
Servidor FTP (sistemas, para imprimir archivos en gestión)
Servidor HTTP (sistemas, almacena la página y tiene la IP clase A)
3 redes de clases A, B y C (Clase A: servidor HTTP, Clase B: el campus va a estar hosteado en la UNAHUR por temas de seguridad debido al quilombo que hubo con PHP, clase C: todas las LAN que haya)
VPN (mantenimiento para conectarse a la red de sistemas desde La Patria)
Acces Point en el aula para conectar los equipos, abajo en gestión para la red pública
Hosts conectados por medio de Wifi (mi netbook xd)
Hosts conectados por medio de Ethernet (el resto de equipos)

Cantidad de dispositivos:
Como mínimo 4 Routers
Como mínimo 4 Switchs
Como mínimo 1 HUB (para mantenimiento de la UNAHUR para no poner un router)
Como mínimo 2 AP’s
Como mínimo 15 Hosts (notebook, desktop, servidores, impresoras)

Ver cómo implementar:
Rutas estáticas 
Rutas dinámicas (a elección el tipo de protocolo) 
STP
VLAN’S (por lo menos 3)
VTRUNK
