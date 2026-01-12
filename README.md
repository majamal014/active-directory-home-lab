<h1>Virtualized Active Directory Home Lab</h1>

<h2>Description</h2>

This VMware-based lab environment showcases the deployment of a corporate Windows Domain. Key features include Internet access via Routing and Remote Access (RRAS), system hardening using Group Policy Objects (GPOs), and secure shared folder access.
<br />

<h2>Network Diagram</h2>

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/7000a943-ecc4-42e6-990f-012c096d8a4d" />

<h2>Environments Used </h2>

- Windows Server 2022
- Windows 10
- VMware Workstation Pro

<h2>Tools Used</h2>

- Active Directory Users and Computers
- Active Directory Administrative Center
- Group Policy Management
- Server Manager
  
<h2>Configuration</h2>

<h3>VMware</h3>

<img width="297" height="332" alt="image" src="https://github.com/user-attachments/assets/fdcff413-9a11-4dbc-a67b-0f5fab59f79e" />
<img width="296" height="313" alt="image" src="https://github.com/user-attachments/assets/da62613b-5a48-4a80-bd2d-b8f8d59d69ee" />

<h3>Server Roles</h3>

<img width="1509" height="569" alt="image" src="https://github.com/user-attachments/assets/33edb583-7e32-4cb7-af0d-abd4fef59003" />

<h3>DHCP</h3>

<p align="center">
  <img width="932" height="325" alt="image" src="https://github.com/user-attachments/assets/a0606815-4e36-45e6-b48f-020afa6a89cb" /><br />
</p>
<h4>DC01 uses DHCP to configure IP settings for client computers (COMP01 settings shown):</h4>
<p align="center">
  <img width="1024" height="245" alt="DHCP assignment" src="https://github.com/user-attachments/assets/c65e9090-5e0d-495d-8866-4bd8a30c3f93" /><br />
</p>
<p align="center">
<img width="980" height="512" alt="image" src="https://github.com/user-attachments/assets/d07f45ab-9c9e-4b06-b47a-792468747890" /><br />
</p>

<h3>Hardening via Group Policy Objects</h3>

<p align="center">
  <img width="1005" height="499" alt="image" src="https://github.com/user-attachments/assets/154464f6-f1bb-43d6-b403-f39d97ebd31f" />
</p>
<h4>Demonstration of "Restrict Settings Visibility" GPO on COMP01; only allowed settings are shown:</h4>
<p align="center">
  <img width="524" height="352" alt="image" src="https://github.com/user-attachments/assets/0ceb4477-6b34-496f-9c69-81af42f3b2c3" />
</p>

<h3>Active Directory Groups and Shared Folder Access</h3>

<h4>Groups are organized into departments with their own shared folders:</h4>
<p align="center">
  <img width="1028" height="411" alt="image" src="https://github.com/user-attachments/assets/89d1795c-192a-43d6-83c5-c8d6be9bda07" />
</p>
<h4>Department Managers have all of the access of their department's staff:</h4>
<p align="center">
  <img width="939" height="456" alt="image" src="https://github.com/user-attachments/assets/03bd9c90-d042-425e-809a-eb84cdf7edd9" />
</p>
<h4>Only IT has Full Control over shared folders; other staff are assigned Modify access:</h4>
<p align="center">
  <img width="1020" height="681" alt="image" src="https://github.com/user-attachments/assets/329aeddc-ad85-47c5-b2f1-2d7589b87f86" />
</p>
<h4>Perspective of Sophie Rivers, an HR employee; only the HR Staff folder is visible:</h4>
<p align="center">
  <img width="1025" height="614" alt="image" src="https://github.com/user-attachments/assets/30ac7121-affd-4366-b3b1-82ed22d4d5ca" />
</p>
<h4>Because Sophie is so good at her job, she got promoted to HR Manager and can now see the HR Management folder:</h4>
<p align="center">
<img width="994" height="592" alt="image" src="https://github.com/user-attachments/assets/a035ba31-3df8-4951-aff4-3b423a9a145a" />
</p>
<p align="center">
  <img width="1025" height="609" alt="image" src="https://github.com/user-attachments/assets/c4f5467d-f288-4627-a887-f61077ab4d83" />
</p>

<h3>Internet Access with NAT via RRAS</h3>

<p align="center">
  <img width="767" height="561" alt="Routing and Remote Access config" src="https://github.com/user-attachments/assets/ccd02820-81db-4a0a-93f8-2d79b0b49474" />
</p>
<p align="center">
<img width="790" height="341" alt="image" src="https://github.com/user-attachments/assets/d834cf59-8e1f-41fd-b9a6-bb904f8ce1cd" />
</p>
