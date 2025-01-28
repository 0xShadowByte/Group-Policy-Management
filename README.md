# Group Policy Management 

## Objective
  
Centralize management of security, configurations, and policies in a domain. Appling best practices.

### Skills Learned

- Creating, editing, and managing GPOs
- Enforcing password policies and desktop environments
- Configuring software installations and restrictions
- Applying drive mappings

### Tools Used

- VMware Workstation Pro
- Windows Server 2022
- Windows 10 Enterprise

## Steps

### Creating and Setting Up Group Policy Management

*Ref 1: Searching for Group Policy Management on Windows Server 2022*

![image](https://github.com/user-attachments/assets/f8f6bf50-40e6-4a42-9dfd-aa8f349af16d)

*Ref 2: Editing Default Domain Controller as an example*

![image](https://github.com/user-attachments/assets/1ddd7b9b-9044-405c-867f-95cfdb2206e5)

*Ref 3: Hands-on Activity #1 Creating Password Policy*

![image](https://github.com/user-attachments/assets/2e7ff352-4f12-4188-b205-88c6c0e0f4d0)

*Ref 4: "Password Policy" folder under "Group Policy Groups"

![image](https://github.com/user-attachments/assets/4b8112a1-dd7f-48cd-b84a-d62b189d0c0b)

*Ref 5: Editing Password Policy*

![image](https://github.com/user-attachments/assets/f8f292e6-1478-4ba3-b0ca-884a852763f5)

*Ref 6: Password Policy->Windows Settings->Security Settings->Account Policies->Password Policy*

![image](https://github.com/user-attachments/assets/ed95ef05-5949-4f8b-88a9-a837d7b5e604)

*Ref 7: Changing the minimum password length policy*

![image](https://github.com/user-attachments/assets/9e1e735c-035d-4fbd-9da2-90e8a2eb002c)

*Ref 8: Changing and enabling the complexity requirements for password*

![image](https://github.com/user-attachments/assets/e036f6cf-2d1d-4d8b-9f4c-ab9b0b385947)

*Ref 9: Changing the maximum password age

![image](https://github.com/user-attachments/assets/ad3948de-481b-4bec-bc98-399a6da6e780)

*Ref 10: Hands-on Activty #2 Drive Mapping*

![image](https://github.com/user-attachments/assets/f31d0470-e0be-45cb-97fb-b89f78bd3536)

*Ref 11: Creating new GPO in domain: Drive Mapping*

![image](https://github.com/user-attachments/assets/30034eae-a297-4a31-b482-d381d8b71a62)

*Ref 12: User Configuration->Preference->Windows Settings->Drive Maps

![image](https://github.com/user-attachments/assets/d7e32bf1-5bd2-46f7-a56c-87d3206b8737)

*Ref 13: "Location: \\servername\folder; Drive Letter: E"

![image](https://github.com/user-attachments/assets/280c006a-80c6-4998-b95c-0b1d9f42c7e8)

*Ref 14: Desktop Wallpaper Policy*

![image](https://github.com/user-attachments/assets/d5fc1610-4c88-48e8-b714-bd8ae753ae9f)

*Ref 15: Creating a new GPO for Desktop Wallpaper Policy*

![image](https://github.com/user-attachments/assets/feffd91d-945a-45c7-9add-de32245ecbd4)

*Ref 16: Enabling Desktop Wallpaper Policy*

![image](https://github.com/user-attachments/assets/f538758f-4f0f-49bc-8a4f-082973c013a1)

*Ref 17: Hands-On Activty #4 Restrict Access to Control Panel*

![image](https://github.com/user-attachments/assets/9fbad4e7-a120-4c7e-b205-a481b6d10738)

*Ref 18: User config->Polices->Admin Templet->Control Panel->Prohibt Access to Control Panel and PC settings*

![image](https://github.com/user-attachments/assets/8e6e8194-0312-48f4-b464-8c68906aa4ae)

*Ref 19: Hands-On Activity #5 Disable USB Storage*

![image](https://github.com/user-attachments/assets/e821f573-c788-4f48-b7c1-c5c336e23aa3)

*Ref 20: Computer Config->Policies->Admin Templete->System->Removable Storage Devices*

![image](https://github.com/user-attachments/assets/0f5ed2fc-a13a-4d0e-8abe-714a55e78a86)

*Ref 21: Account Lockout Policy*

![image](https://github.com/user-attachments/assets/b710816d-bdce-4dcb-a95e-a526e5756bfb)

*Ref 22: Account Lockout Policy->Computer Config->Polices->Windows Settings->Security Settings->Account Policies*

![image](https://github.com/user-attachments/assets/145672b4-236a-45b3-8ad0-7a5fe8dbc41b)

### Applying and testing Group Policy Management

*Ref 1: Installing Windows 10 Enterprise ISO to use on VM to join Computer Domain*

![image](https://github.com/user-attachments/assets/b15b9c53-db35-4619-89ff-59ce84d66c23)

*Ref 2: Setting up Window 10 Enterprise on VM*

![image](https://github.com/user-attachments/assets/7f79a78f-0f0a-45f5-aae7-8d4f556b8c3b)

