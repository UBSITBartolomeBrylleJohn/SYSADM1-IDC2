![image](https://github.com/user-attachments/assets/501893ed-571c-48ab-9994-6ce55745b02a)

SYSADM1 -- Managing Services in Windows\
Requirement:\
• A virtual machine running Linux and Windows OS

**Services** are background processes that run independently of user
interactions in Windows. They provide essential system functions, such
as network connectivity, printing, and time synchronization. This lab
will guide you through the process of managing services using the
Services app.

Instructions:\
1. Open the Start menu and search for \"Services\"

![image](https://github.com/user-attachments/assets/47b3aae1-973c-4b9c-ae59-265fb6116c97)

2\. Familiarize yourself with the columns, including Service Name,
Display Name, Status, and Startup type.

3\. Right-click on a service and select \"Start\", \"Stop\", or
\"Restart\". Fill out the table below

![image](https://github.com/user-attachments/assets/77ade0aa-98f4-43ff-9026-db7a61935d4d)


Page **2** of **7**

![image](https://github.com/user-attachments/assets/c60626c0-006c-4da9-854a-9a3d37798d4a)


4\. Select five network services, right-click to view its properties.
Modify the startup setting to

> Manual.

Page **3** of **7**

![image](https://github.com/user-attachments/assets/00d24d1e-f9d2-4fbe-b4dc-642b5ad85aac)

Page **4** of **7**

![image](https://github.com/user-attachments/assets/84ad4fc6-be5a-464f-a8e3-8106c272b349)

5\. Explore the \"General\", \"Recovery\", and \"Log On\" tabs to
understand additional service settings. 6. Create a batch file that will
be added as a new service later on. Refer to the batch file code below.

![image](https://github.com/user-attachments/assets/1b3cdd6e-03c3-4c17-a255-1c32364dce68)


7\. Save the batch file in Z:\\lastname_timer.bat\
8. Use the sc command to add timer.bat service in the command line
interface. *sc create BatchTimerService binPath=
\"path_to_your_batch_file.bat\" start= auto* *net start
BatchTimerService*

Page **5** of **7**

> **Replace path_to_your_batch_file.bat with the actual path to your
> batch file.** 
9. Verify that BatchTimerService has been added to the services.
**SS:**
![image](https://github.com/user-attachments/assets/f58f5bde-44fb-4bc2-9964-11ec3e615733)

> 10\. **Testing the Service:** Now, if you open a new command prompt,
> you should see the timer countdown without requiring your interaction.
> Once the timer finishes, you\'ll see the \"Timer finished!\" message.
>
> **SS:**
![image](https://github.com/user-attachments/assets/14ba97d4-f443-43c5-9208-f11973fce00d)

>
> **Rubric**
>
> ![](vertopal_1e6781345a30413eb5fd9573badfcf8f/media/image15.png){width="3.1055555555555556in"
> height="2.272221128608924in"}

+-------------+-------------+-------------+-------------+-------------+
| *           | **Excellent | **Good      | >           | **Uns       |
| *Criteria** | (10)**      | (7)**       |  **Needs**\ | atisfactory |
|             |             |             | > **        | (1)**       |
|             |             |             | Improvement |             |
|             |             |             | > (3)**     |             |
+=============+=============+=============+=============+=============+
| > Un        | > D         | > Shows a   | > Has a     | > Shows     |
| derstanding | emonstrates | > solid\    | > basic\    | > little or |
| > of        | > a deep    | > un        | > un        | > no        |
| > Services  | > un        | derstanding | derstanding | > un        |
|             | derstanding | > of\       | > of\       | derstanding |
|             | > of the    | > services, | > services, | > of        |
|             | > concept   | > but may   | > but may\  | > services. |
|             | > of        | > lack some | > struggle  |             |
|             | > services, | > depth in  | > with      |             |
|             | > their     | > specific  | > specific  |             |
|             | > roles,    | > areas.    | > concepts. |             |
|             | > and their |             |             |             |
|             | >           |             |             |             |
|             |  importance |             |             |             |
|             | > in\       |             |             |             |
|             | > Windows.  |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| > Service\  | > S         | > De        | > Can       | > Struggles |
| >           | uccessfully | monstrates\ | > perform   | > to        |
|  Management | > starts,   | >           | > basic     | > perform   |
| > Skills    | > stops,    | proficiency | > service\  | > even      |
|             | > restarts, | > in\       | >           | > basic     |
|             | > and       | > managing  |  management | > service   |
|             | >           | > services, | > tasks,    | >           |
|             |  configures | > but may   | > but may   |  management |
|             | > services  | > encounter | > need\     | > tasks.    |
|             | > using the | > minor     | >           |             |
|             | > Services  | > di        |  assistance |             |
|             | > app.      | fficulties. | > or\       |             |
|             |             |             | > guidance. |             |
+-------------+-------------+-------------+-------------+-------------+
| > Custom    | > S         | > Can       | > Has       | Cannot      |
| > Service   | uccessfully | > create a\ | > limited\  | create a    |
| > Creation  | > creates   | > custom    | >           | custom      |
|             | > and       | > service,  |  experience | service.    |
|             | > manages   | > but may   | > with      |             |
|             | > a\        | >           | > creating  |             |
|             | > custom    |  encounter\ | > custom    |             |
|             | > service   | > minor     | > services. |             |
|             | > using the | > d         |             |             |
|             | >           | ifficulties |             |             |
|             | appropriate | > or        |             |             |
|             | > tools and | > require   |             |             |
|             | >           | >           |             |             |
|             | techniques. | assistance. |             |             |
+-------------+-------------+-------------+-------------+-------------+

Page **6** of **7**

+-------------+-------------+-------------+-------------+-------------+
| > Prob      | > D         | > Can       | > May       | > Struggles |
| lem-Solving | emonstrates | > e         | > require\  | > to\       |
|             | > strong    | ffectively\ | >           | > t         |
|             | > prob      | > t         |  assistance | roubleshoot |
|             | lem-solving | roubleshoot | > to\       | > and       |
|             | > skills    | > and\      | > t         | > resolve   |
|             | > when      | > resolve   | roubleshoot | > issues.   |
|             | > en        | > most      | > some      |             |
|             | countering\ | > issues    | > issues.   |             |
|             | >           | > related   |             |             |
|             |  challenges | > to        |             |             |
|             | > or        | > service\  |             |             |
|             | > errors.   | >           |             |             |
|             |             | management. |             |             |
+=============+=============+=============+=============+=============+
| > Do        | > Provides  | > Documents | > Provides  | > Does not  |
| cumentation | > clear     | > the lab   | > basic\    | > provide\  |
| > and       | > and\      | >           | > doc       | > any       |
| > Reporting | > concise\  | activities\ | umentation, | > do        |
|             | > do        | >           | > but may   | cumentation |
|             | cumentation | adequately, | > be        | > or        |
|             | > of the    | > but\      | > d         | >           |
|             | > lab       | > may lack  | isorganized |  reporting. |
|             | >           | > some\     | > or        |             |
|             | activities, | > detail or | >           |             |
|             | > including | > clarity.  | incomplete. |             |
|             | > relevant  |             |             |             |
|             | >           |             |             |             |
|             | screenshots |             |             |             |
|             | > and       |             |             |             |
|             | > ob        |             |             |             |
|             | servations. |             |             |             |
+-------------+-------------+-------------+-------------+-------------+
| **Score:**  | > **/50**   |             |             |             |
+-------------+-------------+-------------+-------------+-------------+

Page **7** of **7**