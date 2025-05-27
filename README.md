# activities-network-pt1


![image](https://github.com/user-attachments/assets/8e15530e-d851-4467-8421-61c172f9daf0)    

<h2>Resources Used</h2>

- Resource Groups
- Azure virtual networks and subnets
- Azure virtual machines (windows and linux)
  - Azure Network Security Groups (Firewall Resource)



<h2>Prerequisites<h2/>


- All you need is a Azure Tenet and a subscription




<b/>


<b>





First we'll create a Resource Group named RG-network-activities

![image](https://github.com/user-attachments/assets/937a8eea-4844-49b2-bdba-2f43c0e8f700)




- Create a Windows 10 Virtual Machine (VM)
   - While creating the VM, select the previously created Resource Group
 



   - While creating the VM, allow it to create a new Virtual Network (Vnet) and 


   
- Create a Linux (Ubuntu) VM
   - While creating the VM, select the previously created Resource Group and Virtual Network—the Virtual Network MUST BE THE SAME.

     
   - Authentication type: Username/Password
 

  
- Ensure both VMs are in the same Virtual Network / Subnet





- End the lab, but keep both VMs for Part 2!
