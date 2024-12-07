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


Part 2: Filtering and Analyzing IIS Events
   1. Apply filter to the windows log categories to display errors for the past 12 hours.
   2. Identify Critical Events or recurring events. 
   3. Analyze the Events:
        -For each critical or recurring event, record the following details:
                -Event ID
                -Source
                -Timestamp
                -Description

![image](https://github.com/user-attachments/assets/87c16969-25e4-4f2c-96a8-d5841afcf1b4)


Page **2** of **7**

![image](https://github.com/user-attachments/assets/c6c236a4-63e4-4cfe-8b98-554bfae9fb13)

**Part 3: Troubleshooting and Solution Development**

 1\. Review the logs and check for recurring errors.
>
 2\. Is there a specific time or pattern to these errors?
>
 Event ID 8198, indicating potential security breaches, logged multiple
times between 8:39 AM and 9:04 AM. Multiple certificate-related errors
occurred simultaneously at 8:44:55 AM, indicating systemic issues.
Volume Shadow Copy Service error recorded at 9:02:26 AM, indicating
interconnected issues.
>
3\. Draft a Troubleshooting Report:
> 
   o Based on the events found, create a short report with the following sections:

**Report Structure**

**1.** Overview

• A brief summary of the issue and scope of your analysis.
>
The Monitoring was done on October 17, 2024. It focuses on identifying critical web service metrics and recurring errors that may indicate potential security breaches and systemic issues. Event ID 8198, certificate-related problems, and a Volume Shadow Copy Service error are among the notable occurrences.

Page **3** of **7**

**2.** Key Findings
• List the critical events you found. Example:
>
  o **Event ID 503**: Application pool stopped at 10:05 AM.

  o **Event ID 404**: Page not found error at 11:15 AM.

1. **Event ID 8198**: Multiple occurrences of \"License Activation (slui.exe) failed with the following error code\" at various timestamps throughout the morning.

2. **Event ID 8193**:\"Volume Shadow Copy Service error\" logged at 9:02:26 AM. 3. **Event ID 6**:\"Automatic certificate enrollment for local system failed (0x8007054b)\" at 8:44:55 AM.

3. **Event ID 1008:\"**The Open Procedure for service \'BITS\' in DLL failed\" at 8:44:29 AM.

**3.** Root Causes and Solutions

![image](https://github.com/user-attachments/assets/e2f78a81-ee36-46a6-aad5-8214193e942c)


![image](https://github.com/user-attachments/assets/85ed1d16-b9da-40b4-a27e-dc6644979e29)

Page **4** of **7**

![image](https://github.com/user-attachments/assets/46875584-e73a-49d1-aa0c-116b33c63491)


**Part 4: Reflection Questions**

1. What are the most common causes of a **503 Service Unavailable** error?
    A 503 error is often caused by server overload, maintenance, misconfigured settings, application
layer issues, and network problems preventing communication with other services.

2. How would you **monitor login attempts** to detect potential security threats?

Page **5** of **7**

   ![image](https://github.com/user-attachments/assets/8d343947-cb69-4fda-84c2-7045e068c90d)
   
   To monitor login attempts in Server 2012, enable auditing for security events in the Security Policy then check the Security event       log for unsuccessful logins. This will give useful information for detecting possible dangers such as brute-force or illegal access.

3. Why is **monitoring logs** in Event Viewer important for administrators?
   
    Event Viewer logs are important for administrators to monitor security events, detect unauthorized
access, fix problems, and improve security by identifying issues and possible breaches.


Page **6** of **7**

![image](https://github.com/user-attachments/assets/639f1956-6cf0-479f-bab2-7af254fbd714)

![image](https://github.com/user-attachments/assets/21a41825-ea80-485f-bcf0-bbcf78b3a82d)



Page **7** of **7**
