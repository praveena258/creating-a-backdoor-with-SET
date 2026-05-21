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

<img width="588" height="662" alt="image" src="https://github.com/user-attachments/assets/9cc84ef6-f29b-487c-b6ec-f010d3c4fd73" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="440" height="240" alt="image" src="https://github.com/user-attachments/assets/cba845eb-9920-481a-9f07-a7f289c17203" />




It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="367" height="290" alt="image" src="https://github.com/user-attachments/assets/46118b4c-8adc-4b1a-8937-fe141e21539c" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="793" height="299" alt="image" src="https://github.com/user-attachments/assets/fd830371-b94a-4980-9568-da970284ec07" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="738" height="577" alt="image" src="https://github.com/user-attachments/assets/a0e1f8fc-1d80-4a25-b0ee-7d1edcd91c2e" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="491" height="242" alt="image" src="https://github.com/user-attachments/assets/08f04a13-ca63-4320-b470-3e987707ac17" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="891" height="165" alt="image" src="https://github.com/user-attachments/assets/3bb3198a-8457-4071-88d0-565529a1d1c1" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="880" height="834" alt="image" src="https://github.com/user-attachments/assets/cc7aaa73-bc82-40c8-8c60-53b4f50c7342" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="891" height="165" alt="image" src="https://github.com/user-attachments/assets/fcad4171-e44f-4395-90e7-62984c7fb86f" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="926" height="356" alt="image" src="https://github.com/user-attachments/assets/ddad5a75-8991-4e05-8ff8-4307bf5d55cf" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
