# Hotel-Network-Management

#Problem Statement
You are required to design and and implement Vic Modern Hotel Network. The hotel has three floors; in the first floor there are three departments (Reception, Store, and Logistics) , in the second floor there are three departments (Finance, HR, and Sales) , while the third floor hosts the IT and Admin. Therefore, the following are part of the considerations during the design and implementation.

1. There should be three routers connecting each floor (all placed in the server room in IT department)
2. All routers should be connected to each other using serial DCE cable.
3. The network between routers should be 10.10.10.0/30 , 10.10.10.4/30, 10.10.10.8/30
4. Each floor is expected to have one switch (placed in respective floor)
5. Each department is expected to have a printer
6. Each dept is expected to be in different VLAN with the following details:
   1st Floor:
   >> Reception- VLAN 80, Network of 192.168.8.0/24
   >> Store- VLAN 70, Network of 192.168.7.0/24
   >> Logistics- VLAN 60, Network of 192.168.6.0/24

   2nd Floor:
   >> Finance- VLAN 50, Network of 192.168.5.0/24
   >> HR- VLAN 40, Network of 192.168.4.0/24
   >> Sales- VLAN 30, Network of 192.168.3.0/24

   3rd Floor:
   >> Admin- VLAN 20, Network of 192.168.2.0/24
   >> IT- VLAN 10, Network of 192.168.1.0/24

7. Use OSPF as the routing protocol to advertise routes
8. All devices in the network are required to obtain IP Address dynamically with their respective router configured as the DHCP server
9. All the devices in the network are expected to communicate with other.
