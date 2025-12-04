<h1>Home Soc - Honeypot</h1>

<h2>Description</h2>
Built a cloud-based Home Security Operations Center (SOC) lab entirely from scratch using a free Microsoft Azure account and Microsoft Sentinel. Deployed a honeypot in Azure by creating a publicly accessible virtual machine to attract real-world attack traffic. Configured log forwarding to send system events and failed intrusion attempts to a centralized repository integrated with a SIEM. Leveraged the SIEM to run queries and generate a visual attack map, providing clear insight into the geographic origins of incoming threats.
<br />


<h2>Languages and Utilities Used</h2>

- <b>KQL</b> 
- <b>Azure VMs</b>
- <b>SIEM (Microsoft Sentinel)</b>


<h2>Environments Used </h2>

- <b>Windows 10</b>


<h2>Program walk-through:</h2>

<p align="center">
Launch the Microst Azure: <br/>
<img width="1712" height="1225" alt="image" src="https://github.com/user-attachments/assets/e4df2d2d-42f2-40a7-b406-7f3bde5d90d1" />
<br />
<br />
Select the Virtual Machine:  <br/>
<img width="1395" height="282" alt="Screenshot 2025-12-04 112905" src="https://github.com/user-attachments/assets/7b3e48d4-203d-4255-adfa-dfa9db3d3cf3" />
<br />
<br />
Start the Virtual Machine<br/>
<img width="1647" height="591" alt="Screenshot 2025-12-04 113401" src="https://github.com/user-attachments/assets/33828e36-9450-42b6-a2b8-a7d67566262c" />
<br />
<br />
Open the Log Analytics Workspace  <br/>
<img width="1045" height="157" alt="image" src="https://github.com/user-attachments/assets/1bd4f748-a112-4316-a370-ce1ffc8de7be" />
<br />
<br />
Query logs for the attack map
<img width="1238" height="697" alt="image" src="https://github.com/user-attachments/assets/6f4bd036-f491-4abb-9f84-167567e0a7c4" />
<br />
Navigate to Microsoft Sentinel  <br/>
<img width="626" height="193" alt="image" src="https://github.com/user-attachments/assets/68971fdf-ffbb-4432-922a-6bdd6afe01b6" />
<br />
Open Workbooks  <br/>
<img width="500" height="461" alt="Screenshot 2025-12-04 114623" src="https://github.com/user-attachments/assets/4d7fa931-f938-4a77-abf3-9e0e27d47a16" />
<br />
Select attack map workbook <br/>
<img width="628" height="401" alt="Screenshot 2025-12-04 120236" src="https://github.com/user-attachments/assets/b15cfa7b-237c-4e39-baff-42d335891f1f" />
<br />
View attack map <br/>
<img width="1280" height="598" alt="image" src="https://github.com/user-attachments/assets/ae8dc32a-a629-4370-93f5-79c26c3d6ff8" />
<img width="1275" height="409" alt="image" src="https://github.com/user-attachments/assets/3dac7cb9-a439-4647-8785-1e5c346d2523" />
<br />
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
