# Developing an Azure Based SIEM for Immediate RDP Attack Detection
This project entails the creation of a specialized SIEM (Security Information and Event Management) system, leveraging the robust capabilities of Azure Sentinel. Utilizing PowerShell, I transformed Event Viewer logs into a dynamic, real-time mapping system for enhanced detection and visualization of RDP (Remote Desktop Protocol) attacks. 


# Summary
This project demonstrates a real-time RDP attack detection system using Azure Sentinel. By setting up a honeypot through a vulnerable Virtual Machine (VM) in the cloud, we monitor, log, and analyze malicious traffic from various IP addresses. The system uses Azure's powerful analytics to visualize attack origins, helping to understand attack patterns and enhance network security.

# Key Features
- Azure Sentinel Integration: Cloud-based SIEM system for advanced threat detection and visual representation.

- Honeypot Setup: A deliberately vulnerable VM in the cloud to attract attacks.

- Real-Time Monitoring: Continuous logging of RDP attack attempts from multiple geolocations.

- Data Visualization: Attack data is displayed on a map for easy visualization of attack sources.

- IP Geolocation: Integration with ipgeolocation.io for accurate source tracking.

- PowerShell Log Exporter: Utilization of a PowerShell-based API for efficient log export.

# Steps:
- Creating the VM: Screenshot and description of the VM setup process as the honeypot.
  
![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/29178532-5e89-42af-8f41-02aa2b5626d5)

- Setting Up Log Analytics Workspace: Steps to create and configure the workspace for log analysis.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/ac7aa9ef-0706-4d15-ae10-72be9c44d902)

- Running the VM: Image showing the VM in operation with guidelines on how to start it.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/24c92b56-4d80-440d-b491-088ac39b9b8a)

- Event Viewer Log Inspection: Displaying how logs are reviewed to identify suspicious activity.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/de28a009-ffdf-450f-be20-835f304fb732)

- Simulating Hacker Attack: Documentation of the controlled attack simulation to test the system.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/80858c2f-b2f8-4ffc-bc96-b6ae2a2ee159)

- Lowering Firewalls: Strategy for temporarily reducing firewall protection to bait attackers.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/fb925ba5-eaf9-4e16-a584-08aefd4cfa21)

- Ping Test: Evidence of the machine's visibility on the internet to ensure accessibility.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/df790f8a-aeb3-41a0-a78b-92043cb33fed)

- Using PowerShell Log Exporter API: Instructions and code snippets for exporting logs via API.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/6b870144-019e-42c9-a01a-7a4a5a084914)

- Security Log Analysis: Process of examining the security logs to extract IP and location data.
  
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/05a14a2e-cf4a-40af-82d9-ab246c94e5d6)

- Identifying the Simulated logs: A guide on distinguishing between real and simulated attack data.
  ![image](https://github.com/YeranG30/Developing-an-Azure-Based-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/914f8722-9be6-4c7e-931c-e02473397c34)

  
- Azure Sentinel Intrusion Map & Logs: Display of the intrusion map after 1 hour of data collection, with annotations.
    
  <img width="475" alt="image" src="https://github.com/YeranG30/Developing-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/5169d9d2-bfc6-4146-ab97-43b79a07ca29">

![image](https://github.com/YeranG30/Developing-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/64428f8c-3b38-4457-ac29-00f905558209)


- Global Map:
  
Due to running out of API credits, the Powershell script couldn't capture and send the data as intended to the SIEM. It would have shown additional traffic from India, the Philippines, and Taiwan, providing a more comprehensive view of the network activity

<img width="489" alt="image" src="https://github.com/YeranG30/Developing-SIEM-for-Immediate-RDP-Attack-Detection/assets/74067706/3fd1d77c-10bd-4303-aa73-147c076c6998">


# Conclusion: 
Completing this Azure-based SIEM project, I've developed a deeper understanding of real-time cyber threat detection and response. Skills in cloud infrastructure, PowerShell scripting, and security log analysis were enhanced, alongside an appreciation for geolocation tracking and data visualization in cybersecurity. This experience has underscored the importance of proactive defense mechanisms in a continually evolving threat landscape.


  
