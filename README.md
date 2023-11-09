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

![out1](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/098c0b3a-88d0-49e8-a20a-9e3e8338f704)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:


It displays the following menu and select 2 for Website Attack Vectors:

![out2](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/3bb4c127-f934-4936-b6aa-090c25fa4182)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![out3](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/b18ab1dc-30b7-4ae1-9d4e-2eda273e46bf)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![out4](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/117814d4-f8b6-4479-bcf4-25634df85b17)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![out5](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/248aac47-e77a-4f2e-940a-4af024cdba97)

It shows the following screen in which the option Google can be selected:

![out6](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/fea864fe-011d-472b-9e99-19ba7204633b)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![out7](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/2a0ac6ae-95fd-4d70-98a9-7066ad5fb78f)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![login](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/c9389e65-2183-4967-a426-a48a0beb661e)


SET logs the information regarding the Google credentials:

![out8](https://github.com/Reebak04/creating-a-backdoor-with-SET/assets/118364993/31b58a4f-e4d8-4739-8ffa-2597bb82c4e8)

SET logs the information in the xml file under /root/.set directory:



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
