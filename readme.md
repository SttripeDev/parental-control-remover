#  Welcome to the guide to remove Microsoft Family! 

by Sttripe



**NOTE AS OF NOW ONLY WORKS IF ACCOUNT HAS ADMIN ACCESS IF NOT USE THE ACCOUNT THAT DOES**



## [1] INSTALLING PSEXEC:

1. Head too : (https://learn.microsoft.com/en-us/sysinternals/downloads/psexec) and download the file on the page.

2. Once downloaded extract it to a folder (Doesnt matter where)

3. Go into that folder and copy "PsExec.exe" to C:/Windows/System32/

4. Once copied Open a CMD terminal as ADMINISTRATOR

5. Run the following command : "PsExec.exe -i -s cmd.exe"

6. put "whoami" in the new terminal window  to ensure you are running at nt/system


## [2] Running The program killer:

1. In your terminal window , run "cd [The Directory of this instructions]"

2. Then once in the directory run the following command "WpcMonKiller"

3. This should begin running a program that will continuosly kill "WpcMon.exe" or Microsoft Family


## [3] Removing Microsoft Family:

1. go to C:/Windows/System32 in your file explorer (for ease click the shortcut provided)

2. Search for WpcMon.exe and right click to go to PROPERTIES

3. Go to security and click ADVANCED

4. Where it says owner click change, change that to your computer username 

5. Return back to the security page and click EDIT for the permissions

6. Click on the USERS and allow FULL ACCESS

7. Now you can close both pages and return to your file explorer

8. Simply Delete the file , if any issues ensure ProgramKiller is running and repeat from Step 2


## [4] Removing Startup from TaskScheduler:

1. Search for Taskscheduler in the windows search and run

2. In the task Scheduler library follow the following order:
	
	- Microsoft
	- Windows
	- Shell

3. Once in Shell simply delete the scheduled tasks that refer to FamilySafetyMonitor


## [5] Finishing Up:

1. Close all programs including the terminal running the program killer

2. Delete PsExec from System32 if you do not desire to have it there.

3. Restart your computer, and you should be free from control


---


**NOTE: May return after Windows Updates so will have to repeat steps**

Thank you for following the guide, recommendations and spreading how are appreciated.

Enjoy a free computer experience! - Sttripe
```
                         ______                     
 _________        .---"""      """---.              
:______.-':      :  .--------------.  :             
| ______  |      | :                : |             
|:______B:|      | |    Success!    | |             
|:______B:|      | |                | |             
|:______B:|      | |  You Are Free  | |             
|         |      | |                | |             
|:_____:  |      | |                | |             
|    ==   |      | :                : |             
|       O |      :  '--------------'  :             
|       o |      :'---...______...---'              
|       o |-._.-i___/'             \._              
|'-.____o_|   '-.   '-...______...-'  `-._          
:_________:      `.____________________   `-.___.-. 
                 .'.eeeeeeeeeeeeeeeeee.'.      :___:
               .'.eeeeeeeeeeeeeeeeeeeeee.'.         
              :____________________________:

```

*Planning to make this process more automated so stay tuned for an easier solution especially after windows updates*
