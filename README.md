


<h1>Setting up Windows and Linux Virtual Machines (Microsoft Azure)</h1>
Hello and welcome to this tutorial on setting up Virtual Machines in Azure! We will focus on creating the necessary resources, including a Resource Group, a Windows 10 Virtual Machine, and a Linux (Ubuntu) Virtual Machine in Microsoft Azure.
.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to Deploy on-premises Active Directory within Azure Compute](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)
- 
<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Ubuntu Linux (20.04 LTS)
![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/7d03878b-62f3-46fb-8e1d-a865de8e0cdf)
![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/7d3307be-d928-4b88-ad60-d56e43fa55a2)


<h2>Deployment and Configuration Steps</h2>


Step 1: Create a Resource Group
1.1. Open the Azure portal (https://portal.azure.com/) and log in to your Azure account.

1.2. In the left navigation pane, click on "Resource groups."

1.3. Click the "+ Add" button to create a new Resource Group.

1.4. Provide a unique name for your Resource Group, select your preferred region, and click "Review + create."

1.5. Review your settings and click "Create" to create the Resource Group.

Step 2: Create a Windows 10 Virtual Machine (VM)
2.1. In the Azure portal, navigate to "Virtual machines."

2.2. Click the "+ Add" button to create a new Virtual Machine.

2.3. Fill in the necessary information for the VM, ensuring you select the previously created Resource Group.

2.4. In the Networking tab, allow the VM to create a new Virtual Network (Vnet) and Subnet.

2.5. Continue through the wizard, configuring additional settings as needed, and click "Review + create."

2.6. Review your settings and click "Create" to deploy the Windows 10 VM.

Step 3: Create a Linux (Ubuntu) VM
3.1. In the Azure portal, navigate to "Virtual machines."

3.2. Click the "+ Add" button to create a new Virtual Machine.

3.3. Fill in the necessary information for the Linux VM, ensuring you select the previously created Resource Group and Vnet.

3.4. Continue through the wizard, configuring additional settings as needed, and click "Review + create."

3.5. Review your settings and click "Create" to deploy the Linux (Ubuntu) VM.
