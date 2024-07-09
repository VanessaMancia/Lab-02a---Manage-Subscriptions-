# Lab 02a - Manage Subscriptions
## Management groups are used to organize and segment subscriptions. Policy can be assigned and inherited to other management groups and subscriptions. 

### Sign in to the Azure portal - https://portal.azure.com.

### Search for and select Microsoft Entra ID.

### In the Manage blade, select Properties.

### Review the Access management for Azure resources area. Ensure you can manage access to all Azure subscriptions and management groups in the tenant.

### Search for and select Management groups.

### On the Management groups blade, click + Create.

### Create a management group with the following settings. Select Submit when you are done.

| Setting                  | Value
| ------------------------ | -----
| Management group ID                    | az104-mg1 (must be unique in the directory) 
| Management group display name            | az104-mg1

---

![image](https://github.com/VanessaMancia/Lab-02a---Manage-Subscriptions-/assets/112146207/c1755fab-ce1d-4e42-9d2b-a416f038c003)

## Task 2: Review and assign a built-in Azure role
### In this task, you will review the built-in roles and assign the VM Contributor role to a member of the Help Desk.

### Select the az104-mg1 management group > Access Control (IAM) > Roles Tab

### +Add > Add Role Assignment > Search for Virtual Machine Contributor 

### On the Members tab, Select Members > select the helpdesk group > review + assign 

![image](https://github.com/VanessaMancia/Lab-02a---Manage-Subscriptions-/assets/112146207/e267c334-9c0e-4098-9f3e-f7967ce88f55)

Access Control (IAM) > Role Assignments Tab > Confirm helpdesk group has the Virtual Machine Contributor role 

![image](https://github.com/VanessaMancia/Lab-02a---Manage-Subscriptions-/assets/112146207/f0d50444-e432-4881-8c36-17f6163360a5)

