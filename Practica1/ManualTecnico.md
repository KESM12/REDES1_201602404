# Manual Técnico

## 1. Configuración de las VPCs

### 1.1. VPC de Administración

- **IP Asignada:** 192.168.4.10

![IpAdmin](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC0_ADMIN.jpg)

### 1.2. VPC de Gerencia

- **IP Asignada:** 192.168.04.11

![IpGeren](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC1_GEREN.jpg)

### 1.3. VPC de Soporte al Cliente 

- **IP Asignada:** 192.168.04.13

![IpSopClient1](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC2_SCLIENT0.jpg)

### 1.4. VPC de Recursos Humanos

- **IP Asignada:** 192.168.04.15
![IpRecHuman](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC4_RECHUMAN0.jpg)

### 1.5. VPC de Oficina A 

- **IP Asignada:** 192.168.04.2

![IpOfA](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC11_OFA1.jpg)

### 1.6. VPC de Oficina B 

- **IP Asignada:** 192.168.04.23

![IpOfB](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC14_OFB1.jpg)

### 1.7. VPC de Oficina C

- **IP Asignada:** 192.168.04.29

![IpOfB](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC14_OFC1.jpg)

### 1.8. VPC de Recepción

- **IP Asignada:** 192.168.04.3

![IpRec](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC23-REC.jpg)

### 1.9. VPC de TI.

- **IP Asignada:** 192.168.04.31

![IpTI](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC24-TI1.jpg)

### 1.10. VPC de Ventas.

- **IP Asignada:** 192.168.04.34

![IpTI](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PC2_SCLIENT0.jpg)


## 2. Pruebas de Comunicación entre Áreas

### 2.1. Ping desde VPC de Oficina B6 a VPC de Recurso Humanos 5

- **Comando:** `ping 192.168.04.1`

![Ping Ofb6 a RecHuman5](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PING_OFB6_RECHUM5.jpg)

### 2.2. Ping desde VPC de Recursos Humanos 3 a VPC de Secretaria del Gerente

- **Comando:** `ping 192.168.04.12`

![Ping RecHumn2 a Secgeren](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PING_RECHUM2_SECGEREN.jpg)

### 2.3. Ping desde VPC de Recursos Humanos a VPC de Recepción

- **Comando:** `ping 192.168.04.3`

![Ping Rechum0 a Rec](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PING_RECHUMAN0_REC.jpg)

### 2.4. Ping desde VPC de TI1 a VPC de Oficina A2

- **Comando:** `ping 192.168.04.21`

![Ping TI1 Ofa2](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PING_TI1_OFA2.jpg)

### 2.5. Ping desde VPC de TI2 a VPC de Gerencia

- **Comando:** `ping 192.168.04.11`

![Ping Ti2 a Geren](https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/PING_TI2_GEREN.jpg)

## 3. Captura de Paquete ARP/ICMP

### 3.1. Descripción de la Captura

La captura de paquetes se realizó para analizar el tráfico ARP/ICMP entre la VPC de Gerencia y la VPC de TI 1 durante una prueba de ping.

### 3.2. Captura de Pantalla

![Captura de Paquete ARP/ICMP](ruta/a/la/captura16.png)


[vpcAdminConfig]: (https://github.com/KESM12/REDES1_201602404/blob/main/Practica1/imagenes/ARP-ICMP.jpg)
