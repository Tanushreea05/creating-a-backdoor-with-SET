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

<img width="1261" height="684" alt="image" src="https://github.com/user-attachments/assets/c3961ad8-8311-48a4-a5b3-ad850ebb6bf5" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="1118" height="831" alt="image" src="https://github.com/user-attachments/assets/857eaf7b-adde-45d2-aafc-4bfd00c46ab0" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="1672" height="508" alt="image" src="https://github.com/user-attachments/assets/f82ba6fe-b27e-48fc-bc8b-7e662147f9e0" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="689" height="350" alt="image" src="https://github.com/user-attachments/assets/b506e31c-c139-4b21-9be9-ac7d59bb5c78" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="816" height="391" alt="image" src="https://github.com/user-attachments/assets/e98122a2-d600-4269-ba51-5817eb516cc4" />



It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1300" height="578" alt="image" src="https://github.com/user-attachments/assets/877c0b97-0ae6-4bfb-8d98-bcbe1d9ad397" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT


<img width="635" height="702" alt="image" src="https://github.com/user-attachments/assets/ce43bd94-0f25-4553-97fc-bdb0b069c1e9" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1502" height="443" alt="Screenshot 2026-02-13 093407" src="https://github.com/user-attachments/assets/5f68e123-bad3-4780-810c-229a3ad89eff" />


SET logs the information regarding the Google credentials:

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
