# Digitalizza_2019-20

Scripts finales que entregue en el curso DEVNET de la beca Digitaliza de Cisco con PUE (2019/20).

- 01 - Crear carpeta publica en github: la primera practica, solo esta el acceso directo al repositorio.
- 02 - Calculadora: calculadora con menu que suma, resta, multiplica, divide, hace potencias y raices cuadradas.
- 03 - APIC_EM: programa con menu que se conecta al controlador APIC-EM del sandbox de Cisco y saca los dispositivos, hosts, vlans, topologia, etc.
- 04 - CSR1000V: script para el router CSR1000v que lista, crea y borra interfaces y hace consultas por netconf/yang.

Estan hechos con python 3.8 en windows (usan msvcrt) y las librerias que hacen falta son requests, netmiko, ncclient, xmltodict y tabulate. El de APIC-EM seguramente ya no funcione porque Cisco lo retiro.
