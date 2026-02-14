# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2026-02-13 091832" src="https://github.com/user-attachments/assets/aeae56d1-c338-4e57-8658-ba78ec82bfe5" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1920" height="1080" alt="Screenshot 2026-02-13 091851" src="https://github.com/user-attachments/assets/0feaf79a-7c57-4a35-8598-0062cc21b4a3" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2026-02-13 091902" src="https://github.com/user-attachments/assets/348a3442-7389-4827-9a2e-891d7e9b4092" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2026-02-13 091902" src="https://github.com/user-attachments/assets/0f7b71c7-474c-4d3c-b0b8-7469bdaf9bd7" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="1920" height="1080" alt="Screenshot 2026-02-13 091902" src="https://github.com/user-attachments/assets/3b210be3-7f99-4135-b37b-a544fbafca79" />


It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1920" height="1080" alt="Screenshot 2026-02-13 091936" src="https://github.com/user-attachments/assets/ab709847-5e2d-4ae9-b71d-5904b39d48a0" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1920" height="1080" alt="Screenshot 2026-02-13 091957" src="https://github.com/user-attachments/assets/78c9344e-4273-43e2-94fe-f1ddb45fbc53" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width

SET logs the information regarding the Google credentials:
## OUTPUT






<img width="1874" height="165" alt="Screenshot 2026-02-13 093731" src="https://github.com/user-attachments/assets/27a0e350-0283-4dd9-a47f-dbd3faeed94e" />









## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
