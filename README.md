# Ex.No-07-creating-a-backdoor-with-SET.
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

## OUTPUT:
![image](https://github.com/user-attachments/assets/d3f91738-dc89-4995-93e9-27beaafae10d)
The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.
It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT:
![image](https://github.com/user-attachments/assets/84ca40d8-c927-4b13-bf5e-e7b38ef6ce1a)
The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:

## OUTPUT:
![image](https://github.com/user-attachments/assets/7d3aeb8f-b7c7-4925-ab9f-b6db374d77af)
The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:
## OUTPUT:
![image](https://github.com/user-attachments/assets/bde0b925-6941-4ce7-94f2-80138fd1a13e)
The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.
It shows the following screen in which the IP address of the attacker needs to be given (default value):
## OUTPUT:
![image](https://github.com/user-attachments/assets/d4e9664b-dd12-4780-a510-f9c8000c2d4b)
It shows the following screen in which the option Google can be selected:

## OUTPUT:
![image](https://github.com/user-attachments/assets/bff1728c-d7fb-4d41-bce0-88609f4ae859)
SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT:
![image](https://github.com/user-attachments/assets/12ca2717-a3a3-4340-9a17-2cde772e432e)
In Windows IE, on giving the URL http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password.





## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
