## Manual Técnico del Proyecto 1
 LABORATORIO REDES DE COMPUTADORAS 1
 Sección: A
#
#
#
#
#
#
#
#
#
#
#

### **Autor:**

- Kevin - Carnet: 201602404
- Richard Alexandro Marroquin Arana - Carnet: 202102894
#
#
#
#
#
#
### **Auxiliar:**
- Carlos Roberto Quixtán Pérez



### **Título:**

### Manual Técnico del Proyecto 1
#
#
#
#

#
#
#
#
#
---




## Introducción
Después de su demostración exitosa de conocimientos para la configuración de la red
local de la empresa “Solución al Cliente S.A.” usted fue recomendado para trabajar en la
construcción de una nueva red local, esta vez para la municipalidad de Guatemala.
Ellos necesitan que se cree una red donde diferentes departamentos puedan coexistir,
compartiendo el mismo medio físico, esto con el fin de ahorrar costos en instalación,
además es importante para ellos que exista redundancia, esto debido a que partes críticas
de la infraestructura de la municipalidad estarán en la red que se creará.
#
#
#

---
## Resumen de direcciones IP y VLAN

Departamentos sin existencia entre datos o sea vlans separadas

Estudiante 1 201602404
Estudiante 2 202102894

Ip y vlan con terminación 8 

| Departamento  | VLAN | ID Red         |
|---------------|------|----------------|
| Contabilidad  | 28   | 192.168.18.0   |
| Secretaría    | 38   | 192.168.28.0   |
| RRHH          | 48   | 192.168.38.0   |
| IT            | 58   | 192.168.48.0   |


## Configuración de Red

### Clientes
- sw7, 8 y 10
- 2, 3, 4, 5 y 6
- 11, 12, 13

### Transparentes
- 9

### Server
- sw1 (servidor VTP y raíz STP)
- Root bridge en sw1 para las VLAN 18, 28, 38 y 48

### Dominio
- Dominio: P9
- Contraseña: usac

### Implementación STP
- Variante: PVST

## Backbone
- **S_CONTABILIDAD**: 192.168.18.10
- **S_IT**: 192.168.48.10
- **S_RRHH**: 192.168.38.10

## Centro Administrativo
- **CONTABILIDAD2**: 192.168.18.02
- **SECRETARIA**: 192.168.28.10
- **RRHH**: 192.168.38.11
- **IT_2**: 192.168.48.02

## Área de Trabajo
- **SECRETARIA1**: 192.168.28.01
- **IT_1**: 192.168.48.01
- **CONTABILIDAD_1**: 192.168.18.01
- **SECRETARIA2**: 192.168.28.02
- **RRHH1**: 192.168.38.01
- **RRHH2**: 192.168.38.02


## Contabilidad
![Menu](https://i.ibb.co/Dz6vfXr/imagen-2024-09-06-001049764.png)
## S_RRHH
![Menu](https://i.ibb.co/smPWyHh/image.png)
## Secretaria2 
![Menu](https://i.ibb.co/6DM6J0z/image.png)
//////////////////////////////////////////////////////////////////////////////////////////////

## Capturas de la implementación de las topologías
### Centro Administrativo
![Menu](https://i.ibb.co/TkSrQFM/image.png)
### BACKBONE 
![Menu](https://i.ibb.co/zXhm8Jd/image.png)
### AREA DE TRABAJO
![Menu](https://i.ibb.co/LRPRZjL/image.png)

/////////////////////////////////////////////////////////////////////////////////////////////

## Detalle de los comandos usados
-  ##### Comandos para configurar el sw1 como servidor 
enable
configure terminal
vtp domain P9
vtp password usac
vtp mode server
vlan 28
name Contabilidad
exit
vlan 38
name Secretaria
exit
vlan 48
name RRHH
exit
vlan 58
name IT
exit
rapid-pvst vlan 28,38,48,58 priority 0
interface range fa0/1-5
switchport trunk allowed vlan 28,38,48,58
exit

vlan para los sw 2 al 13
enable
configure terminal
vlan 28
name Contabilidad
exit
vlan 38
name Secretaria
exit
vlan 48
name RRHH
exit
vlan 58
name IT
exit


-  ##### Comandos para configurar los sw desde el 2 hasta el 13 evitando el 9
enable
configure terminal
vtp domain P9
vtp password usac
vtp mode client
enable
configure terminal
interface range fa0/1-3
switchport trunk encapsulation dot1q
switchport mode trunk
switchport trunk allowed vlan 28,38,48,58
exit
exit

-  ##### Comando para configurar el SW9 en modo transparent
enable
configure terminal
vtp domain P9
vtp password usac
vtp mode transparent

-  ##### Comando para validar el modo stp en los switch
enable
show spanning-tree

-  ##### Comando para cambiar de psvt a rstp-rapid pvst porque configure como par xd  
enable
configure terminal
spanning-tree mode rapid-pvst


## Ping entre hosts (solamente 2, ustedes eligen los orígenes y destinos).


#### PING_CONTA2_CONTAOK_ITFAIL.png
![Menu](https://i.ibb.co/qRg504B/image.png)


#### NG_RRHH1_RRHHOK_CONTAFAIL
![Menu](https://i.ibb.co/L12SW35/image.png)



---
