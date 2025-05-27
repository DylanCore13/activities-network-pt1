# activities-network-pt1


![image](https://github.com/user-attachments/assets/8e15530e-d851-4467-8421-61c172f9daf0)    

<h2>Resources Used</h2>

- Resource Groups
- Azure virtual networks and subnets
- Azure virtual machines (windows and linux)
  - Azure Network Security Groups (Firewall Resource)



<h2>Prerequisites</h2>


- All you need is a Azure Tenet and a subscription




<b/>
















First we'll create a Resource Group named RG-network-activities, region should be set to East US 2

![image](https://github.com/user-attachments/assets/937a8eea-4844-49b2-bdba-2f43c0e8f700)




- Create a Windows 10 Virtual Machine (VM)
   - While creating the VM, select the previously created Resource Group, also select East US 2, for image Windows 10 22H, and a size that has 2vcpus attached to it.
     You're than going to click on networking section to change the name of the virtual network. Skip Disks, won't be doing anything there.
 
![image](https://github.com/user-attachments/assets/5fb4b6e5-f7d0-4d37-9ba2-76eb3e956d83)


![image](https://github.com/user-attachments/assets/d1995009-5f01-4814-a1d1-430a0a943c39)


![image](https://github.com/user-attachments/assets/80f91df3-05a5-48d5-8b60-df3c172875c8)



   - While creating the VM, allow it to create a new Virtual Network (Vnet) and name it something entirely different from the virtual machine, than just click create. 

![image](https://github.com/user-attachments/assets/fbc289ff-c81b-4d49-8bb5-e79e84f5a4ec)

   
- Create a Linux (Ubuntu) VM
   - While creating the VM, select the previously created Resource Group and Virtual Network—the Virtual Network MUST BE THE SAME. Name the virutal machine linux-vm.
     The image will be Ubantu 22.04LTS - x64 gen2, Size will be 2vcpus.
 
     ![image](https://github.com/user-attachments/assets/a1c6e902-c809-464c-95ff-5ff45a12de5c)

    Password can be the same as the windows-vm 
 

  
- Next skip Disks and go to network section and ensure both VMs are in the same Virtual Network / Subnet

![image](https://github.com/user-attachments/assets/bb06b155-5e9b-476f-9bae-b993ed0c990c)




- End the lab, but keep both VMs for Part 2!
