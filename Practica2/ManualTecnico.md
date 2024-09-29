# Manual Técnico

## 1. Configuración de los Routers

### 1.1 Router R1.
![Config_R1](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R1_1era.png)

### 1.2 Router R2.
![Config_R2](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R2_1era.png)
### 1.3 Router R6.
![Config_R2](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R6_1era.png)

## Configuración HSR
![Config_HSR](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R2_2da.png)

## 2. Configuración de Switches

### 2.1 Switch SW1 - Configuración de PortChannel con PAGP
![Config_SW1](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_SW1_1era.png)
### 2.2 Switch SW3 - Configuración de PortChannel con LACP
![Config_SW3](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_SW3_1era.png)

## 3. Configuración de VPCs

### 3.1 VPC11
![Config_VPC11](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_VPC11.png)

### 3.2 VPC14
![Config_VPC14](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_VPC14.png)

# Resumen de los Comandos Usados

## 1. Configuración R1 y R4 (modificar ip addres)
```bash
enable
configure terminal
interface se0/0
ip address 10.0.0.1 255.255.255.252
no shutdown
interface fa0/0
ip address 142.168.1.2 255.255.255.248
no shutdown
interface fa0/1
ip address 142.168.2.2 255.255.255.248
no shutdown
exit
exit
wr
```

## 2. Configuración R2 - R6 (modificar ip addres)
```bash
enable
configure terminal
interface fa0/0
ip address 142.168.1.2 255.255.255.248
no shutdown
interface fa0/1
ip address 142.168.2.2 255.255.255.248
no shutdown
exit
exit
wr
```



## 3. Configuración Sw0 - Sw1 (PAGP)
```bash
enable
configure terminal
interface range fa0/1-2
channel-group 1 mode desirable
exit
exit
wr
```
## 4. Configuración Sw2 - Sw3 (LACP)
```bash
enable
configure terminal
interface range fa0/1-2
channel-group 1 mode active
exit
exit
wr
```

## 5. Configuración de rutas ip estáticas (cambiar ip's)
```bash
ip route 142.168.1.0 255.255.255.248 142.168.1.2 
ip route 142.178.1.0 255.255.255.248 142.168.1.2 
ip route 142.178.2.0 255.255.255.248 142.168.1.2 
ip route 142.168.2.0 255.255.255.248 142.168.1.2 
ip route 142.178.0.0 255.255.255.0 142.168.1.2 
ip route 142.168.0.0 255.255.255.0 142.168.0.1
```

# Verificación del Funcionamiento de los Protocolos

## 1. Verificación de PortChannel

```bash
show etherchannel summary
```

## 2. Verificación de HSRP

```bash
show standby
```

## 3. Verificación de Rutas Estáticas

```bash
show ip route
```

## 4. Verificación de Conectividad (Ping entre VPCs)

```bash
ping <dirección_ip>
```

## 5. Verificación de la configuración en los Routers
```bash
show running-config
```


# Configuración de redes.

| **Dispositivo** | **Interfaz** | **IP**| **Máscara de Subred**|
|-------------|----------|---------------|-----------------------------|
| **R1**      | se1/0    | 10.0.0.1      | /30 -- 255.255.255.252      |
|             | fa0/0    | 142.168.1.2   | /29 -- 255.255.255.248      |
|             | fa0/1    | 142.168.2.2   | /29 -- 255.255.255.248      |
| **R2**      | fa0/0    | 142.168.1.1   | /29 -- 255.255.255.248      |
|             | fa0/1    | 142.168.0.2   | /24 -- 255.255.255.0        |
| **R3**      | fa0/0    | 142.168.2.1   | /29 -- 255.255.255.248      |
|             | fa0/1    | 142.168.0.3   | /24 -- 255.255.255.0        |
|**R2-R3**    | Virtual  | 142.168.0.1   | /24 -- 255.255.255.0        |
| **VPC11**   | ---      | 142.168.0.4   | /24 -- 255.255.255.0        |
| **VPC13**   | ---      | 142.168.0.5   | /24 -- 255.255.255.0        |
| **R4**      | se1/0    | 10.0.0.2      | /30 -- 255.255.255.252      |
|             | fa0/0    | 142.178.1.1   | /29 -- 255.255.255.248      |
|             | fa0/1    | 142.178.2.1   | /29 -- 255.255.255.248      |
| **R5**      | fa0/0    | 142.172.1.2   | /24 -- 255.255.255.0        |
|             | fa0/1    | 142.178.0.2   | /24 -- 255.255.255.0        |
| **R6**      | fa0/0    | 142.178.2.2   | /29 -- 255.255.255.248      |
|             | fa0/1    | 142.178.0.3   | /24 -- 255.255.255.0        |
| **R5-R6**   | Virtual  | 142.178.0.1   | /24 -- 255.255.255.0        |
| **VPC12**   | ---      | 142.178.0.4   | /24 -- 255.255.255.0        |
| **VPC14**   | ---      | 142.178.0.5   | /24 -- 255.255.255.0        |
