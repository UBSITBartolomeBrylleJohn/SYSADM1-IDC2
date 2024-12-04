![image](https://github.com/user-attachments/assets/bb6e8c7a-9ad8-4109-b519-13c0ab7c79d8)


SYSADM1 -- Setting Up Webserver

Requirement:

• A virtual machine running Linux and Windows OS\
Task Instructions:\
1. Install IIS by adding it as a role, select necessary features,
include monitoring tools

![image](https://github.com/user-attachments/assets/49f5f514-3f5c-488b-8419-1c2751647596)

2. Create a website by opening IIS Manager

+-----------------------------------+-----------------------------------+
| > o\                              | > Right-click on the server's     |
| > o\                              | > name and select Internet        |
| > o                               | > Information Services Manager.   |
|                                   | >                                 |
|                                   | > Right-click on Sites and select |
|                                   | > Add Website.                    |
|                                   | >                                 |
|                                   | > Enter a name, description,      |
|                                   | > physical path (where your       |
|                                   | > website files will reside), IP  |
|                                   | > address, port, and host name.   |
+===================================+===================================+
+-----------------------------------+-----------------------------------+

![image](https://github.com/user-attachments/assets/11d07b34-139e-4ffb-9dc3-60ec76918888)

3\. Configure the Website:

> o Right-click on your website and select Edit.
>
> o Set the Default Document to the name of your main HTML file
> \>default.html
>
> o Configure other settings as needed (e.g., SSL certificates,
> authentication)

Page **2** of **5**

![image](https://github.com/user-attachments/assets/102ff676-40a4-42f9-9d13-102a074fc06c)

4\. Create a Web Page:

> o Create an HTML file in the physical path you specified.
![image](https://github.com/user-attachments/assets/7d7903df-1b27-435d-afd5-9dfd637e492e)

> o Save it as default.html or your preferred name
![image](https://github.com/user-attachments/assets/49d47e65-b862-44cb-8c13-827bc396df4d)

Page **3** of **5**

5\. Test the Web Server:\
o Open a web browser and enter the URL of your website (e.g.,
http://localhost). o You should see your web page displayed.

Page **4** of **5**

Grading Rubric

+-----------------------+-----------------------+-----------------------+
| > **Criteria**        | **Points**            | > **Description**     |
+=======================+=======================+=======================+
| > Web Server\         | 15                    | > Correctly installs  |
| > Installation        |                       | > IIS or another web  |
|                       |                       | > server on the       |
|                       |                       | > virtual machine.    |
+-----------------------+-----------------------+-----------------------+
| > Website\            | 15                    | > Successfully        |
| > Configuration       |                       | > configures the      |
|                       |                       | > website with the    |
|                       |                       | > correct physical    |
|                       |                       | > path, IP address,   |
|                       |                       | > port, and default   |
|                       |                       | > document.           |
+-----------------------+-----------------------+-----------------------+
| > Successful Access   | 15                    | > Successfully        |
|                       |                       | > accesses the web    |
|                       |                       | > page from the       |
|                       |                       | > client computer     |
|                       |                       | > using the correct   |
|                       |                       | > URL.                |
+-----------------------+-----------------------+-----------------------+
| Troubleshooting       | 15                    | > Demonstrates        |
|                       |                       | > ability to          |
|                       |                       | > troubleshoot common |
|                       |                       | > issues, such as     |
|                       |                       | > network             |
|                       |                       | > connectivity        |
|                       |                       | > problems or         |
|                       |                       | > configuration       |
|                       |                       | > errors.             |
+-----------------------+-----------------------+-----------------------+

+-----------------------+-----------------------+-----------------------+
| Documentation         | 10                    | > Provides clear and  |
|                       |                       | > concise             |
|                       |                       | > documentation of    |
|                       |                       | > the installation,   |
|                       |                       | > configuration, and  |
|                       |                       | > testing process.    |
+=======================+=======================+=======================+
| > Total               | /70                   |                       |
+-----------------------+-----------------------+-----------------------+

Page **5** of **5**
