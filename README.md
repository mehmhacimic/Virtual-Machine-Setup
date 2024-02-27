


<h1>Setting up Windows and Linux Virtual Machines (Microsoft Azure)</h1>
  This is a tutorial on setting up Virtual Machines in Azure! We will focus on creating the necessary resources, including a Resource Group, a Windows 10 Virtual Machine, and a Linux (Ubuntu) Virtual Machine in Microsoft Azure.
<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to setup Virtual Machines within Azure](https://www.youtube.com/watch?v=yr2inR-AJxw)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)

   ![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/756b1722-1f2a-4ef9-87bc-9e848f66d2a4)
  <p align="center">

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)
- Ubuntu Linux (20.04 LTS)

<p align="center">
  <img width="800" height="400" src="https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/617df6a6-46e7-4a5b-aa08-60b2a5892044">
</p>   


<p align="center">
  <img width="800" height="200" src="https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/7d3307be-d928-4b88-ad60-d56e43fa55a2">
</p>

 
<h2>Deployment Steps</h2>


**Step 1: Create a Resource Group**


1. Open the Azure portal (https://portal.azure.com/) and log in to your Azure account.


2. In the top search bar, search for "Resource groups."

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/a6db528a-6776-465d-bd76-b16bd20a00d3)

3. Click the "+ Create" to create a new Resource Group.

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/f017174d-1231-497b-bc9e-6583feb6c7fb)

4. Provide a unique name for your Resource Group, select your preferred region, and click "Review + create."

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/152a793c-fa6b-4836-a2bd-e453a105acd2)


5. Review your settings and click "Create" to create the Resource Group.


**Step 2: Create a Windows 10 Virtual Machine (VM)**

6. In the Azure portal, navigate to "Virtual machines."


7. Click the "+ Create" button and then "Azure Virtual Machine" to create a new Virtual Machine.

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/1778e383-6085-4104-96f1-7506d4496ae7)

8. Fill in the necessary information for the Windows VM (*previously created Resource Group, VM Name, Windows 10 Pro Image, VM Size, Username, Password*) 

*Make sure you also select the same region as your Resource Group. and select the 'No infrastructure redundancy required' availability option.*

![WindowsVm1](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/a4db54ad-aca1-4a57-a103-5592b8c5998c) 


9. In the Networking tab, allow the VM to create a new Virtual Network (Vnet) and Subnet.

![image](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/ee32f0a3-0a1f-4d6d-a2b6-bc1811500dce)


10. Continue through the wizard, configuring additional settings as needed, and click "Review + create."


11. Review your settings and click "Create" to deploy the Windows 10 VM.

*AFTER THE VM FINISHES DEPLOYMENT, GO AHEAD AND **REFRESH** YOUR PAGE*


**Step 3: Create a Linux (Ubuntu) VM**


12. In the Azure portal, navigate again to "Virtual machines."


13. Click the "+ Create" button to create a new Virtual Machine.


14. Fill in the necessary information for the Linux VM(*previously created Resource Group, VM Name, Ubuntu Linux Image, VM Size, Authentication type*), ensuring you select the same Vnet that was created during the Windows 10 VM Deployment.

*Again, select the 'No infrastructure redundancy required' availability option.*

![linuxvm1](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/66b316ae-efc3-40aa-b53f-30fa747650f2)
![linuxvm3](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/33fbec5d-b6bf-4c0e-84ec-3e66912d0b9c)


15. Continue through the wizard, configuring additional settings as needed, and click "Review + create."

16. Review your settings and click "Create" to deploy the Linux (Ubuntu) VM.

**OPTIONAL STEP**

Navigate back to your Resource group containing both VMs to ensure everything was setup properly.

     *You should only have 1 virtual network and 2 of everything else*
   ![Rg1page](https://github.com/mehmhacimic/VirtualMachineSetup/assets/157438082/27f4e8f6-623f-4d66-8dd8-0784bbbbb3c2)
 
