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



![image](https://github.com/user-attachments/assets/81088579-afce-405f-ad23-c99b4d20a88f)



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:


![image](https://github.com/user-attachments/assets/7aebd554-ec0a-49d3-986c-af642fa10184)

It displays the following menu and select 2 for Website Attack Vectors:



![image](https://github.com/user-attachments/assets/faaa4d55-818f-43f5-8f54-a464109ae502)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:



![image](https://github.com/user-attachments/assets/4844b88d-6be6-4e59-b306-f104ffaaf3d1)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:


![image](https://github.com/user-attachments/assets/59abe8fb-f9ca-4d0a-b5c5-ea5e8e035fa2)


It shows the following screen in which the ip address of the attacker need to be given which is the default value:



![image](https://github.com/user-attachments/assets/8cb66b45-09e3-46b7-83bc-b4262972059f)



In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password


![image](https://github.com/user-attachments/assets/f297ab35-6374-4ac5-9026-ea6348b30fb6)



SET logs the information regarding the Google credentials:

![image](https://github.com/user-attachments/assets/f61d237f-d95b-4de0-9cb1-498ed243cd09)


SET logs the information in the xml file under /root/.set directory:


![image](https://github.com/user-attachments/assets/82035405-6139-4e04-b24c-66215e858a24)





## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
