<h1>Active Directory Home Lab</h1>

<h2>Description</h2>
This lab consists of a walk through on how to create an Active Directory home lab Enviroment using Oracle Virtual Box. Configuring and running the lab will help to understand active directory and windows networking.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Virtualization (Oracle Virtual Box)</b>

<h2>Environments Used </h2>

- <b>Active Directory</b>
- <b>Windows 10</b> (21H2)
- <b>Windows Server 2019</b>
  
<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
  
![Summary](https://github.com/user-attachments/assets/5bde2e28-8cd4-4465-9b01-8935b2843aa9)
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p align="center">
  
  Create a Virtual Machine: <br/>
  ![4_Suumary](https://github.com/user-attachments/assets/60c193df-c7fc-4a41-8d13-a00e53e22a33)
  <br/>
  <br/>
  Install Windows Server 2019: <br/>
  ![8_WindowsSetup](https://github.com/user-attachments/assets/be8407e0-1b37-4cbf-9813-40e8866ff506)
  <br/>
  <br/>
  Insert Guest Additions: <br/>
  ![14_Runamd64](https://github.com/user-attachments/assets/e5c818e3-7606-4fa5-99ad-e0b77103b911)
  <br/>
  <br/>
  Find your internet and internal internet and name them: <br/>
  ![19_internet_rename](https://github.com/user-attachments/assets/ed0921a8-671f-4696-8701-4fea0cee7659)
  <br/>
  <br/>
  Rename your PC to identify easier later: <br/>
  ![21_Rename_PC](https://github.com/user-attachments/assets/7464e2cf-e845-4dc9-8d7b-a0c9145274e1)
  <br/>
  <br/>
  Install Active Directory Domain Services: <br/>
  ![24_install](https://github.com/user-attachments/assets/fc142883-407d-4031-bde5-d7945f990f05)
  <br/>
  <br/>
  Deploy a new forest and set a new domain: <br/>
  ![28_ReviewOptions_pt1](https://github.com/user-attachments/assets/c046d2d1-3ced-4a40-a38a-bce75336e258)
  <br/>
  <br/>
  Create a new Organizational Unit: <br/>
  ![32_new_OU](https://github.com/user-attachments/assets/112024c3-acd4-4886-bb0d-0bda8bc8ba15)
  <br/>
  <br/>
  Create a new Admin user: <br/>
  ![36_user](https://github.com/user-attachments/assets/daf507b6-5ecb-4609-96c7-f9b198263a90)
  <br/>
  <br/>
  Add user into Domain Admin then sign in to new admin on Windows: <br/>
  ![38_apply](https://github.com/user-attachments/assets/60a1603f-ea63-4e0c-9217-5267fc31cf14)
  <br/>
  <br/>
  Install Remote Access: <br/>
  ![43_install](https://github.com/user-attachments/assets/8e0aab46-4c42-45ab-bbeb-f081b6eae9ad)
  <br/>
  <br/>
  Configure a NAT service: <br/>
  ![45_installnat](https://github.com/user-attachments/assets/f4b3dfd1-29fc-4f90-bb6e-31edae90556a)
  <br/>
  <br/>
  Install a DHCP Server: <br/>
  ![47_DHCP](https://github.com/user-attachments/assets/3ef9f95f-0c69-4166-bdc7-15c82d7269b7)
  <br/>
  <br/>
  Activate Scope then authorize "dc.mydomain.com": <br/>
  ![53_activare](https://github.com/user-attachments/assets/1e56c012-4e4a-421a-8e39-1d01239c33ec)
  <br/>
  <br/>
  
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
