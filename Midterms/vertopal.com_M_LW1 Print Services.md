![image](https://github.com/user-attachments/assets/392138e9-88ba-4ade-81c7-c01de1a33637)

	SYSADM1 – Monitoring Print Services in Windows Server 2019
	Requirement: 
•	A virtual machine running Linux and Windows OS
Part 1: Setting Up Print Services
1.	Install and configure print.srv domain

  	![image](https://github.com/user-attachments/assets/2910a6e4-e089-4355-9a90-1225f6497625)

2.	Connect one client to the recently created domain
   ![image](https://github.com/user-attachments/assets/012d679e-1cc0-4277-a9bf-6421f46bf4a4)
  	
3.	Install Print Services Role:
   
   ![image](https://github.com/user-attachments/assets/99e36709-97f3-4082-81e0-a508a930a62b)

4.	Search the internet for any printer installer and convert it to iso
   ![image](https://github.com/user-attachments/assets/5ab4c63d-6384-493a-97dd-2eac7e68a540)

5.	Install and deploy it as network printer
   
   ![image](https://github.com/user-attachments/assets/87733ac9-5593-47f9-9557-e3d13de712f6)


Part 2: Monitoring Print Services
Objective: Familiarize yourself with monitoring tools available in Windows Server 2019.
1.	Event Viewer:
o	Open Event Viewer (run eventvwr.msc).
o	Navigate to Applications and Services Logs > Microsoft > Windows > PrintService.
o	Review logs for print jobs, errors, and warnings.
2.	Performance Monitor:
o	Open Performance Monitor (run perfmon).
o	In the left pane, expand Data Collector Sets > System.
o	Right-click System Performance and select Start.
o	Monitor performance metrics related to print services.
3.	Using Print Management Console:
o	Open Print Management from Server Manager.
o	View active print jobs and their status.
o	Use the Printers node to check the status of all printers.
Part 3: Exploring Third-Party Monitoring Tools
1.	Research at least two third-party print monitoring tools 
o	Consider factors such as features, pricing, and compatibility with Windows Server 2019.
2.	Install and Configure:
o	Choose one of the tools to install in your environment.
o	Follow the installation instructions provided by the tool's documentation.
o	Configure it to monitor your print services.
3.	Test and Report Findings:
o	Generate a report or dashboard from the tool.
o	Analyze the collected data (e.g., print volume, errors, user activity).

Rubric
Criteria	1 (Unsatisfactory)	2 (Needs Improvement)	3 (Satisfactory)	4 (Good)	5 (Excellent)	Score
Part 1: Setting Up Print Services						
Domain Installation	No domain created	Domain created with errors	Domain created correctly	Domain configured well	Domain configured and documented thoroughly	
Client Connection	Client not connected	Connection attempt failed	Client connected but with issues	Client connected correctly	Client connected and documented well	
Print Services Role Installation	Role not installed	Role installed with issues	Role installed correctly	Role installed and configured	Role installed, configured, and documented thoroughly	
Printer Installer Conversion	No installer found	Installer conversion attempted but failed	Installer converted but not used	Installer converted and used	Installer converted, used, and documented well	
Network Printer Deployment	Printer not deployed	Deployment failed	Printer deployed but not functional	Printer deployed correctly	Printer deployed, tested, and documented well	
Part 2: Monitoring Print Services						
Event Viewer Usage	Event Viewer not opened	Opened but no logs reviewed	Logs reviewed but superficial	Logs reviewed with some analysis	Logs reviewed with thorough analysis and documentation	
Performance Monitor Usage	Performance Monitor not opened	Opened but no metrics monitored	Metrics monitored but not analyzed	Metrics monitored with some analysis	Metrics monitored, analyzed, and documented thoroughly	
Print Management Console Usage	Console not opened	Opened but functionality not used	Active jobs viewed superficially	Active jobs viewed with some detail	Active jobs viewed and documented thoroughly	
Part 3: Exploring Third-Party Tools						
Research on Tools	No tools researched	Research incomplete	Research on one tool completed	Research on two tools with some analysis	Research on two tools, detailed analysis, and comparison	
Installation and Configuration	Tool not installed	Installation failed	Tool installed but not configured	Tool installed and configured with issues	Tool installed, configured, and documented thoroughly	
Reporting Findings	No report generated	Report lacks detail	Report generated but lacks analysis	Report generated with some analysis	Comprehensive report with thorough analysis and documentation	

