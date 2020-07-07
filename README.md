# Skytap-Configuracion-VPN
En esta guía aprenderá cómo crear una conexión VPN entre su cuenta de Skytap y una red externa, la cual para este caso será una VPN IPsec de IBM. El propósto de las VPNs es conectar las máquinas virtuales de Skytap a otra máquina de la red de conexión.

Indice:
1. Crear y configurar VPN Skytap
2. Crear y configurar IPSec VPN 
3. Probar conexión VPN

## Crear y configurar VPN Skytap
Acceda desde la consola de IBM al servicio de Skytap **Launch Skytap on IBM Cloud**, servicio que previamente debió adquirir.

<img width="960" alt="img1" src="https://user-images.githubusercontent.com/60628267/86811209-43bca600-c043-11ea-9c14-30a0b92662d7.PNG">

Desde la barra de navegación, haga clic en **Environments** y seleccione el ambiente en el cual creará la VPN.

### Crear IP Pública estática 
Desde la barra de navegación, ingrese a **Manage -> Public IPs**. En este paso se creará una dirección IP pública estática la cual se utiliza como la dirección IP de Skytap para la conexión VPN. 
Imagen4

Haga clic en **Static Public IP address**, deberá elegir de la lista de regiones disponibles la que pertenece su ambiente de Skytap y luego haga clic en añadir (Add IP address). Como respuesta obtendrá una mensaje en pantalla: Added public IP address [Static Public IP address] in region [region].

Imagen4

### Crear una VPN 
Desde la barra de navegación, haga clic en **Manage -> WAN -> New VPN **

Imagen




## Crear y configurar IPSec VPN 


