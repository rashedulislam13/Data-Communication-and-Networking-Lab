Experiment No:01
Experiment Name: Configure Local Area Network (Wired)
Required Software: Cisco Packet Tracer 

Equipment:
1.	Cisco Packet Tracer
2.	4 PCs
3.	1 Switch
4.	UTP cables (Copper Straight-Through)

Description: A Wireless Local Area Network (WLAN) is a network that allows devices to communicate over a wireless connection within a limited area, such as a home, school, or office. In this experiment, we will configure a wireless LAN using Cisco Packet Tracer. The objective is to set up a wireless router, connect multiple devices via Wi-Fi, and ensure secure communication through proper encryption settings. We will verify the configuration by checking the connectivity and using the ping command to test communication between devices.

Configuration Procedure:
To configure LAN, we need to following steps.  












#Procedure:
(1). Drag and Drop a switch on CISCO Packet Tracer interface.
(2). Take some end device which supports NIC Card with RJ45 connector.
(3). Choose Copper "Straight Through" UTP Cable for connect ion. (4). Click on switch and select the specific port no for new connection.
(5). Repeat procedure (4) as much your end device remain connection less.
(6). Double click on an end device and you can see this interface is by default on "Physical" tab.

(8). Put IP Address and Click on submit section Subnet Mask will take automatically.
 (9). Just close the section. 
(10). Put IP Address on all the remaining end device.

#Simulation Process: 
(#) first way: 
(1). Select a packet from right side bar. Mouse pointer will change with packet symbol. 
(2). Select first a PC and then select another PC with packet symbol pointer. 
(3). It implies that a packet will flow from first device to second device.  
(4). Then you can see successful notification right side bottom section. 
(#). Second way: 
(5). Double click on PC, select “Desktop” tab, Click on “Command Prompt” 
(6). for example, this pc with 192.168.1.1 and it will ping 192.168.1.2 
(7). write down “ping 192.168.1.2” press enter. 
(8). if your physical and logical connection is ok then it will say that... 
Packet Send=4 Packet Received=4  
Packet Lost=0%




Experiment No: 02 
Name of the Experiment: Configure Local Area Network (Wireless).
Required Software: Cisco Packet Tracer.

Equipment:
1.	Router (Linksys-WRT300N) 
2.	End Device (Desktop, Laptop, TabletPC, PDAetc) 
3.	IP Address (192.168.1.0)

Description: A Wireless Local Area Network (WLAN) allows devices to connect and communicate over a wireless connection within a limited area. In this experiment, we will set up a wireless LAN using Cisco Packet Tracer by configuring a wireless router or access point. The objective is to connect devices to the WLAN, secure the network with encryption, and verify communication between devices using the ping command.

Configuration Procedure:
To configure WLAN, we need to following steps
#Procedure:
(1). Drag and Drop a wireless router some device which support wireless communication on 
CISCO Packet Tracer interface. 
(#). For Desktop PC 
(2). Double click on PC-PT then by default “Physical” tab. first power off your pc. We need to add 
Linksys-WMP300N Module on this pc. 
(3). Replace existing module with our “Linksys-WMP300N” module. 
(4). power on your device. 
(#). For laptop same procedure will apply. Now desktop and laptop are ready to communicate 
over wireless media. 
(#). Router configuration: 
(5). Double Click and go to “Config” tab. Then select wireless. 
(6). now give a name to your access point (SSID)  
(7). Select an authentication type. By default, it will Disabled we will check out “WPA-PSK” 
and set password 88888888 and close it.
(8). double click on desktop pc and open “PC Wireless” from “Desktop” tab. 
(9). click on “Connect” tab by default it will link information. Press “Refresh” button. 
(10). Then we will see an access point and press “Connect” button. 
(11). put your password of network on “Pre-Shared key” and then connect. Same on Laptop 
(#) Config for PDA 
(12). Double click on it and then select “Config” tab and also “Wireless” from left bottom. 
(13). put your Access point name (SSID) and password “WPA-PSK” and close it. Same for Tablet.


#Simulation Process: 
(#) first way: 
(1). Select a packet from right side bar. Mouse pointer will change with packet symbol. 
(2). Select first a PC and then select another PC with packet symbol pointer. 
(3). It implies that a packet will flow from first device to second device.  
(4). Then you can see successful notification right side bottom section. 

(#). Second way: 
(5). Double click on PC, select “Desktop” tab, Click on “Command Prompt” 
(6). for example, this pc with 192.168.1.1 and it will ping 192.168.1.2 
(7). write down “ping 192.168.1.2” press enter. 
(8). if your physical and logical connection is ok then it will say that... 
Packet Send=4 Packet Received=4   Packet Lost=0% 
(#). Third way: access router control panel through end device 
(9) Double click on desktop or laptop then selects “Web Browser” from “Desktop” tab.
(10). write down router ip address on browser address bar and press inter. 
(11). A command prompt will appear for authentication give username and password admin. 
(12). If everything is ok, then you will allow to access on router.


Experiment No.: 03 
Name of the Experiment: Transfer packets through two different networks.
Required Software: Cisco Packet Tracer.

Equipment:
1.	Switch.
2.	UTP Cable (Straight Through). 
3.	End Device (Desktop, Laptop etc).
4.	IP Address.

Description: This experiment focuses on transferring data packets across different network segments using routers to facilitate communication. In Cisco Packet Tracer, we will configure multiple routers to enable data transfer between distinct networks. The goal is to observe how packets are routed, ensure correct routing paths, and verify the setup using the ping command and traceroute tool.

Configuration Procedure:
To configure Transfer packets through two different networks., we need to following steps:

Design Network:


Procedure: 
(1). Drag and Drop two switch one router and 2 end device. 
(2). Select cable and connect two switches through router and then end device will be connected with switch. 
(3). Double click on router, here this router by default two interface fa 0/0 and fa 0/1. those two interface are connected two different switches also two different networks. 
(4). Click on CLI type no on the text edit option.  
(5). If you press yes, then router will ask several questions for his system maintains but all of those are not usable to us. So, we just type no. 
(6). Router stay normally three stages. one is privilege mode then global config and Finlay specific configuration 
(7).  Now we are in privilege mode to promote global config type enable and press enter then you can see it’s router symbol will change 
(8). we are now global configuration mode, so we need to access specific interface and configure it. 
(9). just write down “interface fa 0/0” this is for interface 0/0 of router. Then it needs to add ip 
address so that just type e.g “ip address 192.168.1.” then put subnet musk 255.255.255.0 
(10). By default, every interface of Cisco device down state. So, we need it to up. just write down “no shut” command.
(11). Go back to privilege mode by “exit” command. 
(12). Finally write down “wr” to save configuration 
(13). We just configured only one interface. we need another one of different network with 
different ip address. 
(14). After configuring the router, we need to mention ip address of each end device.

CLI Procedure:  
Continue with configuration dialog? [yes/no]: no 
Press RETURN to get started! 
Router>enable  
Router#configure terminal  
Router(config)#interface fastEthernet 0/0 
Router(config-if)#ip address 192.168.1.1 255.255.255.0 
Router(config-if)#no shutdown  
%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up 
%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to up 
Router(config-if)#exit 
Router(config)#interface fastEthernet 0/1 
Router(config-if)#ip address 192.168.2.1 255.255.255.0 
Router(config-if)#no shutdown  
Router(config-if)# 
%LINK-5-CHANGED: Interface FastEthernet0/1, changed state to up 
%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/1, changed state to up 
Router(config-if)#exit 
Router(config)#exit 
Router# 
%SYS-5-CONFIG_I: Configured from console by console 
Router#wr 
Building configuration... 
[OK] 
Router#



#Simulation Process: 
(#) first way: 
(1). Select a packet from right side bar. Mouse pointer will change with packet symbol. 
(2). Select first a PC and then select another PC with packet symbol pointer. 
(3). It implies that a packet will flow from first device to second device.  
(4). Then you can see successful notification right side bottom section.



Experiment No.: 04 
Name of the Experiment: Dynamic IP through DHCP.
Required Software: Cisco Packet Tracer.

Equipment:
1.	Switch 
2.	UTP Cable (Straight Through) 
3.	End Device (Desktop, Laptop etc) 
4.	IP Address (192.168.1.0) 
5.	Router.

Description: Dynamic Host Configuration Protocol (DHCP)  is used to automatically assign IP addresses to devices on a network. In this experiment, we will configure a DHCP server in Cisco Packet Tracer to provide dynamic IP addresses for connected devices. The goal is to set up the server with an IP address range, lease time, and other settings, then verify that devices are receiving IP addresses automatically and can communicate within the network using the ping command.

Configuration Procedure:
To configure Dynamic IP through DHCP, we need to following steps:



#Procedure: 
(1). Drag and Drop one switch one router and 3 or more end device.  
(2). Connect them UTP Straight Through Cable .
(3). Double click on router and then click on CLI Mode .
(4). Enter privilege then global configuration mode. 
(5). Access an interface such as fa 0/0. 
(6). Assign ip and subnet musk then “no shut” to up this state. 
(7). Exit from here to global configuration mode.
(8). Write down the command “ipdhcp pool myPoleName”. 
(9). Mention the network and then router default ip. 
(10). Exit and save change. 
(11) Double click on selects “Desktop” and click on “IP configuration”.
(12). Click on DHCP to send a request for ip.


Figure-02: PC0 IP address and gateway setup.
CLI Procedure:  
Continue with configuration dialog? [yes/no]: no 
Press RETURN to get started! 
Router>enable  
Router#configure terminal  
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#interface fastEthernet 0/0 
Router(config-if)#ip address 192.168.1.1 255.255.255.0 
Router(config-if)#no shutdown  
%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up 
%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to up
Router(config-if)#exit 
Router(config)#ip dhcp pool ice  
Router(dhcp-config)#network 192.168.1.0 255.255.255.0 
Router(dhcp-config)#default-router 192.168.1.1 
Router(dhcp-config)#exit 
Router(config)#exit 
Router# 
%SYS-5-CONFIG_I: Configured from console by console 
Router#wr 
Building configuration... 
[OK] 
Router#


#Simulation Process: 
(#) first way: 
(1). Select a packet from right side bar. Mouse pointer will change with packet symbol. 
(2). Select first a PC and then select another PC with packet symbol pointer. 
(3). It implies that a packet will flow from first device to second device.  
(4). Then you can see successful notification right side bottom section.




Experiment No.: 05 
Name of the Experiment: Configure Routing Information Protocol (RIP). 
Required Software: Cisco Packet Tracer.

Equipment:
1.	Switch.
2.	UTP Cable (Straight Through). 
3.	Ethernet crossover cable.
4.	End Device (Desktop, Laptop etc).
5.	Router.

Description: Routing Information Protocol (RIP) is a distance-vector routing protocol that helps routers exchange information to dynamically update their routing tables. In this experiment, we will configure RIP on routers using Cisco Packet Tracer to facilitate communication across multiple networks. The objective is to establish and verify routing information, ensuring that data can be transferred between networks by testing connectivity with the ping command.

Configuration Procedure:
To Configure Routing Information Protocol (RIP), we need to following steps:


#Procedure: 
(1). Drag and Drop Routers, Switches and PCs. 
(2). Select cable and make sure a proper connection. 
(3). Double click on router. 
(4). Click on CLI Tab.  
(5).  First assign IP Address of on interface 
(6).  Assign RIP command.  
(7).  Mention RIP version 
(8).  Finally save this configuration.
Figure-02: PC0 IP address and gateway setup.
	Figure-03: PC1 IP address and gateway setup.


IP Configuration Router0:
Router>en 
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#interface gig 0/0 
Router(config-if)#ip address 192.168.1.1 255.255.255.0 
Router(config-if)#no shutdown
 
Router(config-if)# 
%LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to up 
 
Router(config-if)#exit 
Router(config)#interface gig 0/1 
Router(config-if)#ip add 192.168.2.1 255.255.255.0 
Router(config-if)#no shutdown 
Router(config-if)#exit 





IP Configuration Router1:
Router>en 
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#interface gig 0/0 
Router(config-if)#ip address 192.168.1.2 255.255.255.0 
Router(config-if)#no shutdown
 
Router(config-if)# 
%LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to up 
 
Router(config-if)#exit 
Router(config)#interface gig 0/1 
Router(config-if)#ip add 192.168.3.1 255.255.255.0 
Router(config-if)#no shutdown 
Router(config-if)#exit 

RIP Configuration Router0:
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#router RIP  
Router(config-router)#version 2 [same for all routers] 
Router(config-router)#net 192.168.1.0 
Router(config-router)#net 192.168.2.0  
Router(config-router)#exit 
Router(config)#exit 
Router# 
Router#wr 
Building configuration... 
[OK] 

RIP Configuration Router1:
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#router RIP  
Router(config-router)#version 2 [same for all routers] 
Router(config-router)#net 192.168.1.0 
Router(config-router)#net 192.168.3.0  
Router(config-router)#exit 
Router(config)#exit 
Router# 
Router#wr 
Building configuration... 
[OK]  

Simulation Process Router0:
Router# 
Router#showip route 
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP 
D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area 
N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2 
E1 - OSPF external type 1, E2 - OSPF external type 2, E - EGP 
i - IS-IS, L1 - IS-IS level-1, L2 - IS-IS level-2, ia - IS-IS inter area 
* - candidate default, U - per-user static route, o - ODR 
P - periodic downloaded static route 
Gateway of last resort is not set 
192.168.1.0/24 is variably subnetted, 2 subnets, 2 masks 
C       192.168.1.0/24 is directly connected, GigabitEthernet0/0 
L     
  192.168.1.2/32 is directly connected, GigabitEthernet0/0 
R    192.168.2.0/24 [110/2] via 192.168.1.1, 00:00:07, GigabitEthernet0/0 
192.168.3.0/24 is variably subnetted, 2 subnets, 2 masks 
C       192.168.3.0/24 is directly connected, GigabitEthernet0/1 
L     
  192.168.3.1/32 is directly connected, GigabitEthernet0/1

    









Name of the Experiment: 06 
Name of the Experiment: Configure Open Shortest Path First (OSPF) Routing Protocol.
Required Software: Cisco Packet Tracer.

Equipment:
1.	Switch 
2.	UTP Cable (Straight Through) 
3.	Ethernet crossover cable
4.	End Device (Desktop, Laptop etc) 
5.	Router.

Description: Open Shortest Path First (OSPF) is a link-state routing protocol used to find the shortest path for data packets in a network. In this experiment, we will set up OSPF on routers in Cisco Packet Tracer, configuring areas and enabling OSPF on specific interfaces. The goal is to observe neighbour relationships and link-state advertisements, verify OSPF routing tables, and test network connectivity using the ping command.

Configuration Procedure:
To Configure Open Shortest Path First (OSPF) Routing Protocol, we need to following steps:


#Procedure: 
(1). Drag and Drop Routers, Switches and PCs. 
(2). Select cable and make sure a proper connections. 
(3). Double click on router. 
(4). Click on CLI Tab.  
(5).  First assign IP Address of on interface 
(6).  Assign OSPF command. (ospf then numerical value such as 1,2,3 ) 
(7).  Mention Network then Wild card mask then area. 
(8).  Finally save this configuration.

 
Figure-02: PC0 IP address and gateway setup.

	 
Figure-03: PC1 IP address and gateway setup.

IP Configuration Router0:
Router>en 
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#interface gig 0/0 
Router(config-if)#ip address 192.168.1.1 255.255.255.0 
Router(config-if)#no shutdown 
Router(config-if)# 
%LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to up 
Router(config-if)#exit 
Router(config)#interface gig 0/1 
Router(config-if)#ip address 192.168.2.1 255.255.255.0 
Router(config-if)#no shutdown

IP Configuration Router1:
Router>en 
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#interface gig 0/0 
Router(config-if)#ip address 192.168.1.2 255.255.255.0 
Router(config-if)#no shutdown
 
Router(config-if)# 
%LINK-5-CHANGED: Interface GigabitEthernet0/0, changed state to up 
 
Router(config-if)#exit 
Router(config)#interface gig 0/1 
Router(config-if)#ip add 192.168.3.1 255.255.255.0 
Router(config-if)#no shutdown 
Router(config-if)#exit

OSPF Configuration Router0:
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#router ospf 1 
Router(config-router)#network 192.168.1.0 0.0.0.255 area 0   
Router(config-router)#network 192.168.2.0 0.0.0.255 area 0     
Router(config-router)#exit     
Router(config)#exit     
Router#      
Router#wr 
Building configuration... 
[OK]

OSPF Configuration Router1:
Router#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z. 
Router(config)#router ospf 1 
Router(config-router)#network 192.168.1.0 0.0.0.255 area 0   
Router(config-router)#network 192.168.3.0 0.0.0.255 area 0     
Router(config-router)#exit     
Router(config)#exit     
Router#      
Router#wr 
Building configuration... 
[OK]
 

Simulation Process Router0:
Router#show ip route
Codes: L - local, C - connected, S - static, R - RIP, M - mobile, B - BGP
       D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area
       N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2
       E1 - OSPF external type 1, E2 - OSPF external type 2, E - EGP
       i - IS-IS, L1 - IS-IS level-1, L2 - IS-IS level-2, ia - IS-IS inter area
       * - candidate default, U - per-user static route, o - ODR
       P - periodic downloaded static route

Gateway of last resort is not set

     192.168.1.0/24 is variably subnetted, 2 subnets, 2 masks
C       192.168.1.0/24 is directly connected, GigabitEthernet0/0
L       192.168.1.1/32 is directly connected, GigabitEthernet0/0
     192.168.2.0/24 is variably subnetted, 2 subnets, 2 masks
C       192.168.2.0/24 is directly connected, GigabitEthernet0/1
L       192.168.2.1/32 is directly connected, GigabitEthernet0/1
O    192.168.3.0/24 [110/2] via 192.168.1.2, 00:05:49, GigabitEthernet0/0




Name of the Experiment: 07 
Name of the Experiment: Configure Enhanced Interior Gateway Routing Protocol (EIGRP).
Required Software: Cisco Packet Tracer.

Equipment:
1.	Switch 
2.	UTP Cable (Straight Through) 
3.	Serial DCE cable 
4.	End Device (Desktop, Laptop etc.) 
5.	Router.

Description: Enhanced Interior Gateway Routing Protocol (EIGRP) is an advanced distance-vector routing protocol that uses metrics such as bandwidth and delay for path selection. In this experiment, we will configure EIGRP on routers using Cisco Packet Tracer to enable dynamic routing within a specified autonomous system. The aim is to set up EIGRP interfaces, verify routing information exchange, and test the network's connectivity with the ping command.

Configuration Procedure:
To Configure Enhanced Interior Gateway Routing Protocol (EIGRP), we need to following steps:



#Procedure: 
(1). Drag and Drop Routers (2811), Switches and PCs. 
(2). Double click on router then by default “Physical” tab. first power off your router. We need to add WIC-!T Module on this router.Then power on your router.
 
Figure -02: Router0 Physical setup.
(3). Select cable and make sure a proper connection. 
(4). Double click on router. 
(5). Click on CLI Tab.  
(6).  First assign IP Address of on interface 
(7).  Assign EIGRP command. ( eigrp then numerical value such as 1,2,3 ) 
(8).  Mention network then subnet mask. 
(9).  Finally save this configuration.

Figure-02: PC1 IP address and gateway setup.
	
CLI Configuration (Router0):
Router>enable 
Router#configure terminal  
Enter configuration commands, one per line. End with CNTL/Z. 
Router(config)#interface fastEthernet 0/0 
Router(config-if)#ip address 192.168.10.1 255.255.255.0 
Router(config-if)#no shutdown
Router(config-if)# 
%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up 
%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to 
up 
Router(config-if)#exit 
Router(config)#interface serial 0/0/0 
Router(config-if)#ip address 192.168.20.1 255.255.255.0 
Router(config-if)#clock rate 128000 
Router(config-if)#no shutdown 
%LINK-5-CHANGED: Interface Serial0/0/0, changed state to down 
Router(config-if)#exit 
Router(config)#exit 
Router# 
%SYS-5-CONFIG_I: Configured from console by console 
Router#copy running-config startup-config  
Destination filename [startup-config]?  
Building configuration... 
[OK] 
Router#

CLI Configuration (Router1):
Router>enable 
Router#configure terminal  
Enter configuration commands, one per line. End with CNTL/Z. 
Router(config)#interface fastEthernet 0/0 
Router(config-if)#ip address 192.168.30.1 255.255.255.0 
Router(config-if)#no shutdown 
Router(config-if)# 
%LINK-5-CHANGED: Interface FastEthernet0/0, changed state to up 
%LINEPROTO-5-UPDOWN: Line protocol on Interface FastEthernet0/0, changed state to 
up 
Router(config-if)#exit 
Router(config)#interface serial 0/0/0 
Router(config-if)#ip address 192.168.20.2 255.255.255.0
Router(config-if)#no shutdown 
Router(config-if)# 
%LINK-5-CHANGED: Interface Serial0/0/0, changed state to up 
Router(config-if)#exit 
Router(config)#exit 
Router# 
%SYS-5-CONFIG_I: Configured from console by console 
Router# 
%LINEPROTO-5-UPDOWN: Line protocol on Interface Serial0/0/0, changed state to up 
Router#copy running-config startup-config  
Destination filename [startup-config]?  
Building configuration... 
[OK] 
Router#




# EIGRP Configuration Router0 :
Router#configure terminal  
Enter configuration commands, one per line. End with CNTL/Z. 
Router(config)#router eigrp 10 
Router(config-router)#network 192.168.10.0 255.255.255.0 
Router(config-router)#network 192.168.20.0 255.255.255.0 
Router(config-router)#^Z 
Router# 
%SYS-5-CONFIG_I: Configured from console by console 
Router#copy running-config startup-config  
Destination filename [startup-config]?  
Building configuration... 
[OK] 
Router#

# EIGRP Configuration Router1 :
Router#configure terminal  
Enter configuration commands, one per line. End with CNTL/Z. 
Router(config)#router eigrp 10 
Router(config-router)#network 192.168.20.0 255.255.255.0 
Router(config-router)# 
%DUAL-5-NBRCHANGE: IP-EIGRP 10: Neighbor 192.168.20.1 (Serial0/0/0) is up: new 
adjacency 
Router(config-router)#network 192.168.30.0 255.255.255.0 
Router(config-router)#^Z 
Router# 
%SYS-5-CONFIG_I: Configured from console by console 
Router#copy runn 
Router#copy running-config st 
Router#copy running-config startup-config  
Destination filename [startup-config]?  
Building configuration... 
[OK] 
Router#

# Simulation Process: (Router0):
Router#show ip route 
Codes: C - connected, S - static, I - IGRP, R - RIP, M - mobile, B - BGP 
D - EIGRP, EX - EIGRP external, O - OSPF, IA - OSPF inter area 
N1 - OSPF NSSA external type 1, N2 - OSPF NSSA external type 2 
E1 - OSPF external type 1, E2 - OSPF external type 2, E - EGP 
i - IS-IS, L1 - IS-IS level-1, L2 - IS-IS level-2, ia - IS-IS inter area 
* - candidate default, U - per-user static route, o - ODR 
P - periodic downloaded static route 
Gateway of last resort is not set 
C 192.168.10.0/24 is directly connected, FastEthernet0/0 
C 192.168.20.0/24 is directly connected, Serial0/0/0 
D 192.168.30.0/24 [90/20514560] via 192.168.20.2, 00:12:51, Serial0/0/


Name of the Experiment: 08 
Name of the Experiment: Configure Virtual Local Area Network (VLAN).
Required Software: Cisco Packet Tracer .
Equipment:
1.	Cisco Packet Tracer
2.	1 Switch
3.	4 PCs
4.	UTP cables (Copper Straight-Through).
Description: A Virtual Local Area Network (VLAN) is a logical network segment that groups devices from different physical networks into a single virtual network, allowing for better traffic management and network segmentation. VLANs are commonly used in larger business networks to optimize communication and improve performance. They can be implemented across various physical network types, such as Ethernet and Wi-Fi. By configuring VLANs, network traffic can be handled more efficiently, as communication within the same VLAN is managed by network switches rather than passing through central routers. This setup reduces congestion and enhances network speed. Additionally, VLANs increase security by isolating traffic, ensuring that devices in different VLANs cannot communicate directly. This feature is particularly useful for scenarios like setting up separate guest networks.
In this experiment, two switches are deployed in different physical locations within the same network, each connected to four PCs—two belonging to the IT department and two to the HR department. The objective is to configure the network so that PCs within the same department can communicate seamlessly, despite being connected to different switches, thereby demonstrating the benefits of VLAN segmentation.
IP addresses assigned to each department are given below:
IT department                         198.168.1.1-198.168.1.10
HR department                       198.168.1.11-198.168.1.20

Configuration Procedure:  
To Configure Enhanced Interior Gateway Routing Protocol (EIGRP), we need to following steps:


Procedure:
1. Open Cisco Packet Tracer.
2. Pick up two switches from the network devices.
3. We have picked up four PCs for each switch from end devices. 
4. Connect the switches with each other using Copper Cross-Over.
5. Connect remaining components using Copper Straight-Through.
6. Let us consider the name of the VLAN under IT department as "vlan 10" and VLAN under HR department as "vlan 20".
7. In figure 01 we have indicated the IT department's PCs and HR department's PCs as desired.



CLI Configuration (Switch0 and Switch2):
Switch>en
Switch#configure terminal
Enter configuration commands, one per line.  End with CNTL/Z.
Switch(config)#VLAN 10
Switch(config-vlan)#name IT
Switch(config-vlan)#exit 
Switch(config)#VLAN 20
Switch(config-vlan)#name HR
Switch(config-vlan)#exit
Switch(config)#exit
Switch#show VLAN brief
Switch#configure terminal 
Enter configuration commands, one per line.  End with CNTL/Z.
Switch(config)#interface fastEthernet 0/1
Switch(config-if)#switchport access VLAN 10
Switch(config-if)#exit
Switch(config)#interface fastEthernet 0/2
Switch(config-if)#switchport access VLAN 10
Switch(config-if)#exit

Switch(config)#interface fastEthernet 0/3
Switch(config-if)#switchport access VLAN 20
Switch(config-if)#exit
Switch(config)#interface fastEthernet 0/4
Switch(config-if)#switchport access VLAN 20
Switch(config-if)#exit
Switch(config)#exit
Switch#show VLAN brief 

VLAN Configuration (Switch0 and Switch1):
Switch#configure terminal
Enter configuration commands, one per line.  End with CNTL/Z.
Switch(config)#interface fastEthernet 0/5
Switch(config-if)#switchport mode trunk

Switch(config-if)#exit
Switch(config)#interface range fastEthernet 0/1-fastEthernet 0/4
Switch(config-if-range)#switch mode access
Switch(config-if-range)#exit


Simulation Process Switch0 and Switch1:
Switch#show VLAN brief

VLAN Name                             Status    Ports
---- -------------------------------- --------- -------------------------------
1    default                              active    Fa0/5, Fa0/6, Fa0/7, Fa0/8
                                                Fa0/9, Fa0/10, Fa0/11, Fa0/12
                                                Fa0/13, Fa0/14, Fa0/15, Fa0/16
                                                Fa0/17, Fa0/18, Fa0/19, Fa0/20
                                                Fa0/21, Fa0/22, Fa0/23, Fa0/24
                                                Gig0/1, Gig0/2
10   IT                                     active    Fa0/1, Fa0/2
20   HR                                   active    Fa0/3, Fa0/4
1002 fddi-default                    active    
1003 token-ring-default          active    
1004 fddinet-default               active    
1005 trnet-default                   active  

