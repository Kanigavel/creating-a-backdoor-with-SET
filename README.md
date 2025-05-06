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
## Output
![Screenshot 2025-05-06 223357](https://github.com/user-attachments/assets/8ac03033-bfb3-466f-903b-3ff400f83b4a)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks. It displays the following menu and select 2 for Website Attack Vectors:
## Output
![Screenshot 2025-05-06 223627](https://github.com/user-attachments/assets/2faf737d-e8b4-46a2-afde-bf9bec81b05b)
The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:
## Output
![Screenshot 2025-05-06 223645](https://github.com/user-attachments/assets/aae4344a-4859-45e7-984a-ca6c5e75957a)
The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:
## Output
![Screenshot 2025-05-06 223656](https://github.com/user-attachments/assets/79bce2d1-6e31-412f-ab85-429c5bf6373b)
The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected. It shows the following screen in which the IP address of the attacker needs to be given (default value):
## Output
![Screenshot 2025-05-06 223712](https://github.com/user-attachments/assets/6e4ee789-6393-45c9-90c7-6de19c27938e)
It shows the following screen in which the option Google can be selected:
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## Output
![Screenshot 2025-05-06 223732](https://github.com/user-attachments/assets/b186d589-2a7a-4cd0-aaa5-741d421b638f)

In Windows IE, on giving the URL http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password.
## Output
![eth6](https://github.com/user-attachments/assets/c6ccf0a1-01bb-4813-982b-c85dda35a059)
SET logs the information regarding the Google credentials:
## Output
![eth7](https://github.com/user-attachments/assets/986f8bcf-d07f-489b-837e-1d5213dba548)
SET logs the information in the XML file under /root/.set directory:
## Output
![eth8](https://github.com/user-attachments/assets/ca8f618a-b074-4385-8b3d-f7f0ccbcf708)





## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
