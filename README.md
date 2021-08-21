# Ansible-EveNG
Network Automation using Ansible on EVE NG

![image](https://user-images.githubusercontent.com/84218572/130321778-0a9cad14-193e-450e-ab24-12a168371d78.png)

In the above topology the Linux VM is being used as the Ansible control machine.
Routers R1 and R2 as PE routers
Routers R3 and R4 as CE routers
Switches SW01 and SW02 as Core Switches
Switch Sw5 as the Access switch

This is a typical campus site topology which will be configured using Ansible as per below

R1-R2, R3-R4 iBGP peers
R1-R3, R1-R4, R2-R3, R2-R4 being eBGP Peers


