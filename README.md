# Packet-Tracer---Modify-Single-Area-OSPFv2
Scenario In this activity, OSPF is already configured and all end devices currently have full connectivity. You will modify the default OSPF routing configurations by changing the hello and dead timers and adjusting the bandwidth of a link. Then you will verify that full connectivity is restored for all end devices.
Objectives
Part 1: Modify OSPF Default Settings
Part 2: Verify Connectivity


On cisco routers you can change the cost of an ospf path by chaning the bandwidth. But you can also use another command that does almost the same thing. But you are just manualy setting the cost, inssted on making the devices run spf algorithm, you can set the cost. for example you can use this command.
int g0/0 
ip ospf cost 200 

just take note that the commands do the same thing but in a different way. One adjusts the bandwidth and the other changes the cost manually.

![image](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/92abc483-6724-4a61-ada1-479107be6056)
![Screenshot (146)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/ee73b359-4795-4816-af72-d6bf199e7dcc)
![Screenshot (145)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/e1a6a766-7b36-47f8-a007-bad8c843576c)
![Screenshot (144)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/0271a184-d2ed-4044-a1ec-58ed7c0e93c0)
![Screenshot (143)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/baf8686c-55bd-4778-b8f8-2b3204d95ead)
![Screenshot (142)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/ddf234d8-0c04-44e6-9f34-25ed9b3ad0b6)
![Screenshot (141)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/ec7f8c8b-f135-4c77-a7b4-ad929039bfef)
![Screenshot (140)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/60d15389-3d90-4675-90d4-8ecd15ed5326)
![Screenshot (139)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/03a178cb-fc6b-47ef-805e-58ac1afed35f)
![Screenshot (138)](https://github.com/AZGANG/Packet-Tracer---Modify-Single-Area-OSPFv2/assets/128199477/4095c67c-2f47-48d1-9735-5acbbfbab930)
