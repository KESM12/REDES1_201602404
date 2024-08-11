# Manual Técnico

## 1. Configuración de las VPCs

### 1.1. VPC de Administración

- **IP Asignada:** 192.168.4.10

![Config Admin](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC0_ADMIN.jpg)

### 1.2. VPC de Gerencia

- **IP Asignada:** 192.168.04.12

![Configuración VPC Gerencia](ruta/a/la/captura2.png)

### 1.3. VPC de Secretaría de Gerencia

- **IP Asignada:** 192.168.04.13

![Configuración VPC Secretaría](ruta/a/la/captura3.png)

### 1.4. VPC de Atención al Cliente 1

- **IP Asignada:** 192.168.04.14

![Configuración VPC Atención al Cliente 1](ruta/a/la/captura4.png)

### 1.5. VPC de Atención al Cliente 2

- **IP Asignada:** 192.168.04.15
- **Configuración:**
    - **Puerta de Enlace:** 192.168.04.1
    - **Máscara de Subred:** 255.255.255.0

![Configuración VPC Atención al Cliente 2](ruta/a/la/captura5.png)

### 1.6. VPC de Recursos Humanos 1

- **IP Asignada:** 192.168.04.16
- **Configuración:**
    - **Puerta de Enlace:** 192.168.04.1
    - **Máscara de Subred:** 255.255.255.0

![Configuración VPC Recursos Humanos 1](ruta/a/la/captura6.png)

### 1.7. VPC de Recursos Humanos 2

- **IP Asignada:** 192.168.04.17
- **Configuración:**
    - **Puerta de Enlace:** 192.168.04.1
    - **Máscara de Subred:** 255.255.255.0

![Configuración VPC Recursos Humanos 2](ruta/a/la/captura7.png)

### 1.8. VPC de Oficina A 1

- **IP Asignada:** 192.168.04.31
- **Configuración:**
    - **Puerta de Enlace:** 192.168.04.2
    - **Máscara de Subred:** 255.255.255.0

![Configuración VPC Oficina A 1](ruta/a/la/captura8.png)

### 1.9. VPC de Oficina B 1

- **IP Asignada:** 192.168.04.34
- **Configuración:**
    - **Puerta de Enlace:** 192.168.04.2
    - **Máscara de Subred:** 255.255.255.0

![Configuración VPC Oficina B 1](ruta/a/la/captura9.png)

### 1.10. VPC de Recepción

- **IP Asignada:** 192.168.04.51
- **Configuración:**
    - **Puerta de Enlace:** 192.168.04.3
    - **Máscara de Subred:** 255.255.255.0

![Configuración VPC Recepción](ruta/a/la/captura10.png)

## 2. Pruebas de Comunicación entre Áreas

### 2.1. Ping desde VPC de Administración a VPC de Gerencia

- **Comando:** `ping 192.168.04.12`

![Ping Administración a Gerencia](ruta/a/la/captura11.png)

### 2.2. Ping desde VPC de Atención al Cliente 1 a VPC de Recursos Humanos 1

- **Comando:** `ping 192.168.04.16`

![Ping Atención al Cliente 1 a Recursos Humanos 1](ruta/a/la/captura12.png)

### 2.3. Ping desde VPC de Oficina A 1 a VPC de Oficina B 1

- **Comando:** `ping 192.168.04.34`

![Ping Oficina A 1 a Oficina B 1](ruta/a/la/captura13.png)

### 2.4. Ping desde VPC de Recepción a VPC de TI 1

- **Comando:** `ping 192.168.04.52`

![Ping Recepción a TI 1](ruta/a/la/captura14.png)

### 2.5. Ping desde VPC de Ventas a VPC de Administración

- **Comando:** `ping 192.168.04.11`

![Ping Ventas a Administración](ruta/a/la/captura15.png)

## 3. Captura de Paquete ARP/ICMP

### 3.1. Descripción de la Captura

La captura de paquetes se realizó para analizar el tráfico ARP/ICMP entre la VPC de Recepción y la VPC de TI 1 durante una prueba de ping.

### 3.2. Captura de Pantalla

![Captura de Paquete ARP/ICMP](ruta/a/la/captura16.png)


[vpcAdminConfig]: Practica1\PC0_ADMIN.jpg
