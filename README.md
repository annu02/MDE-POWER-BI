# MDE-POWER-BI Report

# Steps to create a report in Power BI
**Step1: Access the Microsoft Defender for Endpoint APIs**

**Step2: **

**Access the Microsoft Defender for Endpoint APIs**
1. Create an app
2. Log on to Azure with a user that has the Global Administrator role.
3. Navigate to Azure Active Directory > App registrations > New registration.
4. 4. In the registration form, choose a name for your application, and then select Register.

![alt text](https://user-images.githubusercontent.com/67975253/156917305-a5e84c90-da05-4500-bab3-1b9cff296040.png)

5. To enable your app to access Defender for Endpoint and assign it 'Read all alerts' (assign all the releavant readonly permission such as machine, File,IP) permission, on your application page. For API permission, select API Permissions > Add permission > APIs my organization uses >, type WindowsDefenderATP, and then select WindowsDefenderATP.

![image](https://user-images.githubusercontent.com/67975253/156917367-89f00e13-231d-4ffa-9505-0f131e1c2f77.png)
![image](https://user-images.githubusercontent.com/67975253/156917516-d881e778-c2fb-4024-a3c7-dcde86ae3bec.png)

![image](https://user-images.githubusercontent.com/67975253/156929354-cb09c2ed-a349-45fc-9ae7-f7586f62cefd.png)

Quick view once permission are granted:
![image](https://user-images.githubusercontent.com/67975253/156929799-677b6075-5b0a-411e-9e57-b8858fdc1234.png)





 **Note** :You need to select read only permissions. 'Read All Alerts' shared above is only an example. For example:
 
a. To read Machine details Machine.Read  permission.

b.To pull the vulnerability details, select the 'Vulnerability.Read' permission.

c.To determine which permission you need, look at the Permissions section in the API you are interested to call.

 6. To add a secret to the application, select Certificates & secrets, add a description to the secret, and then select Add.
 ![image](https://user-images.githubusercontent.com/67975253/156928903-13460c42-b453-4d2c-a389-26c13559b8ec.png)


