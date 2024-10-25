## Manual Técnico del Proyecto 2
LABORATORIO REDES DE COMPUTADORAS 1
Sección: A
### **Autor:**  
- Kevin Estuardo Secaida Molina - Carnet: 201602404
- Richard Alexandro Marroquin Arana - Carnet: 202102894  
### **Auxiliar:**
- Carlos Roberto Quixtán Pérez  
### Resumen de direcciones IP y VLAN
#### Sede Jutiapa.  
##### Vlan's
| Departamento  | VLAN | ID Red         |Masacara de subred |
|---------------|------|----------------|------------------ |
| RRHH          | 14  |192.168.09.0/28  | 255.255.255.240   |
| Ventas        | 34  |192.168.09.0/27 | 255.255.255.224   |
| Contabilidad  | 24  |192.168.09.0/29  | 255.255.255.248   |
| IT            | 44  |192.168.09.0/28  | 255.255.255.240   |

##### IP's
| Departamento  | IP             | Puerto Ethernet     | Máscara de Subred    |
|---------------|----------------|---------------------|----------------------|
| RRHH          | 192.168.09.1   | GigabitEthernet0/0  | 255.255.255.240      |
|               | 192.168.09.2   | GigabitEthernet0/1  | 255.255.255.240      |
|               | 192.168.09.3   | GigabitEthernet0/2  | 255.255.255.240      |
|               | 192.168.09.4   | GigabitEthernet0/3  | 255.255.255.240      |
|               | 192.168.09.5   | GigabitEthernet0/4  | 255.255.255.240      |
|               | 192.168.09.6   | GigabitEthernet0/5  | 255.255.255.240      |
|               | 192.168.09.7   | GigabitEthernet0/6  | 255.255.255.240      |
|               | 192.168.09.8   | GigabitEthernet0/7  | 255.255.255.240      |
|               | 192.168.09.9   | GigabitEthernet0/8  | 255.255.255.240      |
|               | 192.168.09.10  | GigabitEthernet0/9  | 255.255.255.240      |
|               | 192.168.09.11  | GigabitEthernet0/10 | 255.255.255.240      |
|               | 192.168.09.12  | GigabitEthernet0/11 | 255.255.255.240      |
|               | 192.168.09.13  | GigabitEthernet0/12 | 255.255.255.240      |
|               | 192.168.09.14  | GigabitEthernet0/13 | 255.255.255.240      |
| Ventas        | 192.168.09.17  | GigabitEthernet0/14 | 255.255.255.224      |
|               | 192.168.09.18  | GigabitEthernet0/15 | 255.255.255.224      |
|               | 192.168.09.19  | GigabitEthernet0/16 | 255.255.255.224      |
|               | 192.168.09.20  | GigabitEthernet1/1  | 255.255.255.224      |
|               | 192.168.09.21  | GigabitEthernet1/2  | 255.255.255.224      |
|               | 192.168.09.22  | GigabitEthernet1/3  | 255.255.255.224      |
|               | 192.168.09.23  | GigabitEthernet1/4  | 255.255.255.224      |
|               | 192.168.09.24  | GigabitEthernet1/5  | 255.255.255.224      |
|               | 192.168.09.25  | GigabitEthernet1/6  | 255.255.255.224      |
|               | 192.168.09.26  | GigabitEthernet1/7  | 255.255.255.224      |
|               | 192.168.09.27  | GigabitEthernet1/8  | 255.255.255.224      |
|               | 192.168.09.28  | GigabitEthernet1/9  | 255.255.255.224      |
|               | 192.168.09.29  | GigabitEthernet1/10 | 255.255.255.224      |
|               | 192.168.09.30  | GigabitEthernet1/11 | 255.255.255.224      |
|               | 192.168.09.31  | GigabitEthernet1/12 | 255.255.255.224      |
|               | 192.168.09.32  | GigabitEthernet1/13 | 255.255.255.224      |
|               | 192.168.09.33  | GigabitEthernet1/14 | 255.255.255.224      |
|               | 192.168.09.34  | GigabitEthernet1/15 | 255.255.255.224      |
|               | 192.168.09.35  | GigabitEthernet1/16 | 255.255.255.224      |
|               | 192.168.09.36  | GigabitEthernet2/1  | 255.255.255.224      |
|               | 192.168.09.37  | GigabitEthernet2/2  | 255.255.255.224      |
|               | 192.168.09.38  | GigabitEthernet2/3  | 255.255.255.224      |
|               | 192.168.09.39  | GigabitEthernet2/4  | 255.255.255.224      |
|               | 192.168.09.40  | GigabitEthernet2/5  | 255.255.255.224      |
|               | 192.168.09.41  | GigabitEthernet2/6  | 255.255.255.224      |
|               | 192.168.09.42  | GigabitEthernet2/7  | 255.255.255.224      |
|               | 192.168.09.43  | GigabitEthernet2/8  | 255.255.255.224      |
|               | 192.168.09.44  | GigabitEthernet2/9  | 255.255.255.224      |
|               | 192.168.09.45  | GigabitEthernet2/10 | 255.255.255.224      |
|               | 192.168.09.46  | GigabitEthernet2/11 | 255.255.255.224      |
| Contabilidad  | 192.168.09.49  | GigabitEthernet2/12 | 255.255.255.248      |
|               | 192.168.09.50  | GigabitEthernet2/13 | 255.255.255.248      |
|               | 192.168.09.51  | GigabitEthernet2/14 | 255.255.255.248      |
|               | 192.168.09.52  | GigabitEthernet2/15 | 255.255.255.248      |
|               | 192.168.09.53  | GigabitEthernet2/16 | 255.255.255.248      |
|               | 192.168.09.54  | GigabitEthernet3/1  | 255.255.255.248      |
| Informatica   | 192.168.09.57  | GigabitEthernet3/2  | 255.255.255.240      |
|               | 192.168.09.58  | GigabitEthernet3/3  | 255.255.255.240      |
|               | 192.168.09.59  | GigabitEthernet3/4  | 255.255.255.240      |
|               | 192.168.09.60  | GigabitEthernet3/5  | 255.255.255.240      |
|               | 192.168.09.61  | GigabitEthernet3/6  | 255.255.255.240      |
|               | 192.168.09.62  | GigabitEthernet3/7  | 255.255.255.240      |
|               | 192.168.09.63  | GigabitEthernet3/8  | 255.255.255.240      |
|               | 192.168.09.64  | GigabitEthernet3/9  | 255.255.255.240      |
|               | 192.168.09.65  | GigabitEthernet3/10 | 255.255.255.240      |
|               | 192.168.09.66  | GigabitEthernet3/11 | 255.255.255.240      |
|               | 192.168.09.67  | GigabitEthernet3/12 | 255.255.255.240      |
|               | 192.168.09.68  | GigabitEthernet3/13 | 255.255.255.240      |
|               | 192.168.09.69  | GigabitEthernet3/14 | 255.255.255.240      |
|               | 192.168.09.70  | GigabitEthernet3/15 | 255.255.255.240      |

#### Sede Escuintla
##### Vlan's
| Departamento  | VLAN | ID Red         |Masacara de subred |
|---------------|------|----------------|------------------ |
| RRHH          | 14  |192.148.09.0/28  | 255.255.255.248   |
| Ventas        | 34  |192.148.09.0/27  | 255.255.255.224   |

##### IP's
| Departamento  | IP           | Puerto Ethernet     | Máscara de Subred    |
|---------------|--------------|---------------------|----------------------|
| RRHH          | 192.148.09.1 | GigabitEthernet0/0  | 255.255.255.248      |
|               | 192.148.09.2 | GigabitEthernet0/1  | 255.255.255.248      |
|               | 192.148.09.3 | GigabitEthernet0/2  | 255.255.255.248      |
|               | 192.148.09.4 | GigabitEthernet0/3  | 255.255.255.248      |
|               | 192.148.09.5 | GigabitEthernet0/4  | 255.255.255.248      |
|               | 192.148.09.6 | GigabitEthernet0/5  | 255.255.255.248      |
| Ventas        | 192.148.09.9 | GigabitEthernet0/6  | 255.255.255.224      |
|               | 192.148.09.10| GigabitEthernet0/7  | 255.255.255.224      |
|               | 192.148.09.11| GigabitEthernet0/8  | 255.255.255.224      |
|               | 192.148.09.12| GigabitEthernet0/9  | 255.255.255.224      |
|               | 192.148.09.13| GigabitEthernet0/10 | 255.255.255.224      |
|               | 192.148.09.14| GigabitEthernet0/11 | 255.255.255.224      |
|               | 192.148.09.15| GigabitEthernet0/12 | 255.255.255.224      |
|               | 192.148.09.16| GigabitEthernet0/13 | 255.255.255.224      |
|               | 192.148.09.17| GigabitEthernet0/14 | 255.255.255.224      |
|               | 192.148.09.18| GigabitEthernet0/15 | 255.255.255.224      |
|               | 192.148.09.19| GigabitEthernet0/16 | 255.255.255.224      |
|               | 192.148.09.20| GigabitEthernet1/0  | 255.255.255.224      |
|               | 192.148.09.21| GigabitEthernet1/1  | 255.255.255.224      |
|               | 192.148.09.22| GigabitEthernet1/2  | 255.255.255.224      |
|               | 192.148.09.23| GigabitEthernet1/3  | 255.255.255.224      |
|               | 192.148.09.24| GigabitEthernet1/4  | 255.255.255.224      |
|               | 192.148.09.25| GigabitEthernet1/5  | 255.255.255.224      |
|               | 192.148.09.26| GigabitEthernet1/6  | 255.255.255.224      |
|               | 192.148.09.27| GigabitEthernet1/7  | 255.255.255.224      |
|               | 192.148.09.28| GigabitEthernet1/8  | 255.255.255.224      |
|               | 192.148.09.29| GigabitEthernet1/9  | 255.255.255.224      |
|               | 192.148.09.30| GigabitEthernet1/10 | 255.255.255.224      |

#### Sede Quiche
##### Vlan's
| Departamento  | VLAN | ID Red         |Masacara de subred |
|---------------|------|----------------|------------------ |
| RRHH          | 14   |192.178.09.0/28 | 255.255.255.240   |
| Ventas        | 34   |192.178.09.0/26 | 255.255.255.224   |
| Contabilidad  | 24   |192.178.09.0/28 | 255.255.255.248   |
| IT            | 44   |192.178.09.0/27 | 255.255.255.240   |

##### IP's
| Departamento  | IP             | Puerto Ethernet     | Máscara de Subred    |
|---------------|----------------|---------------------|----------------------|
| RRHH          | 192.178.09.1   | GigabitEthernet0/0  | 255.255.255.240      |
|               | 192.178.09.2   | GigabitEthernet0/1  | 255.255.255.240      |
|               | 192.178.09.3   | GigabitEthernet0/2  | 255.255.255.240      |
|               | 192.178.09.4   | GigabitEthernet0/3  | 255.255.255.240      |
|               | 192.178.09.5   | GigabitEthernet0/4  | 255.255.255.240      |
|               | 192.178.09.6   | GigabitEthernet0/5  | 255.255.255.240      |
|               | 192.178.09.7   | GigabitEthernet0/6  | 255.255.255.240      |
|               | 192.178.09.8   | GigabitEthernet0/7  | 255.255.255.240      |
|               | 192.178.09.9   | GigabitEthernet0/8  | 255.255.255.240      |
|               | 192.178.09.10  | GigabitEthernet0/9  | 255.255.255.240      |
|               | 192.178.09.11  | GigabitEthernet0/10 | 255.255.255.240      |
|               | 192.178.09.12  | GigabitEthernet0/11 | 255.255.255.240      |
|               | 192.178.09.13  | GigabitEthernet0/12 | 255.255.255.240      |
|               | 192.178.09.14  | GigabitEthernet0/13 | 255.255.255.240      |
|Contabilidad   | 192.178.09.17  | GigabitEthernet0/14 | 255.255.255.240      |
|               | 192.178.09.18  | GigabitEthernet0/15 | 255.255.255.240      |
|               | 192.178.09.19  | GigabitEthernet0/16 | 255.255.255.240      |
|               | 192.178.09.20  | GigabitEthernet1/1  | 255.255.255.240      |
|               | 192.178.09.21  | GigabitEthernet1/2  | 255.255.255.240      |
|               | 192.178.09.22  | GigabitEthernet1/3  | 255.255.255.240      |
|               | 192.178.09.23  | GigabitEthernet1/4  | 255.255.255.240      |
|               | 192.178.09.24  | GigabitEthernet1/5  | 255.255.255.240      |
|               | 192.178.09.25  | GigabitEthernet1/6  | 255.255.255.240      |
|               | 192.178.09.26  | GigabitEthernet1/7  | 255.255.255.240      |
|               | 192.178.09.27  | GigabitEthernet1/8  | 255.255.255.240      |
|               | 192.178.09.28  | GigabitEthernet1/9  | 255.255.255.240      |
|               | 192.178.09.29  | GigabitEthernet1/10 | 255.255.255.240      |
|               | 192.178.09.30  | GigabitEthernet1/11 | 255.255.255.240      |
| Ventas        | 192.178.09.31  | GigabitEthernet1/12 | 255.255.255.192      |
|               | 192.178.09.32  | GigabitEthernet1/13 | 255.255.255.192      |
|               | 192.178.09.33  | GigabitEthernet1/14 | 255.255.255.192      |
|               | 192.178.09.34  | GigabitEthernet1/15 | 255.255.255.192      |
|               | 192.178.09.35  | GigabitEthernet1/16 | 255.255.255.192      |
|               | 192.178.09.36  | GigabitEthernet2/1  | 255.255.255.192      |
|               | 192.178.09.37  | GigabitEthernet2/2  | 255.255.255.192      |
|               | 192.178.09.38  | GigabitEthernet2/3  | 255.255.255.192      |
|               | 192.178.09.39  | GigabitEthernet2/4  | 255.255.255.192      |
|               | 192.178.09.40  | GigabitEthernet2/5  | 255.255.255.192      |
|               | 192.178.09.41  | GigabitEthernet2/6  | 255.255.255.192      |
|               | 192.178.09.42  | GigabitEthernet2/7  | 255.255.255.192      |
|               | 192.178.09.43  | GigabitEthernet2/8  | 255.255.255.192      |
|               | 192.178.09.44  | GigabitEthernet2/9  | 255.255.255.192      |
|               | 192.178.09.45  | GigabitEthernet2/10 | 255.255.255.192      |
|               | 192.178.09.46  | GigabitEthernet2/11 | 255.255.255.192      |
|               | 192.178.09.49  | GigabitEthernet2/12 | 255.255.255.192      |
|               | 192.178.09.50  | GigabitEthernet2/13 | 255.255.255.192      |
|               | 192.178.09.51  | GigabitEthernet2/14 | 255.255.255.192      |
|               | 192.178.09.52  | GigabitEthernet2/15 | 255.255.255.192      |
|               | 192.178.09.53  | GigabitEthernet2/16 | 255.255.255.192      |
|               | 192.178.09.54  | GigabitEthernet3/1  | 255.255.255.192      |
|               | 192.178.09.57  | GigabitEthernet3/2  | 255.255.255.192      |
|               | 192.178.09.58  | GigabitEthernet3/3  | 255.255.255.192      |
|               | 192.178.09.59  | GigabitEthernet3/4  | 255.255.255.192      |
|               | 192.178.09.60  | GigabitEthernet3/5  | 255.255.255.192      |
|               | 192.178.09.61  | GigabitEthernet3/6  | 255.255.255.192      |
|               | 192.178.09.62  | GigabitEthernet3/7  | 255.255.255.192      |
|               | 192.178.09.63  | GigabitEthernet3/8  | 255.255.255.192      |
|               | 192.178.09.64  | GigabitEthernet3/9  | 255.255.255.192      |
| Informatica   | 192.178.09.65  | GigabitEthernet3/10 | 255.255.255.224      |
|               | 192.178.09.66  | GigabitEthernet3/11 | 255.255.255.224      |
|               | 192.178.09.67  | GigabitEthernet3/12 | 255.255.255.224      |
|               | 192.178.09.68  | GigabitEthernet3/13 | 255.255.255.224      |
|               | 192.178.09.69  | GigabitEthernet3/14 | 255.255.255.224      |
|               | 192.178.09.70  | GigabitEthernet3/15 | 255.255.255.224      |
|               | 192.178.09.71  | GigabitEthernet3/16 | 255.255.255.224      |
|               | 192.178.09.72  | GigabitEthernet4/1  | 255.255.255.224      |
|               | 192.178.09.73  | GigabitEthernet4/2  | 255.255.255.224      |
|               | 192.178.09.74  | GigabitEthernet4/3  | 255.255.255.224      |
|               | 192.178.09.75  | GigabitEthernet4/4  | 255.255.255.224      |
|               | 192.178.09.76  | GigabitEthernet4/5  | 255.255.255.224      |
|               | 192.178.09.77  | GigabitEthernet4/6  | 255.255.255.224      |
|               | 192.178.09.78  | GigabitEthernet4/7  | 255.255.255.224      |
|               | 192.178.09.79  | GigabitEthernet4/8  | 255.255.255.224      |
|               | 192.178.09.80  | GigabitEthernet4/9  | 255.255.255.224      |
|               | 192.178.09.81  | GigabitEthernet4/10 | 255.255.255.224      |
|               | 192.178.09.82  | GigabitEthernet4/11 | 255.255.255.224      |
|               | 192.178.09.83  | GigabitEthernet4/12 | 255.255.255.224      |
|               | 192.178.09.84  | GigabitEthernet4/13 | 255.255.255.224      |
|               | 192.178.09.85  | GigabitEthernet4/14 | 255.255.255.224      |
|               | 192.178.09.86  | GigabitEthernet4/15 | 255.255.255.224      |
|               | 192.178.09.87  | GigabitEthernet4/16 | 255.255.255.224      |
|               | 192.178.09.88  | GigabitEthernet5/1  | 255.255.255.224      |
|               | 192.178.09.89  | GigabitEthernet5/2  | 255.255.255.224      |
|               | 192.178.09.90  | GigabitEthernet5/3  | 255.255.255.224      |
|               | 192.178.09.91  | GigabitEthernet5/4  | 255.255.255.224      |
|               | 192.178.09.92  | GigabitEthernet5/5  | 255.255.255.224      |
|               | 192.178.09.93  | GigabitEthernet5/6  | 255.255.255.224      |
|               | 192.178.09.94  | GigabitEthernet5/7  | 255.255.255.224      |

#### Sede Peten
##### Vlan's
| Departamento  | VLAN | ID Red         |Masacara de subred |
|---------------|------|----------------|------------------ |
| RRHH          | 14   |192.158.09.0/28 | 255.255.255.240   |
| Ventas        | 34   |192.158.09.0/27 | 255.255.255.224   |
| Informatica   | 44   |192.158.09.0/27 | 255.255.255.224   |  

##### IP's
| Departamento  | IP             | Puerto Ethernet     | Máscara de Subred    |
|---------------|----------------|---------------------|----------------------|
| RRHH          | 192.158.09.1   | GigabitEthernet0/0  | 255.255.255.240      |
|               | 192.158.09.2   | GigabitEthernet0/1  | 255.255.255.240      |
|               | 192.158.09.3   | GigabitEthernet0/2  | 255.255.255.240      |
|               | 192.158.09.4   | GigabitEthernet0/3  | 255.255.255.240      |
|               | 192.158.09.5   | GigabitEthernet0/4  | 255.255.255.240      |
|               | 192.158.09.6   | GigabitEthernet0/5  | 255.255.255.240      |
|               | 192.158.09.7   | GigabitEthernet0/6  | 255.255.255.240      |
|               | 192.158.09.8   | GigabitEthernet0/7  | 255.255.255.240      |
|               | 192.158.09.9   | GigabitEthernet0/8  | 255.255.255.240      |
|               | 192.158.09.10  | GigabitEthernet0/9  | 255.255.255.240      |
|               | 192.158.09.11  | GigabitEthernet0/10 | 255.255.255.240      |
|               | 192.158.09.12  | GigabitEthernet0/11 | 255.255.255.240      |
|               | 192.158.09.13  | GigabitEthernet0/12 | 255.255.255.240      |
|               | 192.158.09.14  | GigabitEthernet0/13 | 255.255.255.240      |
| Ventas        | 192.158.09.17  | GigabitEthernet0/14 | 255.255.255.224      |
|               | 192.158.09.18  | GigabitEthernet0/15 | 255.255.255.224      |
|               | 192.158.09.19  | GigabitEthernet0/16 | 255.255.255.224      |
|               | 192.158.09.20  | GigabitEthernet1/1  | 255.255.255.224      |
|               | 192.158.09.21  | GigabitEthernet1/2  | 255.255.255.224      |
|               | 192.158.09.22  | GigabitEthernet1/3  | 255.255.255.224      |
|               | 192.158.09.23  | GigabitEthernet1/4  | 255.255.255.224      |
|               | 192.158.09.24  | GigabitEthernet1/5  | 255.255.255.224      |
|               | 192.158.09.25  | GigabitEthernet1/6  | 255.255.255.224      |
|               | 192.158.09.26  | GigabitEthernet1/7  | 255.255.255.224      |
|               | 192.158.09.27  | GigabitEthernet1/8  | 255.255.255.224      |
|               | 192.158.09.28  | GigabitEthernet1/9  | 255.255.255.224      |
|               | 192.158.09.29  | GigabitEthernet1/10 | 255.255.255.224      |
|               | 192.158.09.30  | GigabitEthernet1/11 | 255.255.255.224      |
|               | 192.158.09.31  | GigabitEthernet1/12 | 255.255.255.224      |
|               | 192.158.09.32  | GigabitEthernet1/13 | 255.255.255.224      |
|               | 192.158.09.33  | GigabitEthernet1/14 | 255.255.255.224      |
|               | 192.158.09.34  | GigabitEthernet1/15 | 255.255.255.224      |
|               | 192.158.09.35  | GigabitEthernet1/16 | 255.255.255.224      |
|               | 192.158.09.36  | GigabitEthernet2/1  | 255.255.255.224      |
|               | 192.158.09.37  | GigabitEthernet2/2  | 255.255.255.224      |
|               | 192.158.09.38  | GigabitEthernet2/3  | 255.255.255.224      |
|               | 192.158.09.39  | GigabitEthernet2/4  | 255.255.255.224      |
|               | 192.158.09.40  | GigabitEthernet2/5  | 255.255.255.224      |
|               | 192.158.09.41  | GigabitEthernet2/6  | 255.255.255.224      |
|               | 192.158.09.42  | GigabitEthernet2/7  | 255.255.255.224      |
|               | 192.158.09.43  | GigabitEthernet2/8  | 255.255.255.224      |
|               | 192.158.09.44  | GigabitEthernet2/9  | 255.255.255.224      |
|               | 192.158.09.45  | GigabitEthernet2/10 | 255.255.255.224      |
|               | 192.158.09.46  | GigabitEthernet2/11 | 255.255.255.224      |
| Informatica   | 192.158.09.49  | GigabitEthernet2/12 | 255.255.255.224      |
|               | 192.158.09.50  | GigabitEthernet2/13 | 255.255.255.224      |
|               | 192.158.09.51  | GigabitEthernet2/14 | 255.255.255.224      |
|               | 192.158.09.52  | GigabitEthernet2/15 | 255.255.255.224      |
|               | 192.158.09.53  | GigabitEthernet2/16 | 255.255.255.224      |
|               | 192.158.09.54  | GigabitEthernet3/1  | 255.255.255.224      |
|               | 192.158.09.57  | GigabitEthernet3/2  | 255.255.255.224      |
|               | 192.158.09.58  | GigabitEthernet3/3  | 255.255.255.224      |
|               | 192.158.09.59  | GigabitEthernet3/4  | 255.255.255.224      |
|               | 192.158.09.60  | GigabitEthernet3/5  | 255.255.255.224      |
|               | 192.158.09.61  | GigabitEthernet3/6  | 255.255.255.224      |
|               | 192.158.09.62  | GigabitEthernet3/7  | 255.255.255.224      |
|               | 192.158.09.63  | GigabitEthernet3/8  | 255.255.255.224      |
|               | 192.158.09.64  | GigabitEthernet3/9  | 255.255.255.224      |
|               | 192.158.09.65  | GigabitEthernet3/10 | 255.255.255.224      |
|               | 192.158.09.66  | GigabitEthernet3/11 | 255.255.255.224      |
|               | 192.158.09.67  | GigabitEthernet3/12 | 255.255.255.224      |
|               | 192.158.09.68  | GigabitEthernet3/13 | 255.255.255.224      |
|               | 192.158.09.69  | GigabitEthernet3/14 | 255.255.255.224      |
|               | 192.158.09.70  | GigabitEthernet3/15 | 255.255.255.224      |
|               | 192.158.09.71  | GigabitEthernet3/16 | 255.255.255.224      |
|               | 192.158.09.72  | GigabitEthernet4/1  | 255.255.255.224      |
|               | 192.158.09.73  | GigabitEthernet4/2  | 255.255.255.224      |
|               | 192.158.09.74  | GigabitEthernet4/3  | 255.255.255.224      |
|               | 192.158.09.75  | GigabitEthernet4/4  | 255.255.255.224      |
|               | 192.158.09.76  | GigabitEthernet4/5  | 255.255.255.224      |
|               | 192.158.09.77  | GigabitEthernet4/6  | 255.255.255.224      |
|               | 192.158.09.78  | GigabitEthernet4/7  | 255.255.255.224      |



#### Sede Izabal
##### Vlan's  
| Departamento  | VLAN | ID Red         |Masacara de subred |
|---------------|------|----------------|------------------ |
| RRHH          | 14   |192.167.09.0/28 | 255.255.255.240   |
| Contabilidad  | 24   |192.167.09.0/29 | 255.255.255.248   |
| Ventas        | 34   |192.167.09.0/27 | 255.255.255.224   | 
##### IP's  
| Departamento  | IP             | Puerto Ethernet     | Máscara de Subred    |
|---------------|----------------|---------------------|----------------------|
| RRHH          | 192.158.09.1   | GigabitEthernet0/0  | 255.255.255.240      |
|               | 192.158.09.2   | GigabitEthernet0/1  | 255.255.255.240      |
|               | 192.158.09.3   | GigabitEthernet0/2  | 255.255.255.240      |
|               | 192.158.09.4   | GigabitEthernet0/3  | 255.255.255.240      |
|               | 192.158.09.5   | GigabitEthernet0/4  | 255.255.255.240      |
|               | 192.158.09.6   | GigabitEthernet0/5  | 255.255.255.240      |
|               | 192.158.09.7   | GigabitEthernet0/6  | 255.255.255.240      |
|               | 192.158.09.8   | GigabitEthernet0/7  | 255.255.255.240      |
|               | 192.158.09.9   | GigabitEthernet0/8  | 255.255.255.240      |
|               | 192.158.09.10  | GigabitEthernet0/9  | 255.255.255.240      |
|               | 192.158.09.11  | GigabitEthernet0/10 | 255.255.255.240      |
|               | 192.158.09.12  | GigabitEthernet0/11 | 255.255.255.240      |
|               | 192.158.09.13  | GigabitEthernet0/12 | 255.255.255.240      |
|               | 192.158.09.14  | GigabitEthernet0/13 | 255.255.255.240      |
| Contabilidad  | 192.158.09.17  | GigabitEthernet0/14 | 255.255.255.248      |
|               | 192.158.09.18  | GigabitEthernet0/15 | 255.255.255.248      |
|               | 192.158.09.19  | GigabitEthernet0/16 | 255.255.255.248      |
|               | 192.158.09.20  | GigabitEthernet1/1  | 255.255.255.248      |
|               | 192.158.09.21  | GigabitEthernet1/2  | 255.255.255.248      |
|               | 192.158.09.22  | GigabitEthernet1/3  | 255.255.255.248      |
| Ventas        | 192.158.09.25  | GigabitEthernet1/4  | 255.255.255.224      |
|               | 192.158.09.24  | GigabitEthernet1/5  | 255.255.255.224      |
|               | 192.158.09.25  | GigabitEthernet1/6  | 255.255.255.224      |
|               | 192.158.09.26  | GigabitEthernet1/7  | 255.255.255.224      |
|               | 192.158.09.27  | GigabitEthernet1/8  | 255.255.255.224      |
|               | 192.158.09.28  | GigabitEthernet1/9  | 255.255.255.224      |
|               | 192.158.09.29  | GigabitEthernet1/10 | 255.255.255.224      |
|               | 192.158.09.30  | GigabitEthernet1/11 | 255.255.255.224      |
|               | 192.158.09.31  | GigabitEthernet1/12 | 255.255.255.224      |
|               | 192.158.09.32  | GigabitEthernet1/13 | 255.255.255.224      |
|               | 192.158.09.33  | GigabitEthernet1/14 | 255.255.255.224      |
|               | 192.158.09.34  | GigabitEthernet1/15 | 255.255.255.224      |
|               | 192.158.09.35  | GigabitEthernet1/16 | 255.255.255.224      |
|               | 192.158.09.36  | GigabitEthernet2/1  | 255.255.255.224      |
|               | 192.158.09.37  | GigabitEthernet2/2  | 255.255.255.224      |
|               | 192.158.09.38  | GigabitEthernet2/3  | 255.255.255.224      |
|               | 192.158.09.39  | GigabitEthernet2/4  | 255.255.255.224      |
|               | 192.158.09.40  | GigabitEthernet2/5  | 255.255.255.224      |
|               | 192.158.09.41  | GigabitEthernet2/6  | 255.255.255.224      |
|               | 192.158.09.42  | GigabitEthernet2/7  | 255.255.255.224      |
|               | 192.158.09.43  | GigabitEthernet2/8  | 255.255.255.224      |
|               | 192.158.09.44  | GigabitEthernet2/9  | 255.255.255.224      |
|               | 192.158.09.45  | GigabitEthernet2/10 | 255.255.255.224      |
|               | 192.158.09.46  | GigabitEthernet2/11 | 255.255.255.224      |
|               | 192.158.09.49  | GigabitEthernet2/12 | 255.255.255.224      |
|               | 192.158.09.50  | GigabitEthernet2/13 | 255.255.255.224      |
|               | 192.158.09.51  | GigabitEthernet2/14 | 255.255.255.224      |
|               | 192.158.09.52  | GigabitEthernet2/15 | 255.255.255.224      |
|               | 192.158.09.53  | GigabitEthernet2/16 | 255.255.255.224      |
|               | 192.158.09.54  | GigabitEthernet3/1  | 255.255.255.224      |

## Topología de Red

### Sede Jutiapa
![SJutiapa](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/SJutiapa.png)
### Sede Escuintla
![SEscuintla](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/SEscuintla.png)
### Sede Quiche
![SQuiche](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/SQuiche.png)
### Sede Petén
![SPetén](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/SPeten.png)
### Sede Izabal
![SIzabal](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/SIzabal.png)
### Firewall
![Firewall](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/Firewall.png)
### Core
![Core](https://github.com/MRICHARDA/redes1_202102894/blob/b07fa482f8f5bfd5f67cdeab912300fd6dead87e/Proyecto2/images/Core.png)

## Detalle de los comandos usados
-  ##### Comandos para configurar el sw1.
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

-  ##### Comandos para la configuración de vlan's para los sw2 al sw13

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


-  ##### Comandos para configurar el modo trunk y el dominio en los sw2 al sw13.
enable  
configure terminal  
vtp domain P9  
vtp password usac  
vtp mode client  
enable  
configure terminal  
interface range fa0/1-#  
switchport trunk encapsulation dot1q  
switchport mode trunk  
switchport trunk allowed vlan 28,38,48,58  
exit  
exit  

-  ##### Comando para configurar el SW9 
enable  
configure terminal  
vtp domain P9  
vtp password usac  
vtp mode transparent  

-  ##### Comando para validar el modo stp en los switch
enable  
show spanning-tree  
