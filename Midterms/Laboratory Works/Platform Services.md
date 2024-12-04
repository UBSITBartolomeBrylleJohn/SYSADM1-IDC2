![image](https://github.com/user-attachments/assets/fce3d6a9-e3b6-4c9f-85c2-23a068c75d1e)

**SYSADM1 -- Platform Services**

**Requirement:**

• A virtual machine running Windows Server\
**Objective/s:**\
To analyze IIS logs in the Event Viewer to identify critical web service
metrics, understand common error codes, and learn how to monitor the
health of web applications.

**Instructions**\
**Part 1: Opening Event Viewer and Loading Logs**\
1. Access the event viewer in the server.

> 2\. From the event viewer, explore the windows log and list down its
> major categories
![image](https://github.com/user-attachments/assets/c1b56d6f-acd2-4ce0-90e2-a10d873c9dcb)


**Part 2: Filtering and Analyzing IIS Events**\
1. Apply filter to the windows log categories to display errors for the
past 12 hours.

> 2\. **Identify Critical Events** or recurring events.
>
> 3\. **Analyze the Events**:

+-----------------------+-----------------------+-----------------------+
| o                     | > For each critical   |                       |
|                       | > or recurring event, |                       |
|                       | > **record the        |                       |
|                       | > following           |                       |
|                       | > details**:          |                       |
+=======================+=======================+=======================+
|                       |                      | > **Event ID**        |
+-----------------------+-----------------------+-----------------------+
|                       |                      | > **Source**          |
+-----------------------+-----------------------+-----------------------+
|                       |                      | > **Timestamp**       |
+-----------------------+-----------------------+-----------------------+
|                       |                      | > **Description**     |
+-----------------------+-----------------------+-----------------------+

+-----------------+-----------------+-----------------+-----------------+
| > **EVENT ID**  | > **SOURCE**    | > **TIMESTAMP** | >               |
|                 |                 |                 | **DESCRIPTION** |
+=================+=================+=================+=================+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 9:04:05 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 9:02:42 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 8193          | > VSS           | > 10/17/2024    | > Volume Shadow |
|                 |                 | > 9:02:26 AM    | > Copy Service  |
|                 |                 |                 | > error.        |
+-----------------+-----------------+-----------------+-----------------+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 8:46:09 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 8:45:17 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 6             | > Certificat    | > 10/17/2024    | > Automatic     |
|                 | eServicesClient | > 8:44:55 AM    | > certificate\  |
|                 | -AutoEnrollment |                 | > enrollment    |
|                 |                 |                 | > for local\    |
|                 |                 |                 | > system\       |
|                 |                 |                 | > fai           |
|                 |                 |                 | led(0x8007054b) |
|                 |                 |                 | > The specified |
|                 |                 |                 | > domain either |
|                 |                 |                 | > does not      |
|                 |                 |                 | > exist or      |
|                 |                 |                 | > could not be  |
|                 |                 |                 | > contacted.    |
+-----------------+-----------------+-----------------+-----------------+
| > 67            | > Certif        | > 10/17/2024    | > Automatic     |
|                 | icateServicesCl | > 8:44:55 AM    | > certificate\  |
|                 | ient-CertEnroll |                 | > enrollment    |
|                 |                 |                 | > for local\    |
|                 |                 |                 | > system\       |
|                 |                 |                 | > fai           |
|                 |                 |                 | led(0x8007054b) |
|                 |                 |                 | > The specified |
|                 |                 |                 | > domain either |
|                 |                 |                 | > does not      |
|                 |                 |                 | > exist or      |
|                 |                 |                 | > could not be  |
|                 |                 |                 | > contacted.    |
+-----------------+-----------------+-----------------+-----------------+
| > 68            | > Certif        | > 10/17/2024    | > Automatic     |
|                 | icateServicesCl | > 8:44:55 AM    | > certificate\  |
|                 | ient-CertEnroll |                 | > enrollment    |
|                 |                 |                 | > for local\    |
|                 |                 |                 | > system in     |
|                 |                 |                 | >               |
|                 |                 |                 |  authentication |
|                 |                 |                 | > to policy     |
|                 |                 |                 | > servers with  |
|                 |                 |                 | > ID.           |
+-----------------+-----------------+-----------------+-----------------+

Page **2** of **7**

+-----------------+-----------------+-----------------+-----------------+
| > 70            | > Certif        | > 10/17/2024    | > Certificate   |
|                 | icateServicesCl | > 8:44:55 AM    | > enrollment    |
|                 | ient-CertEnroll |                 | > for local     |
|                 |                 |                 | > system        |
|                 |                 |                 | > failed\       |
|                 |                 |                 | > because no    |
|                 |                 |                 | > valid policy  |
|                 |                 |                 | > can be        |
|                 |                 |                 | > obtained      |
|                 |                 |                 | > from\         |
|                 |                 |                 | > servers with  |
|                 |                 |                 | > ID            |
+=================+=================+=================+=================+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 8:44:54 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 16387         | > Security-SSP  | > 10/17/2024    | > Failed to run |
|                 |                 | > 8:44:54 AM    | > task          |
+-----------------+-----------------+-----------------+-----------------+
| > 1008          | > Perflib       | > 10/17/2024    | > The Open      |
|                 |                 | > 8:44:29 AM    | > Procedure for |
|                 |                 |                 | > service       |
|                 |                 |                 | > "BITS" in     |
|                 |                 |                 | > DLL\          |
|                 |                 |                 | > failed        |
+-----------------+-----------------+-----------------+-----------------+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 8:40:38 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 8:39:31 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+
| > 8198          | > Security-SSP  | > 10/17/2024    | > License       |
|                 |                 | > 8:39:31 AM    | > Activation\   |
|                 |                 |                 | > (             |
|                 |                 |                 | slui.exe)failed |
|                 |                 |                 | > with the      |
|                 |                 |                 | > following     |
|                 |                 |                 | > error code:   |
+-----------------+-----------------+-----------------+-----------------+

**Part 3: Troubleshooting and Solution Development**

> 1\. Review the logs and check for recurring errors.
>
> 2\. Is there a specific time or pattern to these errors?
>
> Event ID 8198, indicating potential security breaches, logged multiple
> times between 8:39 AM and 9:04 AM. Multiple certificate-related errors
> occurred simultaneously at 8:44:55 AM, indicating systemic issues.
> Volume Shadow Copy Service error recorded at 9:02:26 AM, indicating
> interconnected issues.
>
> 3\. Draft a Troubleshooting Report:

+-----------------------------------+-----------------------------------+
| o                                 | > Based on the events found,      |
|                                   | > create a short report with the  |
|                                   | > following sections:             |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

**Report Structure**

**1.** Overview

> • A brief summary of the issue and scope of your analysis.
>
> The Monitoring was done on October 17, 2024. It focuses on identifying
> critical web service metrics and recurring errors that may indicate
> potential security breaches and systemic issues. Event ID 8198,
> certificate-related problems, and a Volume Shadow Copy Service error
> are among the notable occurrences.

Page **3** of **7**

**2.** Key Findings

> • List the critical events you found. Example:
>
> o **Event ID 503**: Application pool stopped at 10:05 AM.
>
> o **Event ID 404**: Page not found error at 11:15 AM.
>
> 1\. **Event ID 8198**: Multiple occurrences of \"License Activation
> (slui.exe) failed with the following error code\" at various
> timestamps throughout the morning.
>
> 2\. **Event ID 8193**:\"Volume Shadow Copy Service error\" logged at
> 9:02:26 AM. 3. **Event ID 6**:\"Automatic certificate enrollment for
> local system failed (0x8007054b)\" at 8:44:55 AM.
>
> 4\. **Event ID 1008:\"**The Open Procedure for service \'BITS\' in DLL
> failed\" at 8:44:29 AM.

**3.** Root Causes and Solutions

+-----------------------------------+-----------------------------------+
| •                                 | > Describe the likely cause of    |
|                                   | > each error and how you would    |
|                                   | > fix it.                         |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

+-----------------------+-----------------------+-----------------------+
| > **Event ID**        | > **Root Causes**     | > **Solutions**       |
+=======================+=======================+=======================+
| > Event ID 8198       | > This error usually  | > Verify the internet |
|                       | > indicate issues     | > connection and      |
|                       | > with the Windows    | > ensure that the     |
|                       | > activation service, | > correct product key |
|                       | > which might be the  | > is being used.      |
|                       | > result of poor      | >                     |
|                       | > network access or   | > Running the         |
|                       | > incorrect license   | > command\            |
|                       | > information.        | > slmgr.vbs /ato in   |
|                       |                       | > an elevated command |
|                       |                       | > prompt may help     |
|                       |                       | > activation.         |
+-----------------------+-----------------------+-----------------------+
| > Event ID 8193       | > This error is       | > To fix the system   |
|                       | > usually caused by   | > writer error,       |
|                       | > permissions         | > either clean up     |
|                       | > difficulties or     | > the\                |
|                       | > insufficient disk   | > T                   |
|                       | > space for shadow    | emporaryInternetFiles |
|                       | > copies. It may also | > folder or identify  |
|                       | > happen if the VSS   | > the problematic\    |
|                       | > service isn\'t      | > application writer  |
|                       | > working properly.   | > by analyzing its    |
|                       |                       | > metadata and        |
|                       |                       | > reducing its        |
|                       |                       | > components or by    |
|                       |                       | > running the         |
|                       |                       | > command:\           |
|                       |                       | > diskshadow /l       |
|                       |                       | >                     |
|                       |                       | > C:\\Metadata.txt    |
|                       |                       | >                     |
|                       |                       | > list writers        |
|                       |                       | > detailed            |
|                       |                       | >                     |
|                       |                       | > Exit                |
+-----------------------+-----------------------+-----------------------+

Page **4** of **7**

+-----------------------+-----------------------+-----------------------+
| Event ID 6            | > This error          | > To configure RRAS   |
|                       | > indicates the       | > for SSL\            |
|                       | > system was unable   | > offloading, install |
|                       | > to contact the      | > the same SSL        |
|                       | > domain controller,  | > certificate on both |
|                       | > or that the domain  | > the VPN\            |
|                       | > does not exist.     | > server and load     |
|                       |                       | > balancer.           |
|                       |                       | >                     |
|                       |                       | > Then, use the RRAS\ |
|                       |                       | > management console  |
|                       |                       | > or the\             |
|                       |                       | > Enable-SstpOffload  |
|                       |                       | > PowerShell script   |
|                       |                       | > to set the correct\ |
|                       |                       | > certificate hash    |
|                       |                       | > and enable\         |
|                       |                       | > HTTP for SSL        |
|                       |                       | > offloading.         |
+-----------------------+-----------------------+-----------------------+
| > Event ID 1008       | > This error          | > Verify that         |
|                       | > indicates a failure | > network\            |
|                       | > in the Background   | > performance         |
|                       | > Intelligent         | > counters are\       |
|                       | > Transfer Service    | > being collected and |
|                       | > (BITS), which might | > displayed correctly |
|                       | > be caused by of     | > using Performance   |
|                       | > service             | > Monitor or the      |
|                       | > misconfiguration or | > typeperf\           |
|                       | > corruption.         | > command.            |
+-----------------------+-----------------------+-----------------------+

**Part 4: Reflection Questions**

> 1\. What are the most common causes of a **503 Service Unavailable**
> error?

+-----------------------------------+-----------------------------------+
| •                                 | > A 503 error is often caused by  |
|                                   | > server overload, maintenance,   |
|                                   | > misconfigured settings,         |
|                                   | > application layer issues, and   |
|                                   | > network problems preventing     |
|                                   | > communication with other        |
|                                   | > services.                       |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

> 2\. How would you **monitor login attempts** to detect potential
> security threats?

Page **5** of **7**

![image](https://github.com/user-attachments/assets/8d343947-cb69-4fda-84c2-7045e068c90d)
+-----------------------------------+-----------------------------------+
| •                                 | > To monitor login attempts in    |
|                                   | > Server 2012, enable auditing    |
|                                   | > for security events in the      |
|                                   | > Security Policy then check the  |
|                                   | > Security event log for          |
|                                   | > unsuccessful logins. This will  |
|                                   | > give useful information for     |
|                                   | > detecting possible dangers such |
|                                   | > as brute-force or illegal       |
|                                   | > access.                         |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

3\. Why is **monitoring logs** in Event Viewer important for
administrators?

+-----------------------------------+-----------------------------------+
| •                                 | > Event Viewer logs are important |
|                                   | > for administrators to monitor   |
|                                   | > security events, detect         |
|                                   | > unauthorized access, fix        |
|                                   | > problems, and improve security  |
|                                   | > by identifying issues and       |
|                                   | > possible breaches.              |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

Page **6** of **7**

Grading Rubric

+---------+---------+---------+---------+---------+---------+---------+
| > **Cri | >       | > *     | > **N   |         | > *     | > **P   |
| teria** |  **Exce | *Good** | eeds**\ |         | *Poor** | oints** |
|         | llent** |         | > *     |         |         |         |
|         |         |         | *Improv |         |         |         |
|         |         |         | ement** |         |         |         |
+=========+=========+=========+=========+=========+=========+=========+
| > **Log | > Ide   | > Ide   | > Ide   |         | > Fails | /10     |
| > Ana   | ntifies | ntifies | ntifies |         | > to    |         |
| lysis** | > all   | > most  | > some  |         | > i     |         |
|         | > key   | > key   | >       |         | dentify |         |
|         | >       | >       | events, |         | > key   |         |
|         |  events |  events | > but   |         | >       |         |
|         | > (503, | > with  | > with  |         |  events |         |
|         | > 404,  | > minor | > inc   |         | > or\   |         |
|         | > 500,  | >       | omplete |         | > pr    |         |
|         | > etc.) |  errors | > or\   |         | ovides\ |         |
|         | > with\ | > in    | > in    |         | > in    |         |
|         | > a     | > d     | correct |         | correct |         |
|         | ccurate | etails. | > d     |         | > d     |         |
|         | >       |         | etails. |         | etails. |         |
|         |  event\ |         |         |         |         |         |
|         | > d     |         |         |         |         |         |
|         | etails. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| > **T   | > P     | > So    | > So    |         | > So    | /10     |
| roubles | roposes | lutions | lutions |         | lutions |         |
| hooting | > l     | > are\  | > are\  |         | > are   |         |
| > Solu  | ogical, | >       | > s     |         | >       |         |
| tions** | > eff   |  mostly | omewhat |         | unclear |         |
|         | ective\ | >       | > vague |         | > or\   |         |
|         | > so    | correct | > or    |         | > inc   |         |
|         | lutions | > but   | > inco  |         | orrect. |         |
|         | > to    | > miss  | mplete. |         |         |         |
|         | > all\  | > some  |         |         |         |         |
|         | > ide   | > key\  |         |         |         |         |
|         | ntified | >       |         |         |         |         |
|         | >       | points. |         |         |         |         |
|         | issues. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| > *     | >       | >       | >       |         | >       | /10     |
| *Report | Well-or |  Report |  Report |         |  Report |         |
| > St    | ganized | > is    | > is\   |         | > is\   |         |
| ructure | >       | >       | > disor |         | >       |         |
| > &     |  report |  mostly | ganized |         | unclear |         |
| > Cl    | > with  | > or    | > or    |         | > or\   |         |
| arity** | > all\  | ganized | >       |         | > inco  |         |
|         | > s     | > with\ | missing |         | mplete. |         |
|         | ections | > minor | > se    |         |         |         |
|         | >       | > for   | ctions. |         |         |         |
|         | clearly | matting |         |         |         |         |
|         | > com   | >       |         |         |         |         |
|         | pleted. | issues. |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| > **    | > Pr    | > R     |         | > R     | > Fails | /10     |
| Recomme | ovides\ | ecommen |         | ecommen | > to    |         |
| ndation | > thoug | dations |         | dations | >       |         |
| > s for | htful,\ | > are   |         | > are   | provide |         |
| > Monit | > pro   | > r     |         | > vague | > re    |         |
| oring** | active\ | elevant |         | > or\   | levant\ |         |
|         | >       | > but   |         | > inco  | >       |         |
|         | recomme | > lack  |         | mplete. | recomme |         |
|         | ndation | >       |         |         | ndation |         |
|         | > s to  |  depth. |         |         | > s.    |         |
|         | > p     |         |         |         |         |         |
|         | revent\ |         |         |         |         |         |
|         | >       |         |         |         |         |         |
|         |  future |         |         |         |         |         |
|         | >       |         |         |         |         |         |
|         | issues. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| > *     | > A     | > Parti |         | > M     | > Did   | /10     |
| *Partic | ctively | cipated |         | inimal\ | > not\  |         |
| ipation | >       | > but   |         | > p     | > parti |         |
| > &     | engaged | > r     |         | articip | cipate\ |         |
| > E     | > in    | equired |         | ation,\ | >       |         |
| ffort** | > the   | > some  |         | >       |  meanin |         |
|         | > act   | > gu    |         |  needed | gfully. |         |
|         | ivity,\ | idance. |         | > sign  |         |         |
|         | > fo    |         |         | ificant |         |         |
|         | llowed\ |         |         | > help. |         |         |
|         | >       |         |         |         |         |         |
|         |  instru |         |         |         |         |         |
|         | ctions\ |         |         |         |         |         |
|         | > thor  |         |         |         |         |         |
|         | oughly. |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+
| **      |         |         |         |         |         | **/50** |
| Score** |         |         |         |         |         |         |
+---------+---------+---------+---------+---------+---------+---------+

Page **7** of **7**
