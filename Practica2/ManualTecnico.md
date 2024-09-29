# Manual Técnico

## 1. Configuración de los Routers

### 1.1 Router R1.
![Config_R1](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R1_1era.png)

### 1.2 Router R2.
![Config_R2](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R2_1era.png)
### 1.3 Router R6.
![Config_R2](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R3_1era.png)

## Configuración HSR
![Config_HSR](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_R2_2da.png)

## 2. Configuración de Switches

### 2.1 Switch SW1 - Configuración de PortChannel con PAGP
![Config_SW1](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_SW1_1era.png)
### 2.2 Switch SW3 - Configuración de PortChannel con LACP
![Config_SW3](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_SW3_1era.png)

## 3. Configuración de VPCs

### 3.1 VPC11
![Config_VPC11](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_VPC11_1era.png)

### 3.2 VPC14
![Config_VPC14](https://github.com/KESM12/REDES1_201602404/blob/main/Practica2/Images/Conf_VPC14_1era.png)

# Resumen de los Comandos Usados

## 1. Creación de Ruta Estática

## 2. Creación de PortChannel con PAGP

## 3. Creación de PortChannel con LACP

## 4. Creación de IP Virtual con HSRP

## 5. Configuración de VPC

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