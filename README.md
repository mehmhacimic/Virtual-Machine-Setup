


<h1>Setting up Windows and Linux Virtual Machines (Microsoft Azure)</h1>
  This is a tutorial on setting up Virtual Machines in Azure! We will focus on creating the necessary resources, including a Resource Group, a Windows 10 Virtual Machine, and a Linux (Ubuntu) Virtual Machine in Microsoft Azure.
.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to setup Virtual Machines within Azure](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)

   ![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/756b1722-1f2a-4ef9-87bc-9e848f66d2a4)

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Ubuntu Linux (20.04 LTS)

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/7d03878b-62f3-46fb-8e1d-a865de8e0cdf)

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/7d3307be-d928-4b88-ad60-d56e43fa55a2)


<h2>Deployment and Configuration Steps</h2>


**Step 1: Create a Resource Group**

Open the Azure portal (https://portal.azure.com/) and log in to your Azure account.

In the left navigation pane, click on "Resource groups."

Click the "+ Add" button to create a new Resource Group.

Provide a unique name for your Resource Group, select your preferred region, and click "Review + create."

Review your settings and click "Create" to create the Resource Group.


**Step 2: Create a Windows 10 Virtual Machine (VM)**

In the Azure portal, navigate to "Virtual machines."

Click the "+ Add" button to create a new Virtual Machine.

Fill in the necessary information for the VM, ensuring you select the previously created Resource Group.

In the Networking tab, allow the VM to create a new Virtual Network (Vnet) and Subnet.

Continue through the wizard, configuring additional settings as needed, and click "Review + create."

Review your settings and click "Create" to deploy the Windows 10 VM.


**Step 3: Create a Linux (Ubuntu) VM**

In the Azure portal, navigate to "Virtual machines."

Click the "+ Add" button to create a new Virtual Machine.

Fill in the necessary information for the Linux VM, ensuring you select the previously created Resource Group and Vnet.

Continue through the wizard, configuring additional settings as needed, and click "Review + create."

Review your settings and click "Create" to deploy the Linux (Ubuntu) VM.
