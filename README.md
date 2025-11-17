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

<img width="826" height="902" alt="setoolkit" src="https://github.com/user-attachments/assets/019266d1-53d4-4560-be7f-e7fd3932bb63" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT


<img width="743" height="486" alt="set1" src="https://github.com/user-attachments/assets/289b2576-3f6f-4e52-ad72-cd0edc80db9d" />

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="817" height="628" alt="set2" src="https://github.com/user-attachments/assets/148d9db1-a315-49b1-a24d-6f4520e691bb" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1241" height="450" alt="set3" src="https://github.com/user-attachments/assets/ee555f5b-da19-47c9-b71d-d93740a00bf4" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="781" height="481" alt="set_webattack1" src="https://github.com/user-attachments/assets/10398a95-74bc-4d85-bad2-13fa68791f68" />


It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="887" height="647" alt="set_webattack_template" src="https://github.com/user-attachments/assets/ab020aeb-4e66-4660-b3a8-65b57a8a3a46" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="947" height="571" alt="ipaddress" src="https://github.com/user-attachments/assets/7d17f28d-dfeb-43bd-8e64-a1e7cf83d645" />


In windows IE, on giving the url http://10.188.150.223/ (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="995" height="874" alt="google com" src="https://github.com/user-attachments/assets/478947aa-220f-42ed-af71-e986cf01785a" />

SET logs the information regarding the Google credentials:
SET logs the information in the xml file under /root/.set directory
## OUTPUT

<img width="1241" height="802" alt="username_pass" src="https://github.com/user-attachments/assets/cec52d18-5224-4c19-8cae-0864de10ae4d" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
