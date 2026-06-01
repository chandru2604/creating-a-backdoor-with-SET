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

Open terminal and try execute some parrot linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1068" height="981" alt="image" src="https://github.com/user-attachments/assets/cdfa3bcc-94bc-4c10-b4e2-3e69f28db116" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="545" height="451" alt="image" src="https://github.com/user-attachments/assets/684ca048-1762-495e-83f0-57ad45a8d0b5" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="516" height="306" alt="image" src="https://github.com/user-attachments/assets/10d8ab2d-3a7f-403f-9ccc-5a937e9baf53" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="965" height="525" alt="image" src="https://github.com/user-attachments/assets/ddc0d557-dabd-4df0-a400-d0b635b5914b" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="947" height="197" alt="image" src="https://github.com/user-attachments/assets/099c4087-01f1-4cd0-ba78-7d87a9f8d86b" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="942" height="185" alt="image" src="https://github.com/user-attachments/assets/c24e37a1-c395-4ddf-a0c8-7bd8b94cc715" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1421" height="322" alt="image" src="https://github.com/user-attachments/assets/5534bc12-fe25-4e72-a12e-f487f78087cd" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1090" height="528" alt="image" src="https://github.com/user-attachments/assets/d3b3c8cd-529c-4d62-9652-47b8b7665b2e" />

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1021" height="900" alt="image" src="https://github.com/user-attachments/assets/a5443b9a-0843-41ab-aeac-72fbbaf7d65c" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1071" height="257" alt="image" src="https://github.com/user-attachments/assets/8f53415a-f05c-4e77-b669-2f30f090270a" />











## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
