![image](https://github.com/user-attachments/assets/cf4abf1d-bf63-4d34-a476-14bcfc2aae20)

SYSADM1 -- Monitoring Print Services in Windows Server 2019

Requirement:

• A virtual machine running Linux and Windows OS 

Part 1: Setting Up Print Services

1\. Install and configure **print.srv** domain
![image](https://github.com/user-attachments/assets/b7287980-bfd9-419d-80ce-45892fdc4d42)

2\. Connect one client to the recently created domain
![image](https://github.com/user-attachments/assets/be610db8-4a1e-44e3-b6c2-2925831206da)

3\. Install Print Services Role

![image](https://github.com/user-attachments/assets/63b1960c-ef31-443e-8d9a-94240ffd9ff8)

4\. Search the internet for any printer installer and convert it to iso
![image](https://github.com/user-attachments/assets/26017cc6-7ed7-472a-9530-841432d14828)

5\. Install and deploy it as network printer
![image](https://github.com/user-attachments/assets/49959858-e852-4c0f-a7e6-1393fde0f817)


Page **2** of **4**

Part 2: Monitoring Print Services
Objective: Familiarize yourself with monitoring tools available in Windows Server 2019.

1\. Event Viewer:

  o\ Open Event Viewer (run eventvwr.msc).
 
  o\ Navigate to Applications and Services Logs \> Microsoft \> Windows \> PrintService.
>
  o\ Review logs for print jobs, errors, and warnings.
>
2\. Performance Monitor:
>
  o\ Open Performance Monitor (run perfmon).
>
  o\ In the left pane, expand Data Collector Sets \> System.
>
  o\ Right-click System Performance and select Start.
>
  o\ Monitor performance metrics related to print services.
>
 3\. Using Print Management Console:
>
  o\ Open Print Management from Server Manager.
>
  o\ View active print jobs and their status.
>
  o\ Use the Printers node to check the status of all printers.

Part 3: Exploring Third-Party Monitoring Tools
>
1\. Research at least two third-party print monitoring tools
>
  o\ Consider factors such as features, pricing, and compatibility with Windows Server 2019.
>
2\. Install and Configure:
>
  o\ Choose one of the tools to install in your environment.
>
  o\ Follow the installation instructions provided by the tool's documentation.
>
  o\ Configure it to monitor your print services.
>
3\. Test and Report Findings:
>
  o\ Generate a report or dashboard from the tool.
>
  o\ Analyze the collected data (e.g., print volume, errors, user activity).
>
![image](https://github.com/user-attachments/assets/63a20cd0-a72a-45d7-9d53-81600ff4c521)


![image](https://github.com/user-attachments/assets/d738d05c-3770-40f8-89f3-981475f7a86f)


![image](https://github.com/user-attachments/assets/49f9f4aa-2580-46e0-bf4a-9ee2d6862e7e)


Page **4** of **4**
