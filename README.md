# CCNA-Mega-Lab

# Topologia
![lab](ccna.PNG)

# comandos a usar
```
enable
configure terminal
interface vlan 1
interface GigabitEthernet0/1
ip address 192.168.1.1 255.255.255.0
no shutdown
switchport mode access
switchport access vlan 10
switchport trunk encapsulation dot1q
switchport mode trunk
vlan 10
name VLAN10
ip default-gateway 192.168.1.254
show vlan brief
show interfaces trunk
show mac address-table
```
