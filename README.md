#CPT Projects:

CySecAss1(i)
  Configure LAN with IP address (different Networks)

Procedures:

I.Creating a New Packet Tracer Project
  
    1.Launch Packet Tracer:

    Open the Packet Tracer application on your computer.

    2.Create a New Project:

    Click on “File” and then select “New” to start a new Packet Tracer project.

II.Designing the LAN Topology

    #In this example, we’ll configure a simple LAN consisting of two computers connected to a switch. Follow these steps to design the topology:

    1.Add Devices:

    From the left panel, drag and drop devices onto the workspace. For our basic LAN, use PCs as end devices and a switch to connect them.

    2.Connect Devices:

    Use copper straight-through cables to connect the PCs to the switch. Click on the “Connections” button on the left panel, select the copper straight-through cable, and connect the devices by clicking on the desired interfaces on the PC0 select fa0 and drag to switch fa0/1 like wise for PC1

    3.Arrange Devices:

    Organize the devices on the workspace for a clear and logical layout. This step is optional but can enhance the visual representation of your network.

III.Configuring IP Addresses on PCs

    #For devices in a LAN to communicate, each device must have a unique IP address within the same subnet. Follow these steps to configure IP addresses on the PCs:

    1.Select a PC:

    Click on one of the PCs to select it.

    2.Access Configuration Tab:

    Click on the “Config” tab at the bottom of the screen to access the configuration options for the selected PC.

    3.Assign IP Address:

    Manually assign an IP address to the PC. For example:
        PC1: IP – 192.168.10.2
        PC2: IP – 192.168.10.3
    Set the subnet mask, such as 255.255.255.0.

    4.Repeat for Other PCs:

    Repeat the process for the other PCs, ensuring that each PC has a unique IP address within the same subnet

IV.Check the Connection

    1.Select the PC0 double click to enter configuration goto command prompt ping the ip address of PC1 to check the connection "ping 192.168.10.2"
    if you get reply then the connection is alive else recheck the above steps


![Screenshot (2)](https://github.com/danielbrain2003/Projects/assets/146718471/5cea2c62-b5db-42dd-b9f6-4977c3ad2bc6)

  
CySecAss1(ii)
  Configure two networks with different classes of IP
  
![Screenshot (3)](https://github.com/danielbrain2003/Projects/assets/146718471/7fce2274-27bb-4e8a-8797-602c607d3bfb)
  

CySecAss1(iii)
  Configure OSPF Protocol and Router

![Screenshot (4)](https://github.com/danielbrain2003/Projects/assets/146718471/1dfa77fc-7a64-4d58-bb87-ac1b0be5f598)
  
