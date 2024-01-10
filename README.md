![image](https://github.com/Richan21/Creating-Log-Analytics-Workspace/assets/153684298/b78a0ab5-6cee-4395-b921-774100e3f8b9)

# Creating-Log-Analytics-Workspace
This is a step by step Lab on how to create a Log Analytics Workspace using Microsoft Azure and connect it to an existing VM.


<h1>Creating-Azure-VMs</h1>
The Lab guide outlines step by step method of setting up a Log Analytic Workspace using Microsoft Azure and linking it to a Virtual Machine created on Microsoft Azure.<br />


## Prerequisites
1. Create an Azure Subscription to access the Azure Platform. This comes with an initial $200 credit for new accounts.

<h2>Environments and Technologies Used</h2>
NOTE: I was able to set up the entire project on both my IPAD Pro 2020 and Desktop

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems used</h2>

- windows 10(21h2)
- Safari (IpadOS Version 16)

## Resource Group Creation
1. Sign in to the Azure Portal.
2. Navigate to “Resource groups.”
3. Click “+ Add” to create a new resource group.
4. Fill in the basics:
   - Subscription: Choose Azure subscription.
   - Resource group: Enter a unique name.
   - Region: Choose the deployment region.
5. Review and create the resource group.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/793d928e-f636-43bc-8f46-b61191a2fe94)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/8208fb19-952d-4345-bc71-26c79d74b0b7)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/0fd5d018-52c9-45fa-91b1-4dd2d4c805d7)

## Virtual Machines (VM)
1. Navigate to “Virtual Machines”
2. Click “+ Add” to create a new Virtual Machines.
3. Fill in the basics:
   - Subscription: Choose Azure subscription.
   - Resource group: Create or select.
   - Virtual Machine name: Enter a unique name.
   - Region: Choose the deployment region.
4. Proceed to Create/Review.
6. Create the Virtual Machine.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/3a2baf83-9253-4cda-810c-638bb234791c)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/6f0ceddc-a6a9-4575-b856-4761ed5a5ea0)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/86d47af9-28ed-4f5e-8a35-af6967915736)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/d023c5c1-b66f-4317-ba99-851b2891776f)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/726c6b5a-c4dc-4e49-ab78-d130428e5d8c)

## Log Analytics Workspace
1. Navigate to “Log Analytics.”
2. Click “+ Add” to create a new Log Analytics Workspace.
3. Fill in the basics:
   - Subscription: Choose Azure subscription.
   - Resource group: Create or select.
   - Workspace name: Enter a unique name.
   - Region: Choose the deployment region.
4. Configure settings and review.
5. Create the Log Analytics Workspace.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/c7540f6b-20c0-45fa-8173-7dbea2264f6e)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/79f3c74f-d429-4984-a217-1bee30d4b40e)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/3c5caa4d-756c-42b4-b83c-d0e250b4ded2)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/6e3d026b-6ade-4935-9648-6195e183a51f)

## Connecting Log Analytics workspace to VM
1. Connect to Log Analytics Workspace.
2. Select Log Analystics workspace.
3. Go to Virtual Machines and Select VM.

![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/e67c4b3f-c8dd-47e9-9459-4f0091bae3bb)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/77e80804-32f2-456b-9b81-01b87103f855)
![image](https://github.com/Richan21/How-to-Implement-a-SOC-in-AZURE/assets/153684298/d59abb5a-2210-4454-b5b4-6d82bd753ae2)


## Note
- Configuration: The configurations set for this Lab will not work for eveything. Please adjust variables and configurate settings to fit your needs.
  
