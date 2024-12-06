![image](https://github.com/user-attachments/assets/cf4abf1d-bf63-4d34-a476-14bcfc2aae20)

SYSADM1 -- Monitoring Print Services in Windows Server 2019

Requirement:

• A virtual machine running Linux and Windows OS Part 1: Setting Up
Print Services\
1. Install and configure **print.srv** domain
![image](https://github.com/user-attachments/assets/b7287980-bfd9-419d-80ce-45892fdc4d42)

> 2\. Connect one client to the recently created domain
![image](https://github.com/user-attachments/assets/be610db8-4a1e-44e3-b6c2-2925831206da)

3\. Install Print Services Role:
![image](https://github.com/user-attachments/assets/63b1960c-ef31-443e-8d9a-94240ffd9ff8)

4\. Search the internet for any printer installer and convert it to iso
![image](https://github.com/user-attachments/assets/26017cc6-7ed7-472a-9530-841432d14828)

5\. Install and deploy it as network printer
![image](https://github.com/user-attachments/assets/49959858-e852-4c0f-a7e6-1393fde0f817)


Page **2** of **4**

Part 2: Monitoring Print Services
> Objective: Familiarize yourself with monitoring tools available in
> Windows Server 2019.
>
> 1\. Event Viewer:
>
> o Open Event Viewer (run eventvwr.msc).
>
> o Navigate to Applications and Services Logs \> Microsoft \> Windows
> \> PrintService.
>
> o Review logs for print jobs, errors, and warnings.
>
> 2\. Performance Monitor:
>
> o Open Performance Monitor (run perfmon).
>
> o In the left pane, expand Data Collector Sets \> System.
>
> o Right-click System Performance and select Start.
>
> o Monitor performance metrics related to print services.
>
> 3\. Using Print Management Console:
>
> o Open Print Management from Server Manager.
>
> o View active print jobs and their status.
>
> o Use the Printers node to check the status of all printers.
>
> Part 3: Exploring Third-Party Monitoring Tools
>
> 1\. Research at least two third-party print monitoring tools
>
> o Consider factors such as features, pricing, and compatibility with
> Windows Server 2019.
>
> 2\. Install and Configure:
>
> o Choose one of the tools to install in your environment.
>
> o Follow the installation instructions provided by the tool\'s
> documentation.
>
> o Configure it to monitor your print services.
>
> 3\. Test and Report Findings:
>
> o Generate a report or dashboard from the tool.
>
> o Analyze the collected data (e.g., print volume, errors, user
> activity).
>
> Rubric

+---------+---------+---------+---------+---------+---------+---------+
| **Cri   | >       | > **2   | >       | >       | >       | > **    |
| teria** |  **1**\ | > (N    |  **3**\ |  **4**\ |  **5**\ | Score** |
|         | >       | eeds**\ | > **(S  | > **(   | > *     |         |
|         |  **(Uns | > **    | atisfac | Good)** | *(Excel |         |
|         | atisfac | Improve | tory)** |         | lent)** |         |
|         | tory)** | ment)** |         |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
+---------+---------+---------+---------+---------+---------+---------+

> **Part 1: Setting Up Print Services**

+-----------+-----------+-----------+-----------+-----------+-----------+
| > **      | > No\     | > Domain\ | > Domain\ | Domain\   | > Domain  |
| Domain**\ | > domain  | > created | >         | c         | > c       |
| > **Insta | > created | > with    |  created\ | onfigured | onfigured |
| llation** |           | > errors  | >         | well      | > and     |
|           |           |           | correctly |           | > do      |
|           |           |           |           |           | cumented\ |
|           |           |           |           |           | > t       |
|           |           |           |           |           | horoughly |
+===========+===========+===========+===========+===========+===========+
| > **      | > Client  | > Co      | > Client\ | > Client\ | > Client  |
| Client**\ | > not\    | nnection\ | >         | >         | >         |
| > **Con   | >         | > attempt | connected | connected | connected |
| nection** | connected | > failed  | > but     | >         | > and     |
|           |           |           | > with    | correctly | > d       |
|           |           |           | > issues  |           | ocumented |
|           |           |           |           |           | > well    |
+-----------+-----------+-----------+-----------+-----------+-----------+

Page **3** of **4**

+-----------+-----------+-----------+-----------+-----------+-----------+
| > **Print | > Role    | > Role\   | > Role\   | > Role    | > Role    |
| >         | > not     | > i       | >         | >         | > i       |
|  Services | >         | nstalled\ | installed | installed | nstalled, |
| > Role**\ | installed | > with    | >         | > and\    | > co      |
| > **Insta |           | > issues  | correctly | > c       | nfigured, |
| llation** |           |           |           | onfigured | > and     |
|           |           |           |           |           | > do      |
|           |           |           |           |           | cumented\ |
|           |           |           |           |           | > t       |
|           |           |           |           |           | horoughly |
+===========+===========+===========+===========+===========+===========+
| > **P     | > No\     | > I       | > I       | > I       | > I       |
| rinter**\ | >         | nstaller\ | nstaller\ | nstaller\ | nstaller\ |
| > **Ins   | installer | > co      | > c       | >         | > c       |
| taller**\ | > found   | nversion\ | onverted\ | converted | onverted, |
| > **Con   |           | >         | > but not | > and     | > used,   |
| version** |           | attempted | > used    | > used    | > and     |
|           |           | > but     |           |           | > d       |
|           |           | > failed  |           |           | ocumented |
|           |           |           |           |           | > well    |
+-----------+-----------+-----------+-----------+-----------+-----------+
| > **N     | > Printer | > D       | >         | >         | > Printer |
| etwork**\ | > not     | eployment |  Printer\ |  Printer\ | >         |
| > **P     | >         | > failed  | >         | >         | deployed, |
| rinter**\ |  deployed |           |  deployed |  deployed | > tested, |
| > **Dep   |           |           | > but not | >         | > and\    |
| loyment** |           |           | > f       | correctly | > d       |
|           |           |           | unctional |           | ocumented |
|           |           |           |           |           | > well    |
+-----------+-----------+-----------+-----------+-----------+-----------+

> **Part 2: Monitoring Print Services**
>
> **Event Viewer Usage** Event Viewer not opened Opened but no logs
> reviewed Logs reviewed but superficial Logs reviewed with some
> analysis Logs reviewed with thorough analysis and documentation
>
> **Performance Monitor Usage** Performance Monitor not opened Opened
> but no metrics monitored Metrics monitored but not analyzed Metrics
> monitored with some analysis Metrics monitored, analyzed, and
> documented thoroughly
>
> **Print Management Console Usage** Console not opened Opened but
> functionality not used Active jobs viewed superficially Active jobs
> viewed with some detail Active jobs viewed and documented thoroughly
>
> **Part 3: Exploring Third-Party Tools**

+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| >     | > No  |       | >     | > Res |       | > Res |       | > Res |
| **Res | > t   |       |  Rese | earch |       | earch |       | earch |
| earch | ools\ |       | arch\ | > on  |       | > on  |       | > on  |
| > on  | >     |       | >     | > one |       | > two |       | > two |
| > To  | resea |       | incom | >     |       | >     |       | > t   |
| ols** | rched |       | plete | tool\ |       | tools |       | ools, |
|       |       |       |       | >     |       | >     |       | >     |
|       |       |       |       |  comp |       |  with |       |  deta |
|       |       |       |       | leted |       | >     |       | iled\ |
|       |       |       |       |       |       |  some |       | >     |
|       |       |       |       |       |       | > ana |       |  anal |
|       |       |       |       |       |       | lysis |       | ysis, |
|       |       |       |       |       |       |       |       | >     |
|       |       |       |       |       |       |       |       |  and\ |
|       |       |       |       |       |       |       |       | >     |
|       |       |       |       |       |       |       |       | compa |
|       |       |       |       |       |       |       |       | rison |
+=======+=======+=======+=======+=======+=======+=======+=======+=======+
| >     |       | >     | > In  |       | >     |       | >     | >     |
|  **In |       |  Tool | stall |       |  Tool |       |  Tool |  Tool |
| stall |       | > not | ation |       | >     |       | >     | > i   |
| ation |       | >     | > f   |       |  inst |       |  inst | nstal |
| > and |       |  inst | ailed |       | alled |       | alled | led,\ |
| >     |       | alled |       |       | > but |       | >     | > c   |
| Confi |       |       |       |       | >     |       |  and\ | onfig |
| gurat |       |       |       |       |  not\ |       | > c   | ured, |
| ion** |       |       |       |       | >     |       | onfig | > and |
|       |       |       |       |       | confi |       | ured\ | > d   |
|       |       |       |       |       | gured |       | >     | ocume |
|       |       |       |       |       |       |       |  with | nted\ |
|       |       |       |       |       |       |       | > i   | >     |
|       |       |       |       |       |       |       | ssues | thoro |
|       |       |       |       |       |       |       |       | ughly |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+
| > *   | > No  |       | > R   | > Re  |       | > Re  |       | > Com |
| *Repo | > re  |       | eport | port\ |       | port\ |       | prehe |
| rting | port\ |       | > l   | >     |       | >     |       | nsive |
| >     | >     |       | acks\ |  gene |       |  gene |       | > r   |
| Findi |  gene |       | > d   | rated |       | rated |       | eport |
| ngs** | rated |       | etail | > but |       | >     |       | >     |
|       |       |       |       | >     |       |  with |       |  with |
|       |       |       |       | lacks |       | >     |       | > tho |
|       |       |       |       | > ana |       |  some |       | rough |
|       |       |       |       | lysis |       | > ana |       | > ana |
|       |       |       |       |       |       | lysis |       | lysis |
|       |       |       |       |       |       |       |       | > and |
|       |       |       |       |       |       |       |       | > doc |
|       |       |       |       |       |       |       |       | ument |
|       |       |       |       |       |       |       |       | ation |
+-------+-------+-------+-------+-------+-------+-------+-------+-------+

Page **4** of **4**
